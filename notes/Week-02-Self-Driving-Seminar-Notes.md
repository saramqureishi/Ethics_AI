# Week 2 Seminar Notes — When a Self-Driving Car Kills

**Module:** CS5805 Ethics and Governance of Digital Systems
**Seminar:** Lecture 2 — Self-Driving Vehicles Case (60 minutes)
**Case:** Uber / Tempe 2018 → London 2026
**Readings:** Stilgoe (2021); Siegel & Pappas (2023, pp.215–221 + Table 1)

> How to use this: read "The Story" and "The Four Lenses" so you understand it, then
> use the six answers below as what you'd actually *say* out loud in the seminar.
> Say the lens name and name a reading when you speak — that's what gets you noticed.

---

## The Story (in plain language)

In 2018, in Tempe, Arizona, **Uber** was testing **self-driving cars** on public roads.
One night a car driving itself hit and killed **Elaine Herzberg**, who was walking her
bicycle across a dark road, away from a crossing. It was the first time a self-driving
car ever killed a pedestrian.

It wasn't one mistake — it was a **chain of failures**:

1. **The software got confused.** It saw her 5.6 seconds before impact (enough time to
   stop), but kept changing its mind about what she was — car? bike? unknown object? —
   and each time it changed its guess, it threw away where she'd been heading. So it
   never predicted she'd cross its path.
2. **Uber had made the car slow to brake on purpose.** They built in a 1-second pause
   before emergency braking (to avoid jerky, uncomfortable rides from false alarms), and
   they switched off the Volvo's own factory collision-avoidance system. The plan was:
   the human will catch any mistakes.
3. **The human wasn't watching.** The lone safety driver, Rafaela Vasquez, had been
   looking at a phone for about a third of the trip. She looked up ~1 second before
   impact — too late. (This is "automation complacency": watch a machine succeed for
   hours and you stop expecting it to fail.)
4. **The company was careless.** The crash investigators (NTSB) found Uber had no safety
   division, no safety plan, no safety manager, and didn't check whether drivers obeyed
   the no-phone rule. They called it an "inadequate safety culture."
5. **The regulator was hands-off.** Uber had moved to Arizona *because* California was
   too strict. Arizona wanted the business and barely checked up on them.

**What happened to people:** Uber paid the family (secret amount), faced no criminal
charges, and later sold its self-driving unit. The safety driver was charged, pleaded
guilty to a lesser charge, and got probation — her lawyer argued Uber should share the
blame for leaving her alone in the car. (Herzberg was also found to have contributed —
drugs in her system, crossing in a dark spot — but that doesn't undo the chain above.)

**The 2026 twist:** Eight years later, Uber (with UK company Wayve) is launching
self-driving taxis in London, each still with a safety driver. This time there's a new
law — the **UK Automated Vehicles Act 2024**:
- Self-driving cars must be **at least as safe as a careful, competent human driver**.
- If an authorised car is driving itself and crashes, **the company is responsible**, not
  the person in the seat.
- It's an offence to market a car as "self-driving" if it isn't officially approved.

**The big question of the seminar:** last time weak rules and a careless company got
someone killed. Have we actually learned anything, or are we repeating it in London?

---

## The Four Lenses (your toolkit)

**1. Utilitarianism — judge by the results.**
Greatest good, least suffering. Ask: *what was traded against what, and whose interests
got counted?*

**2. Deontology (Kant) / rights — judge by rules and duties.**
Some things are just wrong regardless of outcome. Never treat a person as *only* a means
to your goal. Includes **Rawls's veil of ignorance**: design the rule as if you don't
know whether you'll be the CEO or the pedestrian.

**3. Virtue ethics — judge the character and the motive.**
Not "what was done" but "what kind of actor does this, and why?" This is where "safety
culture" lives.

**4. Universalist vs relativist (a cross-cutting choice).**
Universalist = one standard for everyone, everywhere. Relativist = it depends on the
place/context. The exam wants you to *name* which one you're taking.

**The two readings in one line each:**
- **Stilgoe (2021):** companies sell safety two ways — "safety in numbers" (we drove X
  million miles, trust us — really just marketing that hides rare edge cases) vs
  "safety by design" (assume it's dangerous and prove it safe). His key move: don't ask
  "is it safe?" — ask **"safe enough for *what*, and safe enough for *whom*?"** And
  **trust is a gift from the public — hard to win, easy to lose.**
- **Siegel & Pappas (2023):** your beginner's guide to the three lenses above. Also says
  the famous **Trolley Problem is just a thought exercise, not a real design tool** —
  real roads have endless messy situations with no clean answer, so don't build your
  argument on it.

---

## The Six Questions — what to actually say

> These are written the way you'd talk in the room, not like a textbook. Trim them to
> taste. The moves that score: name the lens, name a reading, use a specific fact.

### Q1 — Three stakeholders, one ethical concern each

"Okay, so the obvious one is **Elaine Herzberg**, the woman who died. Her concern is
consent and basically dignity — she never signed up to be part of anyone's experiment,
she was just crossing the road, and she ended up as a test subject without knowing it.

Second, I'd pick the **safety driver, Rafaela Vasquez**. The concern for her is fairness
of blame. Uber had originally put *two* people in each car and then cut it to one, so
she was doing two jobs — watch the road *and* watch the software — on her own for hours.
That's a setup that's basically designed to fail, and then she's the one who ends up
charged. There's something off about putting a person in an impossible position and then
pinning it all on them.

And third, the **wider public in Tempe** — all the other pedestrians, cyclists, drivers
sharing those roads. Their concern is that they were turned into part of a live
experiment without ever agreeing to it. Stilgoe makes this exact point — the roads are a
public laboratory, and the public never consented to the trial."

*(If you want a fourth to show range: future users / disabled people who'd genuinely
benefit from this tech, whose concern is that a reckless rollout could kill it off and
take the real benefits with it.)*

---

### Q2 — The 1-second brake delay + disabling the Volvo system (utilitarian analysis)

"So this is really a utilitarian question — it's about weighing outcomes and asking who
got counted.

What Uber did was a straight trade-off. On one side you've got **passenger comfort and
the commercial product** — if the car slams on the brakes every time it sees a plastic
bag or a shadow, the ride is horrible and jerky, and that's bad for the business. So they
added the 1-second delay and turned off the Volvo's own emergency braking to smooth
things out. On the other side you've got **safety** — specifically the safety of anyone
the car might hit.

So in utilitarian terms, they traded *safety* for *comfort, fewer false alarms, and a
faster, cheaper path to market*. And the really damning bit is **whose interests got
counted**. They counted the riders and they counted Uber — comfort, cost, speed, the race
to launch. The one group that didn't get a vote in that calculation was **pedestrians
like Elaine**, who carry all the downside and get none of the upside.

A proper utilitarian wouldn't actually object to trade-offs — utilitarianism is fine with
trade-offs. The objection is that they did the sums *wrong*: they left the biggest cost,
a human life, basically out of the equation. And you can see it in the design — relying
on a bored human to catch a one-second-delayed emergency is a terrible bet when you look
at the actual expected outcome, which is exactly what happened."

---

### Q3 — Testing on people who never consented (deontology / Rawls)

"This is where I'd switch to the deontological lens, because utilitarianism can't quite
capture what feels wrong here.

Kant's basic rule is that you must never treat a person as *only* a means to your end —
people aren't tools. And that's pretty much exactly what happened. Elaine was used, without
her knowledge, as a live test for Uber's software. She was a means to Uber getting its
product to market. From a deontological view it doesn't even matter that self-driving
cars might save thousands of lives one day — you don't get to use a non-consenting person
as an instrument to get there. The ends don't justify it.

The cleanest way to show this is Rawls's **veil of ignorance**. Imagine you're writing
the rules for self-driving testing, but you don't know who you'll be in the story — you
might be the Uber CEO cashing in, or you might be the person walking her bike across the
road at night. Would you agree to the rule 'companies can test unproven cars on public
streets with a distracted lone driver and the backup braking switched off'? Almost nobody
would, *because they might be the pedestrian*. The fact that the rule only looks
acceptable if you're sure you're the CEO tells you it's not a fair rule.

So my answer is: no, testing unproven self-driving cars on public roads like this isn't
morally permissible, because it imposes a fatal risk on people who never agreed to carry
it and had nothing to gain. Stilgoe's point backs this up — the public are being
experimented on in plain sight, and consent and trust can't just be assumed."

---

### Q4 — Where does responsibility lie? (virtue ethics)

"The temptation is to blame the driver — she was on her phone, case closed. But virtue
ethics tells us to look past the single action and ask about *character* — what kind of
actor was behind all this, and why did it happen.

And the NTSB basically said this themselves: the software failure and the driver's
distraction were **symptoms** of Uber's safety culture. That word 'symptoms' is the whole
answer. If a company has no safety division, no safety plan, no safety manager, and never
checks whether its drivers follow the no-phone rule, then a distracted driver isn't a
freak event — it's the *predictable* result of how that company chose to operate.

So through a virtue-ethics lens, responsibility sits most heavily with **Uber's
leadership**, because they're the ones who shaped the culture. A genuinely responsible,
prudent organisation would have expected automation complacency — it's a well-known human
weakness — and built around it. Uber didn't. The engineers carry some too, for choosing
comfort over the braking safety net. The safety driver carries the least, honestly,
because she was put in a position almost guaranteed to produce this. And Arizona carries
some as the body that was supposed to be the grown-up in the room and chose to look away.

The point of virtue ethics here is that you can't fix this by just firing one driver. If
the character of the organisation is careless, you'll get another crash. You have to fix
the culture."

---

### Q5 — Arizona 2018 vs the UK's Automated Vehicles Act 2024

"So the contrast is pretty stark. Arizona in 2018 was deliberately light-touch — they
actively courted self-driving companies, and Uber literally moved there *because*
California was too strict. The NTSB found Arizona exercised insufficient oversight both
before and after the crash. So the governance was basically 'come and test on our roads,
we won't ask hard questions.'

The UK's 2024 Act changes two things that matter directly to this case. First, there's an
actual **safety standard** — authorised cars have to be at least as safe as a careful,
competent human driver — so a company can't just show up and start testing on a vibe.
Second, and this is the big one, **responsibility moves to the company**. When an
authorised car is driving itself, the 'authorised self-driving entity' — the developer or
manufacturer — is on the hook, not the person in the seat.

Would it have prevented the crash? Honestly, I'd be careful here, and I'd lean on Stilgoe.
The Act is a real improvement on allocating *blame* — under it, you couldn't dump
everything on a lone driver the way Arizona effectively did; the company would carry it,
which would force Uber to take safety culture seriously. But Stilgoe's warning is that a
lot of these frameworks still rest on the company's own 'safety case' — the company
proving to the regulator that it's fine — which is closer to his 'safety in numbers'
reassurance than to genuinely independent 'safety by design.' And the detailed UK safety
standard is still being written. So I'd say: the Act would have **reallocated
responsibility** far better and probably pushed Uber to behave more carefully — but on its
own it's not a guarantee the crash wouldn't happen, because it still leans on companies to
mark their own homework."

---

### Q6 — Three governance measures for the London pilot (10 marks — the big one)

"This is the one worth the marks, so I'd actually commit to a position. I'll take a
**universalist** stance — I think there should be one consistent safety standard that any
self-driving operator has to meet, not something that bends depending on which city or
country is keenest for the business. That's basically the opposite of the Arizona 'race to
the bottom,' and it's in the spirit of Stilgoe arguing that safety can't just be left to
whatever each company and local authority will tolerate.

So, three measures:

**One — independent safety verification, not self-certification.** The operator shouldn't
be allowed to just submit its own safety case and get waved through. There should be an
external body actually checking the system before and during the pilot. This goes straight
at Stilgoe's distinction — self-certified 'safety in numbers' is really public
*reassurance*, whereas independent checking is closer to genuine 'safety by design.' And
it directly answers the Arizona failure, where nobody independent was really watching.

**Two — mandatory sharing of safety-critical data, basically an 'ethical black box.'**
Every incident and near-miss on the London pilot should be logged and shared with the
regulator and ideally across operators, so everyone learns from each other's mistakes
instead of each company privately hiding its edge cases. The Tempe car saw Herzberg and
mishandled it; that kind of failure should become shared public knowledge, not a secret.
This is a universalist, 'learn as a whole system' approach rather than every company
protecting itself.

**Three — strict rules on the human safety driver, enforced, not just written down.** Uber
had a no-phone rule and never checked it. So: no lone operators doing two jobs at once,
active monitoring that the driver is actually attentive, and real consequences for the
*company* if it isn't enforced. This answers automation complacency head-on — we *know*
humans switch off when they watch a machine succeed for hours, so you design and police
around that known weakness instead of pretending it away.

And I'd tie it back to why universalist: Stilgoe's line is that trust is a gift from the
public, hard to win and easy to lose. A patchwork where safety depends on how badly a
city wants the business is exactly how you lose that trust. One firm standard, independently
checked, with shared learning, is how you earn it."

*(If pushed on relativism: you can concede that some details — speed limits, which streets
count as the operational area — reasonably vary by city. But the core safety *floor*
should be universal. That nuance shows you understand both sides.)*

---

## 60-Second Pre-Seminar Cheat Sheet

| Q | Lens | One-line answer |
|---|------|-----------------|
| 1 | (any) | Herzberg = no consent; safety driver = unfair blame / set up to fail; public = unwitting experiment |
| 2 | Utilitarian | Traded safety for comfort/profit/speed; counted riders + Uber, not pedestrians |
| 3 | Deontology / Rawls | Used her as a means without consent; behind the veil you'd never allow it → not permissible |
| 4 | Virtue ethics | Failures were *symptoms* of bad safety culture → blame sits with Uber leadership |
| 5 | Governance | UK Act reallocates blame to the company + sets a standard; but still leans on self-certification (Stilgoe) |
| 6 | Universalist | (1) independent verification (2) shared data / ethical black box (3) enforced driver rules |

**Three phrases to drop in the room:** "safe enough for *what* and for *whom*" (Stilgoe) ·
"trust is a gift from the public" (Stilgoe) · the failures were "symptoms" of the safety
culture (NTSB). And flag early that the Trolley Problem is just a thought exercise
(Siegel & Pappas) so nobody wastes the hour on it.
