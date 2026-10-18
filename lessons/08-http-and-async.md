# 08 — Understand requests and asynchronous work

[Previous lesson](07-dom-and-events.md) · [Course home](../README.md) · [Next lesson](09-react-and-vite.md)

## Before you start

Complete lesson 07.

## What you will learn

Learn client versus server, URLs, HTTP methods and status codes, JSON, promises, async work, and request failures.

## Instructions

1. Draw the path from a browser request to a server response. Label which side runs JavaScript and where data might be stored.
2. Inspect a request from your own local development server in the Network panel. Identify its URL, method, status, and response.
3. When the Vite server is available in lesson 09, load a local fictional data file over HTTP as a separate practice exercise. Do not depend on an unrelated public API.
4. Plan idle, loading, success, empty, and error screens. Distinguish an HTTP failure response from a network failure.
5. Simulate offline mode or a missing local file. Explain why a request can complete yet still represent an error. Revisit this exercise after lesson 09 if you do not yet have a local server.

## Done when

- [ ] Explain JSON versus a JavaScript object.
- [ ] Recognize a failed HTTP status separately from a rejected network request.
- [ ] Describe what a user should see during loading and failure.

## ChatGPT prompt — guided practice

> Teach me HTTP and asynchronous JavaScript using a local incident-data request. First check whether my local development server is ready. Explain the request lifecycle and ask me to inspect Network details. Provide a working request example and explain how to implement loading, empty, and failure states. You can write code and help me finish this lesson. Work in manageable steps, identify the file for each change, explain unfamiliar syntax, and give me a way to run or check the result. If I am stuck or have not started, show a worked example rather than requiring an attempt first. End with one small change for me to try so I understand the result.

## ChatGPT prompt — review my attempt

> Review my request handling and ask how it behaves for offline mode, a missing file, malformed data, and success. Provide an improved version and explain how it handles each failure. I will share only fictional data and remove credentials before sharing my work. You can write code and help me finish this lesson. Work in manageable steps, identify the file for each change, explain unfamiliar syntax, and give me a way to run or check the result. If I am stuck or have not started, show a worked example rather than requiring an attempt first. End with one small change for me to try so I understand the result.

## Resources

Read the relevant sections, then return to the exercise. Examples in external documentation are references to study, not a finished project to copy.

- [MDN: Overview of HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Guides/Overview)
- [MDN: Using Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch)

## Save your evidence

In your implementation repository’s learning journal, record what you built, one observation from a check above, one mistake you fixed, and one question you can now answer. Commit a small, understandable milestone before moving on.
