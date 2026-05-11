---
title: "Getting Better with Coplilot"
description: "Latest experience with Copilot and how I'm learning to use it more effectively"
pubDate: "May 10, 2026"
---

This last week I felt like I finally started getting into a reasonable
groove/rhythm with AI assisted coding in VS Code. For context, I've been
playing around with Github Copilot in VS Code to build a sports database
with some wagering analytics on top. Project started a couple months ago
with some documentation I wrote for myself to frame the problem and
goals, then got into coding tools/components to build / update the
database, as well as some initial tooling to do analytics to try and
find betting edges. Given this is all just me + AI assistants putting
things together from scratch, I have zero expectations that I'll find
much in the way of edges, but it\'s fun trying.

Most of the interaction with GitHub Copilot over the last few weeks has
looked something like

- Me: "I want a database that has NHL and Serie A data for betting"

- Copilot: "ok, great idea! Let me build that for you!"

- \<lots of me clicking "ok" when Copilot wants to run some command"\>

- Me: "what you built isn't really want I wanted or even correct if it
  was what I wanted"

- Copilot: "good catch! Let me fix that for you!"

On and on it went. At some point I realized I actually had to bring
critical thinking to the table and do some combination of
correct/interrogate/guide Copilot. Sometimes that came in the form of
questions

- "What do you think a Moneyline bet actually means"

- "Why do you think Inter is the home team in matchday 26"

Other times it came in the form of statements

- "The home/away teams are reversed in the table that has match results,
  fix it"

- "There are two Montreal teams in the NHL teams table, god knows we
  only need one at most, fix it"

In both cases, I occasionally experienced a mix of frustration and loss
of patience with Copilot. Then I realized it was really me that was the
problem, in that my expectations were off, and I had to remember that
Copilot is just a tool to get a job done. I need to be better at
explaining the job I want done and checking the quality of the work done
at the end. The quality check is important because, at least for me, it
was super easy to just trust Copilot would get things right given that I
wasn't asking for super hard stuff, and Copilot has a lot of
information/data/horsepower behind it. Besides, it\'s so fast there's no
way it could come back with a solution that is fast and wrong! This was
clearly naive thinking on my part, but part of the journey.

Once I figured that out, the pace and quality have picked up. I'm better
at giving more bit sized jobs to do and better and checking the quality
at the end of each turn. As an example, instead of me saying

- "Let\'s build analytics on top of our database to find edges" \<\--
  big job

I say

- "Let\'s get match data for Serie A, the last two seasons. Include
  home, away, halftime scores and final scores" \<\-- small job

- \<run some simple SQL to check the data\>

- "Let's explore some ways to find edges" \<\-- small job

- \<iterate on ideas with Copilot to enumerate approaches, then pick
  one\>

- "Ok, let\'s build a model that provides probabilites of expected goals
  per team in the next matchday" \<\-- small job

And it goes on. This has resulted in some actually useful stuff with
less friction. But I'm not rich yet (damn you Parma) but less friction =
more fun / learning.
