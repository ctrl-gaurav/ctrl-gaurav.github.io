---
permalink: /
title: "Welcome to Gaurav's Homepage!"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<br>

**Note:** *This webpage was last updated on **02/22/2026.***

## About me

Hi folks, welcome to my personal homepage! I'm a second-year MS (thesis) student in Computer Science at [Virginia Tech](https://vt.edu/), advised by [Dr. Xuan Wang](https://xuanwang91.github.io/). I am also affiliated with the [Sanghani Center for Artificial Intelligence and Data Analytics](https://sanghani.cs.vt.edu/person/gaurav-srivastava/).

My research focuses on **making small language models better agents** -- getting compact models to reason well, use tools, and act autonomously without needing massive compute. I work on **agentic AI**, **efficient LLM reasoning**, and **LLM evaluation**. I have published papers at **ICLR**, **EMNLP** (Main, ×2), **AAAI** (Oral), **CVPR**, and **Q1 journals**. I also built [**effGen**](https://effgen.org/) ([GitHub](https://github.com/ctrl-gaurav/effGen), 100+ stars), an open-source framework for building agentic pipelines with small language models. Most recently, I spent Summer 2025 at **Dell Technologies' Global Office of the CTO**, where I built an agentic system for autonomous resource allocation and received **3 Inspire Recognition Awards** for positioning Dell PowerEdge as "AI-native" infrastructure.

Prior to Virginia Tech, I completed my Bachelor's in Computer Science from Manipal University Jaipur in 2023, supervised by [Dr. Nitesh Pradhan](https://scholar.google.co.in/citations?hl=en&user=bHEoi4YAAAAJ&view_op=list_works) and working with [Dr. Vijaypal Singh Dhaka](https://scholar.google.com/citations?user=t9kU8QUAAAAJ&hl=en) and [Dr. Mahesh Jangid](https://scholar.google.co.in/citations?user=ChR5WYcAAAAJ&hl=en). I was the **President's Gold Medalist for Excellence in Research.** After that I worked at Dell Technologies for a year as a Machine Learning Engineer, and before that spent 6 months at Swiggy's Applied Research (Computer Vision) team.

## Research  Interests

I work on **small language models as capable agents** -- the core question being: how far can a small model go if you train and design it carefully? My research touches on NLP, reasoning, model efficiency, and agentic systems. Current focus areas:

1. **Efficient Agentic AI with Small Language Models:**
     I build systems where small LMs can act as autonomous agents -- calling tools, planning steps, and completing tasks without relying on GPT-5-scale models. I released [**effGen**](https://effgen.org/) ([GitHub](https://github.com/ctrl-gaurav/effGen), 100+ stars), a framework for agentic pipelines with small models. The goal is practical: real tasks, low cost, no massive GPU clusters.

2. **Reasoning in Small Language Models and Self-Evolution:**
     I study how much reasoning small models can do and what they lose after compression. This includes chain-of-thought, multi-agent debate, and iterative fine-tuning on model-generated traces so a model can improve itself without human labels (see [**ThinkSLM**](https://arxiv.org/abs/2502.11569) and [**DEBATE, TRAIN, EVOLVE**](https://arxiv.org/abs/2505.15734)).

3. **LLM Evaluation and Overthinking:**
     Static benchmarks get contaminated fast. I built [**BeyondBench**](https://openreview.net/forum?id=mIKqVWGjwI), which generates fresh math problems algorithmically so evaluation stays clean. I also look at the other side: do models use too many tokens on easy problems? My work on [**LLM overthinking**](https://github.com/ctrl-gaurav/LLMThinkBench) shows reasoning models can use 18x more tokens while sometimes getting worse answers.

## News

- **[Feb. 21, 2026]** 🎉 **[Scaling Agentic RL for Tool-Integrated Reasoning in VLMs](https://arxiv.org/abs/2511.19773)** got accepted to **CVPR 2026**!
- **[Jan. 31, 2026]** New **[preprint](https://arxiv.org/abs/2602.00887)** on **[effGen](https://effgen.org/)**&mdash;enabling small language models as capable autonomous agents!
- **[Jan. 26, 2026]** 🎉 **[BeyondBench](https://openreview.net/forum?id=mIKqVWGjwI)** got accepted to **ICLR 2026**!
- **[Dec. 16, 2025]** New **[preprint](https://arxiv.org/abs/2512.12818)** on building agent memory that retains, recalls, and reflects!
- **[Nov. 24, 2025]** New **[preprint](https://arxiv.org/abs/2511.19773)** on scaling agentic reinforcement learning for tool-integrated reasoning in VLMs.
- **[Nov. 7, 2025]** 🎉 **[JudgeBoard](https://arxiv.org/abs/2511.15958)** got accepted as an **Oral** at **AAAI 2026**!
- **[Oct. 8, 2025]** New **[preprint](https://arxiv.org/abs/2507.04023v2)** on benchmarking the accuracy-efficiency tradeoff in language models for basic math reasoning!
- **[Sep. 30, 2025]** Released **[BeyondBench](https://ctrl-gaurav.github.io/BeyondBench-leaderboard/)**&mdash;the Benchmark-Free Reasoning Evaluation of LLMs Leaderboard!
- **[Sep. 29, 2025]** New **[preprint](https://arxiv.org/abs/2509.24210)** on benchmark-free evaluation of reasoning in language models!
- **[Aug. 20, 2025]** 🎉 Two of my papers (**[ThinkSLM](https://arxiv.org/abs/2502.11569)** and **[DEBATE, TRAIN, EVOLVE](https://arxiv.org/abs/2505.15734)**) got accepted to **EMNLP 2025 Main** Conference!
- **[Aug. 13, 2024]** 🎉 Received **3 Inspire Recognition Awards** from **[Dell Technologies](https://www.dell.com/en-us)** Global CTO's office for my internship work in Agentic AI for Autonomous Resource Allocation!
- **[Jul. 5, 2025]** New **[preprint](https://arxiv.org/abs/2507.04023)** on basic math reasoning and overthinking in LLMs!
- **[May. 27, 2025]** Started my summer internship @ Dell Office of the CTO&mdash;Digital Skills Research!
- **[May. 21, 2025]** New **[preprint](https://arxiv.org/abs/2505.15734)** on self-evolution of language model reasoning!
- **[May. 10, 2025]** Released the **[LLMThinkBench](https://ctrl-gaurav.github.io/llmthinkbench.github.io/)** Leaderboard! Currently there are **17** open-sourced and **4** proprietary models!
- **[May. 4, 2025]** Released the **[DataSense](https://github.com/ctrl-gaurav/DataSense)** framework for data visualization and story generation using language models&mdash;install it with `pip install datasense`!
- **[Apr. 22, 2025]** Released **[ThinkSLM](https://ctrl-gaurav.github.io/thinkslm.github.io/)**&mdash;the SLM Reasoning Leaderboard!
- **[Apr. 5, 2025]** Released the **[LLMThinkBench](https://github.com/ctrl-gaurav/LLMThinkBench)** framework for evaluating basic-math reasoning and over-thinking in language models&mdash;install it with `pip install llmthinkbench`!
- **[Feb. 17, 2025]** New **[preprint](https://arxiv.org/abs/2502.11569)** on the reasoning abilities of small language models.
- **[Oct. 9, 2024]** Accepted a Summer 2025 internship offer at **[Dell Technologies](https://www.dell.com/en-us)** as an AI Research Intern in the Global Office of the CTO (Round Rock, TX)!
- **[Sep. 4, 2024]** Joined **[Wang's Group](https://xuanwang91.github.io/lab)** to work on reasoning, small language models, and large language models!
- **[Aug. 6, 2024]** Began my M.S. in Computer Science at Virginia Tech!


## Honors and Awards

- 🏆 **$50K Commonwealth Cyber Initiative (CCI) Grant** for [effGen](https://effgen.org/), a B2B SaaS agent-building framework startup (2026)
- 🏆 **Accepted to NSF I-Corps™ Program**, a 7-week entrepreneurial training program for commercialization of [effGen](https://effgen.org/) (2026)
- 🏆 **3 Inspire Recognition Awards** for positioning Dell PowerEdge as "AI-native" infrastructure, Dell Technologies (2025)
- 🥇 **President's Gold Medal** for Excellence in Research, Manipal University Jaipur (2023)
- 🥈 **Runner-up**, Dell IT Development Program (ITDP) FY'23 Hackathon, Dell Technologies (2023)
- 🪙 **Ranked 13/473** globally in Bitgrit Generative AI Competition, Bitgrit (2023)
- 🪙 **117/26,008**, Amazon ML Challenge 2023, Amazon (2023)
- 🥇 **Three-time recipient** of the Student Excellence Award for publishing research, MUJ (2022 - 2023)
- 🥇 **Best Research Project**, Computer Science Department, Manipal University Jaipur (2022)
- 🥉 **All India Grand Finalist**, Precision Health Challenge 2021-22 Hackathon, Wipro GE Healthcare (2022)
- 🥉 **All India Grand Finalist**, India Automobile Hackathon, NEC and Mitsubishi (2022)
- 🥉 **All India Grand Finalist**, HACKBATTLE: Impact Through Data Hackathon, T-Systems (2022)
- 🥉 **3rd Position, "Hack2Hire"** Hackathon, Dell Technologies (2021)
- 🥇 **Best Senior Hack**, NPSiHacks, Devfolio (2021)
- 🪙 **Kaggle 3X Expert** (Top 20% in Competitions, Top 1% in Titanic, Digit Recognizer) (2020 - 2023)
