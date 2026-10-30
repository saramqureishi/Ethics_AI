# Week 3 Seminar Notes — LLMs in Higher Education: AI, Assessment & Academic Integrity

**Module:** CS5805 Ethics and Governance of Digital Systems
**Seminar:** Lecture 3 — Large Language Models in Higher Education (60 minutes)
**Case:** AI detection and academic integrity (ChatGPT, Turnitin, ACU, Texas A&M)
**Readings:** Cotton, Cotton & Shipway (2024); Liang et al. (2023); Adel et al. (2024, §5 & §7)

> How to use this: read the lecture notes + "The Story" so you understand it, then use the
> six answers as what you'd actually say. This week the marker wants DECISION-MAKING, not
> "right vs wrong." Every answer below weighs a real trade-off and lands on a workable call.
> You can't just say "detection is bad" — the university still has to assess fairly, stop
> cheating, and keep ~95% of students who use AI honest. Argue like someone who has to run
> the system, not someone judging it from outside.

---

## LECTURE NOTES — what each thing is

### What's new this week: the topic shifts from cars to US
Week 2 was about a company (Uber) taking risks with the public. Week 3 is about **you** —
students, AI tools, and how universities assess and police integrity. Same method (lenses +
governance), new domain.

### Key terms you must be able to define

- **LLM (Large Language Model) / ChatGPT:** AI that generates human-like text by predicting
  the next most likely word. Released Nov 2022; by 2026, ~95% of UK students use AI, 94% for
  assessed work. It's now near-universal, not a fringe cheating tool.

- **AI-detection software (e.g. Turnitin's AI indicator):** tools that claim to tell whether
  text was AI-written. **Crucial fact:** even Turnitin says its score "should not be used as
  the sole basis for adverse actions against a student." They are unreliable in BOTH
  directions (see below).

- **False positive vs false negative** (learn these cold — Q2 needs them):
  - **False positive** = an *honest* student is wrongly flagged as using AI. (The scary one —
    it punishes the innocent.)
  - **False negative** = real AI use is *missed*. (The one that lets cheating through.)
  - In the Reading blind test, AI answers went **undetected 94% of the time** (false
    negatives) *and* scored higher than real students. So the tool misses cheats AND can
    wrongly flag the honest.

- **Text perplexity** (the technical heart of the bias — great to drop in): a measure of how
  "surprised" a language model is by the next word. **Predictable, simple writing = low
  perplexity = looks "AI-like" to a detector.** Non-native English writers use a smaller
  vocabulary, so their genuine writing has low perplexity and gets flagged. That's *why* the
  bias exists — it's baked into how detectors work.

- **Moral Foundations Theory (MFT — Haidt), the NEW framework for Q4:** the idea that moral
  judgements rest on several innate "foundations," and different people weight them
  differently. The six:
  1. **Care / harm** — protecting people from suffering.
  2. **Fairness / cheating** — justice, proportionality, playing by the rules.
  3. **Loyalty / betrayal** — group solidarity.
  4. **Authority / subversion** — respect for legitimate authority and institutions.
  5. **Sanctity / purity** — some things are "sacred" or should not be defiled.
  6. **Liberty / oppression** — resentment of domination and control.
  MFT explains *why staff and students can look at the same facts and feel differently* — they
  are standing on different foundations. (Staff: fairness + authority. Students: care + liberty.)

### The three readings in a line each
- **Cotton, Cotton & Shipway (2024) — "Chatting and cheating":** survey of ChatGPT's risks and
  what universities can do (educate, redesign assessment, detection as part of a mix). **The
  killer twist:** the authors reveal at the end that *ChatGPT secretly wrote almost the entire
  paper* — they only wrote the prompts, headings and real references (ChatGPT's references were
  fake). The point: the line between "AI-assisted" and "AI-written" is already blurry, and
  accountability (a human taking responsibility) is what still can't be automated.
- **Liang et al. (2023) — "GPT detectors are biased against non-native English writers":**
  Stanford study. 7 detectors flagged **61% of genuine non-native (TOEFL) essays as AI**, but
  were near-perfect on US-born students. Cause = low perplexity. Fix = enriching vocabulary cut
  false positives from 61% → 12%. Also: detectors are *easily bypassed* by a "write more
  literary" prompt. Recommendation: don't use detectors to accuse; use them at most as an
  educational self-check.
- **Adel et al. (2024), §5 & §7 — note on p.4:** the case tells you to look at p.4 and ask how
  the paper was written. (Like the Cotton paper, this flags that AI writing is now woven into
  academic work itself — mention it if asked.)

---

## The Story (in plain language)

ChatGPT launched Nov 2022. By 2026 almost every UK student uses AI, and ~12% admit pasting
AI text straight into assessed work. Universities panicked and reached for **AI-detection
software**. But detection turned out to be a mess:

- **Texas A&M (2023):** a lecturer pasted essays into ChatGPT and asked "did you write this?"
  ChatGPT said yes (it can't actually tell), and he failed a whole class. Students were cleared
  — one proved innocence via Google Docs edit history.
- **Australian Catholic University (2024):** ~6,000 misconduct cases, ~90% AI-related, many
  resting on Turnitin's detector. Accused students had to hand over handwritten notes and even
  their internet search histories to prove innocence. One nursing student, Madeleine, waited 6
  months with "results withheld" and believes it cost her a job offer. ACU later admitted the
  figures were overstated, dismissed detector-only cases, and *stopped using the tool* in 2025.
- **The bias (Stanford/Liang):** detectors wrongly flag non-native English speakers ~61% of the
  time — a fairness disaster.

**The decision in front of the university (this is the exam framing):** it has three options,
which can be **combined**:
1. **Detect and enforce** — keep using detection software to flag suspects.
2. **Redesign assessment** — rely less on detection; use vivas, in-person elements, tasks that
   require disclosing AI use.
3. **Educate and disclose** — teach AI literacy and make students *declare* how they used AI;
   undeclared use is the integrity breach.
Plus: uploading student work to third-party tools processes personal data (UK GDPR), and
students have rights against decisions made *solely* by automated means.

**The real tension (keep this in your head for every answer):** you must (a) protect honest
students from false accusations, (b) still deter real cheating so degrees mean something, and
(c) not punish non-native speakers or process data unlawfully — all at once, with imperfect
tools. There is no clean answer; there's a *best balance*.

---

## The Four Lenses + MFT (your toolkit)

- **Utilitarianism** — weigh outcomes. Here: weigh the harm of false positives (innocent
  students destroyed) against the harm of false negatives (cheating gets through and degrees
  lose value). Ask which policy produces the least total harm.
- **Deontology / rights** — duties and fairness regardless of outcome: due process, presumption
  of innocence, the right not to be convicted by an unreliable machine, data-protection rights.
- **Virtue ethics** — what would a *fair, honest, trusting* institution do? Does it treat
  students as suspects or as people it's educating?
- **Universalist vs relativist** — one policy for all, or context-dependent? (Name your stance
  in Q6.)
- **Moral Foundations Theory** — explains the *disagreement itself* (Q4).

---

## The Six Questions — what to actually say (decision-focused)

> Remember the brief: don't just judge, DECIDE. Acknowledge the trade-off, then make the call
> and say how you'd implement it.

### Q1 — Three stakeholders + one ethical concern each

"The one everyone forgets is the **honest student**, especially the non-native English speaker.
Their concern is being falsely accused by an unreliable tool — Liang found 61% of genuine
non-native essays flagged as AI. For someone like Madeleine at ACU, that meant six months of
'results withheld' and probably a lost job. That's a real harm done to an innocent person.

Second, **academic staff / the university**. Their concern is genuine — if AI cheating goes
undetected, degrees stop meaning anything and that's unfair to everyone who did the work. The
Reading blind test is their nightmare: AI answers slipped through 94% of the time *and* scored
higher. So they're not villains; they have a legitimate integrity problem to solve.

Third, **future employers and the public** — the people who trust that a degree certifies real
ability. If assessment can't tell human from AI work, that trust erodes. It's easy to forget
them, but they're why integrity matters in the first place.

The point I'd make is that these concerns genuinely *conflict* — protecting the honest student
from false accusation pulls against catching the real cheat. That tension is the whole case."

### Q2 — Should universities use AI-detection scores as evidence? (UTILITARIAN)

"This is a utilitarian question, so let's actually weigh the two failure modes instead of just
saying detection is bad.

On one side, **false negatives** — real AI use missed. The Reading test showed detectors miss
AI 94% of the time, so relying on them to catch cheats barely works anyway. If cheating slips
through, degrees lose value — a real but *diffuse* harm, spread thinly across everyone.

On the other side, **false positives** — honest students wrongly flagged. Liang: 61% of genuine
non-native essays flagged. The harm here is *concentrated and severe* — a specific innocent
person gets a misconduct charge, 'results withheld', lost jobs, mental-health damage, and even
if cleared the reputational damage is done. Liang calls it a 'presumption of guilt.'

So the utilitarian calculation isn't symmetrical. A false negative mildly dilutes a credential;
a false positive can wreck an identifiable person's life and future. When one error is severe
and targeted and the other is mild and spread out, you weight *avoiding the severe one* more.

**But here's the decision, not just the critique:** I wouldn't ban detection outright — that
throws away a signal that still has *some* use. The workable call is: **a detector score can
never be evidence on its own.** Use it only as a *trigger to look closer* — a prompt for a human
conversation, a viva, checking draft history — never as proof. That's basically what Turnitin
itself says, and what ACU learned the hard way when it dismissed every detector-only case. So:
keep the tool, demote it from 'judge' to 'smoke alarm.'"

### Q3 — Making students hand over notes and search histories to prove innocence (DEONTOLOGY / RIGHTS)

"From a rights-based view this is the clearest failure in the whole case, and it's about *due
process*, not outcomes.

The core duty a fair system owes anyone accused is the **presumption of innocence** — the
accuser proves guilt; the accused doesn't prove innocence. ACU inverted that. A machine said
'84% AI,' and suddenly the student had to produce dozens of pages of notes and *their entire
internet search history* to clear their name. That's 'presumption of guilt,' exactly what Liang
warns about. You're treating the student as guilty until they exhaust themselves proving
otherwise — and some, like the paramedic student, just complied because fighting cost too much.

There's also a straight **data-protection / privacy** breach. Someone's full search history is
deeply personal — it has nothing to do with one essay, and demanding it is wildly
disproportionate. UK data-protection law also gives people rights where a significant decision
is made *solely* by automated means, which a detector-driven charge basically is.

**So what's the fair alternative — because the university still needs to investigate?** The
decision I'd defend: keep the *option* for a student to clear themselves, but (a) the burden
stays with the institution to show misconduct, (b) you ask for proportionate, relevant evidence
only — e.g. the document's own version history, or a short oral conversation about the work —
never someone's entire digital life, and (c) you resolve it in weeks, not six months. Due
process doesn't mean never investigating; it means investigating *fairly and proportionately*."

### Q4 — Why staff and students judge AI use so differently (MORAL FOUNDATIONS THEORY — use ≥2)

"This is where Moral Foundations Theory earns its place, because the interesting thing isn't who's
right — it's that both sides are standing on *different moral foundations*, so they genuinely
can't see the issue the same way.

**Staff tend to stand on Fairness/cheating and Authority.** For them, undeclared AI use breaks
the rules of the game — it's unfair to students who did the work, and it disrespects the
institution's authority to set the terms of assessment. Through that lens, using ChatGPT without
saying so just *is* cheating, full stop.

**Students tend to stand on Care/harm and Liberty/oppression.** When a tool wrongly flags a
non-native speaker 61% of the time and demands their search history, students see *harm* done to
innocent people and an *oppressive*, surveillance-heavy system treating them as suspects. From
that foundation, the detector is the ethical problem, not the AI use.

That's why the same facts produce opposite reactions. A student thinks 'I used AI to fix my
grammar, I harmed no one, why am I being policed?' (Care + Liberty). A staff member thinks 'you
gained an unfair edge and broke the rules' (Fairness + Authority). You can even fold in the
Liang point: because non-native writers get flagged most, the detector *itself* creates a
Fairness problem — it punishes people for their vocabulary, not their honesty.

**The practical payoff** (decision angle): if you understand the policy is being read through
different foundations, you design it to speak to all of them — clear declared-use rules
(Fairness + Authority) *plus* protection from false accusation and surveillance (Care + Liberty).
A policy that only serves staff's foundations will feel illegitimate to students, and vice versa."

### Q5 — How far does current governance protect students? Where are the gaps?

"Let's be fair to what exists before hitting the gaps.

**What's there:** the Russell Group's five principles (2023) commit universities to AI literacy,
adapting assessment, equal access, and protecting integrity — a decent direction of travel. UK
data-protection law gives rights over personal data and over purely automated decisions. And
tool-makers themselves (Turnitin) warn against using scores as sole evidence.

**The gaps, though, are big:**
- The Russell Group principles are **voluntary and vague** — 'commit to AI literacy' with no
  standard, no enforcement, no consequence for getting it wrong. The survey shows the reality:
  only 48% of students feel staff help them build AI skills. Principles on paper, not in practice.
- **No consistent due-process floor.** ACU could invert the burden of proof and demand search
  histories because nothing concrete stopped it. There's no sector-wide rule saying 'a detector
  score alone is never evidence' — so each institution improvises, and students get wildly
  different treatment.
- **Data protection is reactive.** It gives you rights *after* harm, through complaints — it
  doesn't stop a university uploading your work to a third-party tool or running detector-driven
  cases in the first place.
- **Nothing addresses the bias directly.** No rule requires detectors to be tested on diverse
  writers before use, even though Liang showed the 61% problem in 2023.

**My judgement:** current governance sets a *direction* but gives students very little hard
protection at the moment that matters — when a machine accuses them. It's mostly principles and
after-the-fact rights, with no enforceable due-process standard in between. That gap is exactly
what the Q6 recommendations need to close."

### Q6 — Three governance measures for a UK university (10 MARKS — the big one)

"I'll take a **mostly universalist stance**: there should be a firm, consistent floor of
protections and rules that applies to every student, because fairness and due process shouldn't
depend on which marker or department you land in. I'd allow *relativist* flexibility only on the
teaching layer — different subjects can legitimately permit different levels of AI use. So:
universal rights, context-specific permissions.

**One — a hard due-process rule: a detector score is never sufficient evidence on its own.**
Any case must rest on human judgement plus proportionate, relevant evidence (document version
history, a short viva), the burden stays with the institution, and search-history-style demands
are banned. Justify it with **deontology** (presumption of innocence, proportionality) and
Liang's 'presumption of guilt' warning. This directly fixes the ACU failure.

**Two — shift the centre of gravity from detection to assessment redesign + declared use.**
Lean on the case's option 2 and 3: more vivas and in-person elements, and a required 'how I used
AI' declaration where *undeclared* use is the breach, not use itself. Justify with
**utilitarianism** — this reduces *both* error types at once (you don't need a flaky detector if
the assessment itself reveals understanding), and it's what Cotton and the Reading study both
point toward. It also respects students' Liberty foundation while protecting staff's Fairness one.

**Three — mandatory bias-testing and transparency before any detection tool is used, plus AI
literacy for staff and students.** No tool goes live until it's been tested on diverse writers
(the Liang recommendation), its limits are disclosed, and staff are trained not to over-trust it.
Justify with **fairness / rights** — you can't knowingly deploy a tool that flags non-native
speakers 61% of the time. This closes the bias gap governance currently ignores.

**Tie-back:** the thread is that detection should be demoted from accuser to, at most, a
self-check — Liang's own suggestion — while assessment design and honest disclosure do the real
work. One universal floor of protection, context-sensitive teaching on top. That's how you keep
degrees meaningful *and* stop destroying innocent students."

---

## 60-Second Pre-Seminar Cheat Sheet

| Q | Lens | The DECISION (not just the critique) |
|---|------|---------------------------------------|
| 1 | Stakeholders | Honest/non-native student (false accusation), staff (real integrity need), employers/public (trust in degrees) — concerns genuinely conflict |
| 2 | Utilitarian | Don't ban detection — demote it: a score is a "smoke alarm," never evidence. False positives are severe+targeted, false negatives mild+diffuse → weight avoiding false positives |
| 3 | Deontology / rights | ACU inverted presumption of innocence + breached privacy. Keep investigation, but burden on institution, proportionate evidence only, weeks not months |
| 4 | Moral Foundations | Staff = Fairness + Authority; students = Care + Liberty. Same facts, different foundations → design policy to satisfy both |
| 5 | Governance gaps | Russell Group = voluntary/vague; no due-process floor; data law is reactive; no bias rule. Direction yes, hard protection no |
| 6 | Universalist floor | (1) score never sole evidence (2) redesign assessment + declared use (3) bias-test tools + AI literacy. Universal rights, context-specific permissions |

**Phrases to drop:** "false positives are severe and targeted; false negatives are mild and
diffuse" · "demote the detector from judge to smoke alarm" · "presumption of guilt" (Liang) ·
"the Cotton paper was itself written by ChatGPT" · "low perplexity is why non-native writers get
flagged." **Decision mindset:** the university still has to assess, deter cheating, and stay
lawful — so argue for the best *balance*, not a ban.
