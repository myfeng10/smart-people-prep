# Smart People Prep

Know what to say before talking to someone who thinks fast.

**Use it when:** you have a short conversation with someone senior, want to learn one thing, and tend to over-explain when nervous.

**Returns:** one opening line, a conversation goal, three proofs, one strong question, likely pushback, a stopping rule, and a conditional follow-up.

## Actual user case

> Prepare me for a 15-minute conference conversation with the CTO of an agent-infrastructure startup. She cares about evaluation and production reliability. I built a local MCP workflow plus instrumentation for repeated reads and context saturation, but I have no large-scale production metrics. My goal is to learn which reliability failure their team still cannot measure. I tend to over-explain architecture when nervous.

## What the skill returns

> **Say this first**
>
> “I work on agent evaluation, and recently built a local MCP workflow instrumented to detect repeated reads and context saturation—small-scale so far, but it made me curious about what production agent failures remain effectively invisible.”
>
> **Conversation goal**
>
> Learn which reliability failure their team can observe after something goes wrong but still cannot measure or predict early—and whether your evaluation experience could help frame it.
>
> **Three proofs**
>
> - You built a working MCP-based agent workflow, not merely a benchmark proposal.
> - You instrumented concrete behavioral failure signals: repeated reads and context saturation.
> - You think in terms of detection and evaluation, while being honest that you have not validated the approach at production scale.
>
> **Ask this**
>
> “What reliability failure do you recognize in customer incidents, but still can't reliably surface early through telemetry or evaluations?”
>
> Then stop. Let her choose the problem.
>
> **Bridge if relevant**
>
> “That's close to the kind of problem I enjoy: turning an observed failure pattern into a measurable signal and then testing whether it predicts degraded behavior.”
>
> **Likely pushback**
>
> **Q: “But does your instrumentation work at production scale?”**
>
> “I don't know yet—I've only validated it locally. What I can show is that repeated reads and context saturation became observable rather than anecdotal. The next question I'd test is whether those signals remain predictive across longer, more varied production traces.”
>
> **Behavior rule**
>
> Answer in two layers: one sentence first, then pause. Explain implementation only if she explicitly asks “how?”
>
> Internal cue: **problem → signal → evidence → stop.**
>
> **Follow-up**
>
> “I appreciated your point about [specific failure]. I'd like to sketch how I might turn it into an observable signal and a small evaluation—would it be useful if I sent you a one-page outline?”

The result is designed for use during the conversation: one question, an honest proof boundary, and a stopping cue.

## Try it

```text
Use $smart-people-prep. Give me one intro, one question, likely pushback, a stopping rule, and a conditional follow-up.
```

Give it who you may meet, what they care about, your goal, your strongest honest proof, and what you tend to do when nervous.

## Install

```bash
npx skills add myfeng10/smart-people-prep
```

Restart your agent, then invoke it with `$smart-people-prep`.
