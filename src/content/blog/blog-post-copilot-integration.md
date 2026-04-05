Copilot, AI and integration

There's understandably a lot of conversation and focus on AI technical
capabilities (token counts, model sizes, weights, etc.). These aspects
of AI models help us create scorecards that become increasingly useful
as the number of options from various vendors increases. These aspects
also give us a sense of how we can expect the core features of an AI
system to improve over time (i.e. bigger models with higher token counts
and context windows means AI's that get closer to appearing
intelligent).

In addition to these technical capabilities, we also should be talking
about how AI agents and models are integrated into experiences for
users. Integration is important because users already have tools and
mental models that they work with to accomplish the tasks that AI agents
and models are built to assist us with. For example, ChatGPT or Gemini
on google.com (as two examples) often are used as ways to make finding
information (i.e. search) better, faster and more human like. Before
these chat interfaces, a user would input some keywords, get some links
back, and then spend time going through the links to find the
information they really wanted (the links were just a means to an end).
With ChatGPT or Gemini on google.com, users can input questions and get
answers back. The user can then continue to interact and converse to
expand and/or narrow down on their initial question. This is done
through a chat like interface that users mentally map to a
text/messaging app, hence the interface looks alot like a text/messaging
app interface complete with "send" buttons and "attach" buttons. This is
a pretty straightforward integration.

With Copilot in Office, things get more complicated. Yes, there's still
a chat like interface on the right side when a user starts interacting
with Copilot in Word, PowerPoint, Excel, etc. But there's additional
context in the form of the artifact (i.e. document, slides,
spreadsheet), that is the real focus of the user. Because of this, the
user expects the AI chat to be able to "see" the artifact, but too often
(at least in my experience) this breaks and degrades the level of trust
in the AI core capabilities.

As an example, at least as of this writing, it\'s very easy to break the
Copilot integration in Word. Just follow these steps

- Create a new word document

- Type some content in the document

- Rename the word document (i.e. from "Document 1.docx" to
  "MyLatestBlog.docx"

- Ask Copilot to give feedback on the content

Copilot comes back with "I can't find the doc", because the integration
has a bug that leads Copilot to look for the original name of the
document "Document 1.docx" instead of the new name "MyLatestBlog.docx".

If Copilot isn't able to find the document thats right there on the
screen, it erodes the trust that Copilot can help find other information
not visible on the screen or offer good feedback (based on the
information not visible on the screen).

Experience issues like this cause friction for users that should be very
easy to fix, even prevent before releasing, to enable higher levels of
trust on the rest of the AI technology stack.
