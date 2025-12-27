---
permalink: /
title: Home
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am **KaiXu Chen (陳凱旭)**, a researcher at the [**Center for Computational Sciences (CCS)**](https://www.ccs.tsukuba.ac.jp/eng/), University of Tsukuba, Japan. 
I earned my Ph.D. in Engineering in 2025 at the University of Tsukuba under the supervision of **Prof. Yoshihiro Kuroda** in the [Life Engineering Lab](https://www.lelab.jp/).

Originally from China, I moved to Japan for my graduate studies, completing a Master of Engineering at Kanazawa University and then a Ph.D. at the University of Tsukuba. 
My research focuses on **computer vision** and **medical image analysis**, with an emphasis on deep learning and generative models (such as GANs) for healthcare applications. In particular, I aim to develop intelligent systems that allow machines to interpret visual data and assist in medical diagnostics, with the ultimate goal of improving patient outcomes.

Beyond my core research, I am passionate about scientific outreach and education. I maintain a technical blog where I share insights from my research and development work, with the goal of making complex machine learning and computer vision concepts accessible to a broader audience.

## Research Topics

<ul>{% for post in site.research reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

You can find more details about my research and publications on the [Research](./research/) page.

## Current Focus
- **Video-based clinical motion analysis**: phase-aware gait representation learning and diagnostic classification  
- **Multi-view 3D pose pipeline**: robust 3D reconstruction under imperfect camera setups  
- **Attention-guided multimodal fusion**: combining RGB, optical flow, keypoints, and domain priors for better interpretability  
