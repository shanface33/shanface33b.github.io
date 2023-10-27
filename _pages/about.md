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

Welcome to my homepage! I am currently a Research Scientist and Assistant Lab Director in the [Department of Computer Science and Engineering](https://engineering.buffalo.edu/computer-science-engineering/about-us.html) at the University at Buffalo (UB), State University of New York. I feel lucky to be a member of the [Media Forensic Lab](https://ubmdfl.cse.buffalo.edu/) led by Professor [Siwei Lyu](https://cse.buffalo.edu/~siweilyu/index.html). Before joining to UB, I was a visiting scholar in the [Lane Department of Computer Science and Electrical Engineering](https://lcsee.statler.wvu.edu/) at West Virginia University, working with Professor [Xin Li](https://xinli.faculty.wvu.edu/) and [Guodong Guo](https://directory.statler.wvu.edu/faculty-staff-directory/guodong-guo). In 2021, I finished my Ph.D. from Wuhan University, advised by Professor [Zhengquan Xu](https://www.researchgate.net/profile/Zhengquan-Xu).

**Research Interests**: Digital Media Forensics, Deepfakes Detection, Biometrics, and Computer Vision, etc.


# 🔈 News
* Oct. 2023: A paper on [improving fairness in deepfake detection](https://arxiv.org/pdf/2306.16635.pdf) is accepted by [WACV 2024](https://wacv2024.thecvf.com/) ([**Code**](https://github.com/littlejuyan/DF_Fairness)).
* Sep. 2023: A paper on [audio-visual deepfake detection](https://arxiv.org/pdf/2310.03827.pdf) is accepted by [MIT IEEE Undergraduate Research Technology Conference](https://urtc.mit.edu/). Congratulations to Sneha Muppalla (a senior high school student)!
* Aug. 2023: A paper on [street view imagery analysis](https://arxiv.org/pdf/2305.02911.pdf) is accepted by [ISPRS Journal of Photogrammetry and Remote Sensing](https://www.sciencedirect.com/journal/isprs-journal-of-photogrammetry-and-remote-sensing).
* Aug. 2023: I’m starting a new position as Assistant Lab Director at [UB Media Forensic Lab (UB MDFL)](https://ubmdfl.cse.buffalo.edu/)!😊
* Aug. 2023: A paper on [image forgery detection](https://arxiv.org/pdf/2211.08615.pdf) is accepted by IEEE Transactions on Multimedia.
* Apr. 2023: Two papers on Media Forensics are accepted by the CVPR2023 Workshop on Media Forensics (WMF). Our [Autosplice dataset](https://openaccess.thecvf.com/content/CVPR2023W/WMF/papers/Jia_AutoSplice_A_Text-Prompt_Manipulated_Image_Dataset_for_Media_Forensics_CVPRW_2023_paper.pdf) has been released ([link](https://github.com/shanface33/AutoSplice_Dataset))! 
* Nov. 2022: A paper on [street view image inpainting](https://www.sciencedirect.com/science/article/pii/S0924271622003021?dgcid=author) is accepted by [ISPRS Journal of Photogrammetry and Remote Sensing](https://www.sciencedirect.com/journal/isprs-journal-of-photogrammetry-and-remote-sensing) (Impact Factor: 12.7).
* Jun. 2022: Two papers on Media Forensics (i.e., [Deepfakes Model Attribution](https://ieeexplore.ieee.org/document/9897972) and [AI-synthesized Image Detection](https://ieeexplore.ieee.org/document/9897820)) are accepted by [ICIP 2022](https://cmsworkshops.com/ICIP2022/view_session.php?SessionID=1074).
* Jan. 2022: A paper on [Image-text De-contextualization Detection](https://ieeexplore.ieee.org/document/9746193) is accepted by ICASSP 2022.
* Dec. 2021: I gave a keynote speech on Deepfakes at [Open Media Forensics Challenge (OpenMFC) 2020-2021 Workshop](https://mfc.nist.gov/workshop).
* Oct. 2021: I joined [UC Berkeley InforCamp](https://infocamp.ischool.berkeley.edu/) Deepfake Panel as a speaker.
* Jun. 2021: I defended my Ph.D. dissertation on face spoofing detection and will join UB as a Post-Doctoral Researcher.
* Dec. 2020: I joined [2020 International Graduate Workshop on GeoInformatics](http://www.lmars.whu.edu.cn/Upload/1608014392.pdf), and won the Excellent Presentation Award (1/11).

# 📝Selected Publications
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMM23</div><img src='images/TMM_23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[GLFF: Global and Local Feature Fusion for AI-synthesized Image Detection]**

Yan Ju, <u>Shan Jia</u>, Jialing Cai, Haiying Guan, Siwei Lyu, [**Paper**](https://ieeexplore.ieee.org/abstract/document/10246417), [**Code**](https://github.com/littlejuyan/GLFF)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WMF@CVPR23</div><img src='images/AutoS_23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[AutoSplice: A Text-prompt Manipulated Image Dataset for Media Forensics]**

<u>Shan Jia</u>, Mingzhen Huang, Zhou Zhou, Yan Ju, Jialing Cai, Siwei Lyu, [**Paper**](https://openaccess.thecvf.com/content/CVPR2023W/WMF/papers/Jia_AutoSplice_A_Text-Prompt_Manipulated_Image_Dataset_for_Media_Forensics_CVPRW_2023_paper.pdf), [**Dataset**](https://github.com/shanface33/AutoSplice_Dataset)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISPRS-J23</div><img src='images/ISPRS_23.png' alt="sym" width="50%"></div></div>
<div class='paper-box-text' markdown="1">

**[UPDExplainer: an Interpretable Transformer-based Framework for Urban Physical Disorder Detection Using Street View Imagery]**

Chuanbo Hu, <u>Shan Jia*</u>, Fan Zhang, *et al.*, [**Paper**](https://www.sciencedirect.com/science/article/abs/pii/S0924271622003021)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISPRS-J22</div><img src='images/ISPRSJ_22.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[A Saliency-Guided Street View Image Inpainting Framework for Efficient Last-Meters Wayfinding]**

Chuanbo Hu, <u>Shan Jia*</u>, Fan Zhang, Xin Li, [**PDF**](https://www.sciencedirect.com/science/article/abs/pii/S0924271623002320), [**Code**](https://github.com/shanface33/saliency_last_way_finding)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICIP22</div><img src='images/DFDM_21.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[Model Attribution of Face-swap Deepfake Videos]**

<u>Shan Jia</u>, Xin Li, Siwei Lyu, [**Paper**](https://arxiv.org/pdf/2202.12951.pdf), [**Code & Dataset**](https://github.com/shanface33/Deepfake_Model_Attribution)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSVT20</div><img src='images/FBC_20.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[3D face anti-spoofing with factorized bilinear coding]**

<u>Shan Jia</u>, Xin Li, *et al.*, [**Paper**](https://arxiv.org/pdf/2005.06514.pdf), [**Dataset**](https://github.com/shanface33/Wax_Figure_Face_DB)

</div>
</div>

# 🖊 Services
- Conference Reviewer: *CVPR 22, WACV 24, ICCV 23, ECCV 22*
- Journal Reviewer: *IEEE TIFS, IEEE TMM, IEEE TIP, IEEE TCSVT*
