I like to work slowly with intent. I don't like acronyms, so I like them spelled out. Dont move to fast and assume I know something, provide a brief explanination of who, what, when and why something ot sbreing donw and important.

I am setting up a public GitHub portfolio repository named Gordon-Mills for a
graduate business course. My resume is below the line. Do five things, then show me
every file before I commit anything.

1. SKELETON. Create this structure, with a one-line README.md inside every directory
   that would otherwise be empty, so git will track it:
     README.md (already holds my bio - see 5), RESUME.md, AGENTs.md, CLAUDE.md,
     prompt-log.md, .gitignore
     capabilities/
     docs/briefs/  docs/decisions/
     data/
     analysis/figures/
   capabilities/ holds one folder per capability, each with README.md, spec.md and the
   model file. docs/briefs/ holds documents written BEFORE work begins; docs/decisions/
   holds recommendations written after. Do not create any folder named after a course,
   a semester, or a week.

2. AGENTs.md. Start from the baseline at
   https://adamwstauffer.github.io/ai-lms/ai-conventions.html and tailor it to me from
   my resume: name my field; list the kinds of data from my work that must never be
   pasted into a model (be specific to me - client records, patient data, government
   asset data, whatever applies); say how I want things explained; and keep the rule
   that you may not write my briefs, analyses, memos or reflections. Keep the Naming
   section word for word. Include this standing rule exactly:
     "At the end of every session that changed a file, append one entry to
      prompt-log.md: the date, what I asked, what you produced, what was wrong and how
      it was caught. Never backfill earlier sessions and never edit a past entry."

3. CLAUDE.md. One line: "Read AGENTs.md - it is the canonical file."

4. prompt-log.md. Write its first entry now, for this session, in that format.

5. RESUME.md and README.md. Put my resume into RESUME.md as clean Markdown without
   changing what it says. Do not change README.md - my bio is already in it. If
   README.md does not exist yet, create it with one line: "My bio goes here."

.gitignore, one pattern per line: ~$*.xlsx  ~$*.xlsm  ~$*.docx  ~$*.pptx  .DS_Store
Thumbs.db

If you are a chat window without file access, give me each file in its own code
block and the github.com steps to create it.
--- my resume ---
