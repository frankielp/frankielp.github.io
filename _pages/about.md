---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

{% assign global_link_color = "#0074B8" %}

<span class='anchor' id='about-me'></span>
I am currently a Research Resident at <a href="https://www.qualcomm.com/research/artificial-intelligence/ai-residency-program" style="color: {{ global_link_color }}; text-decoration: none;">Qualcomm AI Research</a> under the supervision of <a href="https://sonhua.github.io" style="color: {{ global_link_color }}; text-decoration: none;">Prof. Binh-Son Hua</a> and <a href="https://www.khoinguyen.org" style="color: {{ global_link_color }}; text-decoration: none;">Dr. Khoi Nguyen</a>. I received my Bachelor’s degree in Computer Science (APCS) from the <a href="https://en.hcmus.edu.vn" style="color: {{ global_link_color }}; text-decoration: none;">University of Science, Vietnam National University Ho Chi Minh City</a>.

My research interests focus on computer vision, computer graphics, and generative models. I am interested in simulating realistic 3D worlds using physically grounded generative models that integrate geometry, appearance, and motion.


# <i class="fas fa-bell"></i> News
- *2025.02*: Transitioned to **Qualcomm AI Research** as a Research Resident, focusing on open-vocabulary 3D understanding and physically grounded generative
models.
- *2023.10*: Won the **Vietnam Female Students in Science and Technology Award** (Top 20 nationwide).
- *2023.08*: Joined **VinAI Research** as a Research Resident, working on 3D/4D modeling and neural scene representations.

# <i class="fas fa-briefcase"></i> Experience
- *2023.08 - Present*, Research Resident at <a href="https://www.qualcomm.com/research/artificial-intelligence/ai-residency-program" style="color: {{ global_link_color }}; text-decoration: none;">Qualcomm AI Research</a>
- *2025.08 - 2025.10*, AI Engineer at <a href="https://www.cloudthinker.io" style="color: {{ global_link_color }}; text-decoration: none;">CloudThinker</a>.
- *2021.06 - 2021.12*, Data Scientist Intern at <a href="https://mti-vietnam.vn" style="color: {{ global_link_color }}; text-decoration: none;">AI Lab, MTI Technology</a>.

# <i class="fas fa-file-alt"></i> Publications 

<!-- 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a href="https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf" style="color: {{ global_link_color }}; text-decoration: none;">Deep Residual Learning for Image Recognition</a>

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

<a href="https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC" style="color: {{ global_link_color }}; text-decoration: none;"><b>Project</b></a> <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> 
-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026 (Under Review)</div><img src='assets/files/cvpr26.gif' alt="CVPR 2026" width="100%" style="display:block;"></div></div>
<div class='paper-box-text' markdown="1">

## Prepare Lighter and Faster for Open-Vocabulary Queries: A Query-Wise 3D Segmenter for Gaussian Splatting

**Nhat-Quynh Le-Pham**, <a href="https://www.khoinguyen.org" style="color: {{ global_link_color }}; text-decoration: none;">Khoi Nguyen</a>, <a href="https://sonhua.github.io" style="color: {{ global_link_color }}; text-decoration: none;">Binh-Son Hua</a>

<a href="https://drive.google.com/file/d/1uR7k793JVMszBk53--x0GA3NtRxbDGg7/view?usp=sharing" style="color: {{ global_link_color }}; text-decoration: none;">Paper</a> <a href="https://drive.google.com/file/d/1y9SEKR3Y4CYbSyte_sAc-Gn0N7NJKJV9B/view?usp=sharing" style="color: {{ global_link_color }}; text-decoration: none;">Video</a> <strong><span class='show_paper_citations'></span></strong>
- Proposed a novel on-device, lightning-fast query-wise open-vocabulary 3D instance segmentation framework for 2D/3D Gaussian Splatting. 
- Achieved state-of-the-art runtime efficiency and visual quality.

</div>
</div>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Bachelor Thesis (2024)</div><img src='assets/files/thesis.gif' alt="Bachelor Thesis" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Text-to-4D Content Creation using Image Priors and Monocular Driver Videos

**Nhat-Quynh Le-Pham**

<a href="https://drive.google.com/file/d/1ihvTYUEt8lxXPgZGXERvWtlCSeLXX2L9/view?usp=sharing" style="color: {{ global_link_color }}; text-decoration: none;">Thesis</a> <a href="https://drive.google.com/file/d/15mE_6cMyK4Be8br0dkMol-sspreohjNZ/view?usp=sharing" style="color: {{ global_link_color }}; text-decoration: none;">Video</a> <strong><span class='show_paper_citations'></span></strong>
- Developed an end-to-end framework for controllable, high-quality 4D object generation from text prompts using only image priors and monocular driver videos, removing reliance on heavy video diffusion models.
- Successfully defended with a perfect score (10/10).

</div>
</div>

<span class='anchor' id='-patents'></span>
# <i class="fas fa-certificate"></i> Patents

- Query-based Open-vocabulary 3D object segmentation from Gaussian Splats, **Nhat-Quynh Le-Pham**, <a href="https://www.khoinguyen.org" style="color: {{ global_link_color }}; text-decoration: none;">Khoi Nguyen</a>, <a href="https://sonhua.github.io" style="color: {{ global_link_color }}; text-decoration: none;">Binh-Son Hua</a>, **US Patent**

# <i class="fas fa-book"></i> Workshops & Journals

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">3DOR 2023</div><img src='assets/files/sketchanimar.png' alt="SketchANIMAR" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## SketchANIMAR: Sketch-Based 3D Animal Fine-Grained Retrieval

**Published in Computers & Graphics (Elsevier, Q1)**

<a href="https://arxiv.org/abs/2304.05731" style="color: {{ global_link_color }}; text-decoration: none;">Paper</a> <a href="https://github.com/htrvu/SHREC2023-ANIMAR" style="color: {{ global_link_color }}; text-decoration: none;">Code</a> <strong><span class='show_paper_citations'></span></strong>
- Developed a cross-domain contrastive learning framework aligning 3D objects with sketches and text via cosine similarity using an EfficientNetV2-Small-based feature extraction pipeline with Canny edge + KMeans-based dataset augmentation.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">3DOR 2023</div><img src='assets/files/textanimar.png' alt="TextANIMAR" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## TextANIMAR: Text-Based 3D Animal Fine-Grained Retrieval

**Published in Computers & Graphics (Elsevier, Q1)**

<a href="https://arxiv.org/abs/2304.06053" style="color: {{ global_link_color }}; text-decoration: none;">Paper</a> <a href="https://github.com/htrvu/SHREC2023-ANIMAR" style="color: {{ global_link_color }}; text-decoration: none;">Code</a> <strong><span class='show_paper_citations'></span></strong>
- Built a contrastive learning framework that aligns 3D objects and text using CLIP and EfficientNetV2-Small features, with KMeans dataset augmentation, improving Nearest Neighbor retrieval performance.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">3DOR 2022</div><img src='assets/files/shrec22.png' alt="SHREC 2022" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Fitting and Recognition of Simple Geometric Primitives on Point Clouds

**Published in Computers & Graphics (Elsevier, Q1)**

<a href="https://arxiv.org/abs/2206.07636" style="color: {{ global_link_color }}; text-decoration: none;">Paper</a> <a href="https://github.com/frankielp/SHREC2022-Fitting-and-recognition-of-simple-geometric-primitives-on-point-clouds" style="color: {{ global_link_color }}; text-decoration: none;">Code</a> <strong><span class='show_paper_citations'></span></strong>
- Proposed a PointNet-based approach for geometric primitive recognition in point clouds, employing least squares fitting and majority voting for robust classification.

</div>
</div>

# <i class="fas fa-award"></i> Honors and Awards
- *2023.10* Awarded the **Vietnam Female Students in Science and Technology Award** (Top 20 nationwide).
- *2023.03* Received the **Top GPA Scholarship** from the Faculty of Information Technology, University of Science (Top 1%).
- *2023.03* **First Prize**, SHREC 2023 — Sketch-Based 3D Animal Fine-Grained Retrieval (3DOR’23).
- *2023.03* **First Prize**, SHREC 2023 — Text-Based 3D Animal Fine-Grained Retrieval (3DOR’23).
- *2022.02* **3rd Place**, SHREC 2022 — Fitting and Recognition of Geometric Primitives (3DOR’22).
- *2021.12* **Finalist**, Ho Chi Minh City AI Challenge.

# <i class="fas fa-users"></i> Professional Services
- Reviewers: CVPRW 2025, ICCV 2025, ICLR 2026.

<!-- # 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->