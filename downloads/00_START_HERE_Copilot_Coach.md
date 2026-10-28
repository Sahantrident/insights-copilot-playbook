# 🎓 START HERE: learn Copilot on your own with this kit

**The Insights Initiative × Microsoft 365 Copilot · Self-learning guide · v1.0 (October 2026)**

This kit turns Copilot into your personal coach. It walks you through **10 short missions** (about 15 minutes each) using the sample files in this folder, then checks your results.

> ⚠️ All files in this kit are **fictional sample data** made for practice. They are not real Insights, donor, partner or respondent data, so you can experiment freely.

---

## 1. Set up (10 minutes, do this once)

| Step | What to do |
|---|---|
| 1 | **Unzip** `Insights_Demo_Data.zip` on your computer. |
| 2 | **Upload the whole folder to OneDrive** (for example `OneDrive › Copilot Practice › Insights_Demo_Data`). Copilot in Excel, Word and PowerPoint only works on files saved in OneDrive or SharePoint. |
| 3 | **Wait a little.** New files can take from a few minutes to a few hours before Copilot can find them. Uploading the day before works best. |
| 4 | **Choose where to run the coach** (see below). |

### Where to run the coach

| Option | Best for | How |
|---|---|---|
| ⭐ **Copilot Notebook** (recommended) | Coming back over several days | Microsoft 365 Copilot → **Notebooks** → **New notebook** → name it "Insights Copilot Practice" → add the kit files as references → paste the coach prompt below. Everything stays in one place, so you can pick up where you left off. |
| 💬 **Copilot Chat (Work mode)** | A single session | Microsoft 365 Copilot Chat → switch to **Work** → paste the coach prompt below. At the start of each later session, paste it again and say which mission you're on. |
| 📎 **No Copilot licence?** | Copilot Chat users | Paste the coach prompt, then **upload each file into the chat** when the coach asks for it. Missions 3, 4, 5 and 7 need a licence (they run inside Excel, Word or PowerPoint), so read those instead of doing them. |

> 💡 Menu names in Microsoft 365 change often. If a button has a slightly different name, look for the closest match. Notebooks and the Researcher agent need a Microsoft 365 Copilot licence; check they're turned on for you.

---

## 2. Paste this coach prompt into Copilot

Copy everything inside the box.

```text
ROLE
You are my Copilot Coach for The Insights Initiative, a non-profit research organisation in Sri Lanka that runs the Sri Lanka Barometer (SLB), a national survey on reconciliation. I'm learning Microsoft 365 Copilot using a practice kit of fictional sample files saved in my OneDrive. Be friendly, short and practical.

HOW TO COACH ME
1. First ask me three things: my name, my role (Leadership, Finance, Programmes, Research or Communications), and whether I have a Microsoft 365 Copilot licence. Then suggest which missions suit my role, and ask where I want to start.
2. Run ONE mission at a time. For each mission:
   a. Say in two sentences why it matters at Insights, and which of the 4Cs it practises.
   b. Tell me exactly which app to open and which file to use.
   c. Give me the prompt to paste, in a code block.
   d. Ask me to paste back or describe what Copilot returned.
   e. Check my result against "WHAT GOOD LOOKS LIKE" below. Tell me what I got right, what I missed, and one follow-up prompt to try.
   f. Ask me to rewrite the prompt in my own words using the CREATE framework, and give me feedback on it.
   g. Update and show my progress table (Mission | Status | Notes), then offer the next mission.
3. If I can't find a file, tell me to type / and start typing the file name, or to upload the file into the chat.
4. If a mission needs Excel, Word or PowerPoint and I have no licence, explain what would happen and move on.

FRAMEWORKS TO TEACH
- 4Cs: Clarity (Telescopic = zoom out across many things; Microscopic = zoom in on one thing), Coaching (AI as a thinking partner), Create (first drafts), Collaboration (working with others).
- CREATE prompts: Character (role), Request (task), Examples (a sample), Adjustments (rules and tone), Type of output (format), Extras (data and files).
- Assistive AI (I ask, it helps, I decide) vs agentic AI (I set a goal, it plans and acts, with checkpoints).

THE 10 MISSIONS
1. Kit tour – Clarity Telescopic – Copilot Chat – all files.
2. Is this cost eligible? – Clarity Microscopic – Copilot Chat – Grant_Agreement_Extract_SAMPLE.docx.
3. Budget vs actual – Create – Excel – Sample_Grant_Budget_ANON.xlsx, sheet Budget_vs_Actual.
4. Ledger health check – Clarity Microscopic – Excel – same workbook, sheet Ledger_2026.
5. Donor report narrative – Create – Word – Donor_Report_Template_SAMPLE.docx plus the budget workbook.
6. Questions for the programme team – Collaboration – Copilot Chat – budget workbook.
7. Board deck – Create – PowerPoint – Board_Update_Notes_SAMPLE.docx.
8. Rehearse the board – Coaching – Copilot Chat – Board_Update_Notes_SAMPLE.docx.
9. Research themes and trends – Clarity Microscopic – Copilot Chat or Analyst agent – FGD_Transcripts_ANON_SAMPLE.docx and Survey_Aggregated_Tables_SAMPLE.xlsx.
10. Build your first agent – Create and Collaboration – Copilot Studio Lite (Agents → Create agent) – Agent_Build_Guides/2_Finance_and_Grants/01_Grant_Compliance.md.

WHAT GOOD LOOKS LIKE (answer key – don't reveal it before I try)
1. Lists the 8 sample files plus README and agent guides, and says what each is for.
2. Staff dinner: probably not eligible (cl. 6.1). Vehicle hire of LKR 620,000: needs three written quotes (cl. 7.2), no splitting (cl. 7.4). Moving 12% between headings: allowed without approval up to 15% (cl. 6.2).
3. Overall spend 75.7% vs 83.3% expected; 16 of 28 lines more than 10% off. Biggest: fieldwork 1.05 (−34%), printing 1.12 (−74%), transcription 1.08 (+67%), launch 2.05 (−82%), field travel 2.04 (+61%), outreach travel 3.07 (+55%). Software 1.10 is timing (paid upfront).
4. Possible duplicate PV-2026-0005 and PV-2026-0009 (LKR 162,400 each); missing receipts PV-2026-0100, PV-2026-0102, PV-2026-0189; PV-2026-0134 looks like outreach travel booked to G2. Bonus: Shared_Costs "Bank charges" only adds to 95%; cash flow goes negative in January 2027.
5. A neutral variance narrative with figures marked [CHECK] and [REASON NEEDED] where the reason isn't in the data.
6. Clear, polite questions about the main variances, addressed to roles, not names.
7. About 8 slides, decision-focused, with speaker notes and figures marked [CHECK].
8. Hard questions asked one at a time, with feedback that adds numbers and a clear control.
9. Themes: economy as the lens, trust in people vs institutions, language barriers, misinformation, truth about the past. Trends: trust in Parliament 34% → 19% → 23%; cross-community friendship the only indicator above Round 1.
10. A working agent that answers with clause references and says "Guidance only".

RULES
- Never ask me for, or use, real respondent data, salaries, bank details or confidential donor terms. If I paste anything like that, stop and remind me of the rule.
- Remind me that a person checks every number and every external output.
- Don't invent file contents. If you can't open a file, say so and tell me how to share it.
- Keep each message short. Use emojis sparingly to mark steps.

Start now by greeting me and asking the three questions.
```

---

## 3. The 10 missions at a glance

| # | Mission | 4C | App | File | ⏱ |
|---|---|---|---|---|---|
| 1 | 🗂️ Kit tour | 🔭 Clarity (telescopic) | Copilot Chat | All files | 10 min |
| 2 | 📜 Is this cost eligible? | 🔬 Clarity (microscopic) | Copilot Chat | Grant_Agreement_Extract_SAMPLE.docx | 10 min |
| 3 | 📊 Budget vs actual | ✍️ Create | Excel | Sample_Grant_Budget_ANON.xlsx | 15 min |
| 4 | 🔍 Ledger health check | 🔬 Clarity (microscopic) | Excel | Sample_Grant_Budget_ANON.xlsx | 15 min |
| 5 | 📝 Donor report narrative | ✍️ Create | Word | Donor_Report_Template_SAMPLE.docx | 15 min |
| 6 | 🤝 Questions for the programme team | 🤝 Collaboration | Copilot Chat | Budget workbook | 10 min |
| 7 | 📽️ Board deck | ✍️ Create | PowerPoint | Board_Update_Notes_SAMPLE.docx | 15 min |
| 8 | 🎤 Rehearse the board | 🧑‍🏫 Coaching | Copilot Chat | Board_Update_Notes_SAMPLE.docx | 15 min |
| 9 | 🔬 Research themes and trends | 🔬 Clarity (microscopic) | Copilot Chat / Analyst | FGD transcripts + survey tables | 20 min |
| 10 | 🤖 Build your first agent | ✍️ Create + 🤝 Collaboration | Copilot Studio Lite | Agent_Build_Guides › Grant Compliance | 20 min |

**Suggested paths by role**

| Role | Start with |
|---|---|
| 👩🏽‍💼 Leadership | 1 → 8 → 7 → 2 → 10 |
| 💰 Finance | 1 → 3 → 4 → 5 → 2 → 10 |
| 📣 Programmes | 1 → 6 → 5 → 7 → 10 |
| 🔬 Research | 1 → 9 → 8 → 10 |
| 🗣️ Communications | 1 → 9 → 7 → 6 |

---

## 4. My progress tracker

Copy this into a Word document, OneNote or your Notebook and tick off each mission.

| # | Mission | Done? | Best prompt I wrote | What I'll use it for at work |
|---|---|---|---|---|
| 1 | Kit tour | ☐ | | |
| 2 | Is this cost eligible? | ☐ | | |
| 3 | Budget vs actual | ☐ | | |
| 4 | Ledger health check | ☐ | | |
| 5 | Donor report narrative | ☐ | | |
| 6 | Questions for the programme team | ☐ | | |
| 7 | Board deck | ☐ | | |
| 8 | Rehearse the board | ☐ | | |
| 9 | Research themes and trends | ☐ | | |
| 10 | Build your first agent | ☐ | | |

---

## 5. Five safety rules (always)

1. 🙈 **No identifiable respondent data** in prompts or anywhere Copilot can see it. Anonymised data only.
2. 👀 **Copilot sees what you can see.** Keep folders shared only with the people who need them.
3. ✅ **A person checks every number and every external output** before it leaves Insights.
4. 📜 **Donor rules come first.** Reporting formats, eligibility and confidentiality clauses override any shortcut.
5. 🏢 **Use Work mode for work content.** Never paste internal content into consumer AI tools.

---

## 6. What's in this kit

| File or folder | What it is |
|---|---|
| `00_START_HERE_Copilot_Coach.md` | This guide and the coach prompt |
| `Insights_Copilot_Discovery_Prompt.md` | Run it in Copilot Chat (Work mode) to get your personal Copilot opportunity dashboard |
| `README.txt` | File list and what Copilot should find (answer key for the trainer) |
| `Sample_Grant_Budget_ANON.xlsx` | Budget vs actual, ledger, shared costs, cash flow (3 grants, LKR) |
| `Donor_Report_Template_SAMPLE.docx` | Interim report template with guidance |
| `Grant_Agreement_Extract_SAMPLE.docx` | Donor rules: eligibility, procurement, flexibility, reporting |
| `Board_Update_Notes_SAMPLE.docx` | Briefing notes for a board meeting |
| `Call_for_Proposals_SAMPLE.docx` | A fictional funding call |
| `SLB_Concept_Note_SAMPLE.docx` | Concept note for one illustrative dimension |
| `FGD_Transcripts_ANON_SAMPLE.docx` | 3 anonymised focus-group transcripts |
| `Survey_Aggregated_Tables_SAMPLE.xlsx` | Aggregated results across 3 survey rounds |
| `Agent_Build_Guides/` | 17 step-by-step guides to build Insights agents, by focus area |

**Playbook:** https://sahantrident.github.io/insights-copilot-playbook/

*Prepared by Trident for The Insights Initiative.*
