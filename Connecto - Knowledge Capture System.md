# 

1. Purpose
This document outlines the process for capturing unstructured information related to the Connecto project. This includes meeting notes, ad-hoc ideas, tool research, and summaries of key decisions. The goal is to ensure that valuable insights are saved and organized without cluttering the formal project plans.
2. The System
We will use a combination of Markdown files within this (connecto-docs) repository and GitHub's built-in features.
A. The /reference Directory
Create a new folder named reference inside the connecto-docs repository. This folder will be the home for evergreen notes and lists.
Examples of files you would create here:
 * tools.md: A running list of tools you are considering or using.
   * Example Entry: "Cursor Pro (IDE), Figma (Prototyping), Gemini (Conversational Partner, Potential API), Vercel (Hosting), Firebase (Backend)."
 * ideas.md: A "braindump" file for random ideas that aren't ready to become formal tasks yet.
   * Example Entry: "What if users could generate a 'weekly digest' email of their activity? Could be a cool AI feature."
 * competitors.md: Notes and links to other apps in the personal knowledge management space.
B. The journal.md File
Create a single file in the root of the connecto-docs repository named journal.md. This file will serve as a chronological log of key decisions and insights. It's perfect for summarizing conversations like the one we are having.
How to use it:
After a discussion or a moment of clarity, add a new entry at the top of the file with the date.
Example Entry:
---
### 2025-07-21

**Decision:** The project will start with a public `connecto-docs` repo to "build in public" and private repos for the actual code. This balances transparency with security.

**Insight:** Realized the need for a system to capture unstructured notes. Decided to create a `/reference` directory and a `journal.md` file to log key decisions. This conversation was the catalyst.
---

C. GitHub Issues & Discussions
 * Use GitHub Issues when an idea becomes actionable. If you decide an idea from ideas.md is worth pursuing, create a new Issue for it (e.g., "Implement 'Weekly Digest' feature"). This moves it from an idea to a to-do item.
 * Use GitHub Discussions for open-ended questions you want to brainstorm, especially if you want to get feedback from others in the future.
3. Your Next Step
 * In your local clone of the connecto-docs repo, create the journal.md file.
 * Create the /reference directory.
 * Add your first entry to journal.md summarizing the decisions we've made today.
 * Commit and push the changes.
This simple system will give you a powerful way to keep your project organized as it grows in complexity.
