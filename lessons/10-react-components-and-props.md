# 10 — Split the dashboard into components

[Previous lesson](09-react-and-vite.md) · [Course home](../README.md) · [Next lesson](11-react-state-and-filtering.md)

## Before you start

Complete lesson 09.

## What you will learn

Learn component boundaries, JSX, props, composition, conditional rendering, lists, and stable keys.

## Instructions

1. Mark reusable pieces on your dashboard sketch: page layout, summary card, incident list, incident card, and status badge.
2. Build one static incident card yourself, then make its content come from props. Keep the fictional records outside the presentation details.
3. Render the incident collection using stable incident identifiers as keys. Explain why the position in a filtered list is not a stable identity.
4. Add a useful empty-list view. Keep text labels for status and severity alongside any colors.
5. Draw which component owns each piece of information and which child receives it. Avoid dividing every single element into a new component.

## Done when

- [ ] Changing a record changes its displayed card without editing card markup.
- [ ] Duplicate titles do not cause identity problems.
- [ ] You can explain props and why a child should not mutate them.

## ChatGPT prompt — guided practice

> Help me decompose my incident dashboard into React components. Ask me where each component’s responsibility begins and ends. Explain props and stable list keys, then ask me to implement one component. Suggest a component tree and provide JSX for one component at a time, explaining its props and responsibilities. You can write code and help me finish this lesson. Work in manageable steps, identify the file for each change, explain unfamiliar syntax, and give me a way to run or check the result. If I am stuck or have not started, show a worked example rather than requiring an attempt first. End with one small change for me to try so I understand the result.

## ChatGPT prompt — review my attempt

> Review my components for duplicated markup, unnecessary splitting, prop mutation, and unstable keys. Explain the most important issue and show corrected code, identifying which file to change. I will share only fictional data and remove credentials before sharing my work. You can write code and help me finish this lesson. Work in manageable steps, identify the file for each change, explain unfamiliar syntax, and give me a way to run or check the result. If I am stuck or have not started, show a worked example rather than requiring an attempt first. End with one small change for me to try so I understand the result.

## Resources

Read the relevant sections, then return to the exercise. Examples in external documentation are references to study, not a finished project to copy.

- [React: Thinking in React](https://react.dev/learn/thinking-in-react)
- [React: Passing props to a component](https://react.dev/learn/passing-props-to-a-component)
- [React: Rendering lists](https://react.dev/learn/rendering-lists)

## Save your evidence

In your implementation repository’s learning journal, record what you built, one observation from a check above, one mistake you fixed, and one question you can now answer. Commit a small, understandable milestone before moving on.
