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

# 👋 Welcome! 
I am currently a second-year Ph.D. student (2023 Fall) at the Hong Kong University of Science and Technology, Guangzhou, under the supervision of Prof. [Ying-Cong Chen](https://www.yingcong.me/). Prior to this, I began my research journey as a Master's student in 2020 at the [MAC Lab](https://mac.xmu.edu.cn/) of [Xiamen University](https://www.xmu.edu.cn/) and received my Master's degree in Artificial Intelligence in 2023, advised by the Prof. [Rongrong Ji](https://mac.xmu.edu.cn/rrji_en/). 

My research interests focus on visual generative models, particularly in exploring their versatility ([Lotus](https://lotus3d.github.io/)), controllability ([DisEnvisioner](https://disenvisioner.github.io/)), and efficiency ([PixelFolder](https://arxiv.org/abs/2204.00833)). I am also interested in 3D vision and other AIGC tasks. 

<p style="color: red;">Feel free to contact me via e-mail if you are interested in discussing or collaborating with me. 😊</p>

<!-- I am passionate about doing more interesting work that can facilitate and enrich people's work and daily lives.  -->

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2025-01-23*: &nbsp;🎉🎉 Two Papers are accepted by ICLR2025! 

# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICLR 2025</div>
      <img src='images/lotus.jpg' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **LOTUS: Diffusion-based Visual Foundation Model for High-quality Dense Prediction**

  **Jing He**&#42; , [Haodong Li](https://haodong-li.com/)&#42;, [Wei Yin](https://yvanyin.net/), [Yixun Liang](https://yixunliang.github.io/), [Kaiqiang Zhou](), [Hongbo Zhang](), [Bingbing Liu](), [Ying-Cong Chen](https://www.yingcong.me/)<sup>†</sup><br>
  ICLR 2025 <br>
  [Paper](https://arxiv.org/abs/2409.18124) / [Project Page](https://lotus3d.github.io/) / [Github](https://github.com/EnVision-Research/Lotus) [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/EnVision-Research/Lotus">](https://github.com/EnVision-Research/Lotus) / [Demo (Depth)](https://huggingface.co/spaces/haodongli/Lotus_Depth) / [Demo (Normal)](https://huggingface.co/spaces/haodongli/Lotus_Normal) / [ComfyUI](https://github.com/kijai/ComfyUI-Lotus)
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICLR 2025</div>
      <img src='images/DE2.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **DisEnvisioner: Disentangled and Enriched Visual Prompt for Image Customization**

  **Jing He**&#42; , [Haodong Li](https://haodong-li.com/)&#42;,[Yongzhe Hu](), [Guibao Shen](https://scholar.google.com/citations?user=d8VVM4UAAAAJ&hl=en), [Yingjie Cai](https://yjcaimeow.github.io/), [Weichao Qiu](https://weichaoqiu.com/), [Ying-Cong Chen](https://www.yingcong.me/)<sup>†</sup><br>
  ICLR 2025 <br>
  [Paper](https://arxiv.org/abs/2410.02067) / [Project Page](https://disenvisioner.github.io/) / [Github](https://github.com/EnVision-Research/DisEnvisioner) [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/EnVision-Research/DisEnvisioner">](https://github.com/EnVision-Research/DisEnvisioner) / [Demo (Soon)]()
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Arxiv 2024</div>
      <img src='images/OmniBooth.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **OmniBooth: Learning Latent Control for Image Synthesis with Multi-modal Instruction**

  [Leheng Li](https://len-li.github.io/), [Weichao Qiu](https://weichaoqiu.com/), [Xu Yan](https://yanx27.github.io/), **Jing He**, [Kaiqiang Zhou](), [Yingjie Cai](https://yjcaimeow.github.io/), [Qing Lian](https://lianqing11.github.io/), [Bingbing Liu](), [Ying-Cong Chen](https://www.yingcong.me/)<sup>†</sup><br>
  arXiv 2024 <br>
  [arXiv](https://arxiv.org/abs/2410.04932) / [Project Page](https://len-li.github.io/omnibooth-web) / [Github](https://github.com/Len-Li/OmniBooth) / [Model](https://huggingface.co/lilelife/OmniBooth)
  </div>
</div>

<!-- <div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Arxiv 2024</div>
      <img src='images/Uni-Renderer.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **Uni-Renderer: Unifying Rendering and Inverse Rendering Via Dual Stream Diffusion**

  [Zhifei Chen](), [Tianshuo Xu](https://scholar.google.com/citations?user=I6_dXvEAAAAJ&hl=zh-CN), [Wenhang Ge](https://g3956.github.io/wenhangge.github.io/), [Leyi Wu](https://yuevii.github.io/), [Dongyu Yan](http://me.starydy.xyz/), **Jing He**, [Luozhou Wang](https://wileewang.github.io/), [Lu Zeng](), [Shunsi Zhang](), [Ying-Cong Chen](https://www.yingcong.me/)<sup>†</sup><br>
  arXiv 2024 <br>
  [Paper](https://arxiv.org/abs/2412.15050) / [Github (Soon)]()
  </div>
</div> -->

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">AAAI 2024</div>
      <img src='images/InstDiffEdit.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **Towards Efficient Diffusion-Based Image Editing with Instant Attention Masks**

  [Siyu Zou](), [Jiji Tang](), [Yiyi Zhou](https://scholar.google.com/citations?user=w3_2ep0AAAAJ&hl=zh-CN&oi=sra), **Jing He**, [Chaoyi Zhao](), [Rongsheng Zhang](https://scholar.google.com/citations?user=H1VQcLAAAAAJ&hl=zh-CN&oi=sra), [Zhipeng Hu](), [Xiaoshuai Sun](https://sites.google.com/view/xssun)<sup>†</sup><br>
  AAAI 2024 <br>
  [Paper](https://arxiv.org/abs/2401.07709) / [Github](https://github.com/xiaotianqing/InstDiffEdit)
  </div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ECCV 2022</div>
      <img src='images/PixelFolder.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **PixelFolder: An efficient progressive pixel synthesis network for image generation**

  **Jing He**, [Yiyi Zhou](https://scholar.google.com/citations?user=w3_2ep0AAAAJ&hl=zh-CN&oi=sra)<sup>†</sup>, [Qi Zhang](https://q7zhang.com/), [Jun Peng](), [Yunhang Shen](https://shenyunhang.github.io/), [Xiaoshuai Sun](https://sites.google.com/view/xssun), [Chao Chen](https://scholar.google.com/citations?user=lFvf1KEAAAAJ&hl=zh-CN&oi=sra), [Rongrong Ji](https://mac.xmu.edu.cn/rrji_en/) <br>
  ECCV 2022 <br>
  [Paper](https://arxiv.org/pdf/2204.00833) / [Github](https://github.com/jingheya/PixelFolder)
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ACM MM 2022</div>
      <img src='images/PixelFace.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **Learning dynamic prior knowledge for text-to-face pixel synthesis**

  [Jun Peng](), [Xiaoxiong Du](https://scholar.google.com/citations?user=fpE5HSsAAAAJ&hl=zh-CN&oi=sra), [Yiyi Zhou](https://scholar.google.com/citations?user=w3_2ep0AAAAJ&hl=zh-CN&oi=sra), **Jing He**, [Yunhang Shen](https://shenyunhang.github.io/), [Xiaoshuai Sun](https://sites.google.com/view/xssun), [Rongrong Ji](https://mac.xmu.edu.cn/rrji_en/) <sup>†</sup><br>
  ACM MM 2022 <br>
  [Paper](https://dl.acm.org/doi/abs/10.1145/3503161.3547818?casa_token=OdX7-mg1OF4AAAAA:cOHCfmEh1nnATLKHhtJxYPh-34cGyZ9l8_lm7m3y_WiDtZh7xSSGJIHOUpmXy-WECq0uV4u1oOdEJA) / [Github](https://github.com/pengjunn/PixelFace)
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ACM MM 2022</div>
      <img src='images/OpenfaceGAN.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **Towards open-ended text-to-face generation, combination and manipulation**

  [Jun Peng](), [Han Pan](), [Yiyi Zhou](https://scholar.google.com/citations?user=w3_2ep0AAAAJ&hl=zh-CN&oi=sra), **Jing He**, [Xiaoshuai Sun](https://sites.google.com/view/xssun), [Yan Wang](), [Yongjian Wu](), [Rongrong Ji](https://mac.xmu.edu.cn/rrji_en/) <sup>†</sup><br>
  ACM MM 2022 <br>
  [Paper](https://dl.acm.org/doi/abs/10.1145/3503161.3547758) / [Github](https://github.com/pengjunn/OpenFace)
  </div>
</div>

# 💻 Internships
- *2021.08 - 2022.01*, Tencent Youtu Lab, Shanghai, China. 
  
# 📚 Services
Reviewer: ICLR2025, AAAI2024


# 📖 Educations
- *2023.09 - present*, Ph.D. Student at AI Trust, The Hong Kong University of Science and Technology, GuangZhou. Advisor: [Ying-Cong Chen](https://www.yingcong.me/). 
- *2020.09 - 2023.06*, Master of Engineering in Artificial Intelligence at the School of Information, Xiamen University. Advisor: [Rongrong Ji](https://mac.xmu.edu.cn/rrji_en/). 
- *2016.09 - 2020.06*, Bachelor of Engineering in Digital Media Technology at the School of Computer Science and Technology, Wuhan Institute of Technology. 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->


# 🎖 Honors and Awards
- *2023-2025* Postgraduate Scholarship, HKUST-GZ. 
- *2020* Outstanding graduate student by WIT. 
- *2016-2020* First-Class Scholarship by WIT. 
