# Awesome-Video-Misinfo-Detection

## Contents

- [Paper List for Misinformation Video Detection](#paper-list-for-misinfomation-video-detection)
  - [Contents](#contents)
  - [Introduction](#introduction)
    - [Keywords Convention](#keywords-convention)
  - [Papers](#papers)
    - [Related Survey](#related-survey)
    - [Detection at Signal Level](#detection-at-signal-level)
    - [Detection at Semantic and Intent Level](#detection-at-semantic-and-intent-level)
    - [Related Areas](#related-areas)
    - [Future Directions](#future-directions)
  - [Resources](#resources)
    - [Datasets](#datasets)
    - [Tools](#tools)


## Introduction

This is a paper list (working in progress) about **Misinformation Video Detection**

### Keywords Convention


![](https://img.shields.io/badge/transferability-EAD8D9) section in our survey

![](https://img.shields.io/badge/textual-D8D0E1) main feature


## Papers

### Related Survey

1. **Multi-modal Misinformation Detection: Approaches, Challenges and Opportunities**. ![](https://img.shields.io/badge/multimodal_detection-D8D0E1)

   *Sara Abdali*. arXiv preprint arXiv:2203.13883 (2022).  [[pdf](https://arxiv.org/pdf/2203.13883.pdf)] 
2. **A Survey on Multimodal Disinformation Detection**. ![](https://img.shields.io/badge/multimodal_detection-D8D0E1)

   *Firoj Alam, Stefano Cresci, Tanmoy Chakraborty, Fabrizio Silvestri, Dimitar Dimitrov, Giovanni Da San Martino, Shaden Shaar, Hamed Firooz, Preslav Nakov*.  arXiv preprint arXiv:2103.12541 (2021) [[pdf](https://arxiv.org/pdf/2103.12541.pdf)] 
3. **Exploring the role of visual content in fake news detection**. ![](https://img.shields.io/badge/multimodal_detection-D8D0E1)

   *Juan Cao, Peng Qi, Qiang Sheng, Tianyun Yang, Junbo Guo, Jintao Li*. Disinformation, Misinformation, and Fake News in Social Media: Emerging Research Challenges and Opportunities (2020): 141-161.  [[pdf](https://arxiv.org/pdf/2003.05096.pdf)] 
4. **A Survey on Video-Based Fake News Detection Techniques**. ![](https://img.shields.io/badge/video_forgery_detection-D8D0E1)

   *Ronak Agrawal, Dilip Kumar Sharma*. 2021 8th International Conference on Computing for Sustainable Global Development (INDIACom). IEEE, 2021.  [[pdf](https://ieeexplore.ieee.org/abstract/document/9441196)]
5. **A Survey of Fake News: Fundamental Theories, Detection Methods, and Opportunities**. ![](https://img.shields.io/badge/fake_news_detection-D8D0E1)

   *Xinyi Zhou, Reza Zafarani*. ACM Computing Surveys (CSUR) 53.5 (2020): 1-40. [[pdf](https://arxiv.org/pdf/1812.00315)]
6. **Fake news detection on social media: A data mining perspective**. ![](https://img.shields.io/badge/fake_news_detection-D8D0E1)

   *Kai Shu,Amy Sliva,Suhang Wang,Jiliang Tang,Huan Liu*.  ACM SIGKDD Explorations Newsletter,Volume 19,Issue 1,June 2017, pp 22–36. [[pdf](https://arxiv.org/pdf/1708.01967)]

### Detection at Signal Level

This section contains the pilot works that detect misinformation video at signal level, i.e., detect with the clues of editing traces or generating traces.
1.  **[MS-2022] Fake COVID-19 videos detector based on frames and audio watermarking**. ![](https://img.shields.io/badge/editing_traces-EAD8D9) ![](https://img.shields.io/badge/watermarking-D8D0E1)

   *Nesrine Tarhouni ,Salma Masmoudi, Maha Charfeddine, Chokri Ben Amar*.  [[pdf](https://link.springer.com/article/10.1007/s00530-022-01006-5)]

2. **[TIFS-2016] ESPRIT-Hilbert-based audio tampering detection with SVM classifier for forensic analysis via electrical network frequency** . ![](https://img.shields.io/badge/editing_traces-EAD8D9) ![](https://img.shields.io/badge/audio-D8D0E1)

   *Reis, Paulo Max Gil Innocencio , da Costa, Joao Paulo Carvalho Lustosa , Miranda, Ricardo Kehrle , Del Galdo, Giovanni*. [[pdf](https://ieeexplore.ieee.org/abstract/document/7775065/)]

3. **[CSUR-2021] The creation and detection of deepfakes: A survey**. ![](https://img.shields.io/badge/generating_traces-EAD8D9) ![](https://img.shields.io/badge/video-D8D0E1)

   *Yisroel Mirsky, Wenke Lee*. [[pdf](https://arxiv.org/pdf/2004.11138)]
4. **[FCST-2023] Overview of Facial Deepfake Video Detection Methods**. ![](https://img.shields.io/badge/generating_traces-EAD8D9) ![](https://img.shields.io/badge/video-D8D0E1)
   
   *Zhang lu, Lu Tianliang, Du Yanhui.* [[pdf](http://fcst.ceaj.org/EN/article/downloadArticleFile.do?attachType=PDF&id=3208)]
5. **[DDAM-2022] Lessons Learned from ASVSpoof and Remaining Challenges**. ![](https://img.shields.io/badge/generating_traces-EAD8D9) ![](https://img.shields.io/badge/audio-D8D0E1)

   *Junichi Yamagishi*. [[pdf](https://dl.acm.org/doi/abs/10.1145/3552466.3554359)]
6. **[ICASSP-2022] Fake audio detection based on unsupervised pretraining models**. ![](https://img.shields.io/badge/generating_traces-EAD8D9) ![](https://img.shields.io/badge/audio-D8D0E1)

   *Zhiqiang Lv, Shanshan Zhang,Kai Tang, Pengfei Hu*.  [[pdf](https://ieeexplore.ieee.org/abstract/document/9747605/)]
7. **[ICCV-2021] Joint audio-visual deepfake detection**. ![](https://img.shields.io/badge/generating_traces-EAD8D9) ![](https://img.shields.io/badge/audiovisual-D8D0E1)

   *Yipin Zhou, Ser-Nam Lim*.  [[pdf](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhou_Joint_Audio-Visual_Deepfake_Detection_ICCV_2021_paper.pdf)]
8. **[TCSVT-2021] Detecting compressed deepfake videos in social networks using frame-temporality two-stream convolutional network**. ![](https://img.shields.io/badge/generating_traces-EAD8D9) ![](https://img.shields.io/badge/compressed_video-D8D0E1)

   *Juan Hu ,XinLiao ,WeiWang, ZhengQin*.  [[pdf](https://ieeexplore.ieee.org/abstract/document/9408664)]
   - The work propose a two-stream method by analyzing the frame-level and temporality-level of compressed Deepfake videos. The frame-level stream can prune the redundant connections to prevent the invalid connections from affecting the final prediction.  The temporality-level stream is utilized to capture temporal features to detect the temporal consistency.


### Detection at Semantic and Intent Level

This section contains the pilot works that utilize multimodal features to detect misinformation video at Semantic/Intent Level.

1. **[MFSec-2017] Web Video Verification using Contextual Cues**.  ![](https://img.shields.io/badge/textual-D8D0E1) ![](https://img.shields.io/badge/social_context-D8D0E1)

   *Olga Papadopoulou, Markos Zampoglou, Symeon Papadopoulos, Yiannis Kompatsiaris*.  [[pdf](https://core.ac.uk/download/pdf/144811239.pdf)]

   - Propose an annotated dataset of real and fake videos(FVC)
   - Use video comment credibility and video metadata features for fake video detection.
2. **[ICMI-2019] Towards Automatic Detection of Misinformation in Online Medical Videos**. ![](https://img.shields.io/badge/textual-D8D0E1) ![](https://img.shields.io/badge/acoustic-D8D0E1) ![](https://img.shields.io/badge/social_context-D8D0E1)

   *Rui Hou, Verónica Pérez-Rosas, Stacy Loeb, Rada Mihalcea*.  [[pdf](https://arxiv.org/pdf/1909.01543)] 
   - Explore the use of linguistic, acoustic, and user engagement features to identify misinformation.

3. **[ECIR-2019] Misleading Metadata Detection on YouTube**. ![](https://img.shields.io/badge/social_context-D8D0E1) ![](https://img.shields.io/badge/textual-D8D0E1)

   *Priyank Palod, Ayush Patwari, Sudhanshu Bahety, Saurabh Bagchi, Pawan Goyal*.  [[pdf](https://arxiv.org/pdf/1901.08759.pdf)]
   - The work presents VAVD, a new dataset for research on fake videos.
   - Propose UCNet , a deep learning based approach using comments and simple features extracted from title and social context to identify fake videos.

4. **[ACL Workshop-2020] NLP-based Feature Extraction for the Detection of COVID-19 Misinformation Videos on YouTube**. ![](https://img.shields.io/badge/social_context-D8D0E1) ![](https://img.shields.io/badge/textual-D8D0E1)

   *Juan Carlos Medina Serrano, Orestis Papakyriakopoulos, Simon Hegelich*.  [[pdf](https://aclanthology.org/2020.nlpcovid19-acl.17.pdf)]
   - Create a multi-label classifier based on transfer-learning that can categorize conspiratorial content; use the percentage of conspiracy comments and the first hundred comments as tf-idf features in the classifier.

5. **[arXiv-2021] Misinformation Detection on YouTube Using Video Captions**. ![](https://img.shields.io/badge/textual-D8D0E1)

   *Raj Jagtap, Abhinav Kumar, Rahul Goel, Shakshi Sharma, Rajesh Sharma, Clint P. George*.  [[pdf](https://arxiv.org/pdf/2107.00941.pdf)] 
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

13. **[AAAI-2023] FakeSV: A Multimodal Benchmark with Rich Social Context for Fake News Detection on Short Video Platforms** ![](https://img.shields.io/badge/visual-D8D0E1) ![](https://img.shields.io/badge/textual-D8D0E1) ![](https://img.shields.io/badge/acoustic-D8D0E1) ![](https://img.shields.io/badge/social_context-D8D0E1)
    
    *Peng Qi, Yuyan Bu, Juan Cao, Wei Ji, Ruihao Shui,Junbin Xiao, Danding Wang, Tat-Seng Chua*.  [[pdf](https://arxiv.org/pdf/2211.10973.pdf)]

14. **[SSRN-2022]A Novel Method for Detecting Misinformation in Videos, Utilizing Reverse Image Search, Semantic Analysis, and Sentiment Comparison of Metadata**. ![](https://img.shields.io/badge/pipeline-D8D0E1)
    
    *Dhanvi Ganti*. [[pdf](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4128499)]

### Related Areas

This section contains the pilot works that discuss areas related to misinformation video detection.

1. **[Soft Computing-2022] Intelligent techniques for deception detection: a survey and critical study**. ![](https://img.shields.io/badge/deception_detection-EAD8D9) ![](https://img.shields.io/badge/survey-D8D0E1) 

   *Haya Alaskar, Zohra Sbaï, Wasiq Khan, Abir Hussain, Arwa Alrawais*.  [[pdf](https://link.springer.com/article/10.1007/s00500-022-07603-w)]

2. **[CICLing-2018] A deep learning approach for multimodal deception detection**. ![](https://img.shields.io/badge/deception_detection-EAD8D9)

   *Gangeshwar Krishnamurthy, Navonil Majumder, Soujanya Poria, Erik Cambria*.  [[pdf](https://arxiv.org/abs/1803.00344)]

3. **[Applied Intelligence-2021] A unified approach for detection of Clickbait videos on YouTube using cognitive evidences**. ![](https://img.shields.io/badge/clickbait_detection-EAD8D9)

   *Deepika Varshney, Dinesh Kumar Vishwakarma*.  [[pdf](https://link.springer.com/article/10.1007/s10489-020-02057-9)], 

### Future Directions

This section contains the pilot works that related to critical open issues and future directions for misinformation video detection.

1. **[ICWSM-2022] Cross-Platform Multimodal Misinformation: Taxonomy, Characteristics and Detection for Textual Posts and Videos**. ![](https://img.shields.io/badge/transferability-EAD8D9) ![](https://img.shields.io/badge/multiplatform-D8D0E1)

   *Nicholas Micallef, Marcelo Sandoval-Castañeda, Adi Cohen, Mustaque Ahamad, Srijan Kumar, Nasir Memon*.  [[pdf](https://ojs.aaai.org/index.php/ICWSM/article/view/19323)]
2. **[SIGIR-2022] Generalizing to the future: Mitigating entity bias in fake news detection**. ![](https://img.shields.io/badge/transferability-EAD8D9) ![](https://img.shields.io/badge/temporal-D8D0E1)

   *Yongchun Zhu, Qiang Sheng, Juan Cao, Shuokai Li, Danding Wang, Fuzhen Zhuang*.  [[pdf](https://dl.acm.org/doi/pdf/10.1145/3477495.3531816)]
3. **[TKDE-2022] Memory-guided multi-view multi-domain fake news detection**. ![](https://img.shields.io/badge/transferability-EAD8D9) ![](https://img.shields.io/badge/multidomain-D8D0E1)

   *Yongchun Zhu, Qiang Sheng, Juan Cao, Qiong Nan, Kai Shu, Minghui Wu, Jindong Wang, Fuzhen Zhuang*.  [[pdf](https://arxiv.org/pdf/2206.12808)]
4. **[IP&M-2022] Characterizing multi-domain false news and underlying user effects on Chinese Weibo**. ![](https://img.shields.io/badge/transferability-EAD8D9) ![](https://img.shields.io/badge/multidomain-D8D0E1)

   *Qiang Sheng, Juan Cao, H. Russell Bernard, Kai Shu,  Jintao Li, Huan Liu*.  [[pdf](https://arxiv.org/pdf/2205.03068)]
5. **[NAACL-2018] Fever: a large-scale dataset for fact extraction and verification** . ![](https://img.shields.io/badge/explainability-EAD8D9) ![](https://img.shields.io/badge/verification-D8D0E1)

   *James Thorne, Andreas Vlachos, Christos Christodoulopoulos, Arpit Mittal* [[pdf](https://arxiv.org/pdf/1803.05355)]
6. **[CVPR-2022] Open-Domain, Content-based, Multi-modal Fact-checking of Out-of-Context Images via Online Resources**. ![](https://img.shields.io/badge/explainability-EAD8D9) ![](https://img.shields.io/badge/verification-D8D0E1)

   *Sahar Abdelnabi, Rakibul Hasan, Mario Fritz*. [[pdf](http://openaccess.thecvf.com/content/CVPR2022/papers/Abdelnabi_Open-Domain_Content-Based_Multi-Modal_Fact-Checking_of_Out-of-Context_Images_via_Online_Resources_CVPR_2022_paper.pdf)]
7. **[CVPR-2020] Multi-modal graph neural network for joint reasoning on vision and scene text**. ![](https://img.shields.io/badge/reasoning-EAD8D9)

   *Difei Gao, Ke Li, Ruiping Wang, Shiguang Shan, Xilin Chen*. [[pdf](http://openaccess.thecvf.com/content_CVPR_2020/papers/Gao_Multi-Modal_Graph_Neural_Network_for_Joint_Reasoning_on_Vision_and_CVPR_2020_paper.pdf)]
8. **[NIPS-2022] Chain-of-Thought Prompting Elicits Reasoning in Large Language Models**. ![](https://img.shields.io/badge/reasoning-EAD8D9)

   *Jason Wei, Xuezhi Wang, Dale Schuurmans, Maarten Bosma, Brian Ichter, Fei Xia, Ed Chi, Quoc Le, Denny Zhou* [[pdf](https://arxiv.org/pdf/2201.11903)]
9. **[WWW-2022]Veracity-aware and Event-driven Personalized News Recommendation for Fake News Mitigation**. ![](https://img.shields.io/badge/recommendation-EAD8D9) 

   *Shoujin Wang, Xiaofei Xu, Xiuzhen Zhang, Yan Wang, Wenzhuo Song*. [[pdf](https://scholar.archive.org/work/ncxytdfyjbdizmv6c6i7t6p6ye/access/wayback/https://dl.acm.org/doi/pdf/10.1145/3485447.3512263)]
10. **[AAAI-2020] Weak Supervision for Fake News Detection via Reinforcement Learning**. ![](https://img.shields.io/badge/recommendation-EAD8D9)

      *Yaqing Wang, Weifeng Yang, Fenglong Ma, Jin Xu, Bin Zhong, Qiang Deng, Jing Gao*.  [[pdf](https://ojs.aaai.org/index.php/AAAI/article/view/5389/5245)]

## Resources

### Datasets
1. **FVC** [[paper](https://drive.google.com/file/d/1OfGx0aBHeVK3TmAOP7Wi6APZZlgocmkG/view)] [[dataset](https://mklab.iti.gr/results/fake-video-corpus/)] 
2. **YouTubeAudit** [[paper](https://www.researchgate.net/profile/Eslam-Hussein-12/publication/340681643_Measuring_Misinformation_in_Video_Search_Platforms_An_Audit_Study_on_YouTube/links/5e98be72a6fdcca7891ff9b5/Measuring-Misinformation-in-Video-Search-Platforms-An-Audit-Study-on-YouTube.pdf)] [[dataset](https://social-comp.github.io/YouTubeAudit-data/)]
3. **FakeSV** [[paper](https://arxiv.org/pdf/2211.10973.pdf)] [[dataset](https://github.com/ICTMCG/FakeSV)]
4. **VAVD** [[paper](https://arxiv.org/pdf/1901.08759.pdf)]
5. **MYVC** [[paper](https://dl.acm.org/doi/abs/10.1145/3459637.3482212)]
6. **YouTube-Cancer** [[paper](https://arxiv.org/pdf/1909.01543)]
7. **YouTube-Covid** [[paper](https://aclanthology.org/2020.nlpcovid19-acl.17.pdf)]
7. **TikTok-Covid** [[paper](https://ieeexplore.ieee.org/abstract/document/9671928/)]
8. **Bilibili-Health** [[paper](https://www.nature.com/articles/s41598-022-10117-y)]
### Tools
DeepFake Detector : [WeVerify Project](https://weverify.eu/tools/deepfake-detector/) ; [Sensity](https://sensity.ai/deepfakes-detection/)

Reverse Image Search : [Google](https://images.google.com/) ; [Baidu](https://image.baidu.com/) ; [Bing](https://www.bing.com/visualsearch) ; [Yandex](https://yandex.com/)

Video Verification Plugin : [InVID Verification Plugin](https://www.invid-project.eu/tools-and-services/invid-verification-plugin/)
