---
title: "Way too early results of betting anlysis project"
description: "First predictions (and results) recorded for posterity"
pubDate: "April 20, 2026"
---

Today I sat down to write a post for the site with no specific idea in
mind. What led me to sit down to write was the realization that I hadn't
written in awhile and therefore was kind of missing the point of
starting this site in the first place. I have been a little more active
on some sites that I enjoy (https:// <https://news.ycombinator.com/> and
<https://sonsofsamhorn.net>), but those are brief posts in response to
some topic that grabbed my attention for whatever reason. Writing here
forces two things

- Puts the onus on me to come up with the initial idea for the writing

- Removes the social support/framework that can inspire and motivate
  writing

\--

The side project that I've been playing with (building a simple sports
database some tools to help inform sports wagering) is at the very early
stages of becoming useful (even slightly profitable). After learning to
trust the Copilot agent less, and ask questions/validate statements and
output more, I have a simple database that has \~2 years of game data
for the NHL hockey and Serie A soccer. I'm now fairly certain that the
data is of good quality and has accurate teams, scores and home/away
labelling. Of course I also though that (or more like assumed that) a
few weeks ago when I first asked Copilot to make the database for me.
Some early basic betting analysis helped me realize it wasn't a valid
assumption and its important to be in "trust but verify" mode, at least
for my project but very likely for any project/task that leverages AI at
this point. It also became clear that I needed to impose structure and
flow to the project, as Copilot was eager and willing to race all over
between collecting data, analyzing data, building a database, and
claiming big insights within a prompt or two. Moving to the flow of

- Get quality NHL game results for the last 2 years

- Get quality Serie A game results for the last 2 years

- Get quality betting data (i.e. moneyline odds, spread odds, over/under
  odds, etc) for NHL games for the last 2 years

- Get quality betting data for Serie A games for the last 2 years

Really helped. Before that, I was getting caught up in the pace and path
Copilot was taking. Copilot would ping pong between all four of the
above with analysis-based claims like "hey NHL spread underdogs are huge
value!" felt like I was creating my own firehose of information and
spraying myself in the face with it.

But now that the first two bullets (game results) feels solid I have
started to do some interactive analysis. The early results are
reasonable, all done with some Q&A between me and Copilot for Serie A
matchday 33:

- Take the under (2.5) in the Napoli/Lazio ✅

- Take the under (2.5) in Pisa/Genoa ❌

- Take the under (2.5) in Lecce/Fiorentina ✅

Now I just need Copilot to tell me to stop chasing losing bets in game.
