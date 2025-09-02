---
permalink: /
title: "个人信息"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

贾广美，男，曲阜师范大学在读硕士研究生。研究兴趣主要集中在计算机视觉与医学图像分析领域，特别是智能诊断与辅助决策系统的开发与应用。当前的研究工作聚焦于眼科疾病的智能诊断，致力于通过融合空间域与频率域的特征信息，以增强模型在处理复杂医学影像时的诊断精度与鲁棒性。


教育经历
------
<table style="width: 100%; border-collapse: collapse; margin: 20px 0; font-size: inherit; border: none;">
  <tr>
    <td style="padding: 8px 15px; width: 25%; font-size: inherit; border: none;">2023.6 - 至今</td>
    <td style="padding: 8px 15px; width: 25%; font-size: inherit; border: none;">曲阜师范大学</td>
    <td style="padding: 8px 15px; width: 30%; font-size: inherit; border: none;">计算机技术</td>
    <td style="padding: 8px 15px; width: 20%; font-size: inherit; border: none;">硕士研究生</td>
  </tr>
  <tr>
    <td style="padding: 8px 15px; font-size: inherit; border: none;">2019.9 - 2023.6</td>
    <td style="padding: 8px 15px; font-size: inherit; border: none;">曲阜师范大学</td>
    <td style="padding: 8px 15px; font-size: inherit; border: none;">计算机科学与技术</td>
    <td style="padding: 8px 15px; font-size: inherit; border: none;">本科</td>
  </tr>
</table>


学术成果
------
**[1] Ma F, Jia G, Yan F, et al. XpertDx: Expert-level diabetic retinopathy lesion segmentation with cross-domain feature fusion[J]. Information Fusion, 2025: 103556.** 
（IF 15.5；中科院1区Top；第二作者；[论文链接](https://doi.org/10.1016/j.inffus.2025.103556)；DOI：10.1016/j.inffus.2025.103556）

摘要：视网膜病变标志着一系列破坏正常视网膜功能的病理学改变，因此其自动分割对于眼部疾病的及时检测至关重要。光学相干断层扫描血管成像（OCTA）通过分析不同深度的血流信号，能够无创地可视化视网膜的三维血管结构。然而，诸如微动脉瘤等早期微血管病变的血流变化极小，导致其在OCTA图像中十分微小且容易被忽略。此外，OCTA独特的成像过程会引入固有的条纹噪声。现有的基于深度学习的分割算法主要依赖单一网络的空间域信息，难以准确捕捉此类微小变化。为解决此问题，我们提出了一种多域融合网络（MFNet），该网络能够从OCTA图像中同时捕捉空间域和频率域特征以进行视网膜病变分割。我们首次设计了一种新颖的频率域编码器，它通过融合多级离散小波变换（DWT）来捕捉多尺度纹理特征，同时减少噪声。此外，我们设计了一个域融合模块（DFM），采用多级融合策略和门控机制来充分整合空间与频率特征，解决了现有方法中简单拼接或相加的不足。实验结果表明，MFNet在多个数据集上的表现均优于现有方法。例如，在2022年糖尿病视网膜病变分析挑战赛（DRAC2022）数据集上，MFNet对于新生血管、视网膜内微血管异常和无灌注区的Dice系数分别达到了54.48%和75.36%，交并比（IoU）分别为65.02%、37.44%和60.47%。我们的代码已在 https://github.com/GM-JIa/MFNet 上开源。

**[2] Jia G, Ma F, Li S, et al. Multi-domain fusion network: A novel approach to OCTA image segmentation in diabetic retinopathy[J]. Biomedical Signal Processing and Control, 2025, 109: 107945.**
（IF 4.9；中科院2区；第一作者；[论文链接](https://doi.org/10.1016/j.bspc.2025.107945)；DOI：10.1016/j.bspc.2025.107945）

摘要：糖尿病性视网膜病变是一种严重威胁视觉健康的微血管疾病，其自动分割对于早期诊断和干预至关重要。光学相干断层扫描血管成像（OCTA）是一种能够获取视网膜和脉络膜血管高分辨率结构的无创成像技术。然而，由于早期微小病变的血流变化极为微弱，这些细微的异常在成像中常常被忽略。此外，传统的分割方法主要依赖单一网络提供的单一视角信息，难以有效捕捉此类病变的复杂特征。为解决这些问题，我们提出了一种新颖的病变分割框架，用于OCTA图像中视网膜病变区域的精确分割。具体而言，我们设计了一个带有​​多级离散小波变换的频域编码器，以捕捉多尺度纹理特征。接着，采用自适应融合感知模块（AFPM）来促进空间域和频率域特征之间的深度交互与对齐。此外，我们开发了一个比较监控模块，在图像块（patch）级别嵌入了对比学习机制。我们还提出了一种包含多路径解码和一致性校正的一致性学习策略，以捕捉复杂病变区域的细节。在两个OCTA糖尿病视网膜病变数据集上的实验结果表明，我们的方法优于现有的先进方法。这进一步证实了对视网膜病变的分析可能为各种神经退行性疾病的研究提供新的方案。


荣誉与奖项
------
- 2024-2025 曲阜师范大学研究生一等学业奖学金
- 2023-2024 曲阜师范大学研究生二等学业奖学金
- 2019-2023 第十三届蓝桥杯全国软件和信息技术专业人才大赛山东赛区三等奖、全国大学生数学建模竞赛山东赛区二等奖、全国高校计算机能力挑战赛华东赛区三等奖、山东省大学生电子与信息技术应用大赛二等奖。


实习经历
------
<table style="width: 100%; border-collapse: collapse; margin: 20px 0; font-size: inherit; border: none;">
  <tr>
    <td style="padding: 8px 15px; width: 30%; font-size: inherit; border: none;">2024.1-2024.8</td>
    <td style="padding: 8px 15px; width: 30%; font-size: inherit; border: none;">数字日照有限公司</td>
    <td style="padding: 8px 15px; width: 40%; font-size: inherit; border: none;">研发工程师实习生</td>
  </tr>
</table>

参与“基于大模型智能化应用的企业AI助手”项目的市场调研、系统开发、优化和部署的全过程，研究大语言模型在办公智能化中的应用，被评为优秀实习生。


技能和爱好
------
- 专业技能：熟练使用Python及Pytorch框架、掌握神经网络等机器学习理论基础。
- 爱好：旅游、历史、阅读、乒乓球。
- 自我评价：乐观积极、勤奋务实、有足够的抗压能力、优秀的团队协同能力、强烈的进取心。
