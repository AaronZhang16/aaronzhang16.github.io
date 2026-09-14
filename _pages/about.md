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

<span class='anchor' id='about-me'></span>

I am doing reserach on image processing, such as **super resolution**, **airflow's visualization based on Background Oriented Schlieren (BOS)** and **event camera**. You can check my works in the following part. Please feel free to contact me with kaihang816@gmail.com if you want an academic cooperation.

I was born and grew up in Guangzhou, China. I graduated from School of Electronics and Information Technology (School of Microelectronics), Sun Yat-sen University (中山大学电子与信息工程学院) with a bachelor's degree. I went to Japan for further education from 2021 and graduated from Graduate School of Science and Technology, University of Tsukuba (筑波大学大学院システム情報工学研究群) with a master's degree, advised by Prof. Hajime Nobuhara ([延原肇](https://nobuharaken.com/hajime_nobuhara) 教授). I received my Ph.D. of Engineering degree from the University of Tsukuba in 2026, advised by Prof. Hajime Nobuhara ([延原肇](https://nobuharaken.com/hajime_nobuhara) 教授).

Beside my native language Chinese, I can speak both English and Japanese (JLPT N1 level).

My research interest includes **image restoration**, **image generation** and **evenet camera**.

# 🔥 News

- I received my Ph.D. of Engineering degree from the University of Tsukuba in March, 2026.

# 📝 Publications

### Conference

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">IEEE SMC 2022</div>
      <img src='images/PUB1.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  [A Denoisable Super Resolution Method: A Way to Improve Structure from Motion's Performance against CMOS's Noise](https://ieeexplore.ieee.org/document/9945277)  
  **Kaihang Zhang**, Hajime Nobuhara

This study addresses the effects of low image resolution and CMOS sensor noise on Structure from Motion (SfM) reconstruction. We propose two training strategies, Add Noise before Downsampling (An-Ds) and Downsampling before Adding Noise (Ds-An), that selectively introduce noise extracted from real photographs into super-resolution training images. Without changing the network architecture, these strategies enable simultaneous resolution enhancement and denoising. Experiments with SRCNN and EDSR show improved restoration of noisy images, while EDSR largely preserves its performance on clean images. 

</div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">SICE FES 2025</div>
      <img src='images/Figure3_2.jpg' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  [Observing Colorless, Transparent, High-Speed Airflow: Using Event Camera to Improve Schlieren Airflow Visualization Method](https://ieeexplore.ieee.org/document/11236636)  
  **Kaihang Zhang**, Xingzhen Song, Hajime Nobuhara

This study explores the visualization of transparent, rapidly changing airflow by combining an event camera with a conventional frame camera for background-oriented schlieren (BOS) imaging. A beam splitter and synchronization workflow provide aligned images and event data. We introduce BOS U-Net to generate a BOS image at a specified time from an input frame and the corresponding events, and construct a dataset containing 5,464 frames and 2,732 event samples for training and evaluation. An airflow attention strategy gives greater weight to weak airflow signals during training. Experiments demonstrate the feasibility of this approach, although recovering fine airflow structures remains challenging and requires further improvement.

</div>
</div>


### Journal

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">JACIII Vol.28 No.6 pp. 1284-1298 (2024)</div>
      <img src='images/PUB2.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  [Adding Noise to Super-Resolution Training Set: Method to Denoise Super Resolution for Structure from Motion Preprocessing](https://www.fujipress.jp/jaciii/jc/jacii002800061284/)  
  **Kaihang Zhang**, Hajime Nobuhara, Muhammad Haris

Extending our earlier work, this study investigates noise-aware super-resolution training as a preprocessing step for Structure from Motion (SfM). Two strategies introduce real-world noise before or after downsampling, enabling existing networks to enhance resolution and suppress noise without architectural changes. We evaluate the approach with SRCNN, EDSR, RCAN, and ESRT to examine its applicability across different network designs. The results show improved restoration of noisy images while largely retaining performance on clean images. In SfM experiments, mean reprojection error decreases by up to 27% and the number of densified 3D points increases by up to 310% relative to reconstruction without preprocessing, yielding more complete 3D models.

</div>
</div>


# 🎖 Honors and Awards

- *2018*  **Kaihang Zhang**, Wanqi Shi and Wenxuan Zou, Interdisciplinary Contest in Modeling (MCM/ICM) 2018 **Honorable Mention**

# 📖 Educations

- *2023.04 - 2026.03 (now)*, Graduate School of Science and Technology, University of Tsukuba ((筑波大学大学院システム情報工学研究群　知能機能システム学位プログラム)
- *2021.04 - 2023.03*, Graduate School of Science and Technology, University of Tsukuba (Master) (筑波大学大学院システム情報工学研究群　知能機能システム学位プログラム　修士卒業)
- *2015.09 - 2019.06*, School of Electronics and Information Technology (School of Microelectronics), Sun Yat-sen University (Bachelor). (中山大学电子与信息工程学院，学士)

# 💬 Research Projects

- *2023.09 - 2024.03*　2023 Young Researcher Training Program for the Degree Programs in Systems and Information Engineering / Graduate School of Systems and Information Engineering, University of Tsukuba (筑波大学　令和5年度 システム情報工学研究群　[若手研究者育成プログラム](https://www.sie.tsukuba.ac.jp/edu/re_program)　画像処理手法によりドローンのダウンウォッシュ気流を可視化する方法　**研究代表者**)
- *2023.11 - 2026.03*　"Development of a smart weeding system using AI", Development and improvement of strategic smart agricultural technologies, University of Tsukuba　(筑波大学　戦略的スマート農業技術の開発・改良　[「AIを活用したスマート除草システムの開発」](https://www.naro.go.jp/laboratory/brain/smart-nogyo/theme/files/SA1-415G1.pdf))
- *2024.4-2026.3* [Support for Pioneering Research Initiated by the Next Generation (SPRING)](https://www.jst.go.jp/jisedai/spring/en/index.html), JST (次世代研究者挑戦的研究プログラム、科学技術振興機構)

# 💻 Work Experience

- *2022.06 - 2023.02*, TOA Industry Co.,Ltd. R&D (株式会社東亜産業　研究開発部)
- *2023.11 - 2024.03*, Research Assistant, Ibaraki University (茨城大学　リサーチアシスタント)
- *2023.11 - 2026.03*, Research Assistant, University of Tsukuba (筑波大学　リサーチアシスタント)
