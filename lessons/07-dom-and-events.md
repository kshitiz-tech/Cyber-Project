# 07 — Make the plain HTML prototype interactive

[Previous lesson](06-arrays-objects-and-modules.md) · [Course home](../README.md) · [Next lesson](08-http-and-async.md)

## Before you start

Complete lesson 06.

## What you will learn

Understand the DOM, event listeners, form submission, default browser behavior, and rendering data as text.

## Instructions

1. Connect the report form to JavaScript in the plain HTML prototype. Read submitted values and normalize surrounding whitespace.
2. Validate the field rules before adding a fictional incident to the in-memory list. Show useful errors next to the relevant controls.
3. Display a success message and the new incident without a full page reload. Explain what your submit handler changes.
4. Add a status filter and an empty-results message. Render user-entered titles and descriptions as text instead of interpreting them as HTML.
5. Refresh the browser and observe that in-memory changes disappear. Write down why this happens; persistence comes later.

## Done when

- [ ] One submission adds exactly one incident.
- [ ] A whitespace-only title is rejected.
- [ ] Pasted angle brackets display as ordinary text; they do not create page elements.

## ChatGPT prompt — guided practice

> Help me connect my HTML form to JavaScript events. Ask me to describe what should happen from submission through validation to rendering. Explain DOM and default form behavior with JavaScript examples and help me connect them to my page. Help me test one step at a time. You can write code and help me finish this lesson. Work in manageable steps, identify the file for each change, explain unfamiliar syntax, and give me a way to run or check the result. If I am stuck or have not started, show a worked example rather than requiring an attempt first. End with one small change for me to try so I understand the result.

## ChatGPT prompt — review my attempt

> Review my event flow for duplicate handlers, unsafe HTML insertion, and missing error feedback. Explain the first issue and wait for my fix. I will share only fictional data and remove credentials before sharing my work. You can write code and help me finish this lesson. Work in manageable steps, identify the file for each change, explain unfamiliar syntax, and give me a way to run or check the result. If I am stuck or have not started, show a worked example rather than requiring an attempt first. End with one small change for me to try so I understand the result.

## Resources

Read the relevant sections, then return to the exercise. Examples in external documentation are references to study, not a finished project to copy.

- [MDN: Introduction to the DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model)
- [MDN: JavaScript fundamentals](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Scripting)
- [OWASP: Cross-site scripting prevention](https://cheatsheetseries.owasp.org/cheatsheets/Cross_Site_Scripting_Prevention_Cheat_Sheet.html)

## Save your evidence

In your implementation repository’s learning journal, record what you built, one observation from a check above, one mistake you fixed, and one question you can now answer. Commit a small, understandable milestone before moving on.
