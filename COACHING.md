# Learn with ChatGPT without outsourcing the learning

## Instructions

1. Read the lesson and one linked resource before asking for help.
2. Make a small attempt and record what you expected, what happened, and what you already checked.
3. Paste the lesson’s coaching prompt into ChatGPT. Share only the minimum relevant work, with fictional data and no credentials.
4. Ask for one hint at a time. Write and test the change yourself before asking for another hint.
5. Request a review after the feature works. Explain the result back in your own words and verify technical advice against the linked documentation.
6. Close the chat and rebuild one small part from memory. Return to the resource if you cannot explain it.

Do not paste entire private repositories, session cookies, API keys, or real incident reports into a chat. AI feedback can be mistaken; observed behavior, tests, and official documentation are your checks.

## ChatGPT prompt — understand a concept

> I am learning the concept named in this lesson. Explain it in plain language using an incident-tracker example, without code. Ask me one prediction question, wait for my answer, and correct my reasoning before moving on. Link the relevant official resource from this lesson.

## ChatGPT prompt — debug my attempt

> Help me debug my own work. First ask for the expected behavior, observed behavior, exact error text, relevant versions, and the smallest relevant excerpt. Propose one hypothesis and one check at a time. Do not rewrite the file or give a complete solution. Explain how the evidence supports or rejects each hypothesis.

## ChatGPT prompt — review my attempt

> Review the work I share against the lesson’s completion checks. Prioritize correctness, readability, accessibility, and security where relevant. Describe at most three improvements, explain why they matter, and let me implement them. Do not generate replacement code or claim you ran my project.

## ChatGPT prompt — check my understanding

> Ask me five questions about the lesson, one at a time. Include a prediction question, an edge case, and a request to explain a design choice. Wait for each answer and give feedback. End with one small exercise I should complete independently, without a solution.

## Resources

Use [MDN’s JavaScript curriculum](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Scripting) for fundamentals and [React’s learning guide](https://react.dev/learn) for component behavior. Use [Testing Library’s query guidance](https://testing-library.com/docs/queries/about/) to connect interface behavior to verifiable tests. These are technical references; the prompts above are original coaching templates.
