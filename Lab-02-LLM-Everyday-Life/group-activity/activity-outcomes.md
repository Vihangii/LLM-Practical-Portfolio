# Activity Outcomes

## The Problem

**Group 8 - The Budget-Challenged Student**

Students have many small expenses every day, like food, bus fares, printing, coffee and subscriptions. These small amounts add up quickly and it becomes hard to know where the money went.

From our research with the LLM, we found that this problem is bigger for university students in Sri Lanka because:

- Most daily spending is small cash payments (canteen food, bus fare, printing) that leave no record.
- Money is spread across many places such as cash, bank apps, eZ Cash, QR payments and PickMe, so there is no single place to see everything.
- Money does not come at regular times. Mahapola and bursary payments can be late, and money from parents or part-time work comes at different times.
- Spending is not the same every week. Assignment and exam weeks cost more because of printing and late-night food.
- Existing apps like Money Manager depend on manual entry, and most people stop using them after a short time.

## Product Name

**SpendSense**

## Product Concept

SpendSense is an AI mobile app that helps students track their spending without much effort. It collects spending from voice notes, receipts and bank SMS, sorts each expense into a category, and shows the student one simple number every day: how much they can safely spend today. Students can also ask questions about their spending in a chat and join small saving challenges.

## Target User

University students in Sri Lanka aged 18-25 who live on a monthly allowance (Mahapola, bursary or money from parents) and mostly pay in cash.

**Persona: Nethmi Perera**

> "I don't spend on anything big, but the money is always gone by the 20th."

- 21 years old, 2nd year BSc Management (Business Information Systems) student
- From Kurunegala, boarding in a shared room near campus
- Uses a mid-range Android phone with a prepaid data package
- Monthly income is around Rs. 18,000-22,000 (Mahapola, parents and some tutoring)
- Pays cash at the canteen, on the bus and at the printing shop
- Tried Money Manager in first year but gave up after 10 days
- **Goals:** get to the end of the month without asking her parents for more money, and save Rs. 15,000 for a laptop upgrade
- **Frustrations:** does not know where her money goes, Mahapola sometimes comes late, and assignment weeks break her budget

## Key Features

| Feature | Description |
|---------|-------------|
| 1. Say it, snap it | Log cash spending by voice in Sinhala, Tamil or English (e.g. "Two fifty for kottu at the canteen"), or scan a receipt. Card payments can also be added from bank SMS. |
| 2. Auto-categorise | AI reads the amount, place and payment type, and sorts the spending into food, transport, printing, social and more. The student only has to check and save. |
| 3. Safe to spend today | One daily number: the money left divided by the days until the next allowance. This is shown on the home screen. |
| 4. Ask your money | A chat where the student can ask questions like "How much did I spend on coffee this month?" or "Can I afford the trip?" |
| 5. Nudges and challenges | Early warnings (e.g. "Food is at 82% of its budget"), weekly insights, savings goals and streaks like a no-takeaway week. |

**AI inside the app:** speech-to-text and an LLM turn a voice note like "kottu 250" into a structured expense, the LLM categorises spending and answers questions in the chat, and a simple forecast keeps the daily safe-to-spend amount up to date.

## Visual Prototype / Mock-up

We described each screen and used an AI design tool to draft the five main screens, then reviewed and edited them.

| Screen | Purpose |
|--------|---------|
| [Home](../screenshots/mockup-01-home.png) | Shows the safe-to-spend amount, a budget warning, spending by category and recent expenses. |
| [Add Expense](../screenshots/mockup-02-add-expense.png) | Voice, receipt and bank SMS logging, with the details the AI understood. |
| [Ask AI](../screenshots/mockup-03-ai-chat.png) | Chat where the student asks questions about their spending. |
| [Insights](../screenshots/mockup-04-insights.png) | Weekly spending chart, AI weekly summary and monthly budgets. |
| [Challenges](../screenshots/mockup-05-challenges.png) | Active challenge, savings goal and suggested challenges. |

## How We Used the LLM

We used an LLM as our product-development partner at each step.

| Step | What we asked | What we got | Evidence |
|------|---------------|-------------|----------|
| 1. Problem research | The top 10 spending problems for students in Sri Lanka and why existing apps do not solve them | A list of problems with the reasons current apps fail | [Screenshot](../screenshots/01-problem-research.png) |
| 2. Idea generation | 6 product ideas, with the role of AI and how feasible each one is | Ideas such as a voice and photo expense logger, an SMS auto-tracker and a "runway coach" | [Screenshot](../screenshots/02-idea-generation.png) |
| 3. Idea critique | The weaknesses of our chosen idea and how to fix them | Risks such as too many features, SMS permission limits on Google Play and missing cash records | [Screenshot](../screenshots/03-idea-critique.png) |
| 4. Persona | A user persona and a one-day user journey | The persona Nethmi Perera | [Screenshot](../screenshots/04-persona.png) |
| 5. Naming | 10 names with taglines | Names such as Saviya, Runway and Dawasa | [Screenshot](../screenshots/05-naming.png) |
