# Facundo Viñas Canale

Co-founder and CTO at **Alethia Earth**, where I own the science: eddy-covariance flux towers and satellite imagery feeding models that estimate how much CO₂ a piece of land actually removed — and, just as importantly, how sure we are about it.

AI Engineering student at Universidad de San Andrés (Buenos Aires), 10.0/10.0 GPA and Best Student Award in both first and second year. ICPC regional finalist in 2024 and 2025, and co-founder of UdeSA's competitive programming club — now 100+ members and the Argentine university sending the most teams past regionals.

## What I'm working on

**Carbon flux modeling at Alethia.** \\
Gradient boosting baselines and modern sequence architectures over ~700 FLUXNET sites and 24 years of half-hourly eddy-covariance data, trained and validated site-wise so the numbers mean something on land the model has never seen. Process-model calibration validated against tower ground truth, and a full uncertainty budget propagated by Monte Carlo.

**V-JEPA for biomedical video.** \\
Self-supervised world models over embryo development microscopy — pretraining a joint-embedding predictive architecture on hundreds of thousands of clips, then probing the representations for downstream staging. Half of that work is forensic: reading loss curves and layer statistics closely enough to catch representation collapse before it quietly poisons every result downstream.

**Reacher — an autonomous B2B prospection agent.** \\
Co-lead on a system that researches companies, drafts personalized outreach, sends it, watches for replies and writes follow-ups, all running unattended. Durable search workers, a tool-use harness, Supabase-backed state and an onboarding flow where an agent reads your site and generates its own targeting context. Benchmarked down to cents per company fully researched, which is the number that decides whether a pipeline like this is a product or a demo.

**Autonomous agents that perceive and act.** \\
Behavior cloning and DAgger for embodied agents in open-ended 3D environments, with V-JEPA as the visual encoder — the same architecture family as the biomedical work, pointed at control instead of diagnosis. It sits on top of classical robotics: before learned policies, I did the estimation and planning stack by hand on real hardware.

## What I'm good at

**Deep learning on messy physical-world data.** \\
Spatio-temporal graph networks, transformers for long-horizon time series, and self-supervised pretraining where labels are scarce and expensive. Production computer vision on live factory camera feeds. Enough statistics to know the hard part is rarely the architecture: it's leakage, group-aware validation, calibrated uncertainty, and controls strong enough that a positive result means something. I pre-register the threshold before I run the experiment, and I've killed my own models when the number came in under it.

**LLM systems, not LLM demos.** \\
Agent harnesses that hold context across long-horizon work, MCP servers, tool-use and structured-output pipelines, and the evaluation scaffolding to tell whether any of it actually improved. I routinely orchestrate a dozen coding agents in parallel across isolated worktrees, with adversarial review as a mandatory gate — it has caught real data-corrupting bugs before they shipped. Local inference too — Whisper for ASR, Piper for TTS — when the data shouldn't leave the machine.

**Shipping, not just training.** \\
Multi-tenant SaaS in production with per-tenant billing, row-level security, distributed rate limiting, and an async render path that cut throughput cost by 4×. Fail-closed CI on ephemeral self-hosted runners. Infrastructure migrations that cut hosting spend by two thirds.

**Robotics and state estimation.** \\
A full probabilistic-robotics stack in ROS 2 on TurtleBot3 hardware: LIDAR and odometry processing, differential-drive kinematics, odometry motion models, Monte Carlo localization with a likelihood field, EKF localization against LIDAR landmarks, occupancy-grid mapping and FastSLAM, ICP scan matching, and path planning with A*, Theta*, RRT and RRT*. Written from the math up, not assembled from packages.

**The fundamentals underneath.** \\
Numerical optimization and linear algebra implemented rather than imported: gradient descent with optimal step size, Tikhonov regularization, SVD, condition-number analysis. Competitive programming keeps the algorithms sharp.

Python and PyTorch most days; TypeScript for the tooling; C, C++, Java, Kotlin and Haskell when the problem asks for them.

## Side projects I actually use

Small tools I built for myself and still run every day:

- **[second-brain-system](https://github.com/FacuVCanale/second-brain-system)**
A plain-text graph knowledge base (Obsidian + git) that an AI agent maintains alongside me over MCP. The thesis is separating durable knowledge from daily operation.
- **[cc-life-planner](https://github.com/FacuVCanale/cc-life-planner)** 
The operational half of that split: markdown state, slash commands, and a local timeline viewer that auto-calibrates how optimistic my time estimates are.
- **[session-bridge](https://github.com/FacuVCanale/session-bridge)** 
Converts sessions between Claude Code and Codex CLI so the same work resumes in either tool.
- **[self-hosted-ci](https://github.com/FacuVCanale/self-hosted-ci)** 
A fail-closed protocol for opt-in CI on ephemeral self-hosted runners: transactional leases, admission fencing, and per-commit verifiable attestations.

## Previously

**AI Engineer at PSAG** (2024–2025) — computer-vision pipelines for factory QA/QC with on-site cameras.

**AI Engineer intern at Move37AI** (2024) — real-time performance prediction from time-series data.

**AI Advisor at YDLab I** (2025) — the first edition of the Youth Diplomats AI Lab, training 50+ participants on AI for policy.

**Teaching assistant**, Introduction to Programming at UdeSA (2024).

Freelance work since: a virtual try-on platform taken to production for a retail client.

Selected competition work: First place at HackITBA 2024 as team lead, and first place at the ITBA GameJam 2023.

---

Reach me at [facundovcanale@gmail.com](mailto:facundovcanale@gmail.com) or on [LinkedIn](https://linkedin.com/in/facuvcanale/). Open to research collaborations and consulting work in applied ML.
