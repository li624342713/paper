Convergence Technology Opportunity Discovery for  Firms Based on Technology Portfolio Using the  Stacked Denoising AutoEncoder (SDAE)  
IEEE TRANSACTIONS ON ENGINEERING MANAGEMENT, VOL. 71, 2024  

[pdf](./Kwon和Sohn - 2024 - Convergence Technology Opportunity Discovery for Firms Based on Technology Portfolio Using the Stack_副本.pdf)  

**意义：**  

**政策引导：**  

**研究问题：** 

现有技术机会发现（TOD）方法虽可支持融合技术识别[8]，但存在局限：

Kim等[9]基于专利引文网络与文本挖掘识别高关联融合领域，但未考虑企业个体技术组合等资源禀赋，亦缺乏对技术市场竞争力的评估；  
Park与Yoon[10]采用协同过滤（CF）方法分析企业技术组合，但因传统CF存在数据稀疏性问题，难以精准捕捉技术融合能力，推荐结果非最优。


**研究方法：**


![堆叠降噪自编码器( Sdae )技术组合.png](%E5%A0%86%E5%8F%A0%E9%99%8D%E5%99%AA%E8%87%AA%E7%BC%96%E7%A0%81%E5%99%A8%28%20Sdae%20%29%E6%8A%80%E6%9C%AF%E7%BB%84%E5%90%88.png)

**结论：** 

本文提出的CTOD框架在以下两方面实现创新：

**企业技术融合能力量化**

首次通过企业专利组合解析个体化技术融合能力。不同技术组合导致差异化的融合潜力与价值创造路径[11]，CTOD框架据此精准评估企业技术融合竞争力，助力企业将有限研发资源聚焦于高附加值领域。

**深度神经网络增强推荐鲁棒性**

引入基于堆叠去噪自编码器（SDAE）的深度协同过滤方法。相比传统CF，SDAE通过降噪技术有效处理大规模稀疏数据，提升技术组合潜在因子提取能力，解决数据稀疏性导致的推荐偏差问题。