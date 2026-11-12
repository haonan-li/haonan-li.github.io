---
permalink: /
title: "Haonan Li"
layout: clean
redirect_from:
  - /about/
  - /about.html
---
<h1>{{ site.name }}</h1>

<section class="hero">
<div class="hero-left">
<img class="profile-photo" src="{{ site.author.avatar | prepend: '/images/' }}" alt="Photo of {{ site.name }}">
<p class="affiliation"><b>IFM, MBZUAI</b> &mdash; Senior Research Scientist</p>
<p class="links">
<a href="mailto:{{ site.author.email }}">Email</a>
<a href="{{ site.author.googlescholar }}">Google Scholar</a>
<a href="https://github.com/{{ site.author.github }}">GitHub</a>
<a href="https://huggingface.co/{{ site.author.huggingface }}">Hugging Face</a>
<a href="https://x.com/{{ site.author.twitter }}">X</a>
<a href="https://www.linkedin.com/in/{{ site.author.linkedin }}">LinkedIn</a>
<a href="/cv/">CV</a>
</p>
</div>
<div class="hero-right">
<h2>About</h2>
<p>I am a Senior Research Scientist at the <a href="https://ifm.mbzuai.ac.ae/">Institute of Foundation Models (IFM)</a>, MBZUAI, where I lead a team working on LLM post-training, reasoning, agents, and inference. I am the tech lead of <a href="https://arxiv.org/abs/2611.10224">Jais 3</a> and a core contributor to IFM's K2 models, including <a href="https://mbzuai.ac.ae/?p=34400">K2 Horizon</a>, <a href="https://www.k2think.ai/">K2-Think</a>, <a href="https://huggingface.co/LLM360/K2-V2-Instruct">K2-V2</a>, and <a href="https://huggingface.co/LLM360/K2-Think-V2">K2 Think V2</a>.</p>
<p>My research focuses on <b>LLM post-training</b> (SFT and RL), <b>reasoning</b> and <b>agents</b>, <b>AI for mathematics</b> with Lean verification, and the <b>evaluation and safety</b> of LLMs, including for Arabic and Chinese.</p>
<p>Previously, I was a Postdoctoral Research Fellow at MBZUAI and co-founder and CTO of <a href="https://www.librai.tech/">LibrAI</a>, working on LLM evaluation and safety. I received my Ph.D. from the University of Melbourne, supervised by Timothy Baldwin, Martin Tomko, and Maria Vasardani.</p>
</div>
</section>

## Highlights

* Tech lead of Jais 3: six open Arabic-centric agentic models (0.9B--375B) adapted from K2 Horizon through continual pre-training, SFT, and RL; first author of the [technical report](https://arxiv.org/abs/2611.10224) ([models](https://huggingface.co/inception42/Jais-3-32B)).
* Core contributor to [K2 Horizon](https://mbzuai.ac.ae/?p=34400), IFM's fully open model fleet (0.9B--375B), working on inference and the open-weight release.
* AI for math: [Magenta](https://arxiv.org/abs/2609.11319) closes the loop between LLM reasoning and Lean 4 verification, reaching 100% on AIME 2025, AIME 2026, and HMMT Feb 2026 and solving all six IMO 2026 problems with K2-Horizon-7B; [Pythagoras-Prover](https://arxiv.org/abs/2606.12594) won the Best Paper Award at the MathNLP Workshop at EMNLP 2026.
* Co-led RL training for [K2-Think](https://www.k2think.ai/) and data curation for [K2-V2](https://huggingface.co/LLM360/K2-V2-Instruct); proposed the DALU algorithm, which enables RL training with 2× longer context and improves reasoning benchmarks such as AIME25 and LiveCodeBench by ~10%.
* Led the evaluation of [Jais](https://arxiv.org/abs/2308.16149), an Arabic-centric open LLM, and contributed to [LM Evaluation Harness](https://github.com/EleutherAI/lm-evaluation-harness).
* Built widely used benchmarks and tools, including [CMMLU](https://github.com/haonan-li/CMMLU), [Do-Not-Answer](https://github.com/Libr-AI/do-not-answer) (featured in the Stanford AI Index Report 2024), [Libra-Leaderboard](https://leaderboard.librai.tech/), and [Loki](https://github.com/Libr-AI/OpenFactVerification) (1,000+ GitHub stars).

## News

<table class="news">
{%- for item in site.data.news %}
<tr><td class="news-date">{{ item.date }}</td><td>{{ item.text | markdownify | remove: '<p>' | remove: '</p>' | strip }}</td></tr>
{%- endfor %}
</table>
<p class="more"><a href="/about_old_news/">Older news &rarr;</a></p>

## Selected Publications

{% assign selected = site.data.publications | where_exp: "p", "p.selected" | sort: "selected_order" -%}
{%- for pub in selected %}{% include pub.html pub=pub %}{% endfor %}
<p class="note">* Equal contribution. <a href="/publications/">Full publication list &rarr;</a></p>

## Contact

<p>Feel free to reach out by <a href="mailto:{{ site.author.email }}">email</a> about research or collaboration.</p>
