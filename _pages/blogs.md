---
layout: archive
permalink: /blogs/
author_profile: true
---
<!--
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?user=BoGbpiIAAAAJ}}">my Google Scholar profile</a>.</u>
{% endif %}


{% include base_path %}
-->
{% include base_path %}

Blogs
======

* **Bing He**, Rui Sun, Zhan Shi, Building and Aligning LLM using User Data and RL, [Blog link](https://binghe2727.github.io/Building-and-Aligning-LLM-using-User-Data-and-RL/), November 2025

    **Blog Summary**: This blog discusses the challenges and solutions in building and aligning large language models (LLMs) using user data and reinforcement learning (RL). It walks through an end-to-end alignment stack for an open-ended dialogue model: from low-level training stability in Mixture-of-Experts (MoE) to FP8 serving, supervised fine-tuning (SFT) on user chats, and finally reinforcement learning (RL) driven by engagement and retention signals.

* Zhan Shi, Rui Sun, **Bing He**, Awesome Cursor Training Tutorial, [Blog Link](https://github.com/Gitsamshi/awesome_cursor_tutorial), November 2025

    **Blog Summary**: A comprehensive guide to understanding how Cursor scales Reinforcement Learning (RL) for AI-powered code assistance from Ray Summit 2025. Cursor uses a sophisticated RL pipeline that trains AI models to become better coding assistants by learning from real-world interactions in a production-like environment. The system consists of three main components working in harmony: (1) Trainer: Handles model training with custom optimizations; (2) Inference: Manages model deployment and load balancing; (3) Environment: Provides a production-grade agent server for realistic training. 

* Zhan Shi, Rui Sun, **Bing He**, The Hidden Language of AI: How Chat Templates Reveal the Evolution of LLMs, [Blog Link](https://medium.com/@shizhanszh34/the-hidden-language-of-ai-how-chat-templates-reveal-the-evolution-of-llms-77c1120c0cba), October 2025

    **Blog Summary**: The blog explains that “chat templates”—the hidden formatting that turns role-tagged messages into the exact token strings models were trained on—have quietly driven LLMs’ evolution from plain text completion to multi-turn assistants to tool-enabled agents. It traces the shift from early prompt hacks to role labels and system prompts (which enforce persona and rules), then shows how different ecosystems (OpenAI, Llama, Mistral, Qwen) adopted incompatible templates, prompting Hugging Face’s Jinja-based standardization. We also provide practical guides that using the wrong template degrades quality, highlights the token-economics of template design, and forecasts templates expanding to handle tool use, multi-agent threads, million-token contexts, and richer modalities.


