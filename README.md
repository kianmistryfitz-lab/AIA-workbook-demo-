# AIA-workbook-demo-
A student built workbook designed to fix the issues facing the current workbooks.

AIA Workbook Platform

The problem

The current workbooks are frustrating. I've personally lost 
work in them, and from talking to other students, it's clear I'm 
not the only one. On top of that, there's no built-in way to write 
answers, you have to manually embed your own text boxes. Navigation 
is confusing, loading is slow, and there's no clear way to see what 
you've done and what you still need to do.
I figured I'd try to build something better.


What I built

A fully working workbook platform with both a teacher editor and a 
student reader. It runs as a single HTML file in any browser, no 
install needed.

For students:
There are built-in answer fields for every question, no more embedding text boxes.
Sidebar showing every page colour-coded by progress.
Answers save automatically as you type.
Local backup so your work can't disappear.
6 colour themes to personalise it.
Tracking to show what has and hasn't been completed.

For teachers:
Full workbook editor, create subjects, chapters, and pages
11 content block types: questions, text extracts, PETAL paragraphs, 
YouTube links, vocab boxes, concept boxes, images, and more.
Page types match AIA's real lesson structure, Ignite, Explore, 
Apply, Reflect. There is an answers tab to see exactly what a student has written on any page.
You can back up work manually at any time and once implemented with Fire Base there would be automatic backups.

The demo app comes pre-loaded with Chapter 1 of the Year 10 English 
workbook (Of Mice and Men) built from the actual AIA PDF.


How it was built

I used Claude as a coding collaborator throughout this project. 
Claude wrote much of the implementation code based on my direction, however I can 
confidently explain how any part of this code works.

What I actually did:
Identified the problem from real experience as a student.
Designed every feature and made all the product decisions.
Defined the architecture of how data is structured and stored.
Designed the UX to be as intuitive as possible.
Created the demo workbook.
Debugged issues and understood what was going wrong.
Wrote all the documentation.


What's next

Phase 2: Backend and Accounts
Firebase Auth Google login with school email.
Firestore answers stored in the cloud, not just the browser.
Teacher dashboard see all students' responses in one place.
Students can work across any device.
Hosted at a school URL.

Phase 3 School-wide rollout
All subjects and teachers on the platform.
Replaces the current workbooks.
Student analytics for identifying learning gaps.


