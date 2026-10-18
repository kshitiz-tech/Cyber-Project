# 16 — Test behavior and usability

[Previous lesson](15-web-security-review.md) · [Course home](../README.md) · [Next lesson](17-deployment-and-portfolio.md)

## Before you start

Complete lesson 15.

## What you will learn

Learn unit tests, component interaction tests, boundary cases, regression tests, and manual accessibility checks.

## Instructions

1. Use Vitest and React Testing Library’s current guides to set up tests in your application. Choose a supported browser-like test environment for component tests.
2. Test data filtering, allowed values, and immutable updates separately from the user interface.
3. Test valid report creation, invalid submission, combined filters, no results, and missing detail records through user-visible controls.
4. Prefer queries using accessible roles and names. Give persistence tests isolated storage and reset it between tests.
5. Deliberately break a behavior and confirm its test fails, then repair it. Manually check keyboard operation, visible focus, labels, narrow screens, and zoom.

## Done when

- [ ] At least one test proves invalid input is rejected and one proves a valid report is created.
- [ ] Tests are independent of execution order and previous browser storage.
- [ ] A deliberate regression produces a failure, and manual accessibility findings are documented.

## ChatGPT prompt — guided practice

> Help me design meaningful tests for my incident tracker. Ask which user behavior each test protects, then help me choose inputs and expected outcomes. Use Vitest and React Testing Library documentation. Do not generate test code.

## ChatGPT prompt — review my attempt

> Review my tests for assertions that would still pass if the feature were broken. Ask me to demonstrate a failing regression and explain any missing edge case. I will share only fictional data and remove credentials before sharing my work.

## Resources

Read the relevant sections, then return to the exercise. Examples in external documentation are references to study, not a finished project to copy.

- [Vitest: Getting started](https://vitest.dev/guide/)
- [Testing Library: React introduction](https://testing-library.com/docs/react-testing-library/intro/)
- [Testing Library: Choosing queries](https://testing-library.com/docs/queries/about/)
- [W3C: Easy accessibility checks](https://www.w3.org/WAI/test-evaluate/easy-checks/)

## Save your evidence

In your implementation repository’s learning journal, record what you built, one observation from a check above, one mistake you fixed, and one question you can now answer. Commit a small, understandable milestone before moving on.
