# 15 — Review the React demo as a security student

[Previous lesson](14-effects-and-local-storage.md) · [Course home](../README.md) · [Next lesson](16-testing-and-accessibility.md)

## Before you start

Complete lesson 14.

## What you will learn

Learn trust boundaries, unsafe rendering, client-side limitations, exposed frontend configuration, and basic threat modeling.

## Instructions

1. Draw the browser, user input, local storage, and static host. Label everything a visitor can inspect or change.
2. Review how titles and descriptions are rendered. Keep them as ordinary text; do not introduce rich HTML rendering for this project.
3. Inspect the built frontend and configuration. Explain why frontend environment variables cannot hold private API keys or server secrets.
4. Write a small threat table with an asset, a misuse scenario, a mitigation, and a verification step. Include altered local data, unsafe rendering, and a fake admin flag.
5. Label the app as a frontend learning demo with fictional data. Reserve real authentication and authorization claims for the backend extension and its tests.

## Done when

- [ ] Explain why local storage and hidden controls cannot enforce permission.
- [ ] User text remains text in the interface.
- [ ] List three limitations of the demo and a test or inspection supporting each security claim.

## ChatGPT prompt — guided practice

> Act as a patient security reviewer of my React learning demo. Ask me to draw its trust boundaries and explain what users can modify. Walk through rendering, browser storage, and frontend configuration. Do not generate attack code or claim the app is secure without evidence.

## ChatGPT prompt — review my attempt

> Review my threat table and distinguish a verified safeguard from an assumption. Ask for the evidence behind each claim and suggest one small defensive improvement. I will share only fictional data and remove credentials before sharing my work.

## Resources

Read the relevant sections, then return to the exercise. Examples in external documentation are references to study, not a finished project to copy.

- [OWASP: Cross-site scripting prevention](https://cheatsheetseries.owasp.org/cheatsheets/Cross_Site_Scripting_Prevention_Cheat_Sheet.html)
- [OWASP: Authorization](https://cheatsheetseries.owasp.org/cheatsheets/Authorization_Cheat_Sheet.html)
- [Vite: Environment variables and modes](https://vite.dev/guide/env-and-mode.html)
- [OWASP: Threat modeling](https://cheatsheetseries.owasp.org/cheatsheets/Threat_Modeling_Cheat_Sheet.html)

## Save your evidence

In your implementation repository’s learning journal, record what you built, one observation from a check above, one mistake you fixed, and one question you can now answer. Commit a small, understandable milestone before moving on.
