# LLM Continual Learning Papers 

<div align="center">

[![LICENSE](https://img.shields.io/github/license/wanglingxiang0717/LLM_Continual_Learning_Papers)](https://github.com/wanglingxiang0717/LLM_Continual_Learning_Papers/blob/main/LICENSE)
[![commit](https://img.shields.io/github/last-commit/wanglingxiang0717/LLM_Continual_Learning_Papers?color=blue)](https://github.com/wanglingxiang0717/LLM_Continual_Learning_Papers/commits/main)
[![PR](https://img.shields.io/badge/PRs-Welcome-red)](https://github.com/wanglingxiang0717/LLM_Continual_Learning_Papers/pulls)
[![GitHub Repo stars](https://img.shields.io/github/stars/wanglingxiang0717/LLM_Continual_Learning_Papers)](https://github.com/wanglingxiang0717/LLM_Continual_Learning_Papers)
<!-- ![license](https://img.shields.io/bower/l/bootstrap?style=plastic) -->

</div>

This repo compiles and organizes the latest papers from major conferences on continual learning (multi-task learning), especially in the context of large language models. It includes works on continued pre-training(CP), continued fine-tuning(CFT), and other studies on learning (training), knowledge, and memory in large models that may inspire research in continual learning for LLMs. It also lists related work on knowledge editing as extensions.

Although continued pre-training and continued fine-tuning already have clear definitions in existing literature, the scope here is not limited to those definitions—any work aiming at multi-capability and multi-domain knowledge is included.


**Thanks for all the great contributors!**

## Contents

- [LLM Continual Learning Papers](#LLM-Continual-Learning-Papers)
  - [1. Continued Pre-training (CP)](#1-Continued-Pre-training-(CP))
    - [ICLR](#ICLR)
    - [ICML](#ICML)
    - [ACL](#ACL)
  - [2. Continued Fine-tuning (CFT)](#2-Continued-Fine-tuning-(CFT))
    - [ICLR](#ICLR-1)
    - [ICML](#ICML-1)
    - [ACL](#ACL-1)
  - [3. Learning, Knowledge, and Memory (L,K,M)](#3-Learning-Knowledge-and-Memory-(L,K,M))
    - [ICLR](#ICLR-2)
    - [ICML](#ICML-2)
    - [ACL](#ACL-2)
  - [4. Knowledge Editing (KE)](#4-Knowledge-Editing-(KE))
    - [ICLR](#ICLR-3)
    - [ICML](#ICML-3)
    - [ACL](#ACL-3)

## 1. Continued Pre-training (CP)
### ICLR 
- 2025
  - [**Synthetic continued pretraining**](https://iclr.cc/virtual/2025/poster/31270) *Zitong Yang, Neil Band, Shuangping Li, Emmanuel Candes, Tatsunori Hashimoto.* ICLR'25
  - [**Theory on Mixture-of-Experts in Continual Learning**](https://iclr.cc/virtual/2025/poster/30816) *Hongbo Li, Sen Lin, Lingjie Duan, Yingbin Liang, Ness Shroff.* ICLR'25
  - [**LOIRE: LifelOng learning on Incremental data via pre-trained language model gRowth Efficiently**](https://iclr.cc/virtual/2025/poster/30366) *Xue Han, Yitong Wang, Junlan Feng, wenchun.gao, Qian Hu, Chao Deng.* ICLR'25
  - [**Self-Normalized Resets for Plasticity in Continual Learning**](https://iclr.cc/virtual/2025/poster/30297) *Vivek Farias, Adam Jozefiak.* ICLR'25
  - [**Learning Continually by Spectral Regularization**](https://iclr.cc/virtual/2025/poster/30217) *Alex Lewandowski, Michał Bortkiewicz, Saurabh Kumar, Andras Gyorgy, Dale Schuurmans, Mateusz Ostaszewski, Marlos C. Machado.* ICLR'25
  - [**Budgeted Online Continual Learning by Adaptive Layer Freezing and Frequency-based Sampling**](https://iclr.cc/virtual/2025/poster/28988) *Minhyuk Seo, Hyunseo Koh, Jonghyun Choi.* ICLR'25
  - [**Exploring The Forgetting in Adversarial Training: A Novel Method for Enhancing Robustness**](https://iclr.cc/virtual/2025/poster/28861) *Xianglu Wang, Hu Ding.* ICLR'25


### ICML
- 2025
  - [**Optimal Task Order for Continual Learning of Multiple Tasks**](https://icml.cc/virtual/2025/poster/46654) *Ziyan Li, Naoki Hiratani.* ICML'25
  - [**Learning without Isolation: Pathway Protection for Continual Learning**](https://icml.cc/virtual/2025/poster/46536) *Zhikang Chen, Abudukelimu Wuerkaixi, Sen Cui, Haoxuan Li, Ding Li, Jingfeng Zhang, Bo Han, Gang Niu, Houfang Liu, Yi Yang, Sifan YANG, Changshui Zhang, Tianling Ren.* ICML'25
  - [**Understanding the Forgetting of (Replay-based) Continual Learning via Feature Learning: Angle Matters**](https://icml.cc/virtual/2025/poster/46371) *Hongyi Wan, Shiyuan Ren, Wei Huang, Miao Zhang, Xiang Deng, Yixin Bao, Liqiang Nie.* ICML'25
  - [**Exploiting Presentative Feature Distributions for Parameter-Efficient Continual Learning of Large Language Models**](https://icml.cc/virtual/2025/poster/46354) *Xin Cheng, Jiabo Ye, Haiyang Xu, Ming Yan, Ji Zhang, Feng Liu, Fei Huang, Lei Feng.* ICML'25
  - [**FedSSI: Rehearsal-Free Continual Federated Learning with Synergistic Synaptic Intelligence**](https://icml.cc/virtual/2025/poster/46211) *Yichen Li, Yuying Wang, Haozhao Wang, Yining Qi, Tianzhe Xiao, Ruixuan Li.* ICML'25
  - [**A Selective Learning Method for Temporal Graph Continual Learning**](https://icml.cc/virtual/2025/poster/46118) *Hanmo Liu, Shimin Di, Haoyang LI, Xun Jian, Yue Wang, Lei Chen.* ICML'25
  - [**Probabilistic Group Mask Guided Discrete Optimization for Incremental Learning**](https://icml.cc/virtual/2025/poster/45798) *Fengqiang Wan, Yang Yang.* ICML'25
  - [**Learning Dynamics in Continual Pre-Training for Large Language Models**](https://icml.cc/virtual/2025/poster/45051) *Xingjin Wang, Howe Tissue, Lu Wang, Linjing Li, Daniel Zeng.* ICML'25
  - [**Programming Every Example: Lifting Pre-training Data Quality Like Experts at Scale**](https://icml.cc/virtual/2025/poster/44780) *Fan Zhou, Zengzhi Wang, Qian Liu, Junlong Li, Pengfei Liu.* ICML'25
  - [**BECAME: Bayesian Continual Learning with Adaptive Model Merging**](https://icml.cc/virtual/2025/poster/44474) *Mei Li, Yuxiang Lu, Qinyan Dai, Suizhi Huang, Yue Ding, Hongtao Lu.* ICML'25
  - [**ZeroFlow: Overcoming Catastrophic Forgetting is Easier than You Think**](https://openreview.net/forum?id=iPDw3O6u3T) *Tao Feng, Wei Li, Didi Zhu, Hangjie Yuan, Wendi Zheng, Dan Zhang, Jie Tang.* ICML'25
  - [**Unlocking the Power of Rehearsal in Continual Learning: A Theoretical Perspective**](https://icml.cc/virtual/2025/poster/44025) *Junze Deng, Qinhang Wu, Peizhong Ju, Sen Lin, Yingbin LIANG, Ness Shroff.* ICML'25
  - [**Improved Algorithm for Deep Active Learning under Imbalance via Optimal Separation**](https://icml.cc/virtual/2025/poster/43870) *Shyam Nuggehalli, Jifan Zhang, Lalit Jain, Robert Nowak.* ICML'25
  - [**Memorization Sinks: Isolating Memorization during LLM Training**](https://icml.cc/virtual/2025/poster/43838) *Gaurav Ghosal, Pratyush Maini, Aditi Raghunathan.* ICML'25


### ACL
- 2025
  - [**Fusing Highly Specialized Language Models for Comprehensive Expertise**](https://aclanthology.org/2025.acl-long.42/) *Ning Ding, Yulin Chen, Ganqu Cui, Xingtai Lv, Weilin Zhao, Kaiyan Zhang, Ruobing Xie, Bowen Zhou, Zhiyuan Liu, Maosong Sun.* ACL'25
  - [**LangSAMP: Language-Script Aware Multilingual Pretraining**](https://aclanthology.org/2025.acl-long.88/) *Yihong Liu, Haotian Ye, Chunlan Ma, Mingyang Wang, Hinrich Schuetze.* ACL'25
  - [**Second Language (Arabic) Acquisition of LLMs via Progressive Vocabulary Expansion**](https://aclanthology.org/2025.acl-long.100/) *Jianqing Zhu, Huang Huang, Zhihang Lin, Juhao Liang, Zhengyang Tang, Khalid Almubarak, Mosen Alharthi, Bang An, Juncai He, Xiangbo Wu, Fei Yu, Junying Chen, Ma Zhuoheng, Yuhao Du, He Zhang, Saied Alshahrani, Emad A. Alghamdi, Lian Zhang, Ruoyu Sun, Haizhou Li, Benyou Wang, Jinchao Xu.* ACL'25
  - [**Towards Effective and Efficient Continual Pre-training of Large Language Models**](https://aclanthology.org/2025.acl-long.289/) *Jie Chen, Zhipeng Chen, Jiapeng Wang, Kun Zhou, Yutao Zhu, Jinhao Jiang, Yingqian Min, Xin Zhao, Zhicheng Dou, Jiaxin Mao, Yankai Lin, Ruihua Song, Jun Xu, Xu Chen, Rui Yan, Zhewei Wei, Di Hu, Wenbing Huang, Ji-Rong Wen.* ACL'25
  - [**A Generative Adaptive Replay Continual Learning Model for Temporal Knowledge Graph Reasoning**](https://aclanthology.org/2025.acl-long.537/) *Zhiyu Zhang, Wei Chen, Youfang Lin, Huaiyu Wan.* ACL'25
  - [**Acquisition and Application of Novel Knowledge in Large Language Models**](https://aclanthology.org/2025.acl-long.898/) *Ziyu Shang, Jianghan Liu, Zhizhao Luo, Peng Wang, Wenjun Ke, Jiajun Liu, Zijie Xu, Guozheng Li.* ACL'25
  - [**Velocitune: A Velocity-based Dynamic Domain Reweighting Method for Continual Pre-training**](https://aclanthology.org/2025.acl-long.813/) *Zheheng Luo, Xin Zhang, Xiao Liu, Haoling Li, Yeyun Gong, Qi Chen, Peng Cheng.* ACL'25
  - [**Recurrent Knowledge Identification and Fusion for Language Model Continual Learning**](https://aclanthology.org/2025.acl-long.1328/) *Yujie Feng, Xujia Wang, Zexin Lu, Shenghong Fu, Guangyuan Shi, Yongxin Xu, Yasha Wang, Philip S. Yu, Xu Chu, Xiao-Ming Wu.* ACL'25
  - [**Hierarchical-Task-Aware Multi-modal Mixture of Incremental LoRA Experts for Embodied Continual Learning**](https://aclanthology.org/2025.acl-long.1379/) *Ziqi Jia, Anmin Wang, Xiaoyang Qu, Xiaowen Yang, Jianzong Wang.* ACL'25
  - [**Structure-aware Domain Knowledge Injection for Large Language Models**](https://aclanthology.org/2025.acl-long.1425/) *Kai Liu, Ze Chen, Zhihang Fu, Wei Zhang, Rongxin Jiang, Fan Zhou, Yaowu Chen, Yue Wu, Jieping Ye.* ACL'25
  - [**Emergent Abilities of Large Language Models under Continued Pre-training for Language Adaptation**](https://aclanthology.org/2025.acl-long.1547/) *Ahmed Elhady, Eneko Agirre, Mikel Artetxe.* ACL'25
  - [**Just Go Parallel: Improving the Multilingual Capabilities of Large Language Models**](https://aclanthology.org/2025.acl-long.1602/) *Muhammad Reza Qorib, Junyi Li, Hwee Tou Ng.* ACL'25


## 2. Continued Fine-tuning (CFT)
### ICLR 
- 2025
  - [**Mufu: Multilingual Fused Learning for Low-Resource Translation with LLM**](https://iclr.cc/virtual/2025/poster/31245) *Zheng Wei Lim, Nitish Gupta, Honglin Yu, Trevor Cohn.* ICLR'25
  - [**Test-Time Ensemble via Linear Mode Connectivity: A Path to Better Adaptation**](https://iclr.cc/virtual/2025/poster/30982) *Byungjai Kim, Chanho Ahn, Wissam Baddar, Kikyung Kim, HUIJIN LEE, Saehyun Ahn, Seungju Han, Sungjoo Suh, Eunho Yang.* ICLR'25
  - [**COME: Test-time Adaption by Conservatively Minimizing Entropy**](https://iclr.cc/virtual/2025/poster/30977) *Qingyang Zhang, Yatao Bian, Xinke Kong, Peilin Zhao, Changqing Zhang.* ICLR'25
  - [**MTSAM: Multi-Task Fine-Tuning for Segment Anything Model**](https://iclr.cc/virtual/2025/poster/30892) *Xiaochuan Li, Zichun Yu, Chenyan Xiong.* ICLR'25
  - [**STAR: Stability-Inducing Weight Perturbation for Continual Learning**](https://iclr.cc/virtual/2025/poster/30891) *Masih Eskandar, Tooba Imtiaz, Davin Hill, Zifeng Wang, Jennifer Dy.* ICLR'25
  - [**LoRA-X: Bridging Foundation Models with Training-Free Cross-Model Adaptation**](https://iclr.cc/virtual/2025/poster/30873) *Farzad Farhadzadeh, Debasmit Das, Shubhankar Borse, Fatih Porikli.* ICLR'25
  - [**LiFT: Learning to Fine-Tune via Bayesian Parameter Efficient Meta Fine-Tuning**](https://iclr.cc/virtual/2025/poster/30801) *Minyoung Kim, Timothy Hospedales.* ICLR'25
  - [**Boosting Multiple Views for pretrained-based Continual Learning**](https://iclr.cc/virtual/2025/poster/30627) *Quyen Tran, Tung Lam Tran, Khanh Doan, Toan Tran, Dinh Phung, Khoat Than, Trung Le.* ICLR'25
  - [**Continual Slow-and-Fast Adaptation of Latent Neural Dynamics (CoSFan): Meta-Learning What-How & When to Adapt**](https://iclr.cc/virtual/2025/poster/30443) *Ryan Missel, Linwei Wang.* ICLR'25
  - [**Selective Task Group Updates for Multi-Task Optimization**](https://iclr.cc/virtual/2025/poster/30394) *Wooseong Jeong, Kuk-Jin Yoon.* ICLR'25
  - [**Skill Expansion and Composition in Parameter Space**](https://iclr.cc/virtual/2025/poster/30286) *Tenglong Liu, Jianxiong Li, Yinan Zheng, Haoyi Niu, Yixing Lan, Xin Xu, Xianyuan Zhan.* ICLR'25
  - [**Prevalence of Negative Transfer in Continual Reinforcement Learning: Analyses and a Simple Baseline**](https://iclr.cc/virtual/2025/poster/30073) *Hongjoon Ahn, Jinu Hyeon, Youngmin Oh, Bosun Hwang, Taesup Moon.* ICLR'25
  - [**Efficiently Learning at Test-Time: Active Fine-Tuning of LLMs**](https://iclr.cc/virtual/2025/poster/29875) *Jonas Hübotter, Sascha Bongni, Ido Hakimi, Andreas Krause.* ICLR'25
  - [**LiNeS: Post-training Layer Scaling Prevents Forgetting and Enhances Model Merging**](https://iclr.cc/virtual/2025/poster/30130) *Ke Wang, Nikos Dimitriadis, Alessandro Favero, Guillermo Ortiz-Jimenez, François Fleuret, Pascal Frossard.* ICLR'25
  - [**Efficient Model Editing with Task-Localized Sparse Fine-tuning**](https://iclr.cc/virtual/2025/poster/29556) *Leonardo Iurada, Marco Ciccone, Tatiana Tommasi.* ICLR'25
  - [**Q-Adapter: Customizing Pre-trained LLMs to New Preferences with Forgetting Mitigation**](https://iclr.cc/virtual/2025/poster/29368) *Yi-Chen Li, Fuxiang Zhang, Wenjie Qiu, Lei Yuan, Chengxing Jia, Zongzhang Zhang, Yang Yu, Bo An.* ICLR'25
  - [**Federated Few-Shot Class-Incremental Learning**](https://iclr.cc/virtual/2025/poster/29204) *Muhammad Anwar Masum, Mahardhika Pratama, Lin Liu, H Habibullah, Ryszard Kowalczyk.* ICLR'25
  - [**Adapting Multi-modal Large Language Model to Concept Drift From Pre-training Onwards**](https://iclr.cc/virtual/2025/poster/29128) *Xiaoyu Yang, Jie Lu, En Yu.* ICLR'25
  - [**Unlocking the Power of Function Vectors for Characterizing and Mitigating Catastrophic Forgetting in Continual Instruction Tuning**](https://iclr.cc/virtual/2025/poster/28810) *Gangwei Jiang, caigao jiang, Zhaoyi Li, Siqiao Xue, JUN ZHOU, Linqi Song, Defu Lian, Ying Wei.* ICLR'25
  - [**Coreset Selection via Reducible Loss in Continual Learning**](https://iclr.cc/virtual/2025/poster/28476) *Ruilin Tong, Yuhang Liu, Javen Qinfeng Shi, Dong Gong.* ICLR'25
  - [**Active Learning for Continual Learning: Keeping the Past Alive in the Present**](https://iclr.cc/virtual/2025/poster/28450) *Jaehyun Park, Dongmin Park, Jae-Gil Lee.* ICLR'25

### ICML
- 2025
  - [**Understanding Overadaptation in Supervised Fine-Tuning: The Role of Ensemble Methods**](https://icml.cc/virtual/2025/poster/46611) *Yifan HAO, xingyuan pan, Hanning Zhang, Chenlu Ye, Rui Pan, Tong Zhang.* ICML'25
  - [**Upweighting Easy Samples in Fine-Tuning Mitigates Forgetting**](https://openreview.net/forum?id=13HPTmZKbM) *Sunny Sanyal, Hayden Prairie, Rudrajit Das, Ali Kavis, Sujay Sanghavi.* ICML'25
  - [**Controlling Neural Collapse Enhances Out-of-Distribution Detection and Transfer Learning**](https://icml.cc/virtual/2025/poster/46287) *Md Yousuf Harun, Jhair Gallardo, Christopher Kanan.* ICML'25
  - [**Test-Time Adaptation with Binary Feedback**](https://icml.cc/virtual/2025/poster/46190) *Taeckyung Lee, Sorn Chottananurak, Junsu Kim, Jinwoo Shin, Taesik Gong, Sung-Ju Lee.* ICML'25
  - [**DPCore: Dynamic Prompt Coreset for Continual Test-Time Adaptation**](https://icml.cc/virtual/2025/poster/46187) *Yunbei Zhang, Akshay Mehra, Shuaicheng Niu, Jihun Hamm.* ICML'25
  - [**Knowledge Retention in Continual Model-Based Reinforcement Learning**](https://icml.cc/virtual/2025/poster/45991) *Haotian Fu, Yixiang Sun, Michael L. Littman, George Konidaris.* ICML'25
  - [**Benign Samples Matter! Fine-tuning On Outlier Benign Samples Severely Breaks Safety**](https://icml.cc/virtual/2025/poster/45842) *Zihan Guan, Mengxuan Hu, Ronghang Zhu, Sheng Li, Anil Vullikanti.* ICML'25
  - [**From RAG to Memory: Non-Parametric Continual Learning for Large Language Models**](https://openreview.net/forum?id=LWH8yn4HS2) *Bernal Jiménez Gutiérrez, Yiheng Shu, Weijian Qi, Sizhe Zhou, Yu Su.* ICML'25
  - [**Avoiding Catastrophe in Online Learning by Asking for Help**](https://icml.cc/virtual/2025/poster/45563) *Benjamin Plaut, Hanlin Zhu, Stuart Russell
.* ICML'25
  - [**CALM: Consensus-Aware Localized Merging for Multi-Task Learning**](https://icml.cc/virtual/2025/poster/45426) *Kunda Yan, Min Zhang, Sen Cui, Qu Zikun, Bo Jiang, Feng Liu, Changshui Zhang.* ICML'25
  - [**Safe Delta: Consistently Preserving Safety when Fine-Tuning LLMs on Diverse Datasets**](https://icml.cc/virtual/2025/poster/45317) *Ning LU, Shengcai Liu, Jiahao Wu, Weiyu CHEN, Zhirui Zhang, Yew Soon ONG, Qi Wang, Ke Tang.* ICML'25
  - [**Boosting Multi-Domain Fine-Tuning of Large Language Models through Evolving Interactions between Samples**](https://icml.cc/virtual/2025/poster/45212) *Xize Liang, Lin Yang, Jie Wang, Yiyang Lu, Runyu Wu, Hanzhu Chen, Jianye Hao.* ICML'25
  - [**Online Learning in the Random-Order Model**](https://icml.cc/virtual/2025/poster/45025) *Martino Bernasconi, Andrea Celli, Riccardo Colini Baldeschi, Federico Fusco, Stefano Leonardi, Matteo Russo.* ICML'25
  - [**Overtrained Language Models Are Harder to Fine-Tune**](https://icml.cc/virtual/2025/poster/44907) *Jacob Mitchell Springer, Sachin Goyal, Kaiyue Wen, Tanishq Kumar, Xiang Yue, Sadhika Malladi, Graham Neubig, Aditi Raghunathan.* ICML'25
  - [**Addressing Imbalanced Domain-Incremental Learning through Dual-Balance Collaborative Experts**](https://icml.cc/virtual/2025/poster/44608) *Lan Li, Da-Wei Zhou, Han-Jia Ye, De-Chuan Zhan.* ICML'25
  - [**Online Curvature-Aware Replay: Leveraging 2nd Order Information for Online Continual Learning**](https://icml.cc/virtual/2025/poster/44567) *Edoardo Urettini, Antonio Carta.* ICML'25
  - [**Autoencoder-Based Hybrid Replay for Class-Incremental Learning**](https://icml.cc/virtual/2025/poster/44510) *Milad Khademi Nori, Il-Min Kim, Guanghui Wang.* ICML'25
  - [**Test-Time Learning for Large Language Models**](https://icml.cc/virtual/2025/poster/44367) *Jinwu Hu, Zitian Zhang, Guohao Chen, Xutao Wen, Chao Shuai, Wei Luo, Bin Xiao, Yuanqing Li, Mingkui Tan.* ICML'25
  - [**Tensor Decomposition Based Memory-Efficient Incremental Learning**](https://icml.cc/virtual/2025/poster/44196) *Yuhang Li, Guoxu Zhou, Zhenhao Huang, Xinqi Chen, Yuning Qiu, Qibin Zhao.* ICML'25


### ACL
- 2025
  - [**ATLANTIS: Weak-to-Strong Learning via Importance Sampling**](https://aclanthology.org/2025.acl-long.52/) *Yi Liu, Guoyin Wang, Shicheng Li, Feifan Song, Xu Sun.* ACL'25
  - [**Steering into New Embedding Spaces: Analyzing Cross-Lingual Alignment Induced by Model Interventions in Multilingual Language Models**](https://aclanthology.org/2025.acl-long.118/) *Anirudh Sundar, Sinead Williamson, Katherine Metcalf, Barry-John Theobald, Skyler Seto, Masha Fedzechkina.* ACL'25
  - [**TokAlign: Efficient Vocabulary Adaptation via Token Alignment**](https://aclanthology.org/2025.acl-long.207/) *Chong Li, Jiajun Zhang, Chengqing Zong.* ACL'25
  - [**Bridging the Language Gaps in Large Language Models with Inference-Time Cross-Lingual Intervention**](https://aclanthology.org/2025.acl-long.270/) *Weixuan Wang, Minghao Wu, Barry Haddow, Alexandra Birch.* ACL'25
  - [**HFT: Half Fine-Tuning for Large Language Models**](https://aclanthology.org/2025.acl-long.626/) *Tingfeng Hui, Zhenyu Zhang, Shuohuan Wang, Weiran Xu, Yu Sun, Hua Wu.* ACL'25
  - [**Interactive Evolution: A Neural-Symbolic Self-Training Framework For Large Language Models**](https://aclanthology.org/2025.acl-long.635/) *Fangzhi Xu, Qiushi Sun, Kanzhi Cheng, Jun Liu, Yu Qiao, Zhiyong Wu.* ACL'25
  - [**DoMIX: An Efficient Framework for Exploiting Domain Knowledge in Fine-Tuning**](https://aclanthology.org/2025.acl-long.710/) *Dohoon Kim, Donghun Kang, Taesup Moon.* ACL'25
  - [**Continual Gradient Low-Rank Projection Fine-Tuning for LLMs**](https://aclanthology.org/2025.acl-long.721/) *Chenxu Wang, Yilin Lyu, Zicheng Sun, Liping Jing.* ACL'25
  - [**Cross-Lingual Optimization for Language Transfer in Large Language Models**](https://aclanthology.org/2025.acl-long.734/) *Jungseob Lee, Seongtae Hong, Hyeonseok Moon, Heuiseok Lim.* ACL'25
  - [**CC-Tuning: A Cross-Lingual Connection Mechanism for Improving Joint Multilingual Supervised Fine-Tuning**](https://aclanthology.org/2025.acl-long.933/) *Yangfan Ye, Xiaocheng Feng, Zekun Yuan, Xiachong Feng, Libo Qin, Lei Huang, Weitao Ma, Yichong Huang, Zhirui Zhang, Yunfei Lu, Xiaohui Yan, Duyu Tang, Dandan Tu, Bing Qin.* ACL'25
  - [**Middle-Layer Representation Alignment for Cross-Lingual Transfer in Fine-Tuned LLMs**](https://aclanthology.org/2025.acl-long.778/) *Danni Liu, Jan Niehues.* ACL'25
  - [**From English to Second Language Mastery: Enhancing LLMs with Cross-Lingual Continued Instruction Tuning**](https://aclanthology.org/2025.acl-long.1121/) *Linjuan Wu, Hao-Ran Wei, Baosong Yang, Weiming Lu.* ACL'25
  - [**Alleviating Hallucinations from Knowledge Misalignment in Large Language Models via Selective Abstention Learning**](https://aclanthology.org/2025.acl-long.1199/) *Lei Huang, Xiaocheng Feng, Weitao Ma, Yuchun Fan, Xiachong Feng, Yuxuan Gu, Yangfan Ye, Liang Zhao, Weihong Zhong, Baoxin Wang, Dayong Wu, Guoping Hu, Lingpeng Kong, Tong Xiao, Ting Liu, Bing Qin.* ACL'25
  - [**Efficient Ensemble for Fine-tuning Language Models on Multiple Datasets**](https://aclanthology.org/2025.acl-long.1231/) *Dongyue Li, Ziniu Zhang, Lu Wang, Hongyang R. Zhang.* ACL'25
  - [**Learn to Memorize: Scalable Continual Learning in Semiparametric Models with Mixture-of-Neighbors Induction Memory**](https://aclanthology.org/2025.acl-long.1385/) *Guangyue Peng, Tao Ge, Wen Luo, Wei Li, Houfeng Wang.* ACL'25
  - [**Training-free LLM Merging for Multi-task Learning**](https://aclanthology.org/2025.acl-long.1588/) *Zichuan Fu, Xian Wu, Yejing Wang, Wanyu Wang, Shanshan Ye, Hongzhi Yin, Yi Chang, Yefeng Zheng, Xiangyu Zhao.* ACL'25


## 3. Learning, Knowledge, and Memory (L,K,M)
### ICLR 
- 2025
  - [**Recite, Reconstruct, Recollect: Memorization in LMs as a Multifaceted Phenomenon**](https://iclr.cc/virtual/2025/poster/31090) *USVSN Sai Prashanth, Alvin Deng, Kyle O'Brien, Jyothir S V, Mohammad Aflah Khan, Jaydeep Borkar, Christopher Choquette-Choo, Jacob Fuehne, Stella R Biderman, Tracy Ke, Katherine Lee, Naomi Saphra.* ICLR'25
  - [**Small-to-Large Generalization: Training Data Influences Models Consistently Across Scale**](https://iclr.cc/virtual/2025/poster/30845) *Alaa Khaddaj, Logan Engstrom, Aleksander Madry.* ICLR'25
  - [**Global Convergence in Neural ODEs: Impact of Activation Functions**](https://openreview.net/forum?id=AoraWUmpLU) *Tianxiang Gao, Siyuan Sun, Hailiang Liu, Hongyang Gao.* ICLR'25
  - [**Cut Your Losses in Large-Vocabulary Language Models**](https://iclr.cc/virtual/2025/poster/30424) *Erik Wijmans, Brody Huval, Alexander Hertzberg, Vladlen Koltun, Philipp Krähenbühl.* ICLR'25
  - [**On Linear Representations and Pretraining Data Frequency in Language Models**](https://iclr.cc/virtual/2025/poster/30418) *Jack Merullo, Noah Smith, Sarah Wiegreffe, Yanai Elazar.* ICLR'25
  - [**In Search of Forgotten Domain Generalization**](https://iclr.cc/virtual/2025/poster/30328) *Prasanna Mayilvahanan, Roland Zimmermann, Thaddäus Wiedemer, Evgenia Rusak, Attila Juhos, Matthias Bethge, Wieland Brendel.* ICLR'25
  - [**Uncovering Latent Memories in Large Language Models**](https://iclr.cc/virtual/2025/poster/30058) *Sunny Duan, Mikail Khona, Abhiram Iyer, Rylan Schaeffer, Ila Fiete.* ICLR'25
  - [**Mitigating Memorization in Language Models**](https://iclr.cc/virtual/2025/poster/29943) *Mansi Sakarvadia, Aswathy Ajith, Arham Khan, Nathaniel Hudson, Caleb Geniesse, Kyle Chard, Yaoqing Yang, Ian Foster, Michael W Mahoney.* ICLR'25
  - [**How new data permeates LLM knowledge and how to dilute it**](https://iclr.cc/virtual/2025/poster/29889) *Chen Sun, Renat Aksitov, Andrey Zhmoginov, Nolan Miller, Max Vladymyrov, Ulrich Rueckert, Been Kim, Mark Sandler.* ICLR'25
  - [**From Attention to Activation: Unraveling the Enigmas of Large Language Models**](https://iclr.cc/virtual/2025/poster/30153) *Prannay Kaul, Chengcheng Ma, Ismail Elezi, Jiankang Deng.* ICLR'25
  - [**Learning Dynamics of Deep Matrix Factorization Beyond the Edge of Stability**](https://iclr.cc/virtual/2025/poster/30132) *Avrajit Ghosh, Soo Min Kwon, Rongrong Wang, Saiprasad Ravishankar, Qing Qu.* ICLR'25
  - [**Spurious Forgetting in Continual Learning of Language Models**](https://iclr.cc/virtual/2025/poster/29593) *Junhao Zheng, Xidi Cai, Shengjie Qiu, Qianli Ma.* ICLR'25
  - [**LeanAgent: Lifelong Learning for Formal Theorem Proving**](https://iclr.cc/virtual/2025/poster/29455) *Adarsh Kumarappan, Mohit Tiwari, Peiyang Song, Robert Joseph George, Chaowei Xiao, anima anandkumar.* ICLR'25
  - [**Privacy-Aware Lifelong Learning**](https://iclr.cc/virtual/2025/poster/29446) *Ozan Özdenizci, Elmar Rueckert, Robert Legenstein.* ICLR'25
  - [**Do I Know This Entity? Knowledge Awareness and Hallucinations in Language Models**](https://iclr.cc/virtual/2025/poster/29377) *Javier Ferrando, Oscar Obeso, Senthooran Rajamanoharan, Neel Nanda.* ICLR'25
  - [**Semantic Aware Representation Learning for Lifelong Learning**](https://iclr.cc/virtual/2025/poster/29333) *Fahad Sarfraz, Elahe Arani, Bahram Zonooz.* ICLR'25
  - [**Strong Model Collapse**](https://openreview.net/forum?id=et5l9qPUhm) *Elvis Dohmatob, Yunzhen Feng, Arjun Subramonian, Julia Kempe.* ICLR'25
  - [**Unlearning or Obfuscating? Jogging the Memory of Unlearned LLMs via Benign Relearning**](https://openreview.net/forum?id=fMNRYBvcQN) *Shengyuan Hu, Yiwei Fu, Steven Wu, Virginia Smith.* ICLR'25
  - [**Last Iterate Convergence of Incremental Methods as a Model of Forgetting**](https://iclr.cc/virtual/2025/poster/28465) *Xufeng Cai, Jelena Diakonikolas.* ICLR'25
  - [**Learning system dynamics without forgetting**](https://iclr.cc/virtual/2025/poster/28175) *Xikun ZHANG, Dongjin Song, Yushan Jiang, Yixin Chen, Dacheng Tao.* ICLR'25
  - [**Uncovering Overfitting in Large Language Model Editing**](https://iclr.cc/virtual/2025/poster/28074) *Mengqi Zhang, Xiaotian Ye, Qiang Liu, shu wu, Pengjie Ren, Zhumin Chen.* ICLR'25
  - [**Learning Dynamics of LLM Finetuning**](https://iclr.cc/virtual/2025/poster/28056) *YI REN, Danica Sutherland.* ICLR'25
  - [**Is Large-scale Pretraining the Secret to Good Domain Generalization?**](https://iclr.cc/virtual/2025/poster/27866) *Qintong Li, Jiahui Gao, Sheng Wang, Renjie Pi, Xueliang Zhao, Chuan Wu, Xin Jiang, Zhenguo Li, Lingpeng Kong.* ICLR'25

### ICML
- 2025
  - [**Positional Attention: Expressivity and Learnability of Algorithmic Computation**](https://icml.cc/virtual/2025/poster/46691) *Artur Back de Luca, George Giapitzakis, Shenghao Yang, Petar Veličković, Kimon Fountoulakis.* ICML'25
  - [**Towards Understanding Fine-Tuning Mechanisms of LLMs via Circuit Analysis**](https://icml.cc/virtual/2025/poster/46507) *Xu Wang, Yan Hu, Wenyu Du, Reynold Cheng, Benyou Wang, Difan Zou.* ICML'25
  - [**An Entropy-Based Model for Hierarchical Learning**](https://icml.cc/virtual/2025/poster/46717) *Amir R. Asadi.* ICML'25
  - [**Demystifying Singular Defects in Large Language Models**](https://icml.cc/virtual/2025/poster/46453) *Haoqi Wang, Tong Zhang, Mathieu Salzmann.* ICML'25
  - [**Knowledge Swapping via Learning and Unlearning**](https://openreview.net/forum?id=B3zlIHdnER) *Mingyu Xing, Lechao Cheng, Shengeng Tang, Yaxiong Wang, Zhun Zhong, Meng Wang.* ICML'25
  - [**Spurious Correlations in High Dimensional Regression: The Roles of Regularization, Simplicity Bias and Over-Parameterization**](https://icml.cc/virtual/2025/poster/46042) *Simone Bombari, Marco Mondelli.* ICML'25
  - [**System-Aware Unlearning Algorithms: Use Lesser, Forget Faster**](https://icml.cc/virtual/2025/poster/45985) *Linda Lu, Ayush Sekhari, Karthik Sridharan.* ICML'25
  - [**GRU: Mitigating the Trade-off between Unlearning and Retention for LLMs**](https://icml.cc/virtual/2025/poster/45967) *Yue Wang, Qizhou Wang, Feng Liu, Wei Huang, Yali Du, Xiaojiang Du, Bo Han.* ICML'25
  - [**Vulnerability-Aware Alignment: Mitigating Uneven Forgetting in Harmful Fine-Tuning**](https://icml.cc/virtual/2025/poster/45951) *Liang CHEN, Xueting Han, Li Shen, Jing Bai, Kam-Fai Wong.* ICML'25
  - [**Understanding and Mitigating Memorization in Generative Models via Sharpness of Probability Landscapes**](https://openreview.net/forum?id=EW2JR5aVLm) *Dongjae Jeon, Dueun Kim, Albert No.* ICML'25
  - [**Activation Space Interventions Can Be Transferred Between Large Language Models**](https://icml.cc/virtual/2025/poster/45778) *Narmeen Oozeer, Dhruv Nathawani, Nirmalendu Prakash, Michael Lan, Abir HARRASSE, Amirali Abdullah.* ICML'25
  - [**Are Large Brainwave Foundation Models Capable Yet ? Insights from Fine-Tuning**](https://icml.cc/virtual/2025/poster/45713) *Na Lee, Konstantinos Barmpas, Yannis Panagakis, Dimitrios Adamos, Nikolaos Laskaris, Stefanos Zafeiriou.* ICML'25
  - [**Continual Generalized Category Discovery: Learning and Forgetting from a Bayesian Perspective**](https://icml.cc/virtual/2025/poster/45679) *Hao Dai, Jagmohan Chauhan.* ICML'25
  - [**Towards Memorization Estimation: Fast, Formal and Free**](https://icml.cc/virtual/2025/poster/45633) *Deepak Ravikumar, Efstathia Soufleri, Abolfazl Hashemi, Kaushik Roy.* ICML'25
  - [**LoRA-One: One-Step Full Gradient Could Suffice for Fine-Tuning Large Language Models, Provably and Efficiently**](https://openreview.net/forum?id=KwIlvmLDLm) *Yuanhe Zhang, Fanghui Liu, Yudong Chen.* ICML'25
  - [**Measuring Representational Shifts in Continual Learning: A Linear Transformation Perspective**](https://icml.cc/virtual/2025/poster/45616) *Joonkyu Kim, Yejin Kim, Jy-yong Sohn.* ICML'25
  - [**Demystifying Catastrophic Forgetting in Two-Stage Incremental Object Detector**](https://icml.cc/virtual/2025/poster/45396) *Qirui Wu, Shizhou Zhang, De Cheng, Yinghui Xing, di xu, Peng Wang, Yanning Zhang.* ICML'25
  - [**Model Uncertainty Quantification by Conformal Prediction in Continual Learning**](https://icml.cc/virtual/2025/poster/45394) *Rui Gao, Weiwei Liu.* ICML'25
  - [**How Much Can We Forget about Data Contamination?**](https://icml.cc/virtual/2025/poster/45377) *Sebastian Bordt, Suraj Srinivas, Valentyn Boreiko, Ulrike Luxburg.* ICML'25
  - [**A Theoretical Framework For Overfitting In Energy-based Modeling**](https://icml.cc/virtual/2025/poster/45237) *Giovanni Catania, Aurélien Decelle, Cyril Furtlehner, Beatriz Seoane.* ICML'25
  - [**Towards Understanding Catastrophic Forgetting in Two-layer Convolutional Neural Networks**](https://icml.cc/virtual/2025/poster/44997) *Boqi Li, Youjun Wang, Weiwei Liu.* ICML'25
  - [**Neural Collapse Beyond the Unconstrained Features Model: Landscape, Dynamics, and Generalization in the Mean-Field Regime**](https://icml.cc/virtual/2025/poster/44830) *Diyuan Wu, Marco Mondelli.* ICML'25
  - [**SFT Memorizes, RL Generalizes: A Comparative Study of Foundation Model Post-training**](https://icml.cc/virtual/2025/poster/44633) *Tianzhe Chu, Yuexiang Zhai, Jihan Yang, Shengbang Tong, Saining Xie, Dale Schuurmans, Quoc Le, Sergey Levine, Yi Ma.* ICML'25
  - [**The Importance of Being Lazy: Scaling Limits of Continual Learning**](https://icml.cc/virtual/2025/poster/44575) *Jacopo Graldi, Alessandro Breccia, Giulia Lanzillotta, Thomas Hofmann, Lorenzo Noci.* ICML'25
  - [**Balancing the Scales: A Theoretical and Algorithmic Framework for Learning from Imbalanced Data**](https://icml.cc/virtual/2025/poster/44448) *Corinna Cortes, Anqi Mao, Mehryar Mohri, Yutao Zhong.* ICML'25
  - [**Stay Hungry, Keep Learning: Sustainable Plasticity for Deep Reinforcement Learning**](https://icml.cc/virtual/2025/poster/44413) *Huaicheng Zhou, Zifeng Zhuang, Donglin Wang.* ICML'25
  - [**Fishers for Free? Approximating the Fisher Information Matrix by Recycling the Squared Gradient Accumulator**](https://icml.cc/virtual/2025/poster/44175) *YuXin Li, Felix Dangel, Derek Tam, Colin Raffel.* ICML'25
  - [**Learning Dynamics under Environmental Constraints via Measurement-Induced Bundle Structures**](https://icml.cc/virtual/2025/poster/44131) *Dongzhe Zheng, Wenjie Mei.* ICML'25
  - [**LensLLM: Unveiling Fine-Tuning Dynamics for LLM Selection**](https://icml.cc/virtual/2025/poster/44045) *Xinyue Zeng, Haohui Wang, Junhong Lin, Jun Wu, Tyler Cody, Dawei Zhou.* ICML'25
  - [**Predicting the Susceptibility of Examples to Catastrophic Forgetting**](https://icml.cc/virtual/2025/poster/43833) *Guy Hacohen, Tinne Tuytelaars.* ICML'25
  - [**Scaling Trends in Language Model Robustness**](https://icml.cc/virtual/2025/poster/43784) *Nikolaus Howe, Ian McKenzie, Oskar Hollinsworth, Michał Zając, Tom Tseng, Aaron Tucker, Pierre-Luc Bacon, Adam Gleave.* ICML'25
  - [**Scaling Laws for Forgetting during Finetuning with Pretraining Data Injection**](https://icml.cc/virtual/2025/poster/43670) *Louis Béthune, David Grangier, Dan Busbridge, Eleonora Gualdoni, Marco Cuturi, Pierre Ablin.* ICML'25



### ACL
- 2025
  - [**EvoWiki: Evaluating LLMs on Evolving Knowledge**](https://aclanthology.org/2025.acl-long.47/) *Wei Tang, Yixin Cao, Yang Deng, Jiahao Ying, Bo Wang, Yizhe Yang, Yuyue Zhao, Qi Zhang, Xuanjing Huang, Yu-Gang Jiang, Yong Liao.* ACL'25
  - [**Evaluating Lexical Proficiency in Neural Language Models**](https://aclanthology.org/2025.acl-long.64/) *Cristiano Ciaccio, Alessio Miaschi, Felice Dell’Orletta.* ACL'25
  - [**Disentangling Memory and Reasoning Ability in Large Language Models**](https://aclanthology.org/2025.acl-long.84/) *Mingyu Jin, Weidi Luo, Sitao Cheng, Xinyi Wang, Wenyue Hua, Ruixiang Tang, William Yang Wang, Yongfeng Zhang.* ACL'25
  - [**UnSeenTimeQA: Time-Sensitive Question-Answering Beyond LLMs’ Memorization**](https://aclanthology.org/2025.acl-long.94/) *Md Nayem Uddin, Amir Saeidi, Divij Handa, Agastya Seth, Tran Cao Son, Eduardo Blanco, Steven Corman, Chitta Baral.* ACL'25
  - [**Exploring Forgetting in Large Language Model Pre-Training**](https://aclanthology.org/2025.acl-long.105/) *Chonghua Liao, Ruobing Xie, Xingwu Sun, Haowen Sun, Zhanhui Kang.* ACL'25
  - [**A Survey of Post-Training Scaling in Large Language Models**](https://aclanthology.org/2025.acl-long.140/) *Hanyu Lai, Xiao Liu, Junjie Gao, Jiale Cheng, Zehan Qi, Yifan Xu, Shuntian Yao, Dan Zhang, Jinhua Du, Zhenyu Hou, Xin Lv, Minlie Huang, Yuxiao Dong, Jie Tang.* ACL'25
  - [**Unveiling Language-Specific Features in Large Language Models via Sparse Autoencoders**](https://aclanthology.org/2025.acl-long.229/) *Boyi Deng, Yu Wan, Baosong Yang, Yidan Zhang, Fuli Feng.* ACL'25
  - [**Knowledge Boundary of Large Language Models: A Survey**](https://aclanthology.org/2025.acl-long.256/) *Moxin Li, Yong Zhao, Wenxuan Zhang, Shuaiyi Li, Wenya Xie, See-Kiong Ng, Tat-Seng Chua, Yang Deng.* ACL'25
  - [**YuLan-Mini: Pushing the Limits of Open Data-efficient Language Model**](https://aclanthology.org/2025.acl-long.268/) *Hu Yiwen, Huatong Song, Jie Chen, Jia Deng, Jiapeng Wang, Kun Zhou, Yutao Zhu, Jinhao Jiang, Zican Dong, Yang Lu, Xu Miao, Xin Zhao, Ji-Rong Wen.* ACL'25
  - [**P(2) Law: Scaling Law for Post-Training After Model Pruning**](https://aclanthology.org/2025.acl-long.283/) *Xiaodong Chen, Yuxuan Hu, Xiaokang Zhang, Yanling Wang, Cuiping Li, Hong Chen, Jing Zhang.* ACL'25
  - [**Cross-Lingual Pitfalls: Automatic Probing Cross-Lingual Weakness of Multilingual Large Language Models**](https://aclanthology.org/2025.acl-long.404/) *Zixiang Xu, Yanbo Wang, Yue Huang, Xiuying Chen, Jieyu Zhao, Meng Jiang, Xiangliang Zhang.* ACL'25
  - [**INTERACT: Enabling Interactive, Question-Driven Learning in Large Language Models**](https://aclanthology.org/2025.acl-long.441/) *Aum Kendapadi, Kerem Zaman, Rakesh R Menon, Shashank Srivastava.* ACL'25
  - [**Circuit Stability Characterizes Language Model Generalization**](https://aclanthology.org/2025.acl-long.442/) *Alan Sun.* ACL'25
  - [**Cooperative or Competitive? Understanding the Interaction between Attention Heads From A Game Theory Perspective**](https://aclanthology.org/2025.acl-long.688/) *Xiaoye Qu, Zengqi Yu, Dongrui Liu, Wei Wei, Daizong Liu, Jianfeng Dong, Yu Cheng.* ACL'25
  - [**From Selection to Generation: A Survey of LLM-based Active Learning**](https://aclanthology.org/2025.acl-long.708/) *Yu Xia, Subhojyoti Mukherjee, Zhouhang Xie, Junda Wu, Xintong Li, Ryan Aponte, Hanjia Lyu, Joe Barrow, Hongjie Chen, Franck Dernoncourt, Branislav Kveton, Tong Yu, Ruiyi Zhang, Jiuxiang Gu, Nesreen K. Ahmed, Yu Wang, Xiang Chen, Hanieh Deilamsalehy, Sungchul Kim, Zhengmian Hu, Yue Zhao, Nedim Lipka, Seunghyun Yoon, Ting-Hao Kenneth Huang, Zichao Wang, Puneet Mathur, Soumyabrata Pal, Koyel Mukherjee, Zhehao Zhang, Namyong Park, Thien Huu Nguyen, Jiebo Luo, Ryan A. Rossi, Julian McAuley.* ACL'25
  - [**Circuit Compositions: Exploring Modular Structures in Transformer-Based Language Models**](https://aclanthology.org/2025.acl-long.727/) *Philipp Mondorf, Sondre Wold, Barbara Plank.* ACL'25
  - [**Between Circuits and Chomsky: Pre-pretraining on Formal Languages Imparts Linguistic Biases**](https://aclanthology.org/2025.acl-long.478/) *Michael Y. Hu, Jackson Petty, Chuan Shi, William Merrill, Tal Linzen.* ACL'25
  - [**If Attention Serves as a Cognitive Model of Human Memory Retrieval, What is the Plausible Memory Representation?**](https://aclanthology.org/2025.acl-long.483/) *Ryo Yoshida, Shinnosuke Isono, Kohei Kajikawa, Taiga Someya, Yushi Sugimoto, Yohei Oseki.* ACL'25
  - [**The Knowledge Microscope: Features as Better Analytical Lenses than Neurons**](https://aclanthology.org/2025.acl-long.516/) *Yuheng Chen, Pengfei Cao, Kang Liu, Jun Zhao.* ACL'25
  - [**Developmentally-plausible Working Memory Shapes a Critical Period for Language Acquisition**](https://aclanthology.org/2025.acl-long.462/) *Masato Mita, Ryo Yoshida, Yohei Oseki.* ACL'25
  - [**Inferring Functionality of Attention Heads from their Parameters**](https://aclanthology.org/2025.acl-long.866/) *Amit Elhelo, Mor Geva.* ACL'25
  - [**Multilingual Encoder Knows more than You Realize: Shared Weights Pretraining for Extremely Low-Resource Languages**](https://aclanthology.org/2025.acl-long.893/) *Zeli Su, Ziyin Zhang, Guixian Xu, Jianing Liu, Xu Han, Ting Zhang, Yushuang Dong.* ACL'25
  - [**Cramming 1568 Tokens into a Single Vector and Back Again: Exploring the Limits of Embedding Space Capacity**](https://aclanthology.org/2025.acl-long.948/) *Yuri Kuratov, Mikhail Arkhipov, Aydar Bulatov, Mikhail Burtsev.* ACL'25
  - [**Enabling LLM Knowledge Analysis via Extensive Materialization**](https://aclanthology.org/2025.acl-long.789/) *Yujia Hu, Tuan-Phong Nguyen, Shrestha Ghosh, Simon Razniewski.* ACL'25
  - [**Analyzing the Rapid Generalization of SFT via the Perspective of Attention Head Activation Patterns**](https://aclanthology.org/2025.acl-long.831/) *Yang Zhao, Li Du, Xiao Ding, Kai Xiong, Ting Liu, Bing Qin.* ACL'25
  - [**Neural Incompatibility: The Unbridgeable Gap of Cross-Scale Parametric Knowledge Transfer in Large Language Models**](https://aclanthology.org/2025.acl-long.1047/) *Yuqiao Tan, Shizhu He, Kang Liu, Jun Zhao.* ACL'25
  - [**Language Models Resist Alignment: Evidence From Data Compression**](https://aclanthology.org/2025.acl-long.1141/) *Jiaming Ji, Kaile Wang, Tianyi Alex Qiu, Boyuan Chen, Jiayi Zhou, Changye Li, Hantao Lou, Josef Dai, Yunhuai Liu, Yaodong Yang.* ACL'25
  - [**Capability Salience Vector: Fine-grained Alignment of Loss and Capabilities for Downstream Task Scaling Law**](https://aclanthology.org/2025.acl-long.1157/) *Qiming Ge, Shuhao Xing, Songyang Gao, Yunhua Zhou, Yicheng Zou, Songyang Zhang, Zhi Chen, Hang Yan, Qi Zhang, Qipeng Guo, Kai Chen.* ACL'25
  - [**Revisiting Scaling Laws for Language Models: The Role of Data Quality and Training Strategies**](https://aclanthology.org/2025.acl-long.1163/) *Zhengyu Chen, Siqi Wang, Teng Xiao, Yudong Wang, Shiqi Chen, Xunliang Cai, Junxian He, Jingang Wang.* ACL'25
  - [**Training Dynamics Underlying Language Model Scaling Laws: Loss Deceleration and Zero-Sum Learning**](https://aclanthology.org/2025.acl-long.1366/) *Andrei Mircea, Supriyo Chakraborty, Nima Chitsazan, Irina Rish, Ekaterina Lobacheva.* ACL'25
  - [**Memorizing is Not Enough: Deep Knowledge Injection Through Reasoning**](https://aclanthology.org/2025.acl-long.1392/) *Ruoxi Xu, Yunjie Ji, Boxi Cao, Yaojie Lu, Hongyu Lin, Xianpei Han, Ben He, Yingfei Sun, Xiangang Li, Le Sun.* ACL'25
  - [**Hierarchical Memory Organization for Wikipedia Generation**](https://aclanthology.org/2025.acl-long.1423/) *Eugene J. Yu, Dawei Zhu, Yifan Song, Xiangyu Wong, Jiebin Zhang, Wenxuan Shi, Xiaoguang Li, Qun Liu, Sujian Li.* ACL'25
  - [**A Survey on Efficient Large Language Model Training: From Data-centric Perspectives**](https://aclanthology.org/2025.acl-long.1493/) *Junyu Luo, Bohan Wu, Xiao Luo, Zhiping Xiao, Yiqiao Jin, Rong-Cheng Tu, Nan Yin, Yifan Wang, Jingyang Yuan, Wei Ju, Ming Zhang.* ACL'25
  - [**Separating Tongue from Thought: Activation Patching Reveals Language-Agnostic Concept Representations in Transformers**](https://aclanthology.org/2025.acl-long.1536/) *Clément Dumas, Chris Wendler, Veniamin Veselovsky, Giovanni Monea, Robert West.* ACL'25
  - [**What Happened in LLMs Layers when Trained for Fast vs. Slow Thinking: A Gradient Perspective**](https://aclanthology.org/2025.acl-long.1545/) *Ming Li, Yanhong Li, Tianyi Zhou.* ACL'25
  - [**Multi-Level Explanations for Generative Language Models**](https://aclanthology.org/2025.acl-long.1553/) *Lucas Monteiro Paes, Dennis Wei, Hyo Jin Do, Hendrik Strobelt, Ronny Luss, Amit Dhurandhar, Manish Nagireddy, Karthikeyan Natesan Ramamurthy, Prasanna Sattigeri, Werner Geyer, Soumya Ghosh.* ACL'25
  - [**Mapping 1,000+ Language Models via the Log-Likelihood Vector**](https://aclanthology.org/2025.acl-long.1584/) *Momose Oyama, Hiroaki Yamagiwa, Yusuke Takase, Hidetoshi Shimodaira.* ACL'25



## 4. Knowledge Editing (KE)
### ICLR 
- 2025
  - [**CollabEdit: Towards Non-destructive Collaborative Knowledge Editing**](https://iclr.cc/virtual/2025/poster/31140) *Jiamu Zheng, Jinghuai Zhang, Tianyu Du, Xuhong Zhang, Jianwei Yin, Tao Lin.* ICLR'25
  - [**Precise Localization of Memories: A Fine-grained Neuron-level Knowledge Editing Technique for LLMs**](https://iclr.cc/virtual/2025/poster/30923) *Haowen Pan, Xiaozhi Wang, Yixin Cao, Zenglin Shi, Xun Yang, Juanzi Li, Meng Wang.* ICLR'25
  - [**Revealing and Mitigating Over-Attention in Knowledge Editing**](https://iclr.cc/virtual/2025/poster/30995) *Pinzheng Wang, Zecheng Tang, Keyan Zhou, Juntao Li, Qiaoming Zhu, Min Zhang.* ICLR'25
  - [**AlphaEdit: Null-Space Constrained Knowledge Editing for Language Models**](https://iclr.cc/virtual/2025/poster/30202) *Junfeng Fang, Houcheng Jiang, Kun Wang, Yunshan Ma, Jie Shi, Xiang Wang, Xiangnan He, Tat-Seng Chua.* ICLR'25
  - [**Everything is Editable: Extend Knowledge Editing to Unstructured Data in Large Language Models**](https://iclr.cc/virtual/2025/poster/29325) *Jingcheng Deng, Zihao Wei, Liang Pang, Hanxing Ding, Huawei Shen, Xueqi Cheng.* ICLR'25
  - [**Can Knowledge Editing Really Correct Hallucinations?**](https://iclr.cc/virtual/2025/poster/28744) *Baixiang Huang, Canyu Chen, Xiongxiao Xu, Ali Payani, Kai Shu.* ICLR'25


### ICML
- 2025
  - [**Reinforced Lifelong Editing for Language Models**](https://openreview.net/forum?id=1jUXprrfcb) *Zherui Li, Houcheng Jiang, Hao Chen, Baolong Bi, Zhenhong Zhou, Fei Sun, Junfeng Fang, Xiang Wang.* ICML'25
  - [**Towards Lifelong Model Editing via Simulating Ideal Editor**](https://icml.cc/virtual/2025/poster/45062) *Yaming Guo, Siyang Guo, Hengshu Zhu, Ying Sun.* ICML'25
  - [**AnyEdit: Edit Any Knowledge Encoded in Language Models**](https://icml.cc/virtual/2025/poster/44807) *Houcheng Jiang, Junfeng Fang, Ningyu Zhang, Mingyang Wan, Guojun Ma, Xiang Wang, Xiangnan He, Tat-Seng Chua.* ICML'25
  - [**Locate-then-edit for Multi-hop Factual Recall under Knowledge Editing**](https://icml.cc/virtual/2025/poster/44270) *Zhuoran Zhang, Yongxiang Li, Zijian Kan, Keyuan Cheng, Lijie Hu, Di Wang.* ICML'25


### ACL
- 2025
  - [**AdaEdit: Advancing Continuous Knowledge Editing For Large Language Models**](https://aclanthology.org/2025.acl-long.208/) *Qi Li, Xiaowen Chu.* ACL'25
  - [**Knowledge Decoupling via Orthogonal Projection for Lifelong Editing of Large Language Models**](https://aclanthology.org/2025.acl-long.646/) *Haoyu Xu, Pengxiang Lan, Enneng Yang, Guibing Guo, Jianzhe Zhao, Linying Jiang, Xingwei Wang.* ACL'25
  - [**ChainEdit: Propagating Ripple Effects in LLM Knowledge Editing through Logical Rule-Guided Chains**](https://aclanthology.org/2025.acl-long.665/) *Zilu Dong, Xiangqing Shen, Zinong Yang, Rui Xia.* ACL'25
  - [**The Mirage of Model Editing: Revisiting Evaluation in the Wild**](https://aclanthology.org/2025.acl-long.745/) *Wanli Yang, Fei Sun, Jiajun Tan, Xinyu Ma, Qi Cao, Dawei Yin, Huawei Shen, Xueqi Cheng.* ACL'25
  - [**Revealing the Deceptiveness of Knowledge Editing: A Mechanistic Analysis of Superficial Editing**](https://aclanthology.org/2025.acl-long.868/) *Jiakuan Xie, Pengfei Cao, Yubo Chen, Kang Liu, Jun Zhao.* ACL'25
  - [**SAKE: Steering Activations for Knowledge Editing**](https://aclanthology.org/2025.acl-long.777/) *Marco Scialanga, Thibault Laugel, Vincent Grari, Marcin Detyniecki.* ACL'25
  - [**One for All: Update Parameterized Knowledge Across Multiple Models with Once Edit**](https://aclanthology.org/2025.acl-long.780/) *Weitao Ma, Xiyuan Du, Xiaocheng Feng, Lei Huang, Yichong Huang, Huiyi Zhang, Xiaoliang Yang, Baohang Li, Xiachong Feng, Ting Liu, Bing Qin.* ACL'25
  - [**BMIKE-53: Investigating Cross-Lingual Knowledge Editing with In-Context Learning**](https://aclanthology.org/2025.acl-long.798/) *Ercong Nie, Bo Shao, Mingyang Wang, Zifeng Ding, Helmut Schmid, Hinrich Schuetze.* ACL'25
  - [**Parameter-Aware Contrastive Knowledge Editing: Tracing and Rectifying based on Critical Transmission Paths**](https://aclanthology.org/2025.acl-long.1367/) *Songlin Zhai, Yuan Meng, Yuxin Zhang, Guilin Qi.* ACL'25
  - [**Serial Lifelong Editing via Mixture of Knowledge Experts**](https://aclanthology.org/2025.acl-long.1492/) *YuJu Cheng, Yu-Chu Yu, Kai-Po Chang, Yu-Chiang Frank Wang.* ACL'25
  - [**Efficient Knowledge Editing via Minimal Precomputation**](https://aclanthology.org/2025.acl-short.65/) *Akshat Gupta, Maochuan Lu, Thomas Hartvigsen, Gopala Anumanchipalli.* ACL'25


### *Contact me*

*wanglingxiang@buaa.edu.cn*
