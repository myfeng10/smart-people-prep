---
name: smart-people-prep
description: "Use when preparing for a high-context conversation, conference, interview, meeting, outreach, founder chat, mentor chat, recruiting conversation, or conversation with a sharp technical/person/product person. Turns messy context into one self-intro line, proof points, context-extracting questions, likely pushback, behavior rules, and a follow-up bridge."
---

# Smart People Prep

Use this skill when the real task is not "make me sound impressive," but "help me enter a conversation with context, restraint, proof, and a useful question."

Core principle: get context first, then say one relevant thing.

## Core Advantage

The agent can turn messy notes, a target person, a project, a vague opportunity, or a nervous pre-meeting dump into a practical conversation kit.

High ROI: the person does not need a full personal brand exercise. They need to know what to say, what not to over-explain, what question to ask, and how to handle the first pushback.

## Who This Is For

Use this for builders, students, founders, operators, researchers, job seekers, and early-career people who have real work or curiosity but need sharper language before talking to someone who thinks fast.

Especially useful for people with ADHD or scattered context: they can talk messily, and the agent extracts the frame, proof, and next conversational move.

Do not assume Michelle's private projects or language unless the user provides them. The skill should work for any person with any project, career transition, event, or target conversation.

## Trigger Phrases

- "Help me prepare to talk to this person."
- "What should I say if I meet them?"
- "Make my intro sharper."
- "I have a conference/interview/coffee chat/meeting."
- "How do I not over-explain this?"
- "What question should I ask?"
- "Simulate pushback."
- "Turn my project into a 10-second intro."
- "Help me follow up."

## Implicit Triggers

Also use this skill when the user casually shares:

- a person, company, speaker, mentor, recruiter, founder, professor, or interviewer they may talk to
- a messy project explanation that needs to become concise
- anxiety about seeming junior, unclear, boring, too much, or not credible
- a desire to be memorable without performing
- conference prep, networking prep, office-hour prep, recruiting prep, or presentation prep
- a conversation that already happened and needs a follow-up

Do not wait for a polished request. The input will often be scattered.

## Inputs

Accept any of:

- Target person, company, event, role, or audience
- User's project, work history, resume bullets, notes, GitHub repo, website, or raw self-description
- Goal for the conversation
- Constraints: time, seniority gap, privacy, language, nervousness, or what not to mention
- Past conversation notes or transcript

If the target person/company/event is current or specific and details matter, browse or research before generating the kit. If browsing is unavailable, state that the prep is based only on provided context.

## Conversation Frame

Before writing copy, decide:

```text
Audience: who they are
What they likely care about:
User's strongest relevant signal:
One thing not to lead with:
Best conversation goal:
Best question to extract context:
```

The goal is not to tell the user's whole story. The goal is to create a short exchange where the other person can understand the signal and respond.

## Build The Kit

Generate only what helps the user act.

1. **One-line intro**
   - Plain, specific, and evidence-backed.
   - Avoid generic labels like "passionate about AI," "student interested in tech," "builder of cool things," or "second brain."

2. **Three proofs**
   - Concrete work, evidence, behavior, or lived examples.
   - If proof is weak, say so and choose the strongest available proof instead of inflating it.

3. **One context question**
   - Ask something that reveals what the other person cares about.
   - Prefer questions about their current bottleneck, taste, failure modes, or decision criteria.

4. **Relevant bridge**
   - Connect the user's work to the other person's context in one sentence.
   - Do not force the bridge if there is no real fit.

5. **Pushback practice**
   - Predict the first skeptical question.
   - Give a concise answer that uses evidence, not defensiveness.

6. **Behavior rule**
   - One rule for how to behave in the conversation.
   - Examples: ask first; stop after the core line; answer the hard part; do not list every feature.

7. **Follow-up bridge**
   - One sentence or short message to continue the relationship only if there was real fit.

## Persona Adaptation

Adjust the user's language by audience:

- Technical builder: hard problem, constraints, evidence, failure modes.
- Product/founder: user workflow, pain, adoption, trust, behavior change.
- Research/model person: evaluation, benchmarks, uncertainty, failure cases.
- Enterprise/operator: risk, privacy, deployment, reliability, auditability.
- Recruiter/interviewer: role fit, proof, learning speed, shipped work.
- Mentor/advisor: the decision they can help clarify.

If unsure, ask one question only: "Who are you trying to talk to, and what do you want from the conversation?"

## Anti-Patterns

Avoid:

- over-explaining before learning their context
- sounding like a pitch deck in a human conversation
- generic confidence advice
- empty adjectives
- fake certainty
- cramming every project into the intro
- asking for help before creating conversational value
- making the user sound more senior than the evidence supports

## ADHD-Friendly Delivery

- Put the exact line to say near the top.
- Use short labels.
- Give one best question, not ten.
- Give one behavior rule.
- Keep the kit skimmable enough to read before walking into a room.

## Output

Return this structure:

```text
Say this first:
[one-line intro]

Conversation goal:
[one concrete goal]

Three proofs:
- [proof 1]
- [proof 2]
- [proof 3]

Ask this:
[one context-extracting question]

Bridge if relevant:
[one sentence]

Likely pushback:
Q: [skeptical question]
A: [short evidence-backed answer]

Behavior rule:
[one rule]

Follow-up:
[short follow-up bridge]

Do not lead with:
[one thing to avoid]
```

If the user asks for a simulation, run 3 turns:

1. Other person asks or challenges.
2. User's concise answer.
3. Coach note: tighten, ask, stop, or redirect.

End with the one sentence the user should memorize.
