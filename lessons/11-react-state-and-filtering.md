# 11 — Add state and interactive filters

[Previous lesson](10-react-components-and-props.md) · [Course home](../README.md) · [Next lesson](12-react-forms-and-validation.md)

## Before you start

Complete lesson 10.

## What you will learn

Learn state, event handlers, render cycles, immutable updates, shared state, and derived values.

## Instructions

1. Store the incident collection in a shared parent component. Identify which children need the records and which need callbacks.
2. Add text search, status filtering, and severity filtering. Decide whether filters combine and make the behavior explicit.
3. Derive the visible list and summary counts from the source data. Avoid storing duplicate copies of values you can calculate while rendering.
4. Allow a demo status update using an immutable record update. Explain why editing an existing object directly can cause confusing behavior.
5. Add clear-filter and no-results states. Test filtering after changing an incident’s status.

## Done when

- [ ] Filters combine consistently and clear correctly.
- [ ] A status change updates the list and dashboard counts together.
- [ ] You can distinguish source state from derived information.

## ChatGPT prompt — guided practice

> Teach me React state using my incident filters. Ask me to list what can change and what can be calculated. Help me choose a state owner and predict a render after an event. Do not write hooks or handlers for me.

## ChatGPT prompt — review my attempt

> Review my state design for duplicated derived values and mutation. Give me one sequence of user actions that could expose a bug, then let me investigate. I will share only fictional data and remove credentials before sharing my work.

## Resources

Read the relevant sections, then return to the exercise. Examples in external documentation are references to study, not a finished project to copy.

- [React: State, a component’s memory](https://react.dev/learn/state-a-components-memory)
- [React: Sharing state between components](https://react.dev/learn/sharing-state-between-components)
- [React: Updating arrays in state](https://react.dev/learn/updating-arrays-in-state)
- [React: You might not need an effect](https://react.dev/learn/you-might-not-need-an-effect)

## Save your evidence

In your implementation repository’s learning journal, record what you built, one observation from a check above, one mistake you fixed, and one question you can now answer. Commit a small, understandable milestone before moving on.
