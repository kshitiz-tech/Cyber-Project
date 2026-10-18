# 19 — Optional: persist records with SQLite

[Previous lesson](18-backend-with-node.md) · [Course home](../README.md) · [Next lesson](20-authentication-and-permissions.md)

## Before you start

Complete lesson 18.

## What you will learn

Learn tables, rows, primary keys, relationships, constraints, parameterized queries, transactions, and persistence.

## Instructions

1. Draw tables for users, incidents, and status-history events. Specify identifiers, ownership, timestamps, and relationships before implementing them.
2. Choose a maintained SQLite driver compatible with your installed Node.js release and read its official documentation. Record the choice and resource link in your implementation notes.
3. Replace in-memory data access one operation at a time. Use parameters for user-supplied query values rather than assembling SQL from user input.
4. Add constraints for required fields and allowed values. Configure foreign-key enforcement for the chosen SQLite connection and verify that an orphaned relationship is rejected.
5. Use a transaction when a status change and its history entry must succeed together. Keep database files and local secrets out of version control; use fictional seed records.

## Done when

- [ ] Records survive a server restart.
- [ ] A title containing an apostrophe is stored correctly without changing query meaning.
- [ ] An invalid relationship is rejected and a failed transaction leaves no half-completed status change.

## ChatGPT prompt — guided practice

> Teach me relational database design for users, incidents, and status history. Ask me to explain the relationships first. Help me choose a maintained SQLite driver from its official documentation, then plan parameterized queries and transaction tests. Provide schema and parameterized-query examples for my selected driver, explain them, and help me integrate them. You can write code and help me finish this lesson. Work in manageable steps, identify the file for each change, explain unfamiliar syntax, and give me a way to run or check the result. If I am stuck or have not started, show a worked example rather than requiring an attempt first. End with one small change for me to try so I understand the result.

## ChatGPT prompt — review my attempt

> Review my schema and data-access approach. Ask how I verified parameter binding, foreign keys, server restart persistence, and transaction rollback; explain one missing safeguard at a time. I will share only fictional data and remove credentials before sharing my work. You can write code and help me finish this lesson. Work in manageable steps, identify the file for each change, explain unfamiliar syntax, and give me a way to run or check the result. If I am stuck or have not started, show a worked example rather than requiring an attempt first. End with one small change for me to try so I understand the result.

## Resources

Read the relevant sections, then return to the exercise. Examples in external documentation are references to study, not a finished project to copy.

- [SQLite: SQL language reference](https://www.sqlite.org/lang.html)
- [OWASP: SQL injection prevention](https://cheatsheetseries.owasp.org/cheatsheets/SQL_Injection_Prevention_Cheat_Sheet.html)
- [Node.js: Introduction](https://nodejs.org/learn/getting-started/introduction-to-nodejs)

## Save your evidence

In your implementation repository’s learning journal, record what you built, one observation from a check above, one mistake you fixed, and one question you can now answer. Commit a small, understandable milestone before moving on.
