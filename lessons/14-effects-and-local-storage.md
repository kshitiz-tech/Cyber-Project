# 14 — Keep fictional demo data after refresh

[Previous lesson](13-routing-and-details.md) · [Course home](../README.md) · [Next lesson](15-web-security-review.md)

## Before you start

Complete lesson 13.

## What you will learn

Understand persistence, serialization, effects, external synchronization, initialization, and recovery from bad stored data.

## Instructions

1. Read the storage and effect resources. Decide which work is a user event, a derived calculation, or synchronization with browser storage.
2. Initialize from saved demo incidents when available. Validate the stored structure, allowed values, and required fields before trusting it.
3. Save changes without overwriting existing data with an empty initial collection. Test startup and development-mode repeated effect execution.
4. Handle corrupted storage, unavailable storage, and write failures with a clear message and a usable in-memory fallback.
5. Add a confirmed reset-demo action. Use fictional reports only; local storage is editable, browser-specific, and unsuitable for credentials or confidential incidents.

## Done when

- [ ] Created reports survive refresh in the same browser.
- [ ] Corrupt or unavailable storage does not crash the app.
- [ ] Reset restores a predictable demo state, and filter calculations do not need an effect.

## ChatGPT prompt — guided practice

> Help me design browser persistence for fictional incident data. Ask how I will initialize, validate, save, and recover before discussing effects. Explain the danger of saving an empty initial state over existing data. Do not write code.

## ChatGPT prompt — review my attempt

> Review my persistence lifecycle. Ask me to test refresh, corrupted data, denied storage, and repeated effects. Help me locate the cause of one failure without supplying a solution. I will share only fictional data and remove credentials before sharing my work.

## Resources

Read the relevant sections, then return to the exercise. Examples in external documentation are references to study, not a finished project to copy.

- [MDN: Browser local storage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)
- [React: Synchronizing with effects](https://react.dev/learn/synchronizing-with-effects)
- [React: You might not need an effect](https://react.dev/learn/you-might-not-need-an-effect)

## Save your evidence

In your implementation repository’s learning journal, record what you built, one observation from a check above, one mistake you fixed, and one question you can now answer. Commit a small, understandable milestone before moving on.
