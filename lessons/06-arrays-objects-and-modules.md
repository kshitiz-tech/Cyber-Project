# 06 — Organize and transform incident records

[Previous lesson](05-javascript-foundations.md) · [Course home](../README.md) · [Next lesson](07-dom-and-events.md)

## Before you start

Complete lesson 05.

## What you will learn

Learn objects, arrays, stable identifiers, mapping, filtering, finding, immutable updates, and module imports.

## Instructions

1. Represent five fictional incidents using the fields in the project brief. Give each a stable identifier; the title is not an identifier.
2. Write separate functions to find one incident, filter by status, and count incidents by severity.
3. Add a combined text-and-status search. Decide and document whether search ignores capitalization and surrounding spaces.
4. Update one record while preserving the original collection. Explain why a changed list should not accidentally modify another copy.
5. Move reusable data operations into a separate module in your application. Describe its inputs and outputs before importing it.

## Done when

- [ ] Two incidents with identical titles still remain distinct.
- [ ] A search with no matches returns an empty collection without an error.
- [ ] You can explain mapping versus filtering and show that your update preserves the original.

## ChatGPT prompt — guided practice

> Coach me on JavaScript arrays, objects, and modules using fictional incidents. Give me a plain-language filtering challenge, ask for my attempt, and then test my reasoning with an edge case. Provide example functions and help me adapt them to my records. You can write code and help me finish this lesson. Work in manageable steps, identify the file for each change, explain unfamiliar syntax, and give me a way to run or check the result. If I am stuck or have not started, show a worked example rather than requiring an attempt first. End with one small change for me to try so I understand the result.

## ChatGPT prompt — review my attempt

> Review my data functions for mutation, missing identifiers, and combined filters. Ask me to demonstrate the issue using a small example before I fix it. I will share only fictional data and remove credentials before sharing my work. You can write code and help me finish this lesson. Work in manageable steps, identify the file for each change, explain unfamiliar syntax, and give me a way to run or check the result. If I am stuck or have not started, show a worked example rather than requiring an attempt first. End with one small change for me to try so I understand the result.

## Resources

Read the relevant sections, then return to the exercise. Examples in external documentation are references to study, not a finished project to copy.

- [MDN: JavaScript fundamentals](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Scripting)
- [MDN: Array reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)

## Save your evidence

In your implementation repository’s learning journal, record what you built, one observation from a check above, one mistake you fixed, and one question you can now answer. Commit a small, understandable milestone before moving on.
