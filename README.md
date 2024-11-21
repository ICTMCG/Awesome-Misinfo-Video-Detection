# Awesome-Misinfo-Video-Detection

## Contents

- [Paper List for Misinformation Video Detection](#paper-list-for-misinfomation-video-detection)
  - [Contents](#contents)
  - [Introduction](#introduction)
    - [Keywords Convention](#keywords-convention)
  - [Papers](#papers)
    - [Related Survey](#related-survey)
    - [Analysis](#analysis)
    - [Detection at Signal Level](#detection-at-signal-level)
    - [Detection at Semantic and Intent Level](#detection-at-semantic-and-intent-level)
    - [Related Areas](#related-areas)
    - [Future Directions](#future-directions)
  - [Resources](#resources)
    - [Datasets](#datasets)
    - [Tools](#tools)
  - [Citation](#citation)


## Introduction

This is a paper list (working in progress) about **Misinformation Video Detection**

### Keywords Convention


![](https://img.shields.io/badge/transferability-EAD8D9) section in our survey

![](https://img.shields.io/badge/textual-D8D0E1) main feature


## Papers

### Related Survey
1. **The Challenges of Studying Misinformation on Video-Sharing Platforms During Crises and Mass-Convergence Events**. ![](https://img.shields.io/badge/misinformation_video-D8D0E1)

   *Sukrit Venkatagiri, Joseph S. Schafer, Stephen Prochaska*. CHI 2023 Workshop on Building Credibility, Trust, and Safety on VideoSharing Platforms, April 23–28, 2023, Hamburg, Germany.[[pdf](https://arxiv.org/pdf/2303.14309.pdf)]


1. **Multi-modal Misinformation Detection: Approaches, Challenges and Opportunities**. ![](https://img.shields.io/badge/multimodal_detection-D8D0E1)

   *Sara Abdali*. arXiv preprint arXiv:2203.13883 (2022).  [[pdf](https://arxiv.org/pdf/2203.13883.pdf)] 
2. **A Survey on Multimodal Disinformation Detection**. ![](https://img.shields.io/badge/multimodal_detection-D8D0E1)

   *Firoj Alam, Stefano Cresci, Tanmoy Chakraborty, Fabrizio Silvestri, Dimitar Dimitrov, Giovanni Da San Martino, Shaden Shaar, Hamed Firooz, Preslav Nakov*.  arXiv preprint arXiv:2103.12541 (2021) [[pdf](https://arxiv.org/pdf/2103.12541.pdf)] 
3. **Exploring the role of visual content in fake news detection**. ![](https://img.shields.io/badge/multimodal_detection-D8D0E1)

   *Juan Cao, Peng Qi, Qiang Sheng, Tianyun Yang, Junbo Guo, Jintao Li*. Disinformation, Misinformation, and Fake News in Social Media: Emerging Research Challenges and Opportunities (2020): 141-161.  [[pdf](https://arxiv.org/pdf/2003.05096.pdf)] 
4. **A Survey on Video-Based Fake News Detection Techniques**. ![](https://img.shields.io/badge/video_forgery_detection-D8D0E1)

   *Ronak Agrawal, Dilip Kumar Sharma*. 2021 8th International Conference on Computing for Sustainable Global Development (INDIACom). IEEE, 2021.  [[pdf](https://ieeexplore.ieee.org/abstract/document/9441196)]

5. **A comprehensive survey on passive techniques for digital video forgery detection**. ![](https://img.shields.io/badge/video_forgery_detection-D8D0E1)

   *Nitin Arvind Shelke, Singara Singh Kasana*. Multimed Tools Appl 80, 6247–6310 (2021) [[pdf](https://link.springer.com/article/10.1007/s11042-020-09974-4)]

5. **Fighting Malicious Media Data: A Survey on
Tampering Detection and Deepfake Detection**. ![](https://img.shields.io/badge/media_forensic-D8D0E1) 

    *Junke Wang, Zhenxin Li, Chao Zhang, Jingjing Chen, Zuxuan Wu, Larry S. Davis, Yu-Gang Jiang*. ArXiv, 2022. [[pdf](https://arxiv.org/pdf/2212.05667.pdf)]
5. **A Survey of Fake News: Fundamental Theories, Detection Methods, and Opportunities**. ![](https://img.shields.io/badge/fake_news_detection-D8D0E1)

   *Xinyi Zhou, Reza Zafarani*. ACM Computing Surveys (CSUR) 53.5 (2020): 1-40. [[pdf](https://arxiv.org/pdf/1812.00315)]
6. **Fake news detection on social media: A data mining perspective**. ![](https://img.shields.io/badge/fake_news_detection-D8D0E1)

   *Kai Shu,Amy Sliva,Suhang Wang,Jiliang Tang,Huan Liu*.  ACM SIGKDD Explorations Newsletter,Volume 19,Issue 1,June 2017, pp 22–36. [[pdf](https://arxiv.org/pdf/1708.01967)]

### Analysis

This section contains the pilot works that analyze misinformation video on online platform, including the impact of video modality and the propagation feature on recommendation-dominated plaforms.
1. **[PACMHCI-2020] Measuring Misinformation in Video Search Platforms: An Audit Study on YouTube**. 

   *Eslam Hussein,  Prerna Juneja, Tanushree Mitra*. [[pdf](https://www.researchgate.net/profile/Eslam-Hussein-12/publication/340681643_Measuring_Misinformation_in_Video_Search_Platforms_An_Audit_Study_on_YouTube/links/5e98be72a6fdcca7891ff9b5/Measuring-Misinformation-in-Video-Search-Platforms-An-Audit-Study-on-YouTube.pdf)]
   - This audit experiments investigate whether personalization (based on age, gender, geolocation, or watch history) contributes to amplifying misinformation.

2. **[PNAS-2021] The (minimal) persuasive advantage of political video over text**.

   *Chloe Wittenberg, Ben M. Tappin, Adam J. Berinsky, David G. Rand*. [[pdf](https://www.pnas.org/doi/full/10.1073/pnas.2114388118)]
   - This paper tests the assumption that video is more compelling than text.

3. **[JCMC-2021] Seeing is believing: Is video modality more powerful in spreading fake news via online messaging apps?** 

   *S. Shyam Sundar, Maria D. Molina , Eugene Cho*. [[pdf](https://academic.oup.com/jcmc/article-pdf/26/6/301/41139661/zmab010.pdf)]
   -  This works finds that video is processed more superficially, and therefore users believe in it more readily and share it with others.
4. **[TORS-2022] Auditing YouTube's Recommendation Algorithm for Misinformation Filter Bubbles**.

   *Ivan Srba, Robert Moro, Matus Tomlein, Branislav Pecher, Jakub Simko, Elena Stefancova, Michal Kompan, Andrea Hrckova, Juraj Podrouzek, Adrian Gavornik, Maria Bielikova*. [[pdf](https://dl.acm.org/doi/pdf/10.1145/3568392)]
   - This paper presents results of an auditing study performed over YouTube aimed at investigating how fast a user can get into a misinformation filter bubble, but also what it takes to “burst the bubble”.
5. **[IJCAI-2022] Black-box Audit of YouTube's Video Recommendation: Investigation of Misinformation Filter Bubble Dynamics (Extended Abstract)**.

   *Matus Tomlein, Branislav Pecher, Jakub Simko, Ivan Srba, Robert Moro, Elena Stefancova, Michal Kompan, Andrea Hrckova, Juraj Podrouzek, Maria Bielikova*. [[pdf](https://www.ijcai.org/proceedings/2022/0749.pdf)]
   - This paper describes a black-box sockpuppeting audit which was carried out to investigate the creation and bursting dynamics of misinformation flter bubbles on YouTube.

### Detection at Signal Level

This section contains the pilot works that detect misinformation video at signal level, i.e., detect with the clues of editing traces or generating traces.
1.  **[MS-2023] Fake COVID-19 videos detector based on frames and audio watermarking**. ![](https://img.shields.io/badge/editing_traces-EAD8D9) ![](https://img.shields.io/badge/watermarking-D8D0E1)

    *Nesrine Tarhouni ,Salma Masmoudi, Maha Charfeddine, Chokri Ben Amar*.  [[pdf](https://link.springer.com/article/10.1007/s00530-022-01006-5)]
    - This paper presents a fake video detector based on combining audio and frames watermarking which makes possible the detection of modifications in the two video channels and assures a fast detection of fake video.

2. **[arXiv-2022] VideoFACT: Detecting Video Forgeries Using Attention, Scene Context, and Forensic Traces**. ![](https://img.shields.io/badge/editing_traces-EAD8D9) ![](https://img.shields.io/badge/video-D8D0E1)

   *Tai D. Nguyen, Shengbang Fang, Matthew C. Stamm*. [[pdf](https://arxiv.org/pdf/2211.15775.pdf)]
   - This paper designs VideoFACT to exploit forensic traces’ contextual dependencies upon scene content as well as spatial dependencies and proposes datasets that are composed not only of standard video manipulations but also advanced AI-based content manipilation techniques.

3. **[MMM-2019] Detecting tampered videos with multimedia forensics and deep learning**. ![](https://img.shields.io/badge/editing_traces-EAD8D9) ![](https://img.shields.io/badge/video-D8D0E1)

   *Markos Zampoglou, Foteini Markatopoulou, Gregoire Mercier, Despoina Touska, Evlampios Apostolidis, Symeon Papadopoulos, Roger Cozien, Ioannis Patras, Vasileios Mezaris, Ioannis Kompatsiaris*. [[pdf](https://qmro.qmul.ac.uk/xmlui/bitstream/handle/123456789/55029/Apostolidis%20Detecting%20Tampered%20Videos%202018%20Accepted.pdf?sequence=2)]

4. **[MTA-2017] Malicious inter-frame video tampering detection in MPEG videos using time and spatial domain analysis of quantization effects**. ![](https://img.shields.io/badge/editing_traces-EAD8D9) ![](https://img.shields.io/badge/video-D8D0E1)

   *Javad Abbasi Aghamaleki, Alireza Behrad*. [[pdf](https://link.springer.com/article/10.1007/s11042-016-4004-z)]

5. **[JFS-2018] Authentication of surveillance videos: detecting frame duplication based on residual frame**. ![](https://img.shields.io/badge/editing_traces-EAD8D9) ![](https://img.shields.io/badge/video-D8D0E1)

   *Sondos M. Fadl, Qi Han, Qiong Li*. [[pdf](https://onlinelibrary.wiley.com/doi/abs/10.1111/1556-4029.13658)]

6. **[CSPA-2017] A comprehensive approach for exposing inter-frame video forgeries**. ![](https://img.shields.io/badge/editing_traces-EAD8D9) ![](https://img.shields.io/badge/video-D8D0E1)

   *K Sitara, B M Mehtre*. [[pdf](https://ieeexplore.ieee.org/abstract/document/8064927)]

7. **[SCAIE-2018] Detection clone an object movement using an optical flow approach**. ![](https://img.shields.io/badge/editing_traces-EAD8D9) ![](https://img.shields.io/badge/video-D8D0E1)

   *Omar Ismael Al-Sanjary, Ahmed Abdullah Ahmed, Adam Amril Bin Jaharadak, Musab AM Ali, and Hewa Majeed Zanga*. [[pdf](https://www.researchgate.net/profile/Ahmed-Ahmed-24/publication/326276548_Detection_clone_an_object_movement_using_an_optical_flow_approach/links/5c2c9612458515a4c706a871/Detection-clone-an-object-movement-using-an-optical-flow-approach.pdf)]

8. **[ICIEAM-2016] Implementation of image/video copy-move forgery detection using brute-force matching**. ![](https://img.shields.io/badge/editing_traces-EAD8D9) ![](https://img.shields.io/badge/video-D8D0E1)

   *Neema Antony, Binet Rose Devassy*. [[pdf](https://ieeexplore.ieee.org/abstract/document/8553953/)]

9. **[NCA-2020] Video tampering localisation using features learned from authentic content**. ![](https://img.shields.io/badge/editing_traces-EAD8D9) ![](https://img.shields.io/badge/video-D8D0E1)

   *Pamela Johnston, Eyad Elyan, Chrisina Jayne*. [[pdf](https://link.springer.com/article/10.1007/s00521-019-04272-z)]

10. **[AECE-2019] Spatial video forgery detection and localization using texture analysis of consecutive frames**. ![](https://img.shields.io/badge/editing_traces-EAD8D9) ![](https://img.shields.io/badge/video-D8D0E1)

      *Mubbashar Saddique, Khurshid Asghar, Usama Ijaz Bajwa, Muhammad Hussain,Zulfiqar Habib*. [[pdf](https://www.academia.edu/download/61003489/aece_2019_3_1220191024-40459-1p66trc.pdf)]

3. **[TIFS-2016] ESPRIT-Hilbert-based audio tampering detection with SVM classifier for forensic analysis via electrical network frequency** . ![](https://img.shields.io/badge/editing_traces-EAD8D9) ![](https://img.shields.io/badge/audio-D8D0E1)

   *Reis, Paulo Max Gil Innocencio , da Costa, Joao Paulo Carvalho Lustosa , Miranda, Ricardo Kehrle , Del Galdo, Giovanni*. [[pdf](https://ieeexplore.ieee.org/abstract/document/7775065/)]
   - In this paper, a new technique to detect adulterations in audio recordings is proposed by exploiting abnormal variations in the electrical network frequency (ENF) signal eventually embedded in a questioned audio recording.

4. **[CSUR-2021] The creation and detection of deepfakes: A survey**. ![](https://img.shields.io/badge/generating_traces-EAD8D9) ![](https://img.shields.io/badge/video-D8D0E1)

   *Yisroel Mirsky, Wenke Lee*. [[pdf](https://arxiv.org/pdf/2004.11138)]
5. **[FCST-2023] Overview of Facial Deepfake Video Detection Methods**. ![](https://img.shields.io/badge/generating_traces-EAD8D9) ![](https://img.shields.io/badge/video-D8D0E1)
   
   *Zhang lu, Lu Tianliang, Du Yanhui.* [[pdf](http://fcst.ceaj.org/EN/article/downloadArticleFile.do?attachType=PDF&id=3208)]
6. **[DDAM-2022] Lessons Learned from ASVSpoof and Remaining Challenges**. ![](https://img.shields.io/badge/generating_traces-EAD8D9) ![](https://img.shields.io/badge/audio-D8D0E1)

   *Junichi Yamagishi*. [[pdf](https://dl.acm.org/doi/abs/10.1145/3552466.3554359)]
7. **[ICASSP-2022] Fake audio detection based on unsupervised pretraining models**. ![](https://img.shields.io/badge/generating_traces-EAD8D9) ![](https://img.shields.io/badge/audio-D8D0E1)

   *Zhiqiang Lv, Shanshan Zhang,Kai Tang, Pengfei Hu*.  [[pdf](https://ieeexplore.ieee.org/abstract/document/9747605/)]
   - This work presents the authors' systems for the ADD2022 challenge, which is the first audio deep synthesis detection challenge. They explored using unsupervised pretraining models to build fake audio detection systems.
8. **[ICCV-2021] Joint audio-visual deepfake detection**. ![](https://img.shields.io/badge/generating_traces-EAD8D9) ![](https://img.shields.io/badge/audiovisual-D8D0E1)

   *Yipin Zhou, Ser-Nam Lim*.  [[pdf](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhou_Joint_Audio-Visual_Deepfake_Detection_ICCV_2021_paper.pdf)]
   - This work proposes a novel visual / auditory deepfake joint detection task and show that exploiting the intrinsic synchronization between the visual and auditory modalities could benefit deepfake detection.

9. **[MM-2020] Emotions don't lie: An audio-visual deepfake detection method using affective cues**. ![](https://img.shields.io/badge/generating_traces-EAD8D9) ![](https://img.shields.io/badge/audiovisual-D8D0E1)

   *Trisha Mittal, Uttaran Bhattacharya, Rohan Chandra, Aniket Bera, Dinesh Manocha*. [[pdf](https://arxiv.org/pdf/2003.06711)]

9. **[TCSVT-2021] Detecting compressed deepfake videos in social networks using frame-temporality two-stream convolutional network**. ![](https://img.shields.io/badge/generating_traces-EAD8D9) ![](https://img.shields.io/badge/compressed_video-D8D0E1)

   *Juan Hu ,XinLiao ,WeiWang, ZhengQin*.  [[pdf](https://ieeexplore.ieee.org/abstract/document/9408664)]
   - The work propose a two-stream method by analyzing the frame-level and temporality-level of compressed Deepfake videos. The frame-level stream can prune the redundant connections to prevent the invalid connections from affecting the final prediction.  The temporality-level stream is utilized to capture temporal features to detect the temporal consistency.

10. **[arXiv-2023] Anti-Compression Contrastive Facial Forgery Detection**. ![](https://img.shields.io/badge/generating_traces-EAD8D9) ![](https://img.shields.io/badge/compressed_video-D8D0E1)

    *Jiajun Huang, Xinqi Zhu, Chengbin Du, Siqi Ma, Surya Nepal, Chang Xu*. [[pdf](https://arxiv.org/pdf/2302.06183.pdf)]
    - The authors propose a novel anti-compression forgery detection framework by maintaining closer relations within data under different compression levels.


### Detection at Semantic and Intent Level

This section contains the pilot works that utilize multimodal features to detect misinformation video at Semantic/Intent Level.

1. **[MFSec-2017] Web Video Verification using Contextual Cues**.  ![](https://img.shields.io/badge/textual-D8D0E1) ![](https://img.shields.io/badge/social_context-D8D0E1)

   *Olga Papadopoulou, Markos Zampoglou, Symeon Papadopoulos, Yiannis Kompatsiaris*.  [[pdf](https://core.ac.uk/download/pdf/144811239.pdf)] [[repo](https://github.com/MKLab-ITI/contextual-video-verification/tree/master/MFSec_2017)]

   - Propose an annotated dataset of real and fake videos(FVC)
   - Use video comment credibility and video metadata features for fake video detection.
2. **[ICMI-2019] Towards Automatic Detection of Misinformation in Online Medical Videos**. ![](https://img.shields.io/badge/textual-D8D0E1) ![](https://img.shields.io/badge/acoustic-D8D0E1) ![](https://img.shields.io/badge/social_context-D8D0E1)

   *Rui Hou, Verónica Pérez-Rosas, Stacy Loeb, Rada Mihalcea*.  [[pdf](https://arxiv.org/pdf/1909.01543)] 
   - Explore the use of linguistic, acoustic, and user engagement features to identify misinformation.

3. **[ECIR-2019] Misleading Metadata Detection on YouTube**. ![](https://img.shields.io/badge/social_context-D8D0E1) ![](https://img.shields.io/badge/textual-D8D0E1)

   *Priyank Palod, Ayush Patwari, Sudhanshu Bahety, Saurabh Bagchi, Pawan Goyal*.  [[pdf](https://arxiv.org/pdf/1901.08759.pdf)] [[repo](https://github.com/ucnet01/UCNet_Implementation)]
   - The work presents VAVD, a new dataset for research on fake videos.
   - Propose UCNet , a deep learning based approach using comments and simple features extracted from title and social context to identify fake videos.

4. **[ACL Workshop-2020] NLP-based Feature Extraction for the Detection of COVID-19 Misinformation Videos on YouTube**. ![](https://img.shields.io/badge/social_context-D8D0E1) ![](https://img.shields.io/badge/textual-D8D0E1)

   *Juan Carlos Medina Serrano, Orestis Papakyriakopoulos, Simon Hegelich*.  [[pdf](https://aclanthology.org/2020.nlpcovid19-acl.17.pdf)] [[repo](https://github.com/JuanCarlosCSE/YouTube_misinfo)]
   - Create a multi-label classifier based on transfer-learning that can categorize conspiratorial content; use the percentage of conspiracy comments and the first hundred comments as tf-idf features in the classifier.

5. **[arXiv-2021] Misinformation Detection on YouTube Using Video Captions**. ![](https://img.shields.io/badge/textual-D8D0E1)

   *Raj Jagtap, Abhinav Kumar, Rahul Goel, Shakshi Sharma, Rajesh Sharma, Clint P. George*.  [[pdf](https://arxiv.org/pdf/2107.00941.pdf)] [[repo](https://github.com/jagtapraj123/YT-Misinformation)]
   -  This work  exploited the YouTube captions to understand the content of the videos using multiple pre-trained word embeddings.

6. **[Scientific Reports-2022] A CNN-based Misleading Video Detection Model**. ![](https://img.shields.io/badge/social_context-D8D0E1) ![](https://img.shields.io/badge/textual-D8D0E1)

   *Xiaojun Li, Xvhao Xiao, Jia Li, Changhua Hu, JunpingYao , Shaochen Li*.  [[pdf](https://www.nature.com/articles/s41598-022-10117-y)] 
   -  In this paper, three categories of features (content features, uploader features and environment features) are proposed to construct a convolutional neural network (CNN) for misleading video detection.

7. **[CIKM-2021] Using Topic Modeling and Adversarial Neural Networks for Fake News Video Detection**.  ![](https://img.shields.io/badge/visual-D8D0E1) ![](https://img.shields.io/badge/textual-D8D0E1) ![](https://img.shields.io/badge/social_context-D8D0E1)

   *Hyewon Choi, Youngjoong Ko*.  [[pdf](https://dl.acm.org/doi/abs/10.1145/3459637.3482212)]
   - The work proposes a topic agnostic fake news video detection model based on adversarial learning and topic modeling. The stance difference estimation (using Gibbs sampling-based LDA) between title/description and comments on topic modeling was used to dynamically adjust the encoding ratio of the comments.


8. **[PRL-2022] Effective fake news video detection using domain knowledge and multimodal data fusion on youtube**.  ![](https://img.shields.io/badge/visual-D8D0E1) ![](https://img.shields.io/badge/textual-D8D0E1) ![](https://img.shields.io/badge/social_context-D8D0E1)

   *Hyewon Choi, Youngjoong Ko*.  [[pdf](https://www.sciencedirect.com/science/article/abs/pii/S0167865522000071)]
   - The framework is Similar to 6-[CIKM-2021], but remove the adversarial learning and topic modeling.This paper use domain knowledge to perform learning by reflecting the potential meaning of comments and use the linear combination to adjust the encoding rate for each characteristic of the video.

9. **[BigData-2021] A Multimodal Misinformation Detector for COVID-19 Short Videos on TikTok**. ![](https://img.shields.io/badge/visual-D8D0E1) ![](https://img.shields.io/badge/textual-D8D0E1) ![](https://img.shields.io/badge/acoustic-D8D0E1)

   *Lanyu Shang, Ziyi Kou, Yang Zhang, Dong Wang*.  [[pdf](https://ieeexplore.ieee.org/abstract/document/9671928/)]

   -  The work develops TikTec, a multimodal misinformation detection framework that explicitly exploits the captions extracted from the audio track and the visual frame to accurately capture the key information from the distractive video content, and effectively learns the composed misinformation that is jointly conveyed by the visual and audio content.

10. **[MMM-2022] Multi-modal semantic inconsistency detection in social media news posts**. ![](https://img.shields.io/badge/visual-D8D0E1) ![](https://img.shields.io/badge/textual-D8D0E1) ![](https://img.shields.io/badge/crossmodal_correlation-D8D0E1)
    
    *Scott McCrae, Kehan Wang, Avideh Zakhor*.  [[pdf](https://arxiv.org/pdf/2105.12855.pdf)]
    - The work develops a multi-modal fusion framework to identify mismatches between videos and captions in social media posts by leveraging an ensemble method based on textual analysis of the caption, automatic audio transcription, semantic video analysis, object detection, named entity consistency, and facial verification.

11. **[arXiv-2022] Misinformation Detection in Social Media Video Posts**.  ![](https://img.shields.io/badge/visual-D8D0E1) ![](https://img.shields.io/badge/textual-D8D0E1) ![](https://img.shields.io/badge/crossmodal_correlation-D8D0E1)

    *Kehan Wang, David Chan, Seth Z. Zhao, John Canny, Avideh Zakhor*.  [[pdf](https://arxiv.org/abs/2202.07706)]
    - This work proposes two new methods for detecting semantic inconsistencies within short-form social media video posts, based on contrastive learning and masked language modeling.

12. **[MMSP Workshop-2022] Multimodal Semantic Mismatch Detection in Social Media Posts**. ![](https://img.shields.io/badge/visual-D8D0E1) ![](https://img.shields.io/badge/textual-D8D0E1) ![](https://img.shields.io/badge/crossmodal_correlation-D8D0E1)
    
    *Kehan Wang, Seth Z. Zhao, David Chan, Avideh Zakhor, John Canny*.  [[pdf](http://www-video.eecs.berkeley.edu/papers/kwang-2/MMSP-Final-2022186318.pdf)]
    - This work uses language, video and audio models to extract dense features from each modality, and explore transformer architecture together with contrastive learning methods.

13. **[AAAI-2023] FakeSV: A Multimodal Benchmark with Rich Social Context for Fake News Detection on Short Video Platforms** ![](https://img.shields.io/badge/visual-D8D0E1) ![](https://img.shields.io/badge/textual-D8D0E1) ![](https://img.shields.io/badge/acoustic-D8D0E1) ![](https://img.shields.io/badge/social_context-D8D0E1)
    
    *Peng Qi, Yuyan Bu, Juan Cao, Wei Ji, Ruihao Shui,Junbin Xiao, Danding Wang, Tat-Seng Chua*.  [[pdf](https://arxiv.org/pdf/2211.10973.pdf)] [[repo](https://github.com/ICTMCG/FakeSV)]
    - This paper proposes the largest Chinese short video dataset about fake news named FakeSV and provides a new multimodal baseline method SV-FEND.

14. **[EACL-2023] COVID-VTS: Fact Extraction and Verification on Short Video Platforms**. ![](https://img.shields.io/badge/visual-D8D0E1) ![](https://img.shields.io/badge/textual-D8D0E1)
   
    *Fuxiao Liu, Yaser Yacoob, Abhinav Shrivastava*. [[pdf](https://arxiv.org/pdf/2302.07919.pdf)] [[repo](https://github.com/FuxiaoLiu/Twitter-Video-dataset)]
    - This work introduces a new benchmark, COVIDs-VTS, for fact-checking multi-modal information, as well as proposes TwtrDetective, an effective model incorporating cross-media consistency checking to detect token-level malicious tampering in different modalities, and generate explanations.

15. **[ChineseCSCW-2022] Video Rumor Classification Based on Multi-modal Theme and Keyframe Fusion**. ![](https://img.shields.io/badge/visual-D8D0E1) ![](https://img.shields.io/badge/textual-D8D0E1) ![](https://img.shields.io/badge/acoustic-D8D0E1) 

    *Jinpeng You, Yanghao Lin, Dazhen Lin, and Donglin Cao*. [[pdf](https://link.springer.com/chapter/10.1007/978-981-99-2356-4_5)]
    - This work propose a multi-modal fusion model based on theme and keyframe. It can effectively capture the theme and key-frame information of the three modalities in the video, and carry out rumor detection from them.

16. **[ACL-2023] Improving Fake News Video Detection by Correlating with Neighbors**. ![](https://img.shields.io/badge/visual-D8D0E1) ![](https://img.shields.io/badge/textual-D8D0E1) ![](https://img.shields.io/badge/acoustic-D8D0E1)

    *Peng Qi, Yuyang Zhao, Yufeng Shen,Wei Ji, Juan Cao, and Tat-Seng Chua*. [[pdf](https://arxiv.org/pdf/2306.05241.pdf)] [[repo](https://github.com/ICTMCG/NEED)]
    - This work propose the NEED framework, which exploits the neighborhood relationship explicitly and implicitly to enhance the fake news video detection. The authors also formulate a new multimodal inference task and propose a novel model that utilizes the consistency to leverage factual information to rectify false negative predictions.

17. **[arXiv-2023] Multimodal Short Video Rumor Detection System Based on Contrastive Learning**. ![](https://img.shields.io/badge/visual-D8D0E1) ![](https://img.shields.io/badge/textual-D8D0E1) ![](https://img.shields.io/badge/acoustic-D8D0E1)
    
    *Yuxing Yang, Junhao Zhao, Siyi Wang, Xiangyu Min, Pengchao Wang, and Haizhou Wang*. [[pdf](https://arxiv.org/pdf/2304.08401.pdf)] 
    - This paper proposes a framework for detecting and classifying short video rumors based on multimodal feature fusion: the authors use the TSN (Temporal Segment Networks) to extract video visual features; then OCR and ASR technologies are exploited to extract text features; BERT model is utilized to fuse text and video visual features. Contrastive learning is applied for the final prediction.

18. **[arXiv-2023] Identifying Misinformation on YouTube through Transcript Contextual Analysis with Transformer Models**. ![](https://img.shields.io/badge/textual-D8D0E1) 
    
    *Christos Christodoulou, Nikos Salamanos, Pantelitsa Leonidou, Michail Papadakis, Michael Sirivianos*. [[pdf](https://arxiv.org/pdf/2307.12155.pdf)] [[repo](https://github.com/christoschr97/misinf-detection-llms)] 
    - This paper converts the conventional vide classification task into a text classification task by leveraging the textual content derived from the video transcripts and presents a methodology for detecting misinformation on YouTube using different fine-tuned transformer models and few-shot learning.

19. **[EMNLP-2023] Not all Fake News is Written: A Dataset and Analysis of Misleading Video Headlines**. ![](https://img.shields.io/badge/textual-D8D0E1) 

    *Yoo Yeon Sung, Jordan Boyd-Graber, Naeemul Hassan*. [[pdf](https://arxiv.org/pdf/2310.13859.pdf)] [[repo](https://github.com/yysung/VMH/tree/master)]
    - This paper presents VMH, a dataset of misleading headlines from social media videos and analyze multimodal baselines for detecting misleading headlines.

20. **[MTA-2023] Emotion aided multi-task framework for video embedded misinformation detection**. ![](https://img.shields.io/badge/visual-D8D0E1) ![](https://img.shields.io/badge/textual-D8D0E1) ![](https://img.shields.io/badge/acoustic-D8D0E1)
    
    *Rina Kumari, Vipin Gupta, Nischal Ashok, Tirthankar Ghosal, Asif Ekbal*. [[pdf](https://link.springer.com/article/10.1007/s11042-023-17208-6)]
    - This paper develops a video-based multimodal fake news detection dataset named FakeClips and introduces a deep multitask framework dedicated to video-embedded multimodal fake news detection in which fake news detection is the main task and emotion recognition is the auxiliary task.

21. **[ArXiv-2024] FakeClaim: A Multiple Platform-driven Dataset for Identification of Fake News on 2023 Israel-Hamas War**.  ![](https://img.shields.io/badge/textual-D8D0E1)

    *Gautam Kishore Shahi, Amit Kumar Jaiswal, Thomas Mandl*. [[pdf](https://arxiv.org/pdf/2401.16625.pdf)] [[repo](https://github.com/Gautamshahi/FakeClaim)]
    - This paper constructs a dataset of factual claims from different platforms and fake YouTube videos on the 2023 Israel-Hamas war for automatic fake YouTube video classification. A fine-tuned pretrain model is leveraged to classify fake videos within the subset of YouTube videos with textual information and user comments.

22. **[TCSS-2024] Cross-Modal Attention Network for Detecting Multimodal Misinformation From Multiple Platforms**. ![](https://img.shields.io/badge/visual-D8D0E1) ![](https://img.shields.io/badge/textual-D8D0E1) 

    *Zhiwei Guo, Yang Li, Zhenguo Yang, Xiaoping Li, Lap-Kei Lee, Qing Li, Wenyin Liu* [[pdf](https://ieeexplore.ieee.org/abstract/document/10478449/)]
     - This paper constructs a multiplatform multimodal misinformation(3M) dataset by collecting data from TikTok(Chinese version) and Weibo and designs a crossmodal attention misinformation detection(CAMD) network. Extensive experiments on the 3M dataset validate the effectiveness of the proposed CAMD model.
23. **[COLING-2024] Interpretable Short Video Rumor Detection based on Modality Tampering**. ![](https://img.shields.io/badge/visual-D8D0E1) ![](https://img.shields.io/badge/textual-D8D0E1) ![](https://img.shields.io/badge/acoustic-D8D0E1)

    *Kaixuan Wu, Yanghao Lin, Donglin Cao, Dazhen Lin* [[pdf](https://aclanthology.org/2024.lrec-main.804.pdf)]
     - This paper considers how to detect rumors from the perspective of modality tampering. The authors propose a short video rumor detection framework by designing two pretraining tasks: modality tampering detection and inter-modal matching and design an interpretability mechanism to make the rumor detection results more reasonable by backtracking the model’s decision-making process.

24. **[PACIS-2024] Detecting Misinformation in Multimedia Content through Cross-Modal Entity Consistency: A Dual Learning Approach**. ![](https://img.shields.io/badge/visual-D8D0E1) ![](https://img.shields.io/badge/textual-D8D0E1) ![](https://img.shields.io/badge/acoustic-D8D0E1)

    *Zhe Fu, Kanlun Wang, Wangjiaxuan Xin, Lina Zhou, Shi Chen, Yaorong Ge, Daniel Janies, Dongsong Zhang* [[pdf](https://www.researchgate.net/profile/Kanlun-Wang/publication/381458898_Detecting_Misinformation_in_Multimedia_Content_through_Cross-Modal_Entity_Consistency_A_Dual_Learning_Approach/links/666df49385a4ee7261c5af54/Detecting-Misinformation-in-Multimedia-Content-through-Cross-Modal-Entity-Consistency-A-Dual-Learning-Approach.pdf)]
     - This paper proposed a Multimedia Misinformation Detection (MultiMD) framework for detecting misinformation from video content by leveraging cross-modal entity consistency.

25. **[ACL-2024] Unveiling Opinion Evolution via Prompting and Diffusion for Short Video Fake News Detection**. ![](https://img.shields.io/badge/visual-D8D0E1) ![](https://img.shields.io/badge/textual-D8D0E1) ![](https://img.shields.io/badge/acoustic-D8D0E1)
       *Linlin Zong, Jiahui Zhou, Wenmin Lin, Xinyue Liu, Xianchao Zhang, Bo Xu* [[pdf](https://aclanthology.org/2024.findings-acl.642.pdf)]
       - This paper leverages the analytical capabilities of LLMs to assist in short video fake news detection tasks and devise opinion evolution based on a diffusion model to achieve cross-modal interaction.
   
25. **[MM-2024] Mitigating World Biases: A Multimodal Multi-View Debiasing Framework for Fake News Video Detection**. ![](https://img.shields.io/badge/visual-D8D0E1) ![](https://img.shields.io/badge/textual-D8D0E1) ![](https://img.shields.io/badge/acoustic-D8D0E1)

    *Zhi Zeng, Minnan Luo, Xiangzheng Kong, Huan Liu, Hao Guo, Hao Yang, Zihan Ma, Xiang Zhao* [[pdf](https://openreview.net/pdf?id=N7KGLxoKcC)]
    - This paper propose a Multimodal MultiView Debiasing(MMVD) framework to solve the issue of biased fake news video detection. MMVD designs a multiview causal reasoning strategy to learn unbiased dependencies within the cognitive biases.

26. **[MM-2024] FakingRecipe: Detecting Fake News on Short Video Platforms from the Perspective of Creative Process**. ![](https://img.shields.io/badge/visual-D8D0E1) ![](https://img.shields.io/badge/textual-D8D0E1) ![](https://img.shields.io/badge/acoustic-D8D0E1)

    *Yuyan Bu, Qiang Sheng, Juan Cao, Peng Qi, Danding Wang, Jintao Li* [[pdf](https://arxiv.org/abs/2407.16670)]
    - This paper proposees FakingRecipe, a creative process-aware model for detecting fake news short videos. FakingRecipe captures the fake news preferences in material selection from sentimental and semantic aspects and considers the traits of material editing from spatial and temporal aspects. The authors also construct FakeTT, a new English dataset for fake news short video detection. 

27. **[ArXiv-2024] VMID: A Multimodal Fusion LLM Framework for Detecting and Identifying Misinformation of Short Videos**. ![](https://img.shields.io/badge/visual-D8D0E1) ![](https://img.shields.io/badge/textual-D8D0E1) ![](https://img.shields.io/badge/acoustic-D8D0E1)

    *Weihao Zhong, Yinhao Xiao, Minghui Xu, Xiuzhen Cheng* [[pdf](https://arxiv.org/pdf/2411.10032)]
    - This paper proposes method VMID for fake news detection. VMID utilizes pre-trained models—such as Whisper for audio transcription, CogVLM2 for visual frameanalysis, and VSE (Video-subtitle-extractor) for aligningtextual and visual content—to create a unified multimodal representation. It also incorporates metadata, including upload time, engagement metrics, and user comments. The combined data is structured into a prompt for evaluation by a LoRA-tuned LLM, enabling the identification of misinformation within short videos.

28. **[IPM-2024] Enhancing video rumor detection through multimodal deep feature fusion with time-sync comments** . ![](https://img.shields.io/badge/visual-D8D0E1) ![](https://img.shields.io/badge/textual-D8D0E1) ![](https://img.shields.io/badge/acoustic-D8D0E1)

    *Ming Yin, Wei Chen, Dan Zhu, Jijiao Jiang*  [[pdf](https://www.sciencedirect.com/science/article/pii/S0306457324002942)]
    - This paper introduces TSCs(Time-Sync Comment/弹幕) into rumor detection. The authors propose TSC-MDFFM method, which introduces time-sync comments to enhance the propagation structure of videos on social networks and utilizes a graph neural network to  aggregate text features, employing Low-Rank Multimodal Fusion to merge the text features, overall video motion features, and visual features of the video to establish the global feature representation. An attention mechanism is then used to fuse the video's local features and global features, and a fully connected neural network is employed for rumor classification. This paper also curates a TSC-Video Rumor detection dataset from Bilibili, which comprises a total of 645 samples, with 262 labeled as rumors and 383 as non-rumors. The dataset is not open-sourced yet.

15. **[SSRN-2022] A Novel Method for Detecting Misinformation in Videos, Utilizing Reverse Image Search, Semantic Analysis, and Sentiment Comparison of Metadata**. ![](https://img.shields.io/badge/pipeline-D8D0E1)
    
    *Dhanvi Ganti*. [[pdf](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4128499)]
    - This paper proposes a three-step method to detect video-based misinformation. First, this method detects deepfakes first and then applies semantic analysis to detect shifts in the meaning and intent of the associated metadata of both videos. The last step entails a sentiment comparison to detect shifts in emotion.
   
16. **[SCID-2024] TripletViNet: Mitigating Misinformation Video Spread Across
Platforms**. ![](https://img.shields.io/badge/cross--platform-D8D0E1)

    *Petar Smolovic, Thilini Dahanayaka, Kanchana Thilakarathna*. [[pdf](https://arxiv.org/pdf/2407.10644)]

    - This paper focuses on recognizing videos across multiple platforms by using the traffic traces of videos on one platform only and proposed a new framework TripletViNet. TripletViNet encompasses platform-wise pre-processing, an encoder trained utilizing triplet learning for improved accuracy and multiclass classifier for classifying the video title of a traffic trace.

### Related Areas

This section contains the pilot works that discuss areas related to misinformation video detection.


1. **[Soft Computing-2022] Intelligent techniques for deception detection: a survey and critical study**. ![](https://img.shields.io/badge/deception_detection-EAD8D9) ![](https://img.shields.io/badge/survey-D8D0E1) 

   *Haya Alaskar, Zohra Sbaï, Wasiq Khan, Abir Hussain, Arwa Alrawais*.  [[pdf](https://link.springer.com/article/10.1007/s00500-022-07603-w)]

2. **[CICLing-2018] A deep learning approach for multimodal deception detection**. ![](https://img.shields.io/badge/deception_detection-EAD8D9)

   *Gangeshwar Krishnamurthy, Navonil Majumder, Soujanya Poria, Erik Cambria*.  [[pdf](https://arxiv.org/abs/1803.00344)]
   <!-- - This paper proposes a simple yet tough to beat multi-modal neural model for deception detection by combining features from different modalities such as video, audio, and text along with Micro-Expression features. -->

3. **[AAAI-2018] Deception Detection in Videos**. ![](https://img.shields.io/badge/deception_detection-EAD8D9)

   *Zhe Wu, Bharat Singh, Larry Davis, V. Subrahmanian*. [[PDF](https://ojs.aaai.org/index.php/AAAI/article/download/11502/11361)]

4. **[Applied Intelligence-2021] A unified approach for detection of Clickbait videos on YouTube using cognitive evidences**. ![](https://img.shields.io/badge/clickbait_detection-EAD8D9)

   *Deepika Varshney, Dinesh Kumar Vishwakarma*.  [[pdf](https://link.springer.com/article/10.1007/s10489-020-02057-9)]

5. **[ICPR-2022] VidHarm: A Clip Based Dataset for Harmful Content Detection**. ![](https://img.shields.io/badge/harmful_content_detection-EAD8D9)

   *Johan Edstedt, Amanda Berg, Michael Felsberg, Johan Karlsson, Francisca Benavente, Anette Novak, Gustav Grund Pihlgren*. [[pdf](https://arxiv.org/pdf/2106.08323.pdf)]
### Future Directions

This section contains the pilot works that related to critical open issues and future directions for misinformation video detection.

1. **[ICWSM-2022] Cross-Platform Multimodal Misinformation: Taxonomy, Characteristics and Detection for Textual Posts and Videos**. ![](https://img.shields.io/badge/transferability-EAD8D9) ![](https://img.shields.io/badge/multiplatform-D8D0E1)

   *Nicholas Micallef, Marcelo Sandoval-Castañeda, Adi Cohen, Mustaque Ahamad, Srijan Kumar, Nasir Memon*.  [[pdf](https://ojs.aaai.org/index.php/ICWSM/article/view/19323)]
2. **[SIGIR-2022] Generalizing to the future: Mitigating entity bias in fake news detection**. ![](https://img.shields.io/badge/transferability-EAD8D9) ![](https://img.shields.io/badge/temporal-D8D0E1)

   *Yongchun Zhu, Qiang Sheng, Juan Cao, Shuokai Li, Danding Wang, Fuzhen Zhuang*.  [[pdf](https://dl.acm.org/doi/pdf/10.1145/3477495.3531816)]

3. **[AAAI-2021] Embracing domain differences in fake news: Cross-domain fake news detection using multi-modal data**. ![](https://img.shields.io/badge/transferability-EAD8D9) ![](https://img.shields.io/badge/multidomain-D8D0E1)

   *Amila Silva, Ling Luo, Shanika Karunasekera, Christopher Leckie*. [[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/16134)]

4. **[CIKM-2021] MDFEND: Multidomain fake news detection**. ![](https://img.shields.io/badge/transferability-EAD8D9) ![](https://img.shields.io/badge/multidomain-D8D0E1)

   *Qiong Nan, Juan Cao, Yongchun Zhu, Yanyan Wang,Jintao Li*. [[pdf](https://dl.acm.org/doi/pdf/10.1145/3459637.3482139)]

5. **[TKDE-2022] Memory-guided multi-view multi-domain fake news detection**. ![](https://img.shields.io/badge/transferability-EAD8D9) ![](https://img.shields.io/badge/multidomain-D8D0E1)

   *Yongchun Zhu, Qiang Sheng, Juan Cao, Qiong Nan, Kai Shu, Minghui Wu, Jindong Wang, Fuzhen Zhuang*.  [[pdf](https://arxiv.org/pdf/2206.12808)]
6. **[IP&M-2022] Characterizing multi-domain false news and underlying user effects on Chinese Weibo**. ![](https://img.shields.io/badge/transferability-EAD8D9) ![](https://img.shields.io/badge/multidomain-D8D0E1)

   *Qiang Sheng, Juan Cao, H. Russell Bernard, Kai Shu,  Jintao Li, Huan Liu*.  [[pdf](https://arxiv.org/pdf/2205.03068)]
7. **[NAACL-2018] Fever: a large-scale dataset for fact extraction and verification** . ![](https://img.shields.io/badge/explainability-EAD8D9) ![](https://img.shields.io/badge/verification-D8D0E1)

   *James Thorne, Andreas Vlachos, Christos Christodoulopoulos, Arpit Mittal* [[pdf](https://arxiv.org/pdf/1803.05355)]
8. **[CVPR-2022] Open-Domain, Content-based, Multi-modal Fact-checking of Out-of-Context Images via Online Resources**. ![](https://img.shields.io/badge/explainability-EAD8D9) ![](https://img.shields.io/badge/verification-D8D0E1)

   *Sahar Abdelnabi, Rakibul Hasan, Mario Fritz*. [[pdf](http://openaccess.thecvf.com/content/CVPR2022/papers/Abdelnabi_Open-Domain_Content-Based_Multi-Modal_Fact-Checking_of_Out-of-Context_Images_via_Online_Resources_CVPR_2022_paper.pdf)]
9. **[CVPR-2020] Multi-modal graph neural network for joint reasoning on vision and scene text**. ![](https://img.shields.io/badge/reasoning-EAD8D9)

   *Difei Gao, Ke Li, Ruiping Wang, Shiguang Shan, Xilin Chen*. [[pdf](http://openaccess.thecvf.com/content_CVPR_2020/papers/Gao_Multi-Modal_Graph_Neural_Network_for_Joint_Reasoning_on_Vision_and_CVPR_2020_paper.pdf)]
10. **[NIPS-2022] Chain-of-Thought Prompting Elicits Reasoning in Large Language Models**. ![](https://img.shields.io/badge/reasoning-EAD8D9)

    *Jason Wei, Xuezhi Wang, Dale Schuurmans, Maarten Bosma, Brian Ichter, Fei Xia, Ed Chi, Quoc Le, Denny Zhou* [[pdf](https://arxiv.org/pdf/2201.11903)]

11. **[WWW-2022]Veracity-aware and Event-driven Personalized News Recommendation for Fake News Mitigation**. ![](https://img.shields.io/badge/recommendation-EAD8D9) 

    *Shoujin Wang, Xiaofei Xu, Xiuzhen Zhang, Yan Wang, Wenzhuo Song*. [[pdf](https://scholar.archive.org/work/ncxytdfyjbdizmv6c6i7t6p6ye/access/wayback/https://dl.acm.org/doi/pdf/10.1145/3485447.3512263)]

12. **[AAAI-2020] Weak Supervision for Fake News Detection via Reinforcement Learning**. ![](https://img.shields.io/badge/recommendation-EAD8D9)

      *Yaqing Wang, Weifeng Yang, Fenglong Ma, Jin Xu, Bin Zhong, Qiang Deng, Jing Gao*.  [[pdf](https://ojs.aaai.org/index.php/AAAI/article/view/5389/5245)]

## Resources

### Datasets
| Name                 | Paper                                                        | Access                                        | Source Platform     | Language|
| -------------------- | ------------------------------------------------------------ | --------------------------------------------- | ------------------- |---------|
|  **FVC**             | [A corpus of debunked and verified user-generated videos](https://drive.google.com/file/d/1OfGx0aBHeVK3TmAOP7Wi6APZZlgocmkG/view)|[link](https://mklab.iti.gr/results/fake-video-corpus/)|YouTube,Twitter,FaceBook| English,French, Russian,German,Arabic|
|**YouTubeAudit**|[Measuring Misinformation in Video Search Platforms: An Audit Study on YouTube](https://www.researchgate.net/profile/Eslam-Hussein-12/publication/340681643_Measuring_Misinformation_in_Video_Search_Platforms_An_Audit_Study_on_YouTube/links/5e98be72a6fdcca7891ff9b5/Measuring-Misinformation-in-Video-Search-Platforms-An-Audit-Study-on-YouTube.pdf)|[link](https://social-comp.github.io/YouTubeAudit-data/)|YouTube|English (mainly)|
|**VAVD**|[Misleading Metadata Detection on YouTube](https://arxiv.org/pdf/1901.08759.pdf)| |YouTube|English|
|**MYVC**|[Using Topic Modeling and Adversarial Neural Networks for Fake News Video Detection](https://dl.acm.org/doi/abs/10.1145/3459637.3482212)| |YouTube|English|
|**YouTube-Cancer**|[Towards Automatic Detection of Misinformation in Online Medical Videos](https://arxiv.org/pdf/1909.01543)| |YouTube|English|
|**YouTube-Covid**|[NLP-based Feature Extraction for the Detection of COVID-19 Misinformation Videos on YouTube](https://aclanthology.org/2020.nlpcovid19-acl.17.pdf)| |YouTube|English|
|**TikTok-Covid**|[A Multimodal Misinformation Detector for COVID-19 Short Videos on TikTok](https://ieeexplore.ieee.org/abstract/document/9671928/)| |TikTok|English|
|**Bilibili-Health**|[A CNN-based misleading video detection model](https://www.nature.com/articles/s41598-022-10117-y)| |Bilibili|Chinese|
|**FakeSV**|[FakeSV: A Multimodal Benchmark with Rich Social Context for Fake News Detection on Short Video Platforms](https://arxiv.org/pdf/2211.10973.pdf)|[link](https://github.com/ICTMCG/FakeSV)|Douyin,Kuaishou|Chinese|
|**TikTok-Rumor**|[Interpretable Short Video Rumor Detection based on Modality Tampering](https://aclanthology.org/2024.lrec-main.804.pdf)||TikTok|English|
|**FakeTT**|[FakingRecipe: Detecting Fake News on Short Video Platforms from the Perspective of Creative Process](https://www.arxiv.org/abs/2407.16670)|[link](https://github.com/ICTMCG/FakingRecipe)|TikTok|English|
<!-- 1. **FVC** [[paper](https://drive.google.com/file/d/1OfGx0aBHeVK3TmAOP7Wi6APZZlgocmkG/view)] [[dataset](https://mklab.iti.gr/results/fake-video-corpus/)] 
2. **YouTubeAudit** [[paper](https://www.researchgate.net/profile/Eslam-Hussein-12/publication/340681643_Measuring_Misinformation_in_Video_Search_Platforms_An_Audit_Study_on_YouTube/links/5e98be72a6fdcca7891ff9b5/Measuring-Misinformation-in-Video-Search-Platforms-An-Audit-Study-on-YouTube.pdf)] [[dataset](https://social-comp.github.io/YouTubeAudit-data/)]
3. **FakeSV** [[paper](https://arxiv.org/pdf/2211.10973.pdf)] [[dataset](https://github.com/ICTMCG/FakeSV)]
4. **VAVD** [[paper](https://arxiv.org/pdf/1901.08759.pdf)]
5. **MYVC** [[paper](https://dl.acm.org/doi/abs/10.1145/3459637.3482212)]
6. **YouTube-Cancer** [[paper](https://arxiv.org/pdf/1909.01543)]
7. **YouTube-Covid** [[paper](https://aclanthology.org/2020.nlpcovid19-acl.17.pdf)]
7. **TikTok-Covid** [[paper](https://ieeexplore.ieee.org/abstract/document/9671928/)]
8. **Bilibili-Health** [[paper](https://www.nature.com/articles/s41598-022-10117-y)] -->
### Tools
DeepFake Detector : [WeVerify Project](https://weverify.eu/tools/deepfake-detector/) ; [Sensity](https://sensity.ai/deepfakes-detection/)

Reverse Image Search : [Google](https://images.google.com/) ; [Baidu](https://image.baidu.com/) ; [Bing](https://www.bing.com/visualsearch) ; [Yandex](https://yandex.com/) ; [Tineye](https://tineye.com/) ; [ImageRaider](https://infringement.report/api/raider-reverse-image-search/) ; [Duplichecker](https://www.duplichecker.com/)

Video Verification Plugin : [InVID Verification Plugin](https://www.invid-project.eu/tools-and-services/invid-verification-plugin/)

### Citation
This curated list of works on misinformation video detection is based on our [survey](https://arxiv.org/pdf/2302.03242). If you find it helpful, please cite as follows:
```
@inproceedings{mvdsurvey, 
title={Combating Online Misinformation Videos: Characterization, Detection, and Future Directions}, 
author={Bu, Yuyan and Sheng, Qiang and Cao, Juan and Qi, Peng and Wang, Danding and Li, Jintao}, 
booktitle={Proceedings of the 31st ACM International Conference on Multimedia}, 
year={2023},
doi={10.1145/3581783.3612426},
publisher = {Association for Computing Machinery},
} 
```
