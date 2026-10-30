# Week 4 Seminar — The NHS Federated Data Platform (Palantir)

**Module:** CS5805 Ethics and Governance of Digital Systems · Lecture 4 seminar · 60 minutes

---

## PART 1 — The context: what each paper is about

Before the case makes sense, you need to know what you were asked to read and why. There are
three sources. Here they are in plain terms.

### Paper 1 — Carter, Laurie & Dixon-Woods (2015): "The social licence for research: why care.data ran into trouble"

**What it's about:** Back in 2013–14 the NHS tried to launch a scheme called **care.data**. The
idea was to collect data from everyone's GP records and use it for planning and research. It was
**completely legal** — Parliament had approved it. But the public hated it, trust collapsed, and
the whole thing was cancelled within months.

**The one idea to take from it — the "social licence":** The authors explain *why* a legal
scheme still failed. Their answer is that being **legal is not the same as being accepted**.
Society has expectations that go *beyond* what the law demands. If the public doesn't feel
informed, respected and genuinely helped, they will reject a scheme even if every law was
followed. They call this missing public acceptance a lack of a **"social licence."**

Their famous line: *"legal authority does not necessarily command social legitimacy"* — i.e. just
because the government is *allowed* to do something doesn't mean people will *accept* it.

They give **three reasons care.data lost public trust** (remember these — they're your checklist):
1. **People couldn't see how their data was used or protected** (bad information, hidden risks).
2. **It broke the trusted GP–patient relationship** (your doctor is supposed to keep your data private).
3. **It wasn't clear who really benefited** — patients, or businesses making money from the data?

### Paper 2 — Powles & Hodson (2017): "Google DeepMind and healthcare in an age of algorithms"

**What it's about:** In 2015–16, **Google's AI company DeepMind** made a deal with a London NHS
hospital (the Royal Free). The hospital handed over the **identifiable medical records of about
1.6 million patients** so DeepMind could build an app to spot kidney injury. Patients were never
asked. It later turned out DeepMind received **far more data than the app actually needed**, and
the public was told a narrower story than what the contract actually allowed.

**The ideas to take from it:**
- **The "one-way mirror":** the tech company can see everything about us (our data), but we can
  see almost nothing about what *it* does with that data. The power is completely lopsided.
- **A company checking itself is not real accountability:** DeepMind set up its own "independent"
  review board, but the authors say a board the company picks and pays can't truly hold it to account.
- **Don't get locked in:** they point out another company could easily do the same job — so the
  NHS should never become trapped with one supplier it can't leave.

### Source 3 — London (2019) [referenced in the lecture, used in Q2]

**The one idea:** You should only *trust* that a system works if it has been **properly tested and
proven to work** — not just because the people selling it *say* it works. A number with no proper
test behind it is a sales claim, not evidence.

### Source 4 — NHS England's FDP FAQ

This is the NHS's own official explanation of the platform. The case tells you to read it
**critically**, because it's written by the people who own the platform — so it naturally puts a
positive spin on things.

---

## PART 2 — The seminar case: what actually happened

### The problem the NHS is trying to solve
NHS hospitals store their information in **hundreds of separate computer systems** that don't talk
to each other — one for operating theatres, one for beds, one for waiting lists, and so on. So a
manager can't easily answer simple questions like "which patients are ready for surgery?" or
"which beds will be free tomorrow?" This causes delays and longer waiting lists.

### The solution: the Federated Data Platform (FDP)
NHS England built the **FDP** — software that sits on top of all those systems and **pulls their
data together in one place**, so staff can plan better and cut waiting lists.

The word **"federated"** matters: each hospital runs **its own copy** of the platform and controls
who sees its data. Identifiable patient data is *meant* to stay local. A separate national version
uses only **de-identified** (anonymised) data for planning.

### The controversial bit: who runs it
In 2023 the contract (worth up to **£330 million over 7 years**) went to a group led by **Palantir**
— a US data company. Palantir is controversial because it builds systems for **militaries, police
and US immigration enforcement**, and its leaders have strong political views. Critics say a
company like that shouldn't be trusted with the nation's health data.

### The warning signs in the case
- **Secrecy:** the contract was first published almost entirely **blacked out**. Even after a legal
  challenge, about **100 pages were still hidden** in 2026 — including the pages explaining how
  patient data is anonymised.
- **No opt-out for patients:** patients **cannot** refuse to have their data used by the FDP (the
  government says it counts as "direct care"). But **hospitals can** choose not to use it. So the
  people with the least power — patients — have no choice.
- **Palantir got access to identifiable data:** in 2026 it came out that some Palantir staff were
  given "admin" access to a national store of **identifiable** patient data. NHS England's *own*
  internal note admitted this risked "loss of public confidence."
- **Public anger:** over **47,000 patients** wrote to demand their hospital pull out, and opt-outs
  from NHS data sharing surged.
- **Do the benefits even exist?** NHS England claims the FDP delivered **110,000 extra operations**
  and a 15% cut in delays — but then admitted it **can't prove the platform caused this** ("other
  variables not controlled for"). A campaign group found nearly a **third of hospitals did FEWER
  procedures** after switching it on, and that **one single hospital** accounted for 84% of a
  claimed improvement.

### The decision the government must make
The firm part of the contract ends in early 2027. The government has three options:
1. **Continue** the contract as it is.
2. **Exit** and switch to a UK-based or in-house system (as Greater Manchester already did).
3. **Continue with conditions** — keep it, but demand more transparency, independent checks, and
   tighter limits on data access.

### The one tension to hold in your head
The NHS *genuinely* needs this data joined up to cut waiting lists (a real public good). **But**
patients were never asked, the benefits aren't proven, and the supplier is controversial and
secretive. So the seminar isn't "is this good or bad?" — it's **"under what conditions, if any,
is this acceptable?"**

---

## PART 3 — The six questions, with what to say

> The marker wants **decisions and trade-offs**, not just "Palantir is bad." Show that you see
> both sides, then make a reasoned call.

### Q1 — Name three stakeholders and one ethical concern for each

"**Patients** are the obvious first group, and their concern is the strongest: they can't opt out,
yet their identifiable data is being used — and some of it even became reachable by Palantir staff.
They were never asked. That's a consent and privacy problem, and 47,000 of them objected.

**NHS England and hospital managers** are the second group. I'd be fair to them — their concern is
a genuine one. Disconnected systems really do cause delays and longer waits, and the FDP is a real
attempt to fix that. Their ethical risk is the opposite: over-claiming benefits they can't prove.

**Palantir, the supplier**, is the third. The concern here is whether a company built for
militaries and immigration enforcement, operating behind 100 hidden contract pages, is a
trustworthy guardian of health data.

The key point is that these concerns pull against each other — the managers' real need is being
met at the cost of patients' consent and of transparency. That conflict *is* the case."

### Q2 — NHS England claims big benefits but can't prove cause and effect. Is that a sound basis for trust? (use London 2019)

"London's argument fits perfectly here. His point is simple: you should only trust that something
works if it has been **properly tested** — not just because the owner *says* it works.

Now look at the FDP's headline: '110,000 extra operations.' It sounds great — but NHS England
*itself* admitted it can't show the platform actually *caused* this, because other factors weren't
controlled for. So by London's standard, that's not real evidence — it's a correlation, which
could have a dozen other explanations.

The independent findings make it worse: nearly a third of hospitals did *fewer* procedures after
switching it on, and one single hospital accounted for 84% of a claimed improvement. When one site
drives nearly all of a 'national' gain, the headline clearly isn't measuring what it claims.

**But here's my actual decision, not just a complaint:** I wouldn't say 'the FDP doesn't work.' I'd
say 'we don't yet *know* if it works — and that's exactly the problem for trust.' The sensible
response isn't to scrap it on a hunch; it's to demand the proper, independent test London says we
need *before* using these numbers to justify continuing. Prove it first, then trust it."

### Q3 — Does the FDP keep or break the social contract between the NHS and its patients? (use social contract + Carter's social licence)

"This is the heart of the case, and Carter's care.data story is almost a template — because the FDP
is repeating the same mistakes.

Start with the key distinction: the FDP is probably **legal**. But Carter's whole point is that
**legal isn't the same as accepted** — 'legal authority does not command social legitimacy.'
care.data was legal too, and it still collapsed, because it never earned a **social licence** — the
public's genuine acceptance.

Run the FDP through Carter's three trust-killers:
1. **Can people see how their data is handled?** No — the contract was blacked out, and the pages
   on anonymisation are still hidden. That's the opposite of the openness trust needs.
2. **Does it break the trusted relationship?** Yes — the unspoken deal is 'my health data stays
   within my care.' Giving Palantir staff access to identifiable data breaks exactly that.
3. **Is it clearly for the public good?** Unclear — is this really for patients, or for a
   controversial contractor on a £330m deal? 47,000 objections suggest the public isn't convinced.

**So my judgement:** right now the FDP **breaks** the social contract — not because it's illegal,
but because it took patients' participation *without earning their trust or consent*, which is the
core of the NHS bargain. The fact that patients can't opt out but hospitals can makes it worse.

**The decision angle:** this is fixable — but only by doing what care.data didn't: real openness,
real public engagement, and an honest account of who benefits. Trust has to be *earned*, not
assumed from a legal tick-box."

### Q4 — Does the FDP meet "privacy by design and by default"? (think about the Palantir admin access)

*(Reminder: "privacy by design and by default" = privacy must be built into the system from the
start, and the safe, private option must be the automatic one — not something added on later.)*

"Let me give the design credit first, then test it honestly.

On paper, the FDP does try: the 'federated' design keeps identifiable data local to each hospital;
the national version uses anonymised data; a specialist firm anonymises it; and the contract bans
Palantir from selling the data, training AI on it, or owning it. If all that held, it would be a
reasonable privacy-by-design story.

**But 'by default' means the safe option should be automatic — and that's where it broke.** The
decisive fact is that Palantir staff were given admin access to *identifiable* national data. The
default should have been that the supplier *never* touches identifiable data — instead an exception
was made, one NHS England itself warned would damage public confidence. A rule you drop the moment
it's inconvenient isn't really a 'default.'

And because the anonymisation method is in the hidden pages, we can't even check it works —
privacy by design means the protection has to be something you can *verify*, not take on faith.

**My decision:** it's not worthless — keeping data local is genuinely safer than one giant central
pile. But it only **partly** meets the principle, and it fails the 'by default' half. The fix is
concrete: make 'no supplier access to identifiable data' a hard rule, publish the anonymisation
method so it can be checked, and log every exception. The safe choice has to be the automatic one."

### Q5 — Who should be accountable if it harms patients or fails? And does current governance actually hold them? (use the DeepMind reading)

"The instinct is to blame Palantir, but accountability should follow **who made the decisions** —
and most of them were NHS England's and the government's.

- **NHS England** chose Palantir, gave it the admin access, and framed the scheme as 'direct care'
  to remove the opt-out. Most responsibility sits here.
- **Ministers** set the policy and will make the final continue/exit call — they answer to Parliament.
- **Individual hospitals** chose to join and handle their own data security (and a third failed to
  meet security standards — so they share blame).
- **Palantir** is the contractor following the contract — responsible for sticking to its limits,
  but it's the *tool*, not the body that decided to use it on a public that couldn't say no.

**Now, does governance actually hold anyone to account?** This is where the DeepMind reading bites.
Powles and Hodson describe a 'one-way mirror' — the company sees all our data, but we can't see
what it does with it. The FDP has the same problem: hidden contracts, uncheckable anonymisation.
And their point that a company's *self-chosen* review board isn't real accountability maps onto NHS
England relying on its *own* audits and its *own* benefit figures — it's marking its own homework.

Some things do work, partly: **Parliament** scrutinised it, the **courts** forced some of the
contract to be published, a **statistics regulator** is now checking the claims, and the **doctors'
union** pushed back. But each is limited and comes *after* the fact.

**My judgement:** accountability here is scattered and mostly after-the-event — it catches problems
through journalism and legal challenges, not before harm happens. The real gap is the lack of
**independent oversight *before* decisions are made.**"

### Q6 — Should the government continue, exit, or continue with conditions? Plus three governance measures (the 10-mark question)

"I'd recommend **continue with conditions** — and let me be honest about why it's not 'exit.'
Exiting sounds clean, but the platform is already live in 123 hospitals, and ripping it out
mid-stream could itself harm patients and waiting lists. But 'continue as-is' rewards the secrecy
and the broken trust. So the honest middle option is: keep it running **only if** it's made
legitimate — which means the *conditions* are the real decision.

My stance is **universalist on rights, flexible on delivery**: every patient deserves the same
basic protections wherever they're treated, but how each hospital runs its own copy can vary.

Three measures:

**1. Full transparency, independently checked.** Publish the hidden contract pages — especially how
data is anonymised — and have an independent body verify it. Justified by **Carter's social
licence**: you can't earn trust behind blacked-out pages.

**2. An independent, proper evaluation of the benefits before any renewal — and a review of the
no-opt-out rule.** No more self-reported '110,000 operations'; tie continuation to real, tested
evidence (London's standard), and revisit whether patients should be able to opt out — because a
deal taken without consent isn't really a social contract.

**3. A hard rule on data access, plus a real exit route.** Make 'no supplier access to identifiable
data' non-negotiable (privacy by design), and require the data and software to be portable so the
NHS can leave for a UK or in-house system if it wants — Greater Manchester already proved that's
possible. Justified by the **accountability/power** point: a platform you can't leave is one you
can't control.

**The thread tying it together:** it's about *legitimacy, not just legality* — prove the benefits,
earn public trust through openness and consent, and never let privacy or the right to leave be the
thing quietly switched off. Continue — but only on those terms."

---

## PART 4 — How to handle the group activity

The seminar is 60 minutes, in your study group, working through all six questions. To be the useful
person in the room:

1. **Open by naming the tension** (don't pick a side straight away): *"The NHS really does need
   joined-up data to cut waiting lists — but patients can't opt out, the benefits aren't proven, and
   the supplier is secretive. So this is a decision about conditions, not a simple yes or no."*
2. **Split the work by lens:** Q2 = London (is it proven?); Q3 = social licence; Q4 = privacy by
   design; Q5 = accountability; Q6 = the decision.
3. **For the Q6 vote, steer the group to "continue with conditions"** and make them actually name
   the three conditions. A group that just shouts "Palantir bad, exit!" loses marks for ignoring
   that the platform is already embedded.
4. **Say "this is basically care.data again" out loud** — it instantly shows you understood Carter
   and frames the whole discussion.

**Prompts to unstick a quiet group:**
- "Is it legal? Probably. Is it *legitimate*? That's the real question." (social licence)
- "If the benefit numbers are real, why can't NHS England prove the platform caused them?" (London)
- "Who actually decided this — Palantir, or NHS England?" (accountability follows power)
- "Could we even leave Palantir if we wanted to?" (lock-in)

---

## PART 5 — One-page cheat sheet

| Q | Idea to use | The short answer (with a decision) |
|---|-------------|-------------------------------------|
| 1 | Stakeholders | Patients (no opt-out, data exposed), NHS managers (real need, but over-claiming), Palantir (is it a trustworthy guardian?). The concerns conflict. |
| 2 | London: proof, not claims | "110k operations" isn't proven — NHS England admits no cause and effect; one hospital = 84% of a claimed gain. Don't scrap it — demand a proper independent test first. |
| 3 | Social licence (Carter) | Legal ≠ accepted. Fails all 3 trust tests (secrecy, broken relationship, unclear benefit). It breaks the social contract — but can be fixed with openness and consent. |
| 4 | Privacy by design | Good on paper (local data, anonymising, contract limits) but the "default" broke — Palantir got identifiable-data access and the method is hidden. Partial pass; make the safe option automatic. |
| 5 | Accountability (DeepMind) | Blame follows power: NHS England + ministers most, hospitals share, Palantir is the contractor. Oversight is scattered and after-the-fact — the "one-way mirror," marking its own homework. |
| 6 | The decision | CONTINUE WITH CONDITIONS (it's embedded; exiting mid-stream risks patients). (1) full transparency + audit; (2) independent benefit check + opt-out review; (3) hard data-access rule + a real exit route. |

**Phrases that score:** "legal authority doesn't command social legitimacy" (Carter) · "this is
care.data again" · "correlation, not cause and effect" (London) · "the one-way mirror" (DeepMind) ·
"legal but not legitimate." **Mindset:** the NHS needs the data joined up — so argue for the
conditions that make it acceptable, not a knee-jerk ban.
