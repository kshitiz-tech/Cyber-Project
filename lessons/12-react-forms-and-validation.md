# 12 — Create incidents in React

[Previous lesson](11-react-state-and-filtering.md) · [Course home](../README.md) · [Next lesson](13-routing-and-details.md)

## Before you start

Complete lesson 11.

## What you will learn

Learn controlled inputs, form state, validation, error feedback, submission, and reset behavior.

## Instructions

1. Rebuild the accessible report form in React. Decide how each field value is represented and updated.
2. Apply the project brief’s title, description, category, and severity rules. Treat whitespace-only content as empty.
3. On success, add a new incident with a stable identifier, initial Open status, and a creation time. Reset the form only after success.
4. Keep entered values after a validation failure. Move focus to useful feedback and make errors understandable without color.
5. Check repeated submissions and submit-button behavior. In this frontend milestone there is no server; make that limitation visible.

## Done when

- [ ] A valid report appears once with all required fields.
- [ ] Invalid submission preserves the learner’s input and explains the error.
- [ ] Dashboard counts update after creation and the form is keyboard usable.

## ChatGPT prompt — guided practice

> Coach me through a controlled React form for incident reports. Ask me to describe field state, validation rules, and what happens on success or failure. Help me implement one part at a time with explained code for inputs, validation, and submission. You can write code and help me finish this lesson. Work in manageable steps, identify the file for each change, explain unfamiliar syntax, and give me a way to run or check the result. If I am stuck or have not started, show a worked example rather than requiring an attempt first. End with one small change for me to try so I understand the result.

## ChatGPT prompt — review my attempt

> Review my form using empty values, whitespace, maximum lengths, an invalid category, and repeated submission. Provide the corrected implementation and explain the validation and feedback changes. I will share only fictional data and remove credentials before sharing my work. You can write code and help me finish this lesson. Work in manageable steps, identify the file for each change, explain unfamiliar syntax, and give me a way to run or check the result. If I am stuck or have not started, show a worked example rather than requiring an attempt first. End with one small change for me to try so I understand the result.

## Resources

Read the relevant sections, then return to the exercise. Examples in external documentation are references to study, not a finished project to copy.

- [React: Input reference](https://react.dev/reference/react-dom/components/input)
- [W3C: Accessible forms tutorial](https://www.w3.org/WAI/tutorials/forms/)
- [React: State, a component’s memory](https://react.dev/learn/state-a-components-memory)

## Save your evidence

In your implementation repository’s learning journal, record what you built, one observation from a check above, one mistake you fixed, and one question you can now answer. Commit a small, understandable milestone before moving on.
