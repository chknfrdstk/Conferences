# From Log Files to Live Signals: Rethinking HPC Operations on Linux Bare Metal — Borislav Sabotinov

Texas Linux Fest 2026 — November 6–7, 2026, JJ Pickle Research Campus, Austin, TX

Summaries verified live November 12, 2026 from the Texas Linux Fest YouTube channel @texaslinuxfest3002, cross-checked against the official pretalx schedule. View counts and upload dates are as of November 12, 2026. Upload date is inferred from YouTube's "2 days ago" at the time of checking.

- **Video title (YouTube):** "Texas Linux Festival 2026-11-07: Log Files to Live Signals Rethinking HPC Operations on Bare Metal" — note the YouTube title drops "From" at the start and "Linux" before "Bare Metal" versus the pretalx title.
- **URL:** [https://www.youtube.com/watch?v=b_Skx8NwcA0](https://www.youtube.com/watch?v=b_Skx8NwcA0)
- **Duration:** 55:09 · **Uploaded:** November 10, 2026 (inferred) · Views at check: 10
- **Description (YouTube):** not verified — the video page could not be loaded at check time, so the description is unknown, not confirmed empty.
- **Repository:** none found in pretalx, YouTube description, or slides — no talk-linked repo located.
- **Content:** A large share of high-performance compute (HPC) work runs on Linux: the schedulers, bare metal nodes, job queues, and MPI processes. The operating model is usually reactive — an engineer submits a job, waits hours or days, and reads a log file after the damage is done. This talk is a real enterprise case study in flipping that model from reactive to proactive: a Linux-native automation layer connecting a chat-based control plane to underlying bare metal HPC infrastructure, serving several thousand internal engineering users running millions of simulations per year. Shell scripts and system-level integration drive event-driven pipelines; pre-submit validation catches failures that never needed to run, runtime inspection of solver state identifies stalled or diverging jobs while they are still cheap to kill, and near real-time alerts move job status out of log files and into chat. The reported result: hundreds of thousands of compute hours saved per year, tens of thousands of engineer hours reclaimed, and millions of dollars in cost savings. Pretalx: Saturday 2:00 PM, Bevo. Speaker: Borislav Sabotinov, software engineer in Austin, TX working on large-scale engineering platforms spanning HPC, container orchestration, and cloud systems; writes at bss8.dev.
- **Most useful for:** HPC operators and platform engineers; anyone running long jobs on bare metal Linux who lives in log files after the fact.
