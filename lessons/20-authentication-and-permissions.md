# 20 — Optional: add real authentication and permissions

[Previous lesson](19-database-and-sql.md) · [Course home](../README.md) · [Next lesson](21-full-stack-integration.md)

## Before you start

Complete lesson 19. This is an advanced extension, not a prerequisite for learning React.

## What you will learn

Distinguish authentication from authorization; learn password storage, sessions, ownership checks, CSRF defenses, and least privilege.

## Instructions

1. Define the permission matrix before writing login behavior: anonymous users have no incident access; reporters create and read their own incidents; administrators read all incidents and update status.
2. Use maintained password-hashing and session libraries selected from current official documentation. Follow OWASP guidance for password hashing; never store plaintext passwords or invent cryptography.
3. Use server-managed sessions and appropriately configured cookies. Plan HTTPS, Secure, HttpOnly, SameSite, expiration, session renewal at login, logout invalidation, and an appropriate persistent session store.
4. Add CSRF protection for cookie-authenticated state-changing requests, login rate limiting, and generic login errors. SameSite is defense in depth; evaluate the full CSRF design.
5. Enforce ownership and role checks on every server operation, including detail reads. Assign ownership from the authenticated session, not from submitted fields. Do not allow public registration to assign an administrator role.
6. Test with two fictional reporters and one administrator, including direct API calls that bypass the interface. Update and verify your permission matrix.

## Done when

- [ ] Reporter A cannot read or modify Reporter B’s incidents through direct requests.
- [ ] Changing a browser value or submitted role cannot grant administrator access.
- [ ] Logout invalidates the server session, unauthenticated requests fail, and missing or invalid CSRF protection is rejected where required.

## ChatGPT prompt — guided practice

> Help me design authentication for my learning API using the linked OWASP guidance. First review my permission matrix and session lifecycle. Explain password hashing, server-side checks, and CSRF in small steps. Do not generate security code or claim production readiness.

## ChatGPT prompt — review my attempt

> Review my evidence for two-user isolation, role tampering, logout, session expiry, login throttling, and CSRF rejection. Identify assumptions and ask me to prove one missing property. I will share only fictional data and remove credentials before sharing my work.

## Resources

Read the relevant sections, then return to the exercise. Examples in external documentation are references to study, not a finished project to copy.

- [OWASP: Password storage](https://cheatsheetseries.owasp.org/cheatsheets/Password_Storage_Cheat_Sheet.html)
- [OWASP: Session management](https://cheatsheetseries.owasp.org/cheatsheets/Session_Management_Cheat_Sheet.html)
- [OWASP: Cross-site request forgery prevention](https://cheatsheetseries.owasp.org/cheatsheets/Cross-Site_Request_Forgery_Prevention_Cheat_Sheet.html)
- [OWASP: Authorization](https://cheatsheetseries.owasp.org/cheatsheets/Authorization_Cheat_Sheet.html)
- [Express: Production security practices](https://expressjs.com/en/advanced/best-practice-security/)

## Save your evidence

In your implementation repository’s learning journal, record what you built, one observation from a check above, one mistake you fixed, and one question you can now answer. Commit a small, understandable milestone before moving on.
