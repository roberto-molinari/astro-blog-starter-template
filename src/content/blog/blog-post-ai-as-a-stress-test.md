---
title: "AI as a stress test"
description: "How AI agents can create real-world stress tests and drive revenue for enterprise infra"
pubDate: "April 28, 2026"
---

[Github recently posted on their
blog](https://github.blog/news-insights/company-news/an-update-on-github-availability/)
about some recent incidents and their priorities around reliability v.
capacity v. features. When setting the context for their capacity
planning over the last year, they shared some data on the increase they
have seen in usage, predominantly driven by AI scenarios/agents

![](/media/blog-post-as-as-a-stress-test-image-1.png)

<https://github.blog/wp-content/uploads/2026/04/record-accelleration-1920x1080-2.png?w=1920>

The graphs show exponential growth across new repos, commits and merges
since late 2025. For GitHub, this meant re-evaluating their capacity
planning (blog post cites their plans were for 10x, but they had to
revise to 30x after re-evaluating). This makes sense, AI moves faster
than humans do, and a lot of what AI does is optimized for the UX and
resource utilization in training given the high costs that the model
owners incur when developing new models. They are highly incentivized to
keep the training costs down and likely spend significant engineering
cycles on these optimizations.

But once a model is released, and integrated with apps like VS Code,
Claude Code or Codex, the resources consumed expand to include
downstream services like Github and other API providers. Given the
ubiquity of git and GitHub in developer workflows, it makes sense that
GitHub (and likely Gitlab) sees the brunt of this increase in
utilization. The time from idea to code to commit is greatly reduced
with the acceleration that AI provides, so more repos and more commits
make a lot of sense. At best, that cycle of idea -\> repo -\> commit was
measured in 10s of minutes when it was all human driven, but now that
time is measured in seconds when an AI agent is involved, with the
"extra" time that is available, humans can guide the AI to work on new
ideas which start new cycles and result in new repos and commits.

It's interesting to think about what services could be next, which will
be driven by which jobs adopt AI quickly next (after software
engineering). It seems that general knowledge work in an office
environment is in the running for jobs that will adopt AI at a rapid
pace next, given the combination of (1) natural language interfaces for
knowledge workers and (2) requirement for access to organizational
data/information to do the knowledge work. If that pans out, then we
could see "stress tests" coming for products like Microsoft Office and
Google Workspace. Enterprises may also see increases for expansion of
their on prem services (such as SAP systems, VMware applications, SQL
servers, etc), as well as the infra needed to support them. This all
could be leading to meaningful increases in revenue for these companies,
as AI drives more consumption in the enterprise.
