# 🤝 Contribution Guide — cloudcert-sathi

Welcome! We are happy that you want to contribute to **cloudcert-sathi**.

This guide will tell you exactly how to add your notes, questions, or improvements.

---

## Who Can Contribute?

Anyone who:
- Is preparing for AWS Cloud Practitioner or Claude Architect Foundation
- Has notes that helped them understand a topic better
- Wants to create original practice questions
- Wants to improve existing explanations

**No coding experience needed.** You just need to know basic Markdown (which is very simple — just plain text with some symbols).

---

## What Can You Contribute?

✅ **You Can Add:**
- Chapter notes and summaries
- Simple explanations with Indian examples
- Original practice questions (with answers and explanations)
- Memory tricks and mnemonics
- Flashcard content
- Study plan suggestions
- Diagrams or flowcharts (as images or ASCII art)

❌ **You Cannot Add:**
- Copied exam questions from any real exam
- Exam dumps of any kind
- Content copied from other websites without proper credit
- Misleading or incorrect information

---

## How to Contribute — Step by Step

### Step 1 — Fork the Repo

Go to the GitHub page of this repo and click **Fork** in the top right.

This creates your own copy of the repo.

### Step 2 — Clone Your Fork

```bash
git clone https://github.com/YOUR-USERNAME/cloudcert-sathi.git
cd cloudcert-sathi
```

### Step 3 — Create a New Branch

Always create a new branch for your changes.

```bash
git checkout -b add-s3-notes
```

Give the branch a simple name that describes what you are adding.

### Step 4 — Add Your Content

Use the templates from the `templates/` folder.

For notes → use `templates/study-guide-template.md`
For questions → use `templates/question-template.md`

Put your file in the right folder. For example:
- AWS notes go inside `aws-cloud-practitioner/`
- Claude notes go inside `claude-architect-foundation/`

### Step 5 — Follow the File Naming Rules

File names should be:
- All lowercase
- Words separated by hyphens (no spaces)
- Descriptive but short

**Good examples:**
- `s3-basics.md`
- `ec2-vs-lambda.md`
- `security-groups-explained.md`
- `chapter-1-practice-questions.md`

**Bad examples:**
- `MyNotes.md`
- `s3 storage notes.md`
- `notes final v2.md`

### Step 6 — Commit Your Changes

```bash
git add .
git commit -m "Add S3 basics notes for AWS chapter 3"
```

Write a clear commit message that explains what you added.

### Step 7 — Push and Create a Pull Request

```bash
git push origin add-s3-notes
```

Then go to your GitHub fork and click **"Compare & Pull Request"**.

In the PR description, write:
- What you added
- Which chapter or section it belongs to
- Any notes for the reviewer

---

## Content Quality Rules

1. **Write in simple English** — Imagine you are explaining to a friend who is new to cloud
2. **Use examples** — Indian examples are encouraged (e.g., comparing S3 to a digital locker)
3. **Be accurate** — Double-check your content before submitting
4. **Add explanations to questions** — Every practice question must have a clear explanation for the correct answer
5. **No plagiarism** — All content must be your own original writing
6. **No commits from AI agents or unauthorized bots** — Commits from Shizi Softwares, Claude, Codex, or other AI agents/bots are strictly not allowed to keep contributions authentic and human-written.

### Setting Up the Commit Hook
To help enforce this policy locally, you can enable the pre-commit hook by running:
```bash
git config core.hooksPath .githooks
```
This will automatically verify that your git user settings are configured with your real name and email before allowing commits.


---

## Markdown Basics (For Beginners)

If you are new to Markdown, here is a quick reference:

```markdown
# This is a big heading
## This is a medium heading
### This is a small heading

**This text is bold**
*This text is italic*

- This is a bullet point
- Another bullet point

1. This is numbered
2. Second item

> This is a quote or note

`This is code`

```

---

## Questions?

If you are not sure where to put something or how to write something, feel free to:
- Open a GitHub **Issue** and ask your question
- Use the **Discussions** tab if it is enabled

We appreciate every contribution, big or small.

**Thank you for helping students learn! 🙏**
