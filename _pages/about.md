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

Welcome to my homepage! My name is Shan Jia (贾姗). In Mandarin, my name coincidentally mirrors the pronunciation of "Fake Mountain." What's even more interesting is that my research is closely related to "fake things", including the identification and generation of fake images, videos, audio, and news😀.

I am currently a Research Scientist and Assistant Lab Director in the [Department of Computer Science and Engineering](https://engineering.buffalo.edu/computer-science-engineering/about-us.html) at the University at Buffalo (UB), State University of New York. I feel lucky to be a member of the [Media Forensic Lab](https://ubmdfl.cse.buffalo.edu/) led by Professor [Siwei Lyu](https://cse.buffalo.edu/~siweilyu/index.html). Before joining to UB, I was a visiting scholar in the [Lane Department of Computer Science and Electrical Engineering](https://lcsee.statler.wvu.edu/) at West Virginia University, working with Professor [Xin Li](https://xinli.faculty.wvu.edu/) and [Guodong Guo](https://directory.statler.wvu.edu/faculty-staff-directory/guodong-guo). In 2021, I finished my Ph.D. from Wuhan University, advised by Professor [Zhengquan Xu](https://www.researchgate.net/profile/Zhengquan-Xu).

**Research Interests**: Digital Media Forensics, Biometrics, and Computer Vision, etc.

# 🔈 News
* 2024.01: I was interviewed by [Futurum Careers, UK](https://futurumcareers.com/) together with Prof. Siwei Lyu ([link](https://futurumcareers.com/Issue-24.pdf)). 
* 2024.01: A paper on uncovering text-image inconsistency is accepted by ICLR 2024 ([link](https://openreview.net/pdf?id=Ny150AblPu)).
* 2023.11: I am invited to serve The 20th IEEE International Conference on Advanced Video and Signal-Based Surveillance (AVSS) 2024 as a Publication Chair.
* 2023.10: A paper on improving fairness in deepfake detection is accepted by WACV 2024 ([**Code**](https://github.com/littlejuyan/DF_Fairness), [news report by UBNow](https://www.buffalo.edu/ubnow/stories/2024/01/lyu-deepfake-bias.html)).
* 2023.09: A paper on audio-visual deepfake detection is accepted by MIT IEEE Undergraduate Research Technology Conference. Congratulations to Sneha Muppalla (a senior high school student)!
* 2023.08: A paper on street view imagery analysis is accepted by ISPRS Journal of Photogrammetry and Remote Sensing.
* 2023.08: I’m starting a new position as Assistant Lab Director at [UB Media Forensic Lab (UB MDFL)](https://ubmdfl.cse.buffalo.edu/)!😊
* 2023.08: A paper on image forgery detection is accepted by IEEE Transactions on Multimedia.
* 2023.04: Two papers are accepted by the CVPR2023 Workshop on Media Forensics (WMF). Our Autosplice dataset has been released ([link](https://github.com/shanface33/AutoSplice_Dataset))! 
* 2022.11: A paper on street view image inpainting is accepted by ISPRS Journal of Photogrammetry and Remote Sensing (Impact Factor: 12.7).
* 2022.06: Two papers on Media Forensics are accepted by ICIP 2022.
* 2022.01: A paper on Image-text De-contextualization Detection is accepted by ICASSP 2022.
* 2021.12: I gave a keynote speech on Deepfakes at [Open Media Forensics Challenge (OpenMFC) 2020-2021 Workshop](https://mfc.nist.gov/workshop).
* 2021.10: I joined [UC Berkeley InforCamp](https://infocamp.ischool.berkeley.edu/) Deepfake Panel as a speaker.
* 2021.06: I defended my Ph.D. dissertation on face spoofing detection and will join UB as a Post-Doctoral Researcher.
* 2020.12: I joined [2020 International Graduate Workshop on GeoInformatics](http://www.lmars.whu.edu.cn/Upload/1608014392.pdf), and won the Excellent Presentation Award (1/11).

# 📝 Publications
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMM23</div><img src='images/TMM_23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[GLFF: Global and Local Feature Fusion for AI-synthesized Image Detection]**

Yan Ju, <u>Shan Jia</u>, Jialing Cai, Haiying Guan, Siwei Lyu

IEEE Transactions on Multimedia, [**Paper**](https://ieeexplore.ieee.org/abstract/document/10246417), [**Code**](https://github.com/littlejuyan/GLFF)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WMF@CVPR23</div><img src='images/AutoS_23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[AutoSplice: A Text-prompt Manipulated Image Dataset for Media Forensics]**

<u>Shan Jia</u>, Mingzhen Huang, Zhou Zhou, Yan Ju, Jialing Cai, Siwei Lyu

Workshop on Media Forensics, CVPR2023, [**Paper**](https://openaccess.thecvf.com/content/CVPR2023W/WMF/papers/Jia_AutoSplice_A_Text-Prompt_Manipulated_Image_Dataset_for_Media_Forensics_CVPRW_2023_paper.pdf), [**Dataset**](https://github.com/shanface33/AutoSplice_Dataset)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISPRS-J23</div><img src='images/ISPRS_23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[UPDExplainer: an Interpretable Transformer-based Framework for Urban Physical Disorder Detection Using Street View Imagery]**

Chuanbo Hu, <u>Shan Jia*</u>, Fan Zhang, Changjiang Xiao, Mindi Ruan, Jacob Thrasher, and Xin Li

ISPRS Journal of Photogrammetry and Remote Sensing, [**Paper**](https://www.sciencedirect.com/science/article/abs/pii/S0924271622003021)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICIP22</div><img src='images/DFDM_21.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[Model Attribution of Face-swap Deepfake Videos]**

<u>Shan Jia</u>, Xin Li, Siwei Lyu

2022 IEEE International Conference on Image Processing, [**Paper**](https://arxiv.org/pdf/2202.12951.pdf), [**Code, Dataset**](https://github.com/shanface33/Deepfake_Model_Attribution)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISPRS-J22</div><img src='images/ISPRSJ_22.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[A Saliency-Guided Street View Image Inpainting Framework for Efficient Last-Meters Wayfinding]**

Chuanbo Hu, <u>Shan Jia*</u>, Fan Zhang, Xin Li

ISPRS Journal of Photogrammetry and Remote Sensing, [**PDF**](https://www.sciencedirect.com/science/article/abs/pii/S0924271623002320), [**Code**](https://github.com/shanface33/saliency_last_way_finding)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSVT20</div><img src='images/FBC_20.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[3D face anti-spoofing with factorized bilinear coding]**

<u>Shan Jia</u>, Xin Li, Chuanbo Hu, Guodong Guo, Zhengquan Xu

IEEE Transactions on Circuits and Systems for Video Technology, [**Paper**](https://arxiv.org/pdf/2005.06514.pdf), [**Dataset**](https://github.com/shanface33/Wax_Figure_Face_DB)

</div>
</div>

# 🏫 Education
- Oct. 2017 - Jun. 2021, Visiting Ph.D., Computer Science, [Department of Computer Science and Electrical Engineering, West Virginia University](https://lcsee.statler.wvu.edu/), USA
- Sep. 2014 - Jun. 2021, MD-PhD, Communication and Information Systems, [State Key Laboratory of Information Engineering in Surveying, Mapping, and Remote Sensing, Wuhan University](http://www.lmars.whu.edu.cn/en), China
- Sep. 2010 - Jun. 2014, Bachelor, Electrical Engineering, [Electronic Information School, Wuhan University](http://eis.whu.edu.cn/indexone.shtml), China (Recommended to be a graduate student exempt from an admission exam).

# 🖊 Services
- Conference Reviewer: *WACV, ICCV, CVPR, ECCV, ICME*
- Journal Reviewer: *IEEE TIFS, IEEE TMM, IEEE TIP, IEEE TCSVT, IJCV, IEEE TBIOM, PR, ACM TOG*


<div align="center">
</div>

<div align="center">
<script type="text/javascript" id="clustrmaps" src="//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=250&t=tt&d=DWq0xRlaIghROAgH6Lr8tmD_XQEZ-bbDoLfqLus2cPc"></script>
</div>
