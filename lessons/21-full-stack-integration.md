# 21 — Optional: connect React to the protected API

[Previous lesson](20-authentication-and-permissions.md) · [Course home](../README.md) · [Portfolio review](../PROJECT-BRIEF.md)

## Before you start

Complete lessons 18–20, including permission tests.

## What you will learn

Learn authenticated requests, server-owned data, mutation feedback, protected workflows, integration testing, and operational limitations.

## Instructions

1. Replace demo local-storage records with API-backed records for the full-stack mode. Keep any frontend-only demo clearly separate so it cannot be mistaken for authenticated data.
2. Prefer a same-origin browser and API deployment for this learning extension. If origins differ, explicitly plan credentials, CORS, cookies, and CSRF using the relevant documentation.
3. Show loading, validation errors, expired-session feedback, and retry options. Prevent duplicate submissions and do not report success until the server confirms it.
4. Read roles and ownership from trusted server responses while continuing to enforce them on the server. Record status-history events server-side without logging passwords, session identifiers, or sensitive report bodies.
5. Run the two-reporter and administrator flows end to end. Test an expired session, denied access, network failure, and a database restart.
6. Before hosting the API, plan HTTPS, secret configuration, persistent storage, backups, session storage, and log retention. A static host cannot provide these server capabilities. Keep the service local until the controls have evidence.

## Done when

- [ ] React and direct API tests both confirm the permission matrix.
- [ ] Failed or expired requests never appear as successful updates.
- [ ] The README separates implemented protections, tested evidence, and remaining operational work.

## ChatGPT prompt — guided practice

> Coach me through replacing my React demo data with a protected API. Ask me to describe the request lifecycle, session behavior, and error states before implementation. Help me write the React API integration and integration tests, explain the changes, and plan hosting needs. You can write code and help me finish this lesson. Work in manageable steps, identify the file for each change, explain unfamiliar syntax, and give me a way to run or check the result. If I am stuck or have not started, show a worked example rather than requiring an attempt first. End with one small change for me to try so I understand the result.

## ChatGPT prompt — review my attempt

> Review my full-stack evidence using reporter A, reporter B, and an administrator. Challenge unsupported security claims and help me distinguish a working local exercise from a service ready to operate. I will share only fictional data and remove credentials before sharing my work. You can write code and help me finish this lesson. Work in manageable steps, identify the file for each change, explain unfamiliar syntax, and give me a way to run or check the result. If I am stuck or have not started, show a worked example rather than requiring an attempt first. End with one small change for me to try so I understand the result.

## Resources

Read the relevant sections, then return to the exercise. Examples in external documentation are references to study, not a finished project to copy.

- [MDN: Using Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch)
- [OWASP: Session management](https://cheatsheetseries.owasp.org/cheatsheets/Session_Management_Cheat_Sheet.html)
- [OWASP: Cross-site request forgery prevention](https://cheatsheetseries.owasp.org/cheatsheets/Cross-Site_Request_Forgery_Prevention_Cheat_Sheet.html)
- [OWASP: Authorization](https://cheatsheetseries.owasp.org/cheatsheets/Authorization_Cheat_Sheet.html)
- [OWASP: Logging](https://cheatsheetseries.owasp.org/cheatsheets/Logging_Cheat_Sheet.html)
- [Express: Production security practices](https://expressjs.com/en/advanced/best-practice-security/)

## Save your evidence

In your implementation repository’s learning journal, record what you built, one observation from a check above, one mistake you fixed, and one question you can now answer. Commit a small, understandable milestone before moving on.
