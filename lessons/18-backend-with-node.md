# 18 — Optional: build an API with Node.js and Express

[Previous lesson](17-deployment-and-portfolio.md) · [Course home](../README.md) · [Next lesson](19-database-and-sql.md)

## Before you start

Finish the frontend milestone through lesson 17 before starting this extension.

## What you will learn

Learn server-side JavaScript, API contracts, request parsing, server validation, responses, and error handling.

## Instructions

1. Keep this first API local. Add a separate server area in your implementation repository and follow the current Node.js and Express setup resources.
2. Write a plain-language API contract for listing incidents, reading one, creating one, and changing status. Define required fields and expected success and failure responses.
3. Implement one operation at a time with fictional in-memory records. Validate every incoming field on the server even if React already checks it.
4. Limit request sizes, reject unsupported fields, and return useful errors without stack traces or secrets. An in-memory collection resets when the server restarts.
5. Compare CORS, authentication, and authorization. A CORS setting is not a permission check. Do not expose this unauthenticated practice API as a real incident service.

## Done when

- [ ] A direct request with invalid data is rejected independently of the React form.
- [ ] Unknown records and malformed requests receive intentional error responses.
- [ ] Explain browser JavaScript versus server JavaScript and why this API is not yet protected.

## ChatGPT prompt — guided practice

> Coach me through planning a local Node.js and Express incident API. Start with an operation’s request, validation, and response contract. Ask me to implement one behavior and verify it directly. Help me write the server code one operation at a time and explain why CORS is not authentication. You can write code and help me finish this lesson. Work in manageable steps, identify the file for each change, explain unfamiliar syntax, and give me a way to run or check the result. If I am stuck or have not started, show a worked example rather than requiring an attempt first. End with one small change for me to try so I understand the result.

## ChatGPT prompt — review my attempt

> Review my API contract and server behavior for malformed requests, unsupported fields, excessive input, and missing records. Ask for observed responses before suggesting improvements. I will share only fictional data and remove credentials before sharing my work. You can write code and help me finish this lesson. Work in manageable steps, identify the file for each change, explain unfamiliar syntax, and give me a way to run or check the result. If I am stuck or have not started, show a worked example rather than requiring an attempt first. End with one small change for me to try so I understand the result.

## Resources

Read the relevant sections, then return to the exercise. Examples in external documentation are references to study, not a finished project to copy.

- [Node.js: Introduction](https://nodejs.org/learn/getting-started/introduction-to-nodejs)
- [Express: Installation](https://expressjs.com/en/starter/installing/)
- [Express: Routing](https://expressjs.com/en/guide/routing/)
- [Express: Production security practices](https://expressjs.com/en/advanced/best-practice-security/)
- [MDN: Overview of HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Guides/Overview)

## Save your evidence

In your implementation repository’s learning journal, record what you built, one observation from a check above, one mistake you fixed, and one question you can now answer. Commit a small, understandable milestone before moving on.
