---
layout: about
title: about
permalink: /
# subtitle:

profile:
  align: right
  image: tom.JPG
  image_circular: false # crops the image to make it circular
  # more_info: >
  # <p>555 your office number</p>
  # <p>123 your address street</p>
  # <p>Your City, State 12345</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: false # adds a vertical scroll bar if there are more than 3 news items
  limit: # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a research assistant in ML/AI, primarily working with the Data Science Institute at University of Technology Sydney (UTS) under Dr Bin Liang. My research is currently focussed on: Remote Sensing & Earth Observation for Tree Canopy Detection (Carbon sequestration & environmental monitoring); AR and Diffusion-based NLP; and a survey on Transformer-based Time Series Anomaly Detection architectures.

My professional background is in software engineering and product in the AI space - most recently as Chief Product Officer at Sydney-based [Lumachain](https://lumachain.io), developing an end-to-end Computer Vision AI platform for global blue chip food and beverage clients.

## news

- 01/2026 - paper preprint [A Survey of Large Language Models for Time Series Anomaly Detection](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6033215) available on SSRN 
- 01/2026 - qualified as NVIDIA Certified Associate: AI Infrastructure and Operations
- 12/2025 - invited to Session Chair at [17th Asian Conference on Machine Learning (ACML)](https://www.acml-conf.org/2025/) on 09-12 December 2025, Taipei.

## research interests

Currently focussed on: 
- Remote Sensing & CV: Faster-RCNN, ViT, DeepForest, Vision-Language Models & semantic reasoning, Heuristic vs Unguided learning, multimodal e.g. hyperspectral
- NLP: hybrid AR & Diffusion-based generative models i.e. denoising
- Neuro-AI: noisy dynamical systems, loss functions, very interested in unguided emergent behaviour

## papers

{% bibliography --query @*[selected=true] %}

<!-- I am a researcher working with a team at the Data Science Institute at University of Technology Sydney (UTS). My current projects focus on LLMs in Time Series Anomaly Detection, Earth Observation, and Natural Language Processing.

Put your address / P.O. box / other info right below your picture. You can also disable any of these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically.

Link to your social media connections, too. This theme is set up to use [Font Awesome icons](https://fontawesome.com/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below. Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them. -->
