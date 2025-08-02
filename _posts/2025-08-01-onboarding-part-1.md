---

layout: post
title:  "Onboarding a QA Engineer: Part 1 – Onboarding Plan"
date:   2025-08-01
categories: general
-------------------

# Onboarding a QA Engineer: Part 1 – Onboarding Plan

*Help your new QA deliver meaningful value in their very first weeks.*

You can't overestimate the importance of those first 3–6 months when a new person joins your team. It's exciting and, at the same time, a bit terrifying — for both the newcomer and the team. Will they succeed? Will they fit in? Will they find everything they need to get started?

Here’s how to craft an onboarding plan for a mid‑level Exploratory QA at ReSharper (20-year-old Visual Studio extension that enhances the IDE for C# and .NET developers). But where do we start?

# 1. Kick Off with Exploration 🔍

I believe it’s always good to begin with exploration — just as we do in testing. Before you start creating your own onboarding plan, ask yourself:

1. Does your company have corporate onboarding?
2. How do other teams within your organization approach this?
3. How was your own onboarding?
4. What do ChatGPT or Google “think” about it?

You don’t need to invent everything from scratch!

So, let's see what JetBrains has.

1. **Does your company have corporate onboarding?** — Yes. There is “Preboarding,” such as hardware preparation and account creation, and “Onboarding,” such as a meeting with HR about company policies. That means our onboarding plan will skip these topics and instead include a “Take part in corporate onboarding” step.
2. **How do other teams within your organization approach this?** — I found several articles in our Knowledge Base. Approaches vary from “3 months learning” to “assign a task in week 1,” from “everything you need to know is here” to “nothing is here, let's talk.” Though the structure itself and the links to the resources were useful, and I have transferred them to my onboarding plan.
3. **How was your own onboarding?** — I participated in team meetings and team lunches from day 1, and my first two weeks were all about reading ReSharper documentation. In the long run, it was extremely useful, as I became familiar with all ReSharper features.
4. **What do ChatGPT or Google “think” about it?** — I found [a nice article](https://povio.com/blog/effective-qa-onboarding-strategies-a-comprehensive-guide) with general principles and things you should not miss. ChatGPT was helpful with proofreading the plan and suggesting improvements.

# 2. Continue with Goals 🎯

Onboarding milestones are easy to identify. In most cases they are the first week, first month, and three months/end of the probation period. To align expectations, we need to set clear goals and discuss them with the new employee. Think about your project: its complexity and processes, your deadlines, QA tasks. Here is an example of the goals:

**Week 1**

1. **Is familiar with the company and the team(s)** — corporate onboarding; can’t skip and takes time.
2. **Participates in team meetings** — getting familiar with the team.
3. **All needed tools are installed; products are working** — setup is finished.

I consciously did not add any product-related goals, because time allows us to spend the first week on “acclimatization.”

**Month 1**

1. **Independently handles triage in YouTrack** — one of the QA task areas, easy to do.
2. **Is familiar with basic ReSharper and AI functionality** — the product is very complex and learning takes time, so only basic functionality is included in first-month goals.
3. **Handles simple testing tasks with minimal assistance** — the environment is fast-paced and resources are stretched; independence in simple tasks is required.
4. **Creates clear and well-structured issue reports** — one of the QA task areas; important to do immediately.
5. **Fully integrated into processes: QA board, information collection, checklists for testing and for automation, team collaboration** — familiarity with processes is the basis for productive work.

The overall goal is to be familiar with the basics and start applying them in practice.

**Month 3**

1. **Is familiar with all ReSharper and AI functionality**
2. **Has an understanding of the product’s architecture**
3. **Handles complex testing tasks with minimal assistance**

I expect the new QA to work independently and productively after three months.

# 3. Create a Mentor’s Checklist 📋

Remember that there are other participants in onboarding. They too should know what is expected of them. I suggest creating a mentor’s checklist for that. Start writing it down in parallel with the onboarding doc. That way you will not miss anything, and both docs will be in sync.

* [ ] A welcome letter is sent one week before the start date
* [ ] Make sure hardware is ready
* [ ] Share onboarding plan
* [ ] Create a meeting to discuss goals & onboarding plan
* [ ] Add to Slack channels
* [ ] Make a short intro on syncs
* [ ] Create daily 1-1 meetings

# 4. Draft an Onboarding Doc 📄

Use the usual platform for sharing information in your company. Consider the following structure and adapt it to your needs:

1. **Introduction** — Greetings and a short description of what will happen next.
2. **Role overview** — What the person will be doing.
3. **Team and contacts** — Team leads and points of contact within the team(s).
4. **Phases** — Break every onboarding step into 1-2-week periods.
5. **Initial setup** — Mention all software that needs to be installed and where to find it.
6. **Corporate onboarding** - 
7. **Links to employee guide, HR platform**
8. **Licenses** — Mention what licenses the person will need and how to obtain them.
9. **Team meetings** — Meetings that the new person will participate in.
10. **Essential information about the product** — Links to internal videos, documentation, knowledge base, and other resources.
11. **QA tasks** — Describe what types of tasks QA does in your company.
12. **Processes** — Describe the processes in detail: how tasks are handed over to testing, how QAs interact with developers and product owners, how releases happen, which quality gates you have.
13. **Useful links** — Links to additional articles and resources.

If the platform allows it, use checkboxes for tasks so that progress is visible. Don’t hesitate to arrange “get familiar with the tool or process” meetings if something is complex and you don’t have written documentation for it.

# 5. Send the Draft for Review 📤 

My first-line reviewer is ChatGPT. In some cases it works; in some it does not, but I always try. Here I used the following prompt:

```
Hi. You are an exceptionally skilled manual QA Lead with more than 10 years of experience in the software-development industry. You need to create an onboarding plan for a middle manual QA engineer. Here is the plan:

...

Please review it. What is missing? What is unclear?
```

The second-line reviewer is a person. If you have someone experienced in onboarding, ask them for a review. If not, ask the team member with the most knowledge about products, teams, and processes. Listen to their comments and update the draft accordingly.

# 6. Do a Final Cleanup ✨

ChatGPT can also help you with proofreading. Read it one last time and leave it. Yes, it is not perfect, especially if it's your first time doing this. But no matter how imperfect it is, it is still valuable, and only applying it in real life will help make it better. So try it!

Happy onboarding!
