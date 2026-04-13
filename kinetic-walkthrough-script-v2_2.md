# Kinetic — Video Walkthrough Script
**Target length:** 3–4 minutes | **Tone:** Confident & direct

---

## INTRO — Frame the problem
*(no prototype on screen yet, speak to camera)*

"Before I show you the prototype, I want to be clear about what this problem actually is — because the brief frames it correctly.

This is not a data policy problem. It's not an ethics problem. It's an incentive design problem. 71% of clinics want to receive shared history, but only 19% want to share theirs. That gap exists because the rational, self-interested move — right now — is to take without giving.

The task is to flip that. To make sharing the selfish choice."

---

## ASSUMPTIONS — Be transparent upfront
*(still to camera or slide)*

"A few assumptions I'm working with that shape the design.

First — I'm assuming clinics do not need to share PII. No patient contact details, no identifying clinic information. What the network needs is structured, outcome-level data: session counts, protocol categories, functional outcome scores. That's enough to be clinically useful, and it's the minimum needed to address the two fears I'll come to in a moment.

Second — I'm treating this as a Heidi product context. Heidi already operates inside clinics as an AI care partner. That means the contribution score and access gating I've designed isn't some external system clinics have to adopt — it sits inside tooling they're already using. That's a significant adoption advantage. The opt-in isn't a new commitment. It's a settings toggle.

Third — I'm not assuming clinics are altruistic. Every mechanism in this system works even if every clinic is purely self-interested."

---

## ADDRESSING THE TWO FEARS — By design, not by trust
*(still to camera or slide — this is the intellectual core)*

"The brief identifies two fears stopping clinics from sharing. Both of them are rational. And both of them need to be neutralised at the system level — not argued away.

**Fear one: patient switching.** Clinics worry that sharing history makes it easier for patients to leave. The design response is simple — the system never surfaces which clinic treated a patient previously. Not to the receiving clinic, not to the patient during search. History is framed as patient-owned continuity, not clinic-to-clinic transfer. The receiving clinic sees that a patient has prior history. They do not see where it came from. There is no competitive discovery. No contact information is passed. No referral trail. The patient has already booked with you before the history appears — so by the time you see it, you've already won the appointment.

**Fear two: clinical judgment.** Clinics worry that another physio will read their notes and form a negative opinion of their treatment. The design response is to never share notes. What's shared is abstracted and structured: session counts, protocol categories, ICD diagnosis codes, and functional outcome scores. Not a single word of clinician opinion enters the network. There's nothing to judge because the format makes judgment impossible.

Both fears are addressed by what the system structurally cannot do — not by what it promises not to do. That distinction matters. Clinics don't need to trust Heidi. The architecture makes the risk impossible."

---

## PROTOTYPE DEMO — Walk the four states
*(screen share the clinic dashboard)*

"The clinic-facing prototype shows four states. Let me walk through what each one means.

**State one — opted out.** Switch to Shoreside Physio. The dashboard shows a locked history count, zero contribution score, and a banner telling them 612 clinics are sharing data they can't see. The patient lookup shows locked history banners. This is the current reality for clinics that don't participate. The cost is already there — they just can't feel it yet.

**State two — just opted in.** Switch to Peak Health. The toggle is flipped. Score is at 47. History now exists, but it arrives with a 48-hour delay. This is intentional — early adopters get immediate value, but the system signals clearly that their access grows as their score does. They're better off than they were yesterday. Opting in was already worth it.

**State three — Tier 2, mid adopter.** Switch to Harbour Physio. Three months in, score at 412. Patient history is now 70% accessible, outcome benchmarking is unlocked, intake is visibly faster. This clinic has a concrete operational advantage over non-sharers.

**State four — Tier 4, top contributor.** Switch to Apex Rehabilitation. Full history, instant access, priority feature input into the roadmap. This is the end state the system is pulling every clinic toward.

Head to the Data Sharing tab — this is where both fears are addressed visually. Clinics never see who treated the patient before. Treatment notes and clinician opinions are never shared. What's shared is abstracted, structured, and outcome-focused. Judgment fear is solved by design, not by trust."

---

## THE PATIENT-FACING LAYER — Kinetic Connect
*(switch to the patient-facing prototype)*

"Now the piece that makes the whole system self-reinforcing — the patient-facing interface, Kinetic Connect.

This is a discovery layer sitting on top of the same network. Patients search for a physio by condition and location, exactly like they would anywhere else. But the ranking is different. Clinics are surfaced in order of their Network Contribution Score. The clinic that shares the most appears first. Apex Rehabilitation — Tier 4, top 8% of the network — sits at position one. Shoreside Physio, who opted out, sits below a clear divider reading 'not connected to the Heidi Kinetic network.'

This does two things. For patients, it surfaces clinics that can actually access their history — making continuity of care visible and searchable. For clinics, it converts the contribution score into something directly tied to revenue: search rank position. That's a far more visceral incentive than data access alone.

Click into Apex. The detail panel shows their tier, their contribution count, their outcome score — and critically, a history match banner. This patient has prior treatment on the network, and Apex can access it with consent at booking. The patient knows this before they book. That's the selection pressure.

The key design constraint here is that this doesn't reintroduce the switching fear. The patient can see that Apex has history access — but they cannot see which clinic provided it. No competitive discovery. The ranking rewards contribution, not treatment history. A clinic rises by sharing, not by having treated someone before.

The two products — the clinic dashboard and the patient discovery layer — form a closed loop. Clinics share more to rank higher. Ranking higher drives more bookings. More bookings give them more history to share. The network becomes self-reinforcing without anyone needing to act charitably."

---

## SCALING ARGUMENT — 19% → 80%
*(switch to Network Simulator tab on the clinic dashboard)*

"Now the scaling logic. Open the simulator.

Phase one — 19% adoption. Early adopters are protected. Even a thin network gives them something. Their contribution scores are compounding while everyone else's sits at zero. This is the critical design move: early adopters are rewarded, not exposed.

Phase two — 45%. Non-sharers start feeling the cost. Competing clinics have faster intake and higher search visibility on Kinetic Connect. Patients with prior history show locked banners daily. The access gap is visible. Joining is now low-risk because the network is established. Mid adopters don't need to be convinced — the market is doing it.

Phase three — 80%+. Non-participation is now the anomaly. Patients ask why their history isn't being used. Referrers prefer connected clinics. The system has shifted the norm. No one is forced or shamed into joining — the opportunity cost of staying out has become irrational.

That's the game theory principle at work: sharing becomes the dominant strategy. Even if you assume every other clinic is acting entirely selfishly, opting in still benefits you more than opting out."

---

## CLOSE — Tie back to Heidi
*(back to camera)*

"The reason this works in a Heidi context specifically is that the infrastructure is already there. Heidi is inside the clinic workflow. The contribution score, the access tiers, the abstracted data sharing — these aren't a new product to sell. They're a layer on top of what clinics are already doing. And Heidi already has the patient touchpoints that make a discovery layer like Kinetic Connect a natural extension, not a cold launch.

The system doesn't ask clinics to trust each other. It doesn't ask them to be generous. It doesn't argue that sharing is ethically right. It just makes the math work in favour of participation — and makes opting out progressively more expensive.

That's the design."

---

*Total estimated read time at natural speaking pace: ~3 min 30 sec*
