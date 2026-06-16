---
title: "Coding Assistant Observations"
description: "Differences between GitHub Copilot and Claude Code so far"
pubDate: "June 16, 2026"
---

I spend a few hours every morning working on my [sports betting analytics project](https://robertomolinari.com/blog/blog-post-early-betting-analysis-results/). I started with nothing other than some ideas in my head, and a desire to learn how to work with AI coding assistants to build something. Over the course of a couple months I've learned about technology, analytics and how to work (and not work) with AI assistants. The last part, how to work/not work with AI assistants is something pretty much every software engineer on the planet is learning quickly given the advancement in the AI capabilities along with the top-down push in so many organizations to adopt quickly to increase efficiency and speed of execution.

There are multiple challenges when it comes to learning how to work with an AI assistant to code. A few recent ones that I've experienced:

- New model/assistant = new learnings
- AI assistants are humanlike, which is good, and bad
- AI assistants fail to get meta learnings

Taking these one by one

"New model/assistant = new learnings" - when I started my project, I was
all about doing it as cheaply (in terms of dollars) as I could, so I
went with GitHub Coplot since it was free in my free VS code IDE. Can't
beat that price. GitHub Copilot was decent at taking a task like "build
me a database that stores soccer scores and odds" and generating
something simple. The speed at which it worked and the reasonable
quality (with the caveat that it\'s kind of hard to fuck that task up),
got me to using it to write code for collecting data and running
analytics. Then I got an itch to see how other tools did, so started
using Claude Code to write some basic tests (GitHub Copilot wrote none
on its own). The Claude Code experience was good, so I ponied up the
Claude Code subscription fee and switched to getting it to design and
write new stuff (like support for World Cup matches). Some parts of the
switch were expected (context got lost), but others were surprising
(Claude Code acts a lot more confidently and quickly). When it\'s right,
that\'s a good thing. When it\'s wrong, it\'s a mess of backtracking and
fixing which I didn't have to do much if any of with GitHub Copilot.
GitHub Copilot was like a worker bee which required me to be hands on
and took a small task and executed on it with good quality/speed. Claude
Code was like an intern that enabled me to be more hands off and is
smart but a bit arrogant / naive, able to take larger tasks and execute
on them with good quality and inconsistent speed (because of the starts,
stops and detours to fix when its wrong). Still deciding which is better
for my working style.

"AI assistants are humanlike, which is good, and bad" - because of the
natural language interface, it\'s easy to mentally perceive a human on
the receiving end of the messages I type into the chat box. Because of
this, and the fact that the entity on the receiving end NEVER asks me to
clarify a term / language, I think that humans are just as smart, if not
smarter than me. but the obvious reality is that my perception is wrong,
but it\'s hard to untrain that so I expect there to be a smart human
that learns from mistakes. Instead, I have an AI assistant that has a
tiny fraction of my context (just the code/conversation) to work off
with no ability to feel or reason. It's hard to manage that distinction
but with time, I do feel that I'm managing it better and being more
explicit with the assistant.

"AI assistants fail to get meta learnings" - this is a specific, but
important, version of the point above. AI assistants are unable, at
least in my experience, to extract the kind of innovate thinking and
knowledge that comes from doing a task again, like fixing failing tests.
The AI assistants are unable to "zoom out" and see the bigger problem
that needs to be addressed, because they get fixated on the trees that
they miss the forest most of the time. But even worse, it\'s only most
of the time, so I get fooled into thinking the assistant is seeing the
forest when it\'s not, then it surprises me when it does see the forest
when i expect it to only see trees.
