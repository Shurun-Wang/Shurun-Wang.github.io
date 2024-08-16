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

I received the Ph.D. degree in Electrical Engineering from Hefei University of Technology. I have published 5+ papers with 
 <a href='https://scholar.google.com/citations?user=Pb73FP8AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.

My research interest includes: 
- Physiological signal analysis
- Human-exoskeleton interaction
- Brain function connectivity analysis


# 🎓 Educations 
- *2019.09 - 2024.06*&ensp;Ph.D. in School of Electrical Engineering and Automation, Hefei University of Technology, Hefei, China. <a href="https://en.hfut.edu.cn/"><img class="svg" src="/images/hfut.png" width="16pt"></a> 
- *2023.04 - 2024.04*&ensp;Ph.D. in Graduate School of Medicine, Juntendo University, Tokyo, Japan. (Visiting Student) <a href="https://en.juntendo.ac.jp/"><img class="svg" src="/images/juntendo.png" width="16pt"></a> 
- *2016.09 - 2019.06*&ensp;M.Sc. in School of Electrical Engineering and Automation, Hefei University of Technology, Hefei, China. <a href="https://en.hfut.edu.cn/"><img class="svg" src="/images/hfut.png" width="16pt"></a> 
- *2012.09 - 2016.06*&ensp;B.Sc. in School of Electrical Engineering and Automation, Hefei University of Technology, Hefei, China. <a href="https://en.hfut.edu.cn/"><img class="svg" src="/images/hfut.png" width="16pt"></a> 


# 📝 Publications 
<h3 align="center">Under Review</h3>
<div style="border-bottom: 1px solid #000; margin: 0px 0;"></div> 

- __Shurun Wang__, Hao Tang*, Ryutaro Himeno, et al. Estimating Lower Extremity Multi-Joint Kinematics with One IMU Sensor via Attention-based Temporal Convolutional Neural Network.

- __Shurun Wang__, Hao Tang*, Ryutaro Himeno, et al. A Robust Denoising Diffusion Architecture for Completing Missing Regions of Multiple Physiological Signals. 

- __Shurun Wang__, Hao Tang*, Ryutaro Himeno, et al. Optimizing Graph Neural Network Architectures for Schizophrenia Spectrum Disorder Prediction Using Evolutionary Algorithms.

- __Shurun Wang__, Hao Tang*, Zhaowu Ping, et al. Improved Data-Driven Model-Free Adaptive Control Method for an Upper Extremity Power-Assist Exoskeleton.

- __Shurun Wang__, Hao Tang*, Ryutaro Himeno, et al. ECGDenoiser: A Magnitude-Aware Deep Learning Framework for Electrocardiogram Signal Enhancement.


<h3 align="center">2024</h3>
<div style="border-bottom: 1px solid #000; margin: 0px 0;"></div>

<div class='paper-box'>
    <div class='paper-box-image' style="text-align:center;">
        <img src='images/aiim24.png' alt="sym" style="max-width:80%; height:auto; margin:auto; vertical-align:middle">
    </div>
    <div class='paper-box-text'>
        <a href="https://www.sciencedirect.com/science/article/abs/pii/S0933365724000198">
            <papertitle> Integrated Block-Wise Neural Network with Auto-Learning Search Framework for Finger Gesture Recognition using sEMG Signals </papertitle>
        </a>
        <br>
        <strong>Shurun Wang</strong>, Hao Tang*, Feng Chen, et al.
        <br>
        <em> Artificial Intelligence in Medicine</em>, 2024 <a href="https://github.com/Shurun-Wang/ALSF">[code]</a>
        <p></p>
        <p>We propose an innovative auto-learning search framework (ALSF) based on a weighted double Q-learning (WDQ-learning) algo-rithm. The development of this framework is tailored to opti-mize the construction of neural networks to achieve superior gesture recognition performance. </p>
    </div>
</div>


<h3 align="center">2023</h3>
<div style="border-bottom: 1px solid #000; margin: 0px 0;"></div>

<div class='paper-box'>
    <div class='paper-box-image' style="text-align:center;">
        <img src='images/tnnls23.png' alt="sym" style="max-width:80%; height:auto; margin:auto; vertical-align:middle">
    </div>
    <div class='paper-box-text'>
        <a href="https://ieeexplore.ieee.org/document/9609089">
            <papertitle> A Novel Approach to Detecting Muscle Fatigue Based on sEMG by Using Neural Architecture Search Framework </papertitle>
        </a>
        <br>
        <strong>Shurun Wang</strong>, Hao Tang*, Bin Wang, et al.
        <br>
        <em> IEEE Transactions on Neural Networks ＆ Learning Systems</em>, 2023 <a href="https://github.com/Shurun-Wang/NAS">[code]</a>
        <p></p>
        <p>We propose a hierarchical exploration mechanism based on reinforcement learning to automatically generate high-performance CNN models, which can be used in detecting the muscle fatigue.</p>
    </div>
</div>


<h3 align="center">2022</h3>
<div style="border-bottom: 1px solid #000; margin: 0px 0;"></div>

<div class='paper-box'>
    <div class='paper-box-image' style="text-align:center;">
        <img src='images/jbhl22.png' alt="sym" style="max-width:80%; height:auto; margin:auto; vertical-align:middle">
    </div>
    <div class='paper-box-text'>
        <a href="https://ieeexplore.ieee.org/document/9857571">
            <papertitle> Continuous estimation of human joint angles from sEMG using a multi-feature temporal convolutional attention-based network </papertitle>
        </a>
        <br>
        <strong>Shurun Wang</strong>, Hao Tang*, Lifu Gao, et al.
        <br>
        <em> IEEE Journal of Biomedical and Health Informatics </em>, 2022 <a href="https://github.com/Shurun-Wang/MFTCAN-KNR">[code]</a>
        <p></p>
        <p> We propose a multi-feature temporal convolutional attention-based network (MFTCAN) to estimate the joint angles. <br>
          We develop a joint training mechanism that integrates MFTCAN with traditional statistical algorithms such as KNR and SVR.
</p>
    </div>
</div>

<div class='paper-box'>
    <div class='paper-box-image' style="text-align:center;">
        <img src='images/tim22.png' alt="sym" 
          style="max-width:80%; height:auto; margin:auto; vertical-align:middle">
    </div>
    <div class='paper-box-text'>
        <a href="https://ieeexplore.ieee.org/document/9762275">
            <papertitle> A Double Threshold Adaptive Method for Robust Detection of Muscle Activation Intervals from Surface Electromyographic Signals </papertitle>
        </a>
        <br>
        Hao Tang*, <strong>Shurun Wang</strong>, Qi Tan, et al.
        <br>
        <em> IEEE Transactions on Instrumentation and Measurement </em>, 2022 <a href="https://github.com/Shurun-Wang/sEMGDetection">[code]</a>
        <p></p>
        <p> We develop a robust SampEn-based algorithm to overcome the influence of the motion artifacts and irregular tonic spikes.  <br> We design a double threshold adaptive detection frame-work with interlocking structure to detect the onsets and offsets of muscle activation intervals.
</p>
    </div>
</div>

<h3 align="center">2021</h3>
<div style="border-bottom: 1px solid #000; margin: 0px 0;"></div>

<div class='paper-box'>
    <div class='paper-box-image' style="text-align:center;">
        <img src='images/bspc21.png' alt="sym" style="max-width:80%; height:auto; margin:auto; vertical-align:middle">
    </div>
    <div class='paper-box-text'>
        <a href="https://www.sciencedirect.com/science/article/pii/S1746809421001075">
            <papertitle> Analysis of Fatigue in the Biceps Brachii by Using Rapid Refined Composite Multiscale Sample Entropy </papertitle>
        </a>
        <br>
        <strong>Shurun Wang</strong>, Hao Tang*, Bin Wang, et al.
        <br>
        <em> Biomedical Signal Processing and Control</em>, 2021 <a href="https://github.com/Shurun-Wang/R2CMSE">[code]</a>
        <p></p>
        <p> We propose the rapid refined composite multiscale sample entropy (R2CMSE) to extract sEMG signal features, and this algorithm can describe the change process of muscle fatigue. </p>
    </div>
</div>

<h3 align="center">Patents</h3>
<div style="border-bottom: 1px solid #000; margin: 0px 0;"></div>

- Hao Tang, __Shurun Wang__, Bin Wang. A method for human motion intention recognition based on network architecture search. ZL202111251646.3 (Chinese）

# 🏅 Honors and Awards
- *2023.04*&ensp;Sponsored by the China Scholarship Council
- *2022.10*&ensp;National scholarship for doctoral students


# 💬 News
- *Now* &ensp;&ensp;&ensp;&ensp;![Visitors](https://api.visitorbadge.io/api/visitors?path=https://shurun-wang.github.io/&label=visitors&countColor=%232ccce4&style=plastic)
- *2024.06*&ensp;Graduated with a Ph.D.
- *2023.08*&ensp;Participate in the Brain/MINDS Data Portal Hackathon in RIKEN
- *2022.09*&ensp;Qi Liu and I have entered into matrimony
  



  
