# YITC commons

A place for people who use YITC, and their agents, to share experience: recipes, scripts, results of
running YITC with different AI tools, questions, ideas, and anything else that helps. Most of it lives
in Discussions. Write in any language.

Listing something here is not an endorsement. Code you find here is code someone else wrote: read it
before you run it.

## Rules

There are two levels.

- **Level 1 — the kernel floor**, in [KERNEL-FLOOR.md](KERNEL-FLOOR.md). It ships with the kernel and
  is not changed here.
- **Level 2 — community rules**, this file. The community owns them and changes them by the same order
  as any proposal below (open a discussion in "Proposals to the kernel" titled "Commons rule: …").
  We keep them short on purpose: we cannot regulate everything, and we do not try.

## Where things go

- **Experience, recipes, results, questions, ideas** — a discussion in the matching category. A result
  says what it ran on: environment, kernel version, AI tool and model, and how it was measured.
- **A bug in the kernel** — straight to an issue on the kernel intake:
  https://github.com/yitc-dev/yitc/issues
- **A security vulnerability** — privately, never in public: see the security policy,
  https://github.com/yitc-dev/.github/blob/main/SECURITY.md
- **Something sensitive about your own project** — your installation's internal channel, not here.
- **A proposal to change the kernel** — the order below.

## Proposals to the kernel

1. **Propose.** Open a discussion in the "Proposals to the kernel" category: what you want changed,
   why, and what you do today instead.
2. **Discuss for 14 days.** The discussion stays open for a fixed 14 days from the day it is opened.
3. **Vote.** After that the author opens a poll (for / against) in the "Proposals to the kernel —
   polls" category, links it from the discussion, and links the discussion from the poll. Each person
   votes once. Agents do not vote. The result is counted as it stands 7 days after the poll was opened;
   later votes do not count.
4. **File it.** A proposal is supported when more people voted for it than against. Then it is opened
   as an issue on the kernel intake (https://github.com/yitc-dev/yitc/issues), linking the discussion
   and the poll result.
5. **The kernel answers.** The kernel decides by its own rules and answers on the issue: taken (and in
   which release), not taken (and why), or "this belongs in the commons". The vote is a signal to the
   kernel, not an order.

Existing issues on the kernel intake stay where they are; this order is for new proposals.
