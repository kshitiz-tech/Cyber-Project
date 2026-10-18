# 13 — Add pages and incident details

[Previous lesson](12-react-forms-and-validation.md) · [Course home](../README.md) · [Next lesson](14-effects-and-local-storage.md)

## Before you start

Complete lesson 12.

## What you will learn

Learn client-side routing, navigation, route parameters, detail views, not-found states, and route limitations.

## Instructions

1. Use the current React Router declarative guide that matches your installed version. Plan dashboard, report, incident-detail, and not-found pages.
2. Keep shared navigation and layout around the pages. Make each incident link to a detail view using its stable identifier.
3. Handle an unknown incident identifier and an unknown route with clear recovery links.
4. Test browser back and forward actions. Set a meaningful page title and consider focus after navigation.
5. Refresh a detail URL locally. Record that deployment needs compatible route handling; a hidden route is not an access-control mechanism.

## Done when

- [ ] Direct navigation, back, and forward work.
- [ ] Unknown incident identifiers do not crash the application.
- [ ] Explain why hiding an admin page cannot secure server data.

## ChatGPT prompt — guided practice

> Help me plan React Router pages for my tracker using the declarative documentation. Ask me to describe the routes and how incident identifiers select records. Explain not-found handling and direct-page refresh with route configuration examples that match my installed version. You can write code and help me finish this lesson. Work in manageable steps, identify the file for each change, explain unfamiliar syntax, and give me a way to run or check the result. If I am stuck or have not started, show a worked example rather than requiring an attempt first. End with one small change for me to try so I understand the result.

## ChatGPT prompt — review my attempt

> Review my navigation behavior and ask me to test a missing record, unknown route, back navigation, and refresh. Point me to the relevant documentation for the first failure. I will share only fictional data and remove credentials before sharing my work. You can write code and help me finish this lesson. Work in manageable steps, identify the file for each change, explain unfamiliar syntax, and give me a way to run or check the result. If I am stuck or have not started, show a worked example rather than requiring an attempt first. End with one small change for me to try so I understand the result.

## Resources

Read the relevant sections, then return to the exercise. Examples in external documentation are references to study, not a finished project to copy.

- [React Router: Declarative installation](https://reactrouter.com/start/declarative/installation)
- [React Router: Declarative routing](https://reactrouter.com/start/declarative/routing)
- [OWASP: Authorization](https://cheatsheetseries.owasp.org/cheatsheets/Authorization_Cheat_Sheet.html)

## Save your evidence

In your implementation repository’s learning journal, record what you built, one observation from a check above, one mistake you fixed, and one question you can now answer. Commit a small, understandable milestone before moving on.
