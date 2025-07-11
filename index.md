# 个人信息
## 周文俊
## 博士，讲师，硕士生导师
## 邮箱：zhouwenjun@swpu.edu.cn
## 地址：成都市新都区新都大道8号 西南石油大学计算机与软件学院 
## 科研团队：图像处理与并行计算研究中心（智能油气实验室） [https://ippc-lab.github.io/](https://ippc-lab.github.io/)
# 教育经历
- 日本北海道大学 系统信息科学 博士 信息科学研究科 2016.10 - 2019.09
  导师：金子 俊一 教授
- 日本北海道大学 系统信息科学 研究生 信息科学研究科 2015.10 - 2016.09
- 沈阳化工大学 控制科学与工程 硕士 信息工程学院 2012.09 - 2015.03
- 四川农业大学 农业电气化与自动化 本科 信息工程技术学院 2008.09 - 2012.06

# 研究经历
## 智能视觉感知方向
### 面向动态背景视频下的前景检测方法研究 2015.10-2019.09 
- 提出了一种基于共现性像素块对（Co-occurrence Pixel-Block Pairs:CPB）的新的背景建模方法。针对前景检测中的 背景变化问题，例如光照变化或背景运动，通过利用共生“像素到块”结构，CPB通过学习背景中的变化信息来提取 每个像素点的空间及时域信息，建立一个针对每个像素点的预期背景模型。然后，采用了一个高效的评估策略来识别 每个像素点的当前状态，并对其进行前景或背景的分类，这种策略被命名为相关性决策函数。这种新的背景模型拥有极强的抗动态背景干扰能力。并引入一种降解修正假说（Hypothesis on Degradation Modification:HoD）来增强CPB模型结构的鲁棒性，进一步提高了算法的性能。这种新的前景检测算法对光照变化或背景运动具有极强的鲁棒性。CPB是一种新的机器视觉领域中用于分类的特征，其不仅能够运用于视频中的前景提取，也能够在更多机器视觉领域进行应用的，如：缺陷检测，视频监控，背景复原及图像匹配等。

### PCB基板内高速连接器引脚弯曲检测  2018.10-2019.05
- 合作企业：华为日本
- 针对华为5G通讯高速连接器，其PCB引脚的连接问题，与华为日本研发中心合作，主研相关产品的PCB基板内高速连接器引脚弯曲检测技术。

### 面向视频监控的鲁棒背景初始化及其应用 2020.04 - 2022.12
- 西南石油大学“启航计划”项目 
- 针对现实场景中的视频监控应用，特别是复杂场景下的视频监控，通过对场景的特点及信息，进行鲁棒初始化构建。实现一种在光照变化、动态背景、前景间歇运动等复杂场景下的鲁棒背景初始化算法，能够有效的对场景的背景信息进行复原或重构，从而或缺无前景物体信息的完好清晰视频序列。以此背景初始化算法为基础，将其应用于复杂场景下的异常行为检测中，如公共监控场景下的异常行为检测，海上运输安全预警，石油化工码头或工厂安全监控等计算机视觉应用。

### 一种鲁棒对比度特征提取算子研究及其应用  2020.03-至今
- 合作：项圣 浙江工业大学
- 提出了一种对比度值算子 (contrast value operator：cvo)，可用于鲁棒图像模板匹配及搜索中，其能够有效地从图像中提取出纹理信息并进行更精细的结构呈现。cvo的有效设计，可用于各种机器视觉的工业应用中，如缺陷检测、物体搜索、工件识别等。

### 云雾环境下飞行器结冰视觉检测方法研究 2022.01-2023.12
- 中国空气动力研究与发展中心 结冰与防除冰重点实验室 开放基金项目
- 探索云雾环境下飞行器结冰视觉检测方法，采用视觉感知的机制进行云雾环境下结冰状况检测与识别。

### 面向公共场景安全的视觉目标异常行为检测研究 2023.01 - 至今
- 四川省科技厅自然科学基金 面上项目
- 本研究从视频监控中目标前景的运动特征入手， 根据前景和背景的差异化，从理论分析、算法求解和实验对比等方面展开研究，提出复杂场景下的视觉目标异常行为检测新方法，强调方法在实际应用中的可行性和准确性， 尤其是解决复杂场景下的行为检测鲁棒性， 设计提出适应于复杂光照变化，动态背景情况，高密度人群，目标间歇运动等复杂场景下的特征描述方式，以此构建场景行为模型实现异常行为检测。

### 基于多源数据融合的城市交通拥堵状态判别与预测研究 2024.01 - 
- 智能警务四川省重点实验 开放基金项目
- 本研究致力于利用城市交通多源数据，构建交通拥堵状态判别与预测模型。关键挑战包括数据融合、拥堵状态判别和交通预测。首先，收集并预处理多源数据。其次，运用数据融合技术与特征工程，提取重要数据特征。最后，采用深度学习方法，结合时间序列与回归分析，构建准确的拥堵判别及预测模型。本研究旨在提高城市交通管理效率，改善交通状况，提升市民出行体验，实现智能可持续城市交通系统。
  
## 医学影像智能分析方向
### 应用于编码激励信号中弹性检测的空间-时间域相关性方法研究 2019.12-2021.06
- 合作：彭博 西南石油大学
- 提出了一种基于超声信号空间-时间域相关性编码的超声射频运动估计方法。利用超声信号时空相关性特征，对信号编码从而减少弹性运动检测中的峰值跳变误差，以提高超声弹性成像中位移图像的检测质量。

### 慢性失眠障碍伴发抑郁的个体化脑网络机制及早期预测研究 2020.01-至今
- 合作：龚亮 成都市第二人民医院
- 慢性失眠障碍（Chronic Insomnia Disorder, CID）是最常见的一种睡眠障碍，临床症状表现为频繁入睡困难、维持睡眠困难或早醒等。目前，越来越多人被睡眠问题困扰，CID 患者数量逐年增加，临床研究表明，严重失眠更有可能诱发抑郁症。因此，及时评估诊断能有效避免其症状恶化。本研究旨在结合功能磁共振成像技术与计算机智能技术方法，进行 CID 患者智能识别方法研究，获取 CID 患者显著生物学标记且为临床诊断提供有效数据支撑。
  
## 智能油气工程方向
### 石油钻井工程异常工况智能检测方法研究 2024.01 - 
- 南充市-西南石油大学市校科技战略合作项目（主研）
- 本项目旨在建立一种有效的石油钻井工况异常识别方法，以实现钻井工况实时判断并进行异常识别，从而及时发现并处理现场潜在的安全异常问题。该项目结合人工智能技术、大数据分析和机器感知领域的研究成果，综合分析其特征和优缺点。该研究将从钻井工况状态判别与识别的理论问题分析和设计出发，构建基于大规模参数数据的石油钻井工况异常识别方法，准确判断钻井工况状态，以达到提高石油钻井作业的安全性、稳定性和可靠性，实现智能可持续的石油钻井工况异常识别系统。

### 云边端协同的石油钻井工程异常工况智能识别方法研究 2024.10 -
- 油气藏地质及开发工程国家重点实验室开放基金（主持）
- 本项目旨在创新构建云边端协同的石油钻井工况异常识别新方法，整合云端强大计算力、边缘端实时处理能力与终端数据采集，对大规模钻井工况数据进行快速分析，实现异常精准识别，以提升石油钻井作业安全性、效率，推动石油工程智能化进程。
  
# 学术论文
## 2025年度
-  Zhou, W., Luo, W., Gong, L.*, and Peng, B. (2025). Enhanced Early Diagnosis of Alzheimer’s Disease with HybridCA-Net: A Multimodal Fusion Approach. Expert Systems with Applications, 128580.(**SCI, IF: 7.5**)
- 王天飞，周文俊*，项圣，贺宇航，彭博. 2025. 基于异常特征对抗学习的工业图像异常检测方法. 浙江大学学报（工学版）.(**CSCD，录用**)
- 周文俊，杨新龄，左承林*，王一帆，彭博. 2025. MSFF-GAN:云雾环境下结冰风洞图像去雾模型. 中国图象图形学报，30(04):1100-1117 DOI:10.11834/jig.240343.(**CSCD, CCF 中文B类**)
-  W. Han, W. Zhou, L. Huang, J. Luo and B. Peng, "Tissue Clutter Filtering Methods in Ultrasound Localization Microscopy Based on Complex-valued Networks and Knowledge Distillation," in IEEE Transactions on Ultrasonics, Ferroelectrics, and Frequency Control (2025).(**SCI, IF: 3.0**)
-  B. Xiao, W. Zhou*, T. Wang, Q. Zhang and B. Peng. "Infrared Small Target Detection via Contrast-Enhanced Dual-Branch Network." Digital Signal Processing (2025): 104988.(**SCI, IF: 2.9**)
-  Tao Ding, Wenjun Zhou*, Bo Peng. (2025). Enhancing Time Series Classification with Explainable Time-Frequency Features Representation. In: Lin, Z., et al. Pattern Recognition and Computer Vision. PRCV 2024. Lecture Notes in Computer Science, vol 15031. Springer, Singapore.(**EI, CCF C类**)
     
## 2024年度
-  Peng, B., Lin, W., Zhou, W. et al. Enhanced pediatric thyroid ultrasound image segmentation using DC-Contrast U-Net. BMC Med Imaging 24, 275 (2024).(**SCI, IF: 2.9**)
-  W. Zhou, Y. Liu, N. Wang, Y. Wang and B. Peng. "Dual-Branch Collaborative Siamese Network for Visual Tracking." Digital Signal Processing (2024): 104716.(**SCI, IF: 2.9**)
-  W. Zhou, Y. Liu, N. Wang, Y. Wang and B. Peng, "CoSiNet: Dual-Branch Collaborative Siamese Network for Visual Object Tracking," 2024 27th International Conference on Computer Supported Cooperative Work in Design (CSCWD), Tianjin, China, 2024, pp. 1675-1680.(**EI, CCF C类**)
-  Zhou, W., Liu, Y., Wang, N., Dong, L., and Bo, P. Efficient Siamese model for visual object tracking with attention-based fusion modules. SIViP (Signal, Image and Video Processing) (2024).(**SCI, IF: 2.0**)
-  Yuting Zhang, Wenjun Zhou, Lijie Huang, Yongjie Shao, Anguo Luo, Jianwen Luo* and Bo Peng*. "Efficient Microbubble Trajectory Tracking in Ultrasound Localization Microscopy Using a Gated Recurrent Unit-Based Multitasking Temporal Neural Network," in IEEE Transactions on Ultrasonics, Ferroelectrics, and Frequency Control (2024).(**SCI, IF: 3.0**)
-  Zhou, W.; Wang, T.; Wu, X.; Zuo, C.; Wang, Y.; Zhang, Q.; Peng, B. Salient Object Detection via Fusion of Multi-Visual Perception. Appl. Sci. 2024, 14, 3433.(**SCI, IF: 2.5**)
-  WenJun Zhou, Nan Wang, Dong Liang and Bo Peng. (2024) "Precision in Visual Object Tracking: A Dual-Branch Approach", Journal of Electronic Imaging. 33, 2, 023023.(**SCI**)

## 2023年度
- Zhou, W., Luo, W., Gong, L.*, Ou, J., Peng, B. (2024). Spatial-Temporal Graph Convolutional Network for Insomnia Classification via Brain Functional Connectivity Imaging of rs-fMRI. Pattern Recognition and Computer Vision. PRCV 2023. Lecture Notes in Computer Science, vol 14437. Springer, Singapore.(**EI, CCF C类**)
- Wang, Y., Wang, J., Huang, X., Zhou, T., Zhou, W., & Peng, B. (2023, October). Shadow Detection of Remote Sensing Image by Fusion of Involution and Shunted Transformer. In Chinese Conference on Pattern Recognition and Computer Vision (PRCV) (pp. 330-342). Singapore: Springer Nature Singapore.(**EI, CCF C类**)
- Zhou, W.*, Deng, Y., Peng, B., Xiang, S., & Kaneko, S. I. (2023). Co-occurrence spatial-temporal model for adaptive background initialization in high-dynamic complex scenes. Signal Processing: Image Communication, 119, 117056.(**SCI, IF: 3.5**)
-  WenJun Zhou*, Tianfei Wang, Yuhang He, Shenghua Xie, Anguo Luo, Bo Peng and Lixue Yin. "Contrast U-Net driven by sufficient texture extraction for carotid plaque detection", Mathematical Biosciences and Engineering, 2023, 20(9): 15623-15640.(**SCI**)
- W. Zhou*, N. Wang, D. Liang and B. Peng, "Visual Tracking Based on Efficient Dual-Branch Siamese Network," 2023 IEEE International Conference on Systems, Man, and Cybernetics (SMC), Honolulu, Oahu, HI, USA, 2023, pp. 3677-3682.(**EI, CCF C类**)
- Y. Wang, T. Zhou, P. Yang, W. Zhou and B. Peng, "Neural Implicit 3D Reconstruction with Double Supervision," 2023 IEEE International Conference on Systems, Man, and Cybernetics (SMC), Honolulu, Oahu, HI, USA, 2023, pp. 3690-3695.(**EI, CCF C类**)
- Qiao, Y., Xu, H. M., Zhou, W. J.*, Peng, B., Hu, B., & Guo, X. (2023). A BiGRU joint optimized attention network for recognition of drilling conditions. Petroleum Science.(**SCI, IF: 5.6**)
- Zhou W, Yang X, Zuo C, Wang Y and Peng B, "Dense-HR-GAN: A High-Resolution GAN Model with Dense Connection for Image Dehazing in Icing Wind Tunnel Environment", Applied Sciences. 2023; 13(8):5171.(**SCI, IF: 2.5**)
- Yang X, Zhou W, Zuo C, et al. A high-resolution image dehazing GAN model in icing meteorological environment[C]//International Conference on Images, Signals, and Computing (ICISC 2023). SPIE, 2023, 12783: 25-34.(**EI**)

## 2021年度
- He Y, Xiang S, Zhou W*, et al. A Novel Contrast Operator for Robust Object Searching[C]//2021 17th International Conference on Computational Intelligence and Security (CIS). IEEE, 2021: 309-313.(**EI**)
- Yuheng Deng, Wenjun Zhou*, Bo Peng, Dong Liang, Shun'ichi Kaneko, "Robust Spatial-Temporal Correlation Model For Background Initialization In Severe Scene,"  ICASSP 2021 - 2021 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), 2021, pp. 2415-2419.(**EI, CCF B类**)

## 2020年度
- H. Asano, W. Zhou, H. Takauji and S. Kaneko, "Order-Dependent Convergent Search for Efficient Search of Feature Patterns," Journal of the Japan Society for Precision Engineering 86(2):171-176, 2020.(In Japanese)(**EI**)

## 2016-2019年度
- W. Zhou, S. Kaneko, Y. Satoh, M. Hashimoto, and D. Liang, "Foreground Detection based on Co-occurrence Background Model with Hypothesis on Degradation Modification in Dynamic Scenes," Signal Processing, 160, pp. 66-79, 2019.(**SCI, IF: 4.384**)
- W. Zhou, S. Kaneko, D. Liang, M. Hashimoto, and Y. Satoh, "Background subtraction based on co-occurrence pixel-block pairs for robust object detection in dynamic scenes," IIEEJ transactions on image electronics and visual computing, vol. 5, no. 2, pp. 146–159, 2017.
- W. Zhou, S. Kaneko, M. Hashimoto, Y. Satoh, and D. Liang, "Foreground Detection based on Co-occurrence Background Model with Hypothesis on Degradation Modification in Background Changes." 2018 12th France-Japan and 10th Europe-Asia Congress on Mechatronics. IEEE, 2018, pp. 77-82.(**EI**)
- W. Zhou, S. Kaneko, M. Hashimoto, Y. Satoh, and D. Liang,"A Co-occurrence Background Model with Hypothesis on Degradation Modification for Object Detection in Strong Background Changes," in Proceedings of the 24th International Conference on Pattern Recognition (ICPR) on 2018, pp. 1743-1748.(**EI, CCF C类**)
- W. Zhou, S. Kaneko, M. Hashimoto, Y. Satoh, and D. Liang, "Co-occurrence background model with hypothesis on degradation modification for robust object detection," in Proceedings of the 13th International Joint Conference on Computer Vision, Imaging and Computer Graphics Theory and Applications - Volume 5: VISAPP, 2018, pp. 266–273.(**EI**)
- W. Zhou, S. Kaneko, M. Hashimoto, Y. Satoh, and D. Liang, "Co-occurrence based Foreground Detection with Hypothesis on Degradation Modification in Severe Imaging Conditions," Precision Engineering Society Fall Conference 2018，September 5-7, 2018, Hakodate, Japan.
- W. Zhou, S. Kaneko, M. Hashimoto, Y. Satoh, and D. Liang, "Co-occurrence Background Model with Model Modification based on Hypothesis on Degradation for Robust Object Detection," in Proceeding of Vision Engineering Workshop 2017, December 7-8, 2017, Yokohama, Japan.
- W. Zhou, S. Kaneko, D. Liang, M. Hashimoto, and Y. Satoh, "Co-occurrence Pixel Block Pairs Background Subtraction for Object Detection by Introduction of Hypothesis-based Modification," in Proceeding of Vision Engineering Workshop 2016, December 8-9, 2016, Yokohama, Japan.
- W. Zhou, S. Kaneko, D. Liang, M. Hashimoto, and Y. Satoh, "Co-occurrence Pixel Block Pairs Background Subtraction for Object Detection in Dynamic Scene," in Proceeding of the International Symposium on Optomechatronic Technology 2016, November 7-9, 2016, Tokyo, Japan.

# 研究方向
- 智能视觉感知
- 医学影像智能分析
- 智能油气工程
  
# 其他
- SCI期刊 "Artificial Intelligence Review"，"Pattern Recognition"，"Computer Vision and Image Understandting"，"Digital Signal Processing"，"Displays"，"IEEE Transactions on Geoscience
and Remote Sensing"等期刊审稿人
- CCF YOCSEF成都20-21届通讯AC委员
- 四川省人工智能学会 理事
