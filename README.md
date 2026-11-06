# TEAS 7 Practice Exams

A free, single-page study site with three TEAS 7 practice exams (A, B and C), 183 original questions in all.

**Live site:** https://yoseple.github.io/teas-practice/

## What it does

- Three exams with no repeated questions. Each follows the official ATI TEAS 7 blueprint: Reading, Math, Science, then English, with the real test's topic mix.
- All five TEAS 7 question types: multiple choice, select all that apply, fill in the blank, ordered response, and hot spot.
- Timed sections, an optional 10-minute break after Math, a calculator in every section, and flagging for review.
- Scores by section and topic, plus an explanation for every question.
- **Saved progress:** scores, topic mastery and unfinished exams are saved in the browser (`localStorage`). There is no login and no server, and progress never leaves the device. The only outside request is for Google Fonts.
- **Weak-topic practice:** builds a set from the lowest-scoring topics across all three exams. Missed questions come first, then unseen ones.

## How it's built

Everything lives in `index.html`: plain HTML, CSS and JavaScript, with no build step and no dependencies other than Google Fonts.

## Accuracy

- **Exam format** was checked on November 5, 2026 against ATI's help center and news page and against fall 2026 school test calendars.
- **Questions** were written to the objectives in ATI's TEAS Version 7 content outline. Each one is tagged with its objective code.
- **Review:** independent reviewers re-solved every question, and their fixes have been applied.

These are original practice questions, not actual TEAS items. This site is not affiliated with ATI (Assessment Technologies Institute). ATI TEAS is a registered trademark of ATI.
