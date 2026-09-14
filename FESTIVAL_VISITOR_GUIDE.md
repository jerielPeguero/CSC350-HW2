# Festival Visitor Guide

## Student Information

- Name: [Jeriel Peguero]
- Course and section: [CSC 350 1300]
- Date: [9/14/2026]

## Repository Evidence

- Current branch: [Main]
- Personal Homework 2 GitHub URL: [https://github.com/jerielPeguero/CSC350-HW2.git]
- Starting `git status`: [On branch main
Your branch is up to date with 'origin/main'.
nothing to commit, working tree clean]
- Starting preparation commit ID: [bd125dd]

## Festival Identity

- Festival name: [Byte City Technology Festival]
- Location: [BMCC Fiterman Hall, 30 Church St, New York, NY 10007]
- Intended audience: [Everybody]
- Theme: [Connecting code, community, and creativity.]

## Prediction Before the First Commit

1. Where does the saved change currently live?

   [In the working tree]

2. Has it been staged or committed?

   [No]

## Arrival Information

- Transit or parking: [Fulton Street (A, C, J, Z, 2, 3, 4, 5 lines) – 3 minutes walking distance.]
- Entrance or meeting location: [Main Visitor Entrance is located at the front lobby on 30 Church St. Follow the directional signage for registration and digital badge scanning.]

## Accessibility Information

1. [All main stages, exhibition halls, and presentation rooms are fully wheelchair accessible via ramps and elevator service located near the main lobby.]
2. [ADA-compliant accessible restrooms are available on every floor, clearly marked with international accessibility signage.]

## Visitor Reminder

[Respect fellow attendees, staff, and speakers, and follow all safety and security guidelines posted around the venue.]

## GitHub Verification

[Verified on GitHub by Jeriel Peguero]

## Commit Evidence

| Checkpoint | Short commit ID | Required message |
|---|---|---|
| Personalized guide | [ID] | `docs: personalize festival visitor guide` |
| Visitor access information | [ID] | `docs: add visitor access information` |
| GitHub verification | [ID] | `docs: verify independent homework on GitHub` |
| Final reflection | [ID] | `docs: complete independent Git reflection` |

## Individual Reflection

1. What is the difference between saving a file and committing it?

   [Saving a file only updates it on the local hard drive or editor workspace, whereas committing takes a snapshot of those saved changes and records them permanently into your local Git repository's history with a unique ID and message.]

2. What is the difference between `git diff` and `git diff --staged`?

   [git diff shows the modifications in your working directory that have not yet been staged, while git diff --staged displays the changes that have already been added to the staging area (git add) and are ready to be included in the next commit.]

3. Why did the GitHub verification sentence not appear locally before `git pull`?

   [Because the verification sentence was created and committed directly on the remote GitHub server via the web browser, meaning the local copy of the repository was still pointing to an older snapshot until you explicitly fetched and merged those remote changes.]

4. What did `-u` accomplish in `git push -u origin main`?

   [The -u flag links your local branch to the remote branch on GitHub (origin/main), allowing you to use simple commands like git push or git pull in the future without needing to specify the remote name and branch every time.]

5. What evidence proves that the local and GitHub repositories are synchronized at the end?

   [The confirmation in the terminal showing that both local and remote pointers match the latest commit hash (alongside a clean git status indicating no uncommitted changes and an up-to-date branch status) proves synchronization.]