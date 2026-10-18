# 04 — Make the layout work on phones

[Previous lesson](03-css-basics.md) · [Course home](../README.md) · [Next lesson](05-javascript-foundations.md)

## Before you start

Complete lesson 03.

## What you will learn

Learn Flexbox, Grid, relative sizing, media queries, responsive layouts, and accessible reflow.

## Instructions

1. Start with a single-column phone layout. Arrange navigation and incident cards without fixed desktop widths.
2. Use Flexbox for a row of controls and Grid for the summary cards. Explain why each fits its task.
3. Add a breakpoint when content becomes cramped rather than choosing a device brand. Allow long incident titles to wrap.
4. Test a narrow viewport, a wide viewport, and 200 percent browser zoom. Inspect overflow rather than hiding it globally.
5. Check focus order and touch target usability. Capture a phone-width and desktop-width screenshot.

## Done when

- [ ] At approximately 320 CSS pixels wide, ordinary page content needs no horizontal scrolling.
- [ ] At 200 percent zoom, controls and important text are still usable.
- [ ] Layout changes do not make keyboard navigation confusing.

## ChatGPT prompt — guided practice

> Help me reason about a responsive incident dashboard. Ask me to describe the content and identify which part overflows first. Explain when to use Flexbox or Grid without writing CSS. Give me a short manual testing plan.

## ChatGPT prompt — review my attempt

> Use my screenshots and CSS to identify one layout cause at a time. Explain how I can verify each hypothesis in developer tools; do not rewrite the page. I will share only fictional data and remove credentials before sharing my work.

## Resources

Read the relevant sections, then return to the exercise. Examples in external documentation are references to study, not a finished project to copy.

- [MDN: CSS layout](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout)
- [MDN: CSS styling basics](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics)
- [W3C: Easy accessibility checks](https://www.w3.org/WAI/test-evaluate/easy-checks/)

## Save your evidence

In your implementation repository’s learning journal, record what you built, one observation from a check above, one mistake you fixed, and one question you can now answer. Commit a small, understandable milestone before moving on.
