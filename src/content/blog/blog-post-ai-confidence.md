---
title: "AI Confidence"
description: "Specific example where AI confidence could have cost me money if taken at face value"
pubDate: "April 14, 2026"
---
AI Confidence

Keeping with the theme of my experience using AI, this post is an
extension of the first blog post I wrote about [the language of
AI](https://robertomolinari.com/blog/blog-post-ai-assistant-language/).
One of the points I made in that post was that AI assistants use
language that implies confidence in their responses.

Another, more detailed, example of an interaction I had with the Copilot
assistant in VS Code happened while working on a small side project. In
that project, I\'m building a database of the results of sporting
events, along with betting data for those games to see where/if there
are any interesting trends or observations to draw about the betting
data v. the actual results. The real goal is to just get me playing with
some new technology but since I enjoy sports and wagering, this project
is a good fit.

While building the database, I decided to focus on NHL hockey games to
start. In less than a day, the Copilot assistant was able to get me a
simple database with \~2 years of NHL game results, along with the
betting data for those games. When I say "betting data" here, I mean
stuff like the moneyline odds, the spread / spread odds and over/under
totals and odds per game. After building the database, I asked the
assistant to write some code to do some basic analysis to answer
questions like

- If I had bet \$100 on the moneyline favorite in each game, how much
  would I have won/lost?

- If I had bet \$100 on the moneyline underdog in each game, how much
  would I have won/lost?

- If I had done the same for spreads, how much would I have won/lost?

Copilot was quick to generate and run the code and give me a nicely
worded and formatted summary that claimed betting the underdog with the
spread (typically +1.5 in NHL games) would have been very profitable.
Pretty sure there were some exclamation points in there too with catch
green check emojis (maybe even a stack of 💵)

The numbers seemed too good to be true given my experience, but hey
who's to argue with an AI assistant making data-driven decisions, right?

Turns out, it\'s important to argue (or really debate and challenge) the
confidence of the answers / responses because at least in this case, the
Copilot assistant really had no idea how odds work. The Copilot
assistant assumed that the odds on a team having +1.5 goals were about
the same (if not the same) as the odds on a team without the +1.5 goals,
which is incorrect. Because of this, it skewed the results of the
analysis to have big payouts on the +1.5 teams. For example, if the
Bruins are playing the Rangers, a reasonable (and certainly not biased
from a Bruins fan perspective) set of odds could be:

- Bruins moneyline odds: -140

- Rangers moneyline odds: +120

- Bruins spread (--1.5) odds: +160

- Rangers spread (+1.5) odds: -180

Meaning that if the Rangers cover the +1.5 spread (say if the game ends
Bruins 3, Rangers 2), a \$100 bet would win \$55.56 (because of the
--180 odds). But the code the Copilot assistant generated used the
Rangers moneyline odds, so the analysis thought the same \$100 bet would
generate \$120 (because of the +120 odds). This resulted in inflated
returns the "if I bet \$100 on the underdog spread for every NHL game in
the last 2 years" question.

The problem isn't just that the returns were incorrect, its that the
Copilot assistant answers with confidence AND incorrect returns. Even
more surprising (to me at least) was that once I challenged the Copilot
assistant to explain what was going on, it really had no idea what even
a moneyline bet is, which in sports is the most basic bet you can make.
After I challenged and questioned, then eventually guided, the Copilot
assistant many errors were found and eventually fixed.

But it would have been easy for me to take the initial analysis on face
value, start betting money on the underdog spreads and lose money while
waiting for the "regression to the mean" that the Copilot assistant had
claimed to discover.
