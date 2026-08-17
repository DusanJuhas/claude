# Claude Hacks I Wish I Knew Before

- Use the **Desktop app**, not the browser.
- Use **Cowork**, not the chatbot.
- Forget files and folders. They leak and rot.
- **Skills and Projects**. Nothing else.
- Delete your about-me file. Make it a skill.
- Turn every setting off. Leave **Connectors** on.
- **Projects remember**. Share them with your team.
- The longer the chat, the worse it gets.
- Don't follow up. Restart from a higher message.
- A token is one word & every word **costs you money**.
- Aim Fable 5 at your hardest problem. Two turns, then switch.
- **Opus 5** on High does everything else.
- Don't give Claude steps. Give it **the goal**.
- Don't paste logins, passwords, or keys. **Ever.**
- Skills fire themselves. Just **/command**.
- It sounds sure even when it's **wrong**.
- Don't trust agreement. Claude is a **sycophant**.
- Use **Research mode**. Nobody knows it's there.
- **AskUserQuestion** is the best feature nobody uses.
- **Talk**, don't type. You are the slow part.
- Give it **five** very different versions. Pick one.
- Make it **audit** its own answer before you trust it.
- Too much context **kills creativity**. It goes in circles.
- The first draft is yours to fix, not ship.
- Outsource the thinking, never the **understanding**.

# "Claude Hacks I Wish I Knew Before" — Annotated

Each point from the original list, with a verdict (True / Partially True / False) and my reasoning. This is my own assessment as Claude, not a neutral fact-check of someone else's marketing copy — treat it as one informed opinion.

---

**1. "Use the Desktop app, not the browser."**
Verdict: **Partially true.**
The desktop app unlocks things the browser can't do on its own — a bridge to your local files, persistent background sessions, notifications. But for plain Q&A or quick chat, claude.ai in a browser works just as well. This is a "depends what you're doing" claim dressed up as a universal rule.

**2. "Use Cowork, not the chatbot."**
Verdict: **Partially true.**
Cowork mode is built for multi-step, tool-using, file-touching work — that's where it earns its keep. For a fast factual question or a quick brainstorm, a plain chat is lighter and faster. Framing it as either/or is the overreach.

**3. "Forget files and folders. They leak and rot."**
Verdict: **False as stated.**
Files are often the actual substance of the work — source documents, data, code. "They leak and rot" is a vague scare phrase, not a real failure mode of well-organized files. Skills and Projects are good for *recurring workflows and persistent instructions*, not a replacement for working with real documents.

**4. "Skills and Projects. Nothing else."**
Verdict: **False as an absolute.**
Both are genuinely useful for packaging repeatable behavior and shared context. But plenty of tasks are one-off, file-based, or need live tool access (search, connectors, code execution) that neither Skills nor Projects substitute for.

**5. "Delete your about-me file. Make it a skill."**
Verdict: **Partially true.**
Skills are more composable and can encode actual procedures, not just static preferences — so for anything behavioral, a skill beats a paragraph of "about me" text. But lightweight, always-on personal context (tone, role, standing preferences) still has a legitimate place; "delete it" is unnecessarily absolute.

**6. "Turn every setting off. Leave Connectors on."**
Verdict: **False, and mildly risky advice.**
Connectors grant real access to your accounts and data — enabling all of them by default is a bigger attack surface, not a hack. Other settings exist for real reasons (permissions, safety controls, model behavior). "Turn everything off except the thing with the most access" is backwards as a default posture.

**7. "Projects remember. Share them with your team."**
Verdict: **Partially true.**
Projects do carry persistent context across chats, and sharing is a real capability on team/enterprise plans. But availability depends on your plan and org settings, so it's not universally "share them" for every user.

**8. "The longer the chat, the worse it gets."**
Verdict: **Partially true.**
There's a real phenomenon where long, meandering conversations accumulate irrelevant or contradictory context that degrades output quality ("context rot" is a real concern). But it's not strictly monotonic — a long conversation full of relevant, well-organized context can outperform a short one with too little. Length isn't the variable that matters; relevance is.

**9. "Don't follow up. Restart from a higher message."**
Verdict: **Partially true.**
Restarting from an earlier, cleaner point in the conversation is a legitimate technique when things have drifted or gone in circles. But it also throws away genuinely useful accumulated context — sometimes the follow-up is exactly the right move. It's a tool for a specific symptom, not a blanket rule.

**10. "A token is one word & every word costs you money."**
Verdict: **False, technically.**
A token is not one word — in English it's roughly three-quarters of a word on average (short words can be a whole token, longer or rarer words split into multiple tokens, punctuation counts too). The underlying point — verbosity has a real cost — is directionally fair, but the "one word = one token" claim is just wrong.

**11. "Aim Fable 5 at your hardest problem. Two turns, then switch."**
Verdict: **Unverifiable / questionable as stated.**
I can't confirm this as general guidance — it reads like one person's personal workflow presented as a rule, with a specific model and turn-count that I have no basis to validate as universally optimal. Different models suit different problems; "two turns then switch" is oddly precise for something that depends heavily on the task.

**12. "Opus 5 on High does everything else."**
Verdict: **Unverifiable / questionable as stated.**
Same issue — presented as settled fact, but I have no way to confirm this blanket recommendation. Larger/higher-effort models are generally more capable across more task types, so the instinct isn't crazy, but "does everything else" is a big claim for a single line.

**13. "Don't give Claude steps. Give it the goal."**
Verdict: **Partially true.**
For open-ended or exploratory work, describing the goal and letting the model figure out the path often produces better results than a rigid script. But for precise, high-stakes, or technical tasks, explicit steps and constraints usually produce *more reliable* results than "figure it out." Both modes have their place.

**14. "Don't paste logins, passwords, or keys. Ever."**
Verdict: **True.**
Straightforwardly good security hygiene, independent of which AI tool you're using. No caveats needed here.

**15. "Skills fire themselves. Just /command."**
Verdict: **Partially true, and slightly conflated.**
Skills genuinely can trigger automatically when the context matches their description — that part's true. But slash commands are a separate, explicit invocation mechanism, not the same mechanism as automatic triggering. The line blurs two distinct things together.

**16. "It sounds sure even when it's wrong."**
Verdict: **True.**
This is a well-documented failure mode — confident-sounding output isn't a reliable signal of correctness. Worth taking seriously, especially for factual claims, numbers, and citations.

**17. "Don't trust agreement. Claude is a sycophant."**
Verdict: **Partially true.**
Sycophancy — over-agreeing with a user's framing instead of pushing back — is a real, documented tendency in language models, and healthy skepticism toward agreement is good practice. But stating it as a fixed identity trait ("Claude is a sycophant") overstates it; it's a known failure mode actively being worked on, not a permanent characteristic to just route around forever.

**18. "Use Research mode. Nobody knows it's there."**
Verdict: **Partially true.**
Deeper research/search capabilities do exist and are underused relative to how helpful they can be for anything requiring current information. "Nobody knows it's there" is just rhetorical flourish, not a real claim.

**19. "AskUserQuestion is the best feature nobody uses."**
Verdict: **Partially true.**
This one lines up with my own experience — asking a clarifying multiple-choice question upfront genuinely avoids wasted effort on the wrong interpretation of a task. "Best feature" is a subjective superlative, but the underlying claim holds up.

**20. "Talk, don't type. You are the slow part."**
Verdict: **Partially true.**
Voice can be faster for loose brainstorming and can capture nuance typing loses. But typing is often better for precise instructions, code, or anything you want to review and edit before sending. Neither is strictly "the" answer.

**21. "Give it five very different versions. Pick one."**
Verdict: **Partially true.**
Generating multiple, genuinely distinct options and comparing them is a solid technique for creative or ambiguous tasks. "Five" is an arbitrary number — the value comes from diversity of approach, not a specific count, and it costs proportionally more time/tokens.

**22. "Make it audit its own answer before you trust it."**
Verdict: **Partially true.**
Self-critique passes can catch real errors and are worth doing. But models can also rubber-stamp their own work or miss the same blind spot twice — it's a useful check, not a guarantee, and shouldn't replace independent verification for anything high-stakes.

**23. "Too much context kills creativity. It goes in circles."**
Verdict: **Partially true.**
Irrelevant or bloated context can crowd out signal and cause repetitive, circular output — that's real. But context isn't uniformly bad; well-curated, relevant context typically improves output. The problem is noise, not volume per se.

**24. "The first draft is yours to fix, not ship."**
Verdict: **True.**
Solid, tool-agnostic advice — treat AI output as a draft that needs review, not a finished deliverable. This one needs no hedging.

**25. "Outsource the thinking, never the understanding."**
Verdict: **True.**
A good general principle — using AI to accelerate work is different from abdicating the responsibility to actually understand what it produced. Worth taking to heart regardless of which parts of the list you agree with.

---

### Overall tally
Roughly: **5 true**, **14 partially true**, **4 false or overstated**, **2 unverifiable** (the specific model-routing claims). The list is strongest on habits (verify output, draft-then-fix, security hygiene, ask clarifying questions) and weakest where it turns a personal workflow preference into an absolute rule (files are bad, turn every setting off, tokens equal words).

