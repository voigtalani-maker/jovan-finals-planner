# Jovan's Finals Planner

An hour-by-hour planner for the **IEB NSC Final Examinations 2026** (NSC Circular 38 of 2026). It covers Jovan's 12 papers, from Afrikaans Huistaal P1 on 20 Oct to EGD P2 on 26 Nov.

Live: **https://voigtalani-maker.github.io/jovan-finals-planner/**

## What it does

- Eight weeks, 5 October to 29 November 2026, one column per day. Exam papers fill themselves in at their real times (09:00).
- **Study time is planned automatically.** Each paper starts at Alani's hours less 4 (280 h in total). They go into the open hours before each paper from 09:00, in two-hour stretches with an hour's break after each. A normal day ends at 17:00. Only on days that need it, the plan runs on to 20:00, and no day ever has more than 7 hours of study. There is no study before a paper or for 3 hours after it.
- **Missed some hours? They move.** The plan only covers tomorrow onwards and is redone after every change, so skipped hours spread over the days still left.
- Every non-exam hour is a dropdown. Pick a subject, Break, or free. Your picks are saved automatically, and the plan works around them.

## Hours per paper

Each paper has a card where you can:

- change the hours you want for it (Alani's hours less 4 by default);
- drag **Studied** to log the hours you have really done, which then come off the plan;
- open its IEB SAG at that paper's topics, or attach your own demarcation (kept on this device only).

Everything is stored on the device: localStorage, plus IndexedDB for attached files. Installable as an app (PWA).
