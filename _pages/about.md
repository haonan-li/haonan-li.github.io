---
permalink: /
title: "Haonan Li"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a Senior Research Scientist at the [Institute of Foundation Models (IFM)](https://ifm.mbzuai.ac.ae/), [MBZUAI](https://mbzuai.ac.ae/), where I lead a team working on LLM post-training, reasoning, agents, and inference. I am the tech lead of [Jais 3](https://arxiv.org/abs/2611.10224), IFM's family of open Arabic-centric agentic models, and a core contributor to IFM's K2 models, including [K2 Horizon](https://mbzuai.ac.ae/?p=34400), [K2-Think](https://www.k2think.ai/), [K2-V2](https://huggingface.co/LLM360/K2-V2-Instruct), and [K2 Think V2](https://huggingface.co/LLM360/K2-Think-V2). I also work on AI for mathematics, combining LLM reasoning with Lean verification.

Previously, I was a Postdoctoral Research Fellow at [MBZUAI](https://mbzuai.ac.ae/) and co-founder and CTO of [LibrAI](https://www.librai.tech/), where I worked on the evaluation and safety of LLMs. I received my Ph.D. from the University of Melbourne, supervised by Timothy Baldwin, Martin Tomko, and Maria Vasardani.

My research focuses on LLM post-training (SFT and RL), reasoning, and agents; AI for mathematics; and the evaluation and safety of LLMs, including for Arabic and Chinese.

Highlights
======
* Tech lead of Jais 3: six open Arabic-centric agentic models (0.9B--375B) adapted from K2 Horizon through continual pre-training, SFT, and RL; first author of the [technical report](https://arxiv.org/abs/2611.10224) ([models](https://huggingface.co/inception42/Jais-3-32B)).
* Core contributor to [K2 Horizon](https://mbzuai.ac.ae/?p=34400), IFM's fully open model fleet (0.9B--375B), working on inference and the open-weight release.
* AI for math: [Magenta](https://arxiv.org/abs/2609.11319) closes the loop between LLM reasoning and Lean 4 verification, reaching 100% on AIME 2025, AIME 2026, and HMMT Feb 2026 and solving all six IMO 2026 problems with K2-Horizon-7B; [Pythagoras-Prover](https://arxiv.org/abs/2606.12594) won the Best Paper Award at the MathNLP Workshop at EMNLP 2026.
* Co-led RL training for [K2-Think](https://www.k2think.ai/) and data curation for [K2-V2](https://huggingface.co/LLM360/K2-V2-Instruct); proposed the DALU algorithm, which enables RL training with 2× longer context and improves reasoning benchmarks such as AIME25 and LiveCodeBench by ~10%.
* Led the evaluation of [Jais](https://arxiv.org/abs/2308.16149), an Arabic-centric open LLM, and contributed to [LM Evaluation Harness](https://github.com/EleutherAI/lm-evaluation-harness).
* Built widely used benchmarks and tools, including [CMMLU](https://github.com/haonan-li/CMMLU), [Do-Not-Answer](https://github.com/Libr-AI/do-not-answer) (featured in the Stanford AI Index Report 2024), [Libra-Leaderboard](https://leaderboard.librai.tech/), and [Loki](https://github.com/Libr-AI/OpenFactVerification) (1,000+ GitHub stars).

Selected Publications
======
* <b>Jais 3: Introducing Arabic-centric Agentic AI</b><br>Team IFM: <b>Haonan Li</b>, Hadi Abdine, Nikhil Ranjan, et al. IFM Technical Report, 2026. [[paper](https://arxiv.org/abs/2611.10224)] [[models](https://huggingface.co/inception42/Jais-3-32B)]
* <b>Magenta: Closing the Loop Between Mathematical Reasoning and Lean Verification</b><br>Joshua Ong Jun Leang, <b>Haonan Li</b>, Zheng Zhao, Xinyi Shang, Wenda Li, Zhengzhong Liu, Eric Xing, Shay Cohen, Eleonora Giunchiglia. Preprint, 2026. [[paper](https://arxiv.org/abs/2609.11319)]
* <b>K2-Think: A Parameter-Efficient Reasoning System</b><br>Zhoujun Cheng, Richard Fan, Shibo Hao, Taylor W. Killian, <b>Haonan Li</b>, et al. Preprint, 2025. [[paper](https://arxiv.org/abs/2509.07604)]
* <b>Control Illusion: The Failure of Instruction Hierarchies in Large Language Models</b><br>Yilin Geng, <b>Haonan Li</b>, Honglin Mu, Xudong Han, Timothy Baldwin, Omri Abend, Eduard Hovy, Lea Frermann. AAAI 2026. [[paper](https://arxiv.org/abs/2502.15851)] [[code](https://github.com/yilin-geng/llm_instruction_conflicts)]
* <b>Principled Data Selection for Alignment: The Hidden Risks of Difficult Examples</b><br>Chengqian Gao, <b>Haonan Li</b>, Liu Liu, Zeke Xie, Peilin Zhao, Zhiqiang Xu. ICML 2025. [[paper](https://proceedings.mlr.press/v267/gao25f.html)] [[code](https://github.com/glorgao/SelectiveDPO)]
* <b>ToolGen: Unified Tool Retrieval and Calling via Generation</b><br>Renxi Wang, Xudong Han, Lei Ji, Shu Wang, Timothy Baldwin, <b>Haonan Li</b>. ICLR 2025. [[paper](https://arxiv.org/abs/2410.03439)] [[code](https://github.com/Reason-Wang/ToolGen)]
* <b>CMMLU: Measuring Massive Multitask Language Understanding in Chinese</b><br><b>Haonan Li</b>, Yixuan Zhang, Fajri Koto, Yifei Yang, Hai Zhao, Yeyun Gong, Nan Duan, Timothy Baldwin. Findings of ACL 2024. [[paper](https://aclanthology.org/2024.findings-acl.671/)] [[code](https://github.com/haonan-li/CMMLU)]
* <b>Do-Not-Answer: Evaluating Safeguards in LLMs</b><br>Yuxia Wang\*, <b>Haonan Li\*</b>, Xudong Han\*, Preslav Nakov, Timothy Baldwin. Findings of EACL 2024. [[paper](https://aclanthology.org/2024.findings-eacl.61/)] [[code](https://github.com/Libr-AI/do-not-answer)]

\* Equal contribution. See the [full publication list](/publications/) or [Google Scholar](https://scholar.google.com/citations?user=IqfgexsAAAAJ).

What's New
======
* Nov 2026 --- We released the [Jais 3 technical report](https://arxiv.org/abs/2611.10224), describing how we adapted the K2 Horizon fleet into Arabic-centric agentic models.
* Oct 2026 --- [Pythagoras-Prover](https://arxiv.org/abs/2606.12594), our efficient Lean theorem prover, won the Best Paper Award at the MathNLP Workshop at EMNLP 2026.
* Oct 2026 --- We released [Jais 3](https://huggingface.co/inception42/Jais-3-32B) ([news](https://gulfnews.com/uae/uae-launches-jais-3-arabic-native-ai-for-speech-writing-and-agents-1.500711935)), six open Arabic-centric agentic models (0.9B--375B) built on K2 Horizon, together with an Arabic speech recognition model and 24 Arabic benchmarks. I am the tech lead of the project.
* Sept 2026 --- We released [Magenta](https://arxiv.org/abs/2609.11319), a training-free pipeline that pairs LLM reasoning with Lean 4 verification. It reaches 100% on AIME 2025, AIME 2026, and HMMT Feb 2026, and solves all six IMO 2026 problems with K2-Horizon-7B.
* Sept 2026 --- We released [K2 Horizon](https://mbzuai.ac.ae/?p=34400), six fully open models from 0.9B to 375B parameters, with weights, code, training data, and methodology released under Apache 2.0.
* Jan 2026 --- We released [K2 Think V2](https://mbzuai.ac.ae/news/mbzuai-launches-k2-think-v2-uaes-fully-sovereign-next-generation-reasoning-system/), a 70B reasoning system built on K2-V2 and open end to end, from pre-training data to post-training and evaluation.
* Dec 2025 --- We released [K2-V2](https://huggingface.co/LLM360/K2-V2-Instruct), our most capable fully open model to date, and one of the strongest open-weight models in its class. [X](https://x.com/mbzuai/status/1996986508231012502).
* Sept 2025 --- We released [K2-think](https://www.k2think.ai/), the world’s fastest open-source AI model and the most advanced open-source AI reasoning system ever created.

[Older news](/about_old_news/)
