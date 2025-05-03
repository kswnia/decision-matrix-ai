<p align="center">
  <img src="https://github.com/user-attachments/assets/9b1450bd-a2cd-415e-8d04-202477d7dc9f" width="600"/>
</p>


# Semantic Decision Intelligence System

This is a tool that helps teams and organizations **see how decisions are made**, where they may be going off-track, and how to fix issues before they turn into serious problems.

It combines clear structure (like a timeline or matrix view) with a smarter, more visual map that shows hidden patterns in how decisions connect and evolve.

---

## Why This Exists

As companies grow, decision-making often becomes messy:

- Ownership changes hands too often.
- Teams revisit the same questions over and over.
- Chaos creeps in silently — no one sees the pattern until it’s too late.

This tool helps you catch those patterns early.  
It shows you:

- Where decision loops and fatigue are happening.
- Which decisions may be risky or need a second look.
- How different decisions connect across teams — even when it’s not obvious.

---

## What You Can Do With It

### 1. **Matrix View (Structured Overview)**

- See decisions over time across your org structure.
- Rows = teams, columns = weeks or months.
- Each cell is color-coded:
  - Red = needs review
  - Yellow = drifting or unclear
  - Green = healthy, scalable
- Click a decision to view its timeline, owners, and history.

![Screenshot 2025-05-03 085329](https://github.com/user-attachments/assets/f48a7a9c-d91f-4844-97b0-516b37f0ddfe)
![Frame 61](https://github.com/user-attachments/assets/63fd1281-4daa-4a23-8957-19806e17cecb)

### 2. **Semantic Map (Exploration View)**

- A separate, full-page map that groups similar decisions together based on meaning.
- Each dot = a decision or task.
  - Size = importance
  - Color = health
- You can zoom, pan, filter by type or risk level.
- Great for spotting hidden clusters of problems or insights you wouldn’t see in a spreadsheet or timeline.


https://github.com/user-attachments/assets/e7d0b340-379c-42a4-976d-735048307143

https://github.com/user-attachments/assets/2026f24c-7dbd-41e3-84b3-7d7321c03f41




---

## How It Works

1. It gathers decisions and tasks from tools you already use (like Jira, Notion, Slack, Confluence).
2. It looks at **how** decisions were made — not just what was decided.
3. It uses simple rules and language models to find signals like:
   - Were there too many revisions?
   - Did the owner change a lot?
   - Was the process unclear or rushed?
4. It then visualizes everything so you can explore and act.

---

## What’s In This Version (v0)

- Static JSON sample data
- Integrations into calls
- Matrix view with red/yellow/green attention markers
- Semantic map built from example embeddings
- Hover and click support
- Side panel with decision history

---

How It Decides What’s Risky

It looks at signals like:

    How long did the decision take?

    How many times was it revised?

    Did ownership change mid-way?

    Was the language overcomplicated or missing key pieces?

    Was the decision reversed after being made?

Then it classifies them as:

    Green: Healthy and clear

    Yellow: Needs watching

    Red: Unstable or unclear — better review it

What’s Coming Next

    Live connection to Jira and Notion

    Story view: “how did this decision unfold?”

    Filters that link both views

    Time-lapse: watch chaos or clarity emerge over time

    Smarter risk predictions using AI

License

To be decided. For now, personal or internal use only.


Get Involved

We’re just getting started.

If you want to contribute, test, or integrate this into your org’s decision systems, contact:

**DM me. [![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/kseniya-hudacheuskaya-0037b8264/)
 Let’s plug this into your team and break the bottlenecks for good.**
