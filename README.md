### Hi, I'm Chaitanya 👋

I build the infrastructure that lets AI agents **investigate, act, and improve**: the context they work from, the way they execute, and the evals that show whether they actually got better. I write about it at **[Oddly](https://oddly.fyi)**.

#### Projects

My projects keep coming back to one question: how do you share something scarce among many concurrent users when the feedback arrives late?

- **[lagged-budget-audit](https://github.com/fermibubble/lagged-budget-audit)**: When many LLM agents share one budget, the meter lags behind the spending. This is a reproducible audit of lag-aware pricing, replayed over 2,398 recorded SWE-agent runs. The results are mixed, and the README says so up front.
- **[fair_service_throttle](https://github.com/fermibubble/fair_service_throttle)**: Adaptive (AIMD) throttling for calls between services. When capacity runs short, it shares what is left fairly across customers, in O(1) time and memory.

#### Open source

- **[paperclipai/paperclip#18907](https://github.com/paperclipai/paperclip/pull/18907)** *(in review)*: An agent woken to answer another agent's question was told to continue the task instead. It tried to check the task out, got a `409`, and never answered, so the agent that asked waited forever.

#### Writing

- [How to Write and Score an Agent Eval](https://oddly.fyi/writing/how-to-write-and-score-an-agent-eval/): from a plausible wrong answer to a defensible release decision
- [Trustworthy Autonomy](https://oddly.fyi/writing/trustworthy-autonomy/): nine principles for systems that deserve the authority we give them
- [Building an Agent That Improves Its Own Harness](https://oddly.fyi/writing/building-an-agent-that-improves-its-own-harness/): turning repeated failures into tested changes
- [Implementing Progressive Disclosure for Agent Tools](https://oddly.fyi/writing/implementing-progressive-disclosure-for-agent-tools/): one discoverable CLI for MCP, SQL, and REST
