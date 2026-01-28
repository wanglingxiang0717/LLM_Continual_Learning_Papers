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

*This work was carried out at the Advanced Innovation Center for Future Blockchain and Privacy Computing, School of Artificial Intelligence, Beihang University, during my time with the TapLLM research group.*

[![GitHub](https://img.shields.io/badge/GitHub-TAP--LLM-black?logo=github)](https://github.com/TAP-LLM)
[![Xiaohongshu](https://img.shields.io/badge/小红书-北航TapLLM课题组-red?logo=xiaohongshu)](https://www.xiaohongshu.com/user/profile/5829358a3460941d0f10fda3)


## Contents

- [LLM Continual Learning Papers](#LLM-Continual-Learning-Papers)
  - [1. Continued Pre-training (CP)](#1-Continued-Pre-training-(CP))
    - [ICLR](#ICLR)
    - [ICML](#ICML)
    - [NeurIPS](#NeurIPS)
    - [ACL](#ACL)
    - [CVPR](#CVPR)
  - [2. Continued Fine-tuning (CFT)](#2-Continued-Fine-tuning-(CFT))
    - [ICLR](#ICLR-1)
    - [ICML](#ICML-1)
    - [NeurIPS](#NeurIPS-1)
    - [ACL](#ACL-1)
    - [CVPR](#CVPR-1)
  - [3. Learning, Knowledge, and Memory (L,K,M)](#3-Learning-Knowledge-and-Memory-(L,K,M))
    - [ICLR](#ICLR-2)
    - [ICML](#ICML-2)
    - [NeurIPS](#NeurIPS-2)
    - [ACL](#ACL-2)
    - [CVPR](#CVPR-2)
  - [4. Knowledge Editing (KE)](#4-Knowledge-Editing-(KE))
    - [ICLR](#ICLR-3)
    - [ICML](#ICML-3)
    - [NeurIPS](#NeurIPS-3)
    - [ACL](#ACL-3)
    - [CVPR](#CVPR-3)

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

### NeurIPS
- 2025
  * **[Dual-Space Semantic Synergy Distillation for Continual Learning of Unlabeled Streams](https://openreview.net/forum?id=0g9gVoA7sn)** *Zhi-Hao Xu, Jia-Xing Zhong, Xiao-Yu Zhang, Cheng-Lin Liu.* NeurIPS'25
  * **[Titans: Learning to Memorize at Test Time](https://openreview.net/forum?id=8GjSf9Rh7Z)** *Ali Behrouz, Santosh S. Vempala.* NeurIPS'25
  * **[Are Greedy Task Orderings Better Than Random in Continual Linear Regression?](https://openreview.net/forum?id=8JdPqAMpi4)** *Yao-Chun Chan, Benjamin Gancz, David R. Bosch, Nicolas M. Schuck, Sam Gershman.* NeurIPS'25
  * **[Optimal Mistake Bounds for Transductive Online Learning](https://openreview.net/forum?id=EoebmBe9fG)** *Noga Alon, Shay Moran, Noam Shemtov.* NeurIPS'25
  * **[Reparameterized LLM Training via Orthogonal Equivalence Transformation](https://openreview.net/forum?id=JrZY7ilKLs)** *Yao-Ting Hsu, Chieh-Hsin Lai, Yu-Chiang Frank Wang.* NeurIPS'25
  * **[HyperET: Efficient Training in Hyperbolic Space for Multi-modal Large Language Models](https://openreview.net/forum?id=NM8Apk61NA)** *Xuan-May Le, Van-Quang Nguyen, Huy-Phan Tran, Thieu-Binh Truong, Quan-Ha Ly, Khanh-Khuong Nguyen.* NeurIPS'25
  * **[OVS Meets Continual Learning: Towards Sustainable Open-Vocabulary Segmentation](https://openreview.net/forum?id=y8Hv7EdcRF)** *Shuo-Fei Wang, Liyuan Wang, Xing Sun, Ming-Ming Cheng.* NeurIPS'25


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
 
### CVPR
- 2025
  - [**Advancing Multiple Instance Learning with Continual Learning for Whole Slide Imaging**](https://cvpr.thecvf.com/virtual/2025/poster/32665) *Xianrui Li, Yufei Cui, Jun Li, Antoni B. Chan.* CVPR'25
  - **[Do Your Best and Get Enough Rest for Continual Learning](https://cvpr.thecvf.com/virtual/2025/poster/34881)** *Hankyul Kang, Gregor Seifer, Donghyun Lee, Jongbin Ryu.* CVPR'25
  * **[Identifying and Mitigating Spurious Correlation in Multi-Task Learning](https://cvpr.thecvf.com/virtual/2025/poster/34342)** *Junyi Chai, Shenyu Lu, Xiaoqian Wang.* CVPR'25
  * **[Instance-wise Supervision-level Optimization in Active Learning](https://cvpr.thecvf.com/virtual/2025/poster/33908)** *Shinnosuke Matsuo, Riku Togashi, Ryoma Bise, Seiichi Uchida, Masahiro Nomura.* CVPR'25
  * **[Joint Out-of-Distribution Filtering and Data Discovery Active Learning](https://cvpr.thecvf.com/virtual/2025/poster/33684)** *Sebastian Schmidt, Leonard Schenk, Leo Schwinn, Stephan Günnemann.* CVPR'25
  * **[Self-Expansion of Pre-trained Models with Mixture of Adapters for Continual Learning](https://cvpr.thecvf.com/virtual/2025/poster/32576)** *Jiangmiao Wang, Feng Zheng, Baosheng Yu, Minghui Chen, Yan Huang, Ling Shao.* CVPR'25

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

### NeurIPS
- 2025
  * **[Learning Multi-Source and Robust Representations for Continual Learning](https://openreview.net/forum?id=24vq7c6MpR)** *Zhenyi Wang, Yanqing He, Haoliang Li, Xiaofeng Mao, Enze Xie, Xiuyu Sun, Zheyang Li.* NeurIPS'25
  * **[Decentralized Dynamic Cooperation of Personalized Models for Federated Continual Learning](https://openreview.net/forum?id=16BGOheRzm)** *Zhen Wang, Siyuan Guo, Qingyong Hu, Shuran Song.* NeurIPS'25
  * **[Mitigating Forgetting in LLM Fine-Tuning via Low-Perplexity Token Learning](https://openreview.net/forum?id=1ktdvp1EYI)** *Zhuoheng Ma, Benyou Wang, Jianqing Zhu, Saied Alshahrani, Emad A. Alghamdi, Jinchao Xu.* NeurIPS'25
  * **[Exploring Tradeoffs through Mode Connectivity for Multi-Task Learning](https://openreview.net/forum?id=4ULtNYHc5T)** *Zihong Li, Jialun Ma, Guisheng Wang, Jingwen Ye, Ji-Rong Wen.* NeurIPS'25
  * **[FedRAM: Federated Reweighting and Aggregation for Multi-Task Learning](https://openreview.net/forum?id=5QneXT1qoc)** *Xin-Chun Li, Yan-Fei Wang, Shao-Hua Zhou, De-Chuan Zhan.* NeurIPS'25
  * **[Resource-Constrained Federated Continual Learning: What Does Matter?](https://openreview.net/forum?id=5aIVAGHCa5)** *Yikai Shen, Fangzhao Wu, Tao Xie, See-Kiong Ng.* NeurIPS'25
  * **[On the Loss of Context Awareness in General Instruction Fine-tuning](https://openreview.net/forum?id=7OdU0LYXLr)** *Yuhan Chen, Siyan Jiang, Shuhua Huang, Rui Wang, Kehai Chen, Tiejun Zhao.* NeurIPS'25
  * **[Evolving and Regularizing Meta-Environment Learner for Fine-Grained Few-Shot Class-Incremental Learning](https://openreview.net/forum?id=AU2eaY2QEu)** *Zhuo Zhang, Jing-Hao Sun, Yi-Zhen Ji, Song-Hai Zhang.* NeurIPS'25
  * **[Multitask Learning with Stochastic Interpolants](https://openreview.net/forum?id=9k9ZsDs9Vc)** *Yiduo Guo, Weiduo Liao, Bing Liu.* NeurIPS'25
  * **[GraphKeeper: Graph Domain-Incremental Learning via Knowledge Disentanglement and Preservation](https://openreview.net/forum?id=AIlaBrwwJO)** *Zhengrong Xue, Ziyi Zhang, Jingwen Ye, Shuo Chen, Ji-Rong Wen.* NeurIPS'25
  * **[Agnostic Continuous-Time Online Learning](https://openreview.net/forum?id=9LoVCfMLDl)** *Noga Alon, Shay Moran, Noam Shemtov.* NeurIPS'25
  * **[Lifelong Safety Alignment for Language Models](https://openreview.net/forum?id=9YkEcAqiIK)** *Hao Sun, Zhexuo Li, Xu Han, Zhiyuan Liu, Maosong Sun.* NeurIPS'25
  * **[From Pretraining to Pathology: How Noise Leads to Catastrophic Inheritance in Medical Models](https://openreview.net/forum?id=9c8J2C7ajq)** *Tiancheng Wen, Siyuan Liu, James Zou.* NeurIPS'25
  * **[Temporal-Difference Variational Continual Learning](https://openreview.net/forum?id=9iYKXx5ieE)** *Siddharth Swaroop, Richard E. Turner.* NeurIPS'25
  * **[Continual Optimization with Symmetry Teleportation for Multi-Task Learning](https://openreview.net/forum?id=8P5MUySaqi)** *Bo-Jian Hou, Bo-Bin Zhang, Wei-Min He, Li-Min Wang.* NeurIPS'25
  * **[Mitigating Intra- and Inter-modal Forgetting in Continual Learning of Unified Multimodal Models](https://openreview.net/forum?id=CBsANtjBV4)** *Yi-Fan Zhang, Fan-Xing Kong, Ru-Ping Wang.* NeurIPS'25
  * **[Recurrent Memory for Online Interdomain Gaussian Processes](https://openreview.net/forum?id=BtPg90UEbw)** *Zekai Wang, Jialiang Wang, Philip Torr.* NeurIPS'25
  * **[Federated Continual Learning via Orchestrating Multi-Scale Expertise](https://openreview.net/forum?id=AlSHcopwHi)** *Hao Zhou, Shuo Xu, Ming Yan, Ji Zhang, Fei Huang.* NeurIPS'25
  * **[Hybrid Re-matching for Continual Learning with Parameter-Efficient Tuning](https://openreview.net/forum?id=DCc4OyNX8A)** *Liyuan Wang, Xing Sun, Ming-Ming Cheng.* NeurIPS'25
  * **[Learn and Ensemble Bridge Adapters for Multi-domain Task Incremental Learning](https://openreview.net/forum?id=Cx6Kqto5h1)** *Ji-Hao Sun, Yi-Zhen Ji, Song-Hai Zhang.* NeurIPS'25
  * **[NTKMTL: Mitigating Task Imbalance in Multi-Task Learning from Neural Tangent Kernel Perspective](https://openreview.net/forum?id=D9jXj7nceM)** *Chen-Xuan Li, Ying-Hao Nan, Shao-Fan Jing.* NeurIPS'25
  * **[Adaptable Safe Policy Learning from Multi-task Data with Constraint Prioritized Decision Transformer](https://openreview.net/forum?id=HmsEHahtGx)** *Zeyu Wang, Yong Zhang, Wei Liu.* NeurIPS'25
  * **[Your Pre-trained LLM is Secretly an Unsupervised Confidence Calibrator](https://openreview.net/forum?id=I4PJYZvfW5)** *Sizhe Chen, Xiaolin Huang, Siyuan Liang.* NeurIPS'25
  * **[Triplets Better Than Pairs: Towards Stable and Effective Self-Play Fine-Tuning for LLMs](https://openreview.net/forum?id=Hk4cCTukeI)** *Zhiyu Zhang, Wei Chen, Youfang Lin, Huaiyu Wan.* NeurIPS'25
  * **[Tackling Continual Offline RL through Selective Weights Activation on Aligned Spaces](https://openreview.net/forum?id=KfRfTAJpjh)** *Jae-Won Cho, Hyuntae Jung, Dong-Wan Choi.* NeurIPS'25
  * **[Lifelong Test-Time Adaptation via Online Learning in Tracked Low-Dimensional Subspace](https://openreview.net/forum?id=NFvAa2hNzH)** *Zhi-Hao Xu, Xiao-Yu Zhang, Cheng-Lin Liu.* NeurIPS'25
  * **[A Minimalistic Unified Framework for Incremental Learning across Image Restoration Tasks](https://openreview.net/forum?id=MBQZwQ6vFd)** *Yubin Gu, Yuan Meng, Jiayi Ji, Xiaoshuai Sun.* NeurIPS'25
  * **[Gradient-Guided Epsilon Constraint Method for Online Continual Learning](https://openreview.net/forum?id=MuhYHqLDZT)** *Fei Ye, Adrian G. Bors.* NeurIPS'25
  * **[Dynamic Siamese Expansion Framework for Improving Robustness in Online Continual Learning](https://openreview.net/forum?id=M1OqlaNrw7)** *Guan-Xin Zeng, Qiang-Hua Huang, Wen-Ji Wang.* NeurIPS'25
  * **[Shape it Up! Restoring LLM Safety during Finetuning](https://openreview.net/forum?id=PAIVwOaAnq)** *Sizhe Chen, Siyuan Liang, Xiaolin Huang.* NeurIPS'25
  * **[Online Functional Tensor Decomposition via Continual Learning for Streaming Data Completion](https://openreview.net/forum?id=RPuTB28HsK)** *Sihan Huang, Jihong Yan, Xiao-Yang Liu.* NeurIPS'25
  * **[Knowledge Graph Enhanced Generative Multi-modal Models for Class-Incremental Learning](https://openreview.net/forum?id=SeC5Zb8Orf)** *Sheng-Xian Yang, Yi-Zhen Ji, Song-Hai Zhang.* NeurIPS'25
  * **[Continual Knowledge Adaptation for Reinforcement Learning](https://openreview.net/forum?id=QRlVickNdN)** *Zeyu Wang, Wei Liu, Yong Zhang.* NeurIPS'25
  * **[REP: Resource-Efficient Prompting for Rehearsal-Free Continual Learning](https://openreview.net/forum?id=QjmRIgTcU8)** *Jiangmiao Wang, Baosheng Yu, Yan Huang.* NeurIPS'25
  * **[Exploiting Task Relationships in Continual Learning via Transferability-Aware Task Embeddings](https://openreview.net/forum?id=V8FnYzDX35)** *Xiao-Yu Zhang, Zhi-Hao Xu, Jia-Xing Zhong, Cheng-Lin Liu.* NeurIPS'25
  * **[Separating the 'what' and 'how' of compositional computation to enable reuse and continual learning](https://openreview.net/forum?id=Wg9gAqjAHb)** *Benjamin Gancz, Sam Gershman.* NeurIPS'25
  * **[Pay Attention to Small Weights](https://openreview.net/forum?id=XKnOA7MhCz)** *Yujie Li, Xiheng Kong, Wen-Huang Cheng.* NeurIPS'25
  * **[Turning the Tables: Enabling Backward Transfer via Causal-Aware LoRA in Continual Learning](https://openreview.net/forum?id=bdGsKis3Ew)** *Jun-Hyung Park, Hyuntae Jung, Sang-Won Park.* NeurIPS'25
  * **[Bisecle: Binding and Separation in Continual Learning for Video Language Understanding](https://openreview.net/forum?id=o6keqobP13)** *Yuan He, Zefan Zhou, Di Hu.* NeurIPS'25
  * **[Investigating and Mitigating Catastrophic Forgetting in Medical Knowledge Injection through Internal Knowledge Augmentation Learning](https://openreview.net/forum?id=i9RDDi2SZC)** *Zekun Li, Jinge Ma, Hong-Yu Zhou.* NeurIPS'25
  * **[Continuous Subspace Optimization for Continual Learning](https://openreview.net/forum?id=iLYV4iIC0c)** *Hantian Zhang, Ziheng Qin, Jingyu Yang.* NeurIPS'25
  * **[Continual Multimodal Contrastive Learning](https://openreview.net/forum?id=juROy8NYRD)** *Yifan Zhang, Han-Jia Ye, De-Chuan Zhan.* NeurIPS'25
  * **[Gated Integration of Low-Rank Adaptation for Continual Learning of Large Language Models](https://openreview.net/forum?id=lVV7F0piDK)** *Yubin Gu, Yuan Meng, Xiaoshuai Sun.* NeurIPS'25
  * **[Train with Perturbation, Infer after Merging: A Two-Stage Framework for Continual Learning](https://openreview.net/forum?id=lqm1qJ43Sw)** *Liyuan Wang, Yunhang Shen, Ming-Ming Cheng.* NeurIPS'25
  * **[MindForge: Empowering Embodied Agents with Theory of Mind for Lifelong Cultural Learning](https://openreview.net/forum?id=u7jtLj46i9)** *Yao Mu, Ze-Rui Li, Ping-Luo Zhang.* NeurIPS'25
  * **[K-DeCore: Facilitating Knowledge Transfer in Continual Structured Knowledge Reasoning via Knowledge Decoupling](https://openreview.net/forum?id=stiJen3iNI)** *Zhiyu Zhang, Wei Chen, Huaiyu Wan.* NeurIPS'25
  * **[C^2 Prompt: Class-aware Client Knowledge Interaction for Federated Continual Learning](https://openreview.net/forum?id=pKqLOmF3Lf)** *Chen-Xuan Li, Ying-Hao Nan, Ming-Hui Zhang.* NeurIPS'25
  * **[Contrastive Consolidation of Top-Down Modulations Achieves Sparsely Supervised Continual Learning](https://openreview.net/forum?id=pLDpenGIjl)** *Fei Ye, Adrian G. Bors.* NeurIPS'25
  * **[AnaCP: Toward Upper-Bound Continual Learning via Analytic Contrastive Projection](https://openreview.net/forum?id=qQbvLU34F1)** *Huiping Zhuang, Ruonan Li, Zhiping Lin.* NeurIPS'25
  * **[Learning Expandable and Adaptable Representations for Continual Learning](https://openreview.net/forum?id=uXKgVqYTJ2)** *Yuyang Zhao, Jianan Li, Ge Li.* NeurIPS'25
  * **[Mixture of Noise for Pre-Trained Model-Based Class-Incremental Learning](https://openreview.net/forum?id=wI6oHXeTR8)** *Jia-Wen Xiao, Liyuan Wang, Ming-Ming Cheng.* NeurIPS'25
  * **[Policy Compatible Skill Incremental Learning via Lazy Learning Interface](https://openreview.net/forum?id=xmYT1JqVpj)** *Zeyu Wang, Wei Liu, Yong Zhang.* NeurIPS'25
  * **[Model Inversion with Layer-Specific Modeling and Alignment for Data-Free Continual Learning](https://openreview.net/forum?id=yruGxKsZyH)** *Siyuan Liang, Sizhe Chen, Xiaolin Huang.* NeurIPS'25
  * **[Bigger, Regularized, Categorical: High-Capacity Value Functions are Efficient Multi-Task Learners](https://openreview.net/forum?id=zhOUfuOIzA)** *Hao Sun, Zhexuo Li, Zhiyuan Liu.* NeurIPS'25

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

### CVPR
- 2025
  * **[AVQACL: A Novel Benchmark for Audio-Visual Question Answering Continual Learning](https://cvpr.thecvf.com/virtual/2025/poster/35098)** *Guangyao Li, Wenxuan Hou, Di Hu.* CVPR'25
  * **[Activating Sparse Part Concepts for 3D Class Incremental Learning](https://cvpr.thecvf.com/virtual/2025/poster/32851)** *Yuyang Zhao, Jianan Li, Tingting Liang, Ge Li.* CVPR'25
  * **[AdaDARE-gamma: Balancing Stability and Plasticity in Multi-modal LLMs through Efficient Adaptation](https://cvpr.thecvf.com/virtual/2025/poster/33585)** *Ting-Yi Chu, Chieh-Hsin Lai, Yu-Chiang Frank Wang.* CVPR'25
  * **[Adapter Merging with Centroid Prototype Mapping for Scalable Class-Incremental Learning](https://cvpr.thecvf.com/virtual/2025/poster/32443)** *Yibo Yang, Ruofei Han, Haizhou Wu, Kayeon Kim, Jure Leskovec.* CVPR'25
  * **[CL-MoE: Enhancing Multimodal Large Language Model with Dual Momentum Mixture-of-Experts for Continual Visual Question Answering](https://cvpr.thecvf.com/virtual/2025/poster/34268)** *Hao Zhou, Shuo Xu, Ming Yan, Ji Zhang, Fei Huang.* CVPR'25
  * **[CL-LoRA: Continual Low-Rank Adaptation for Rehearsal-Free Class-Incremental Learning](https://cvpr.thecvf.com/virtual/2025/poster/34286)** *Hantian Zhang, Ziheng Qin, Jingyu Yang, Chenglong Li.* CVPR'25
  * **[Boosting Domain Incremental Learning: Selecting the Optimal Parameters is All You Need](https://cvpr.thecvf.com/virtual/2025/poster/33144)** *Xueshuang Xiang, Yuanyuan Wu, Hanqiang Nie, Jun Wang.* CVPR'25
  * **[Attraction Diminishing and Distributing for Few-Shot Class-Incremental Learning](https://cvpr.thecvf.com/virtual/2025/poster/35177)** *Yuxuan Du, Zongyuan Ge, Fanman Meng, Qingbo Wu, Linfeng Xu, Hongliang Li.* CVPR'25
  * **[BiLoRA: Almost-Orthogonal Parameter Spaces for Continual Learning](https://cvpr.thecvf.com/virtual/2025/poster/32506)** *Yujie Li, Xiheng Kong, Wen-Huang Cheng, Xiaoming Xi.* CVPR'25
  * **[Decouple-Then-Merge: Finetune Diffusion Models as Multi-Task Learning](https://cvpr.thecvf.com/virtual/2025/poster/34782)** *Zeyu Wang, Wei Liu, Jialiang Wang, Yong Zhang.* CVPR'25
  * **[Dual Consolidation for Pre-Trained Model-Based Domain-Incremental Learning](https://cvpr.thecvf.com/virtual/2025/poster/33334)** *Liyuan Wang, Yunhang Shen, Xing Sun, Ke Li.* CVPR'25
  * **[Dynamic Integration of Task-Specific Adapters for Class Incremental Learning](https://cvpr.thecvf.com/virtual/2025/poster/34532)** *Zhiyuan Wang, Liuyu Xiang, Yujie Zhong, Yansong Tang.* CVPR'25
  * **[ConceptGuard: Continual Personalized Text-to-Image Generation with Forgetting and Confusion Mitigation](https://cvpr.thecvf.com/virtual/2025/poster/33715)** *Ying-Cong Chen, Haoyu Chen, Xiaojie Xu, Lei Zhu, Xinchao Wang.* CVPR'25
  * **[Efficient Transfer Learning for Video-language Foundation Models](https://cvpr.thecvf.com/virtual/2025/poster/34228)** *Sijie Zhu, Tianlong Chen, Zhangyang Wang.* CVPR'25
  * **[F-LMM: Grounding Frozen Large Multimodal Models](https://cvpr.thecvf.com/virtual/2025/poster/33673)** *Zhuofan Zong, Guanglu Song, Yanwei Li, Yu Liu, Hongsheng Li.* CVPR'25
  * **[Ferret: An Efficient Online Continual Learning Framework under Varying Memory Constraints](https://cvpr.thecvf.com/virtual/2025/poster/32744)** *Yongqiang Zhao, Ruoyi Du, Yu Wang, Jian Sun.* CVPR'25
  * **[Focus-N-Fix: Region-Aware Fine-Tuning for Text-to-Image Generation](https://cvpr.thecvf.com/virtual/2025/poster/32591)** *Shaoan Xie, Dingning Liu, Hang Su, Jun Zhu.* CVPR'25
  * **[Incremental Object Keypoint Learning](https://cvpr.thecvf.com/virtual/2025/poster/32955)** *Bohan Wu, Han-Kai Hsu, Jia-Bin Huang.* CVPR'25
  * **[KAC: Kolmogorov-Arnold Classifier for Continual Learning](https://cvpr.thecvf.com/virtual/2025/poster/34404)** *Zhongli Zhang, Hongyi Wan, Haofei Wang, Jinjun Wang.* CVPR'25
  * **[Knowledge Memorization and Rumination for Pre-trained Model-based Class-Incremental Learning](https://cvpr.thecvf.com/virtual/2025/poster/33391)** *Jia-Wen Xiao, Liyuan Wang, Xing Sun, Ming-Ming Cheng.* CVPR'25
  * **[Language Guided Concept Bottleneck Models for Interpretable Continual Learning](https://cvpr.thecvf.com/virtual/2025/poster/33298)** *Sheng-Xian Yang, Yi-Zhen Ji, Zhan-Zhan Cheng, Song-Hai Zhang.* CVPR'25
  * **[Learning Conditional Space-Time Prompt Distributions for Video Class-Incremental Learning](https://cvpr.thecvf.com/virtual/2025/poster/35204)** *Ruoyu Chen, Yong Liu, Jinghua Fang, Yanpeng Sun.* CVPR'25
  * **[LoRA Subtraction for Drift-Resistant Space in Exemplar-Free Continual Learning](https://cvpr.thecvf.com/virtual/2025/poster/34314)** *Jun-Hyung Park, Hyuntae Jung, Dong-Wan Choi, Sang-Won Park.* CVPR'25
  * **[Low-Rank Adaptation in Multilinear Operator Networks for Security-Preserving Incremental Learning](https://cvpr.thecvf.com/virtual/2025/poster/33975)** *Guan-Xin Zeng, Qiang-Hua Huang, Wen-Ji Wang, Xin-Yu Zhang.* CVPR'25
  * **[Online Task-Free Continual Learning via Dynamic Expansionable Memory Distribution](https://cvpr.thecvf.com/virtual/2025/poster/33725)** *Fei Ye, Adrian G. Bors.* CVPR'25
  * **[Revisiting Generative Replay for Class Incremental Object Detection](https://cvpr.thecvf.com/virtual/2025/poster/34300)** *Runtian Wang, Longhui Wei, Shiyu Hu, Yunfeng Zhang, Qi Tian.* CVPR'25
  * **[SEC-Prompt: SEmantic Complementary Prompting for Few-Shot Class-Incremental Learning](https://cvpr.thecvf.com/virtual/2025/poster/32859)** *Zhenhua Chen, Ruixuan Yan, Jingyu Yang.* CVPR'25
  * **[Synthetic Data is an Elegant GIFT for Continual Vision-Language Models](https://cvpr.thecvf.com/virtual/2025/poster/32691)** *Minsu Kim, Seong-Hyeon Hwang, Steven Euijong Whang.* CVPR'25
  * **[TADFormer: Task-Adaptive Dynamic TransFormer for Efficient Multi-Task Learning](https://cvpr.thecvf.com/virtual/2025/poster/34594)** *Han-Pang Hsieh, Chi-Hao Wu, Ming-Hsuan Yang.* CVPR'25
  * **[Task-Agnostic Guided Feature Expansion for Class-Incremental Learning](https://cvpr.thecvf.com/virtual/2025/poster/34340)** *Xiao-Yu Zhang, Zhi-Hao Xu, Jia-Xing Zhong, Cheng-Lin Liu.* CVPR'25
  * **[Think Small, Act Big: Primitive Prompt Learning for Lifelong Robot Manipulation](https://cvpr.thecvf.com/virtual/2025/poster/33193)** *Yao Mu, Ze-Rui Li, Sijia Chen, Ping-Luo Zhang.* CVPR'25
  * **[Towards Consistent Multi-Task Learning: Unlocking the Potential of Task-Specific Parameters](https://cvpr.thecvf.com/virtual/2025/poster/34415)** *Yi-Fan Zhang, Fan-Xing Kong, Jin-Gang Wang, Ru-Ping Wang.* CVPR'25
  * **[Tripartite Weight-Space Ensemble for Few-Shot Class-Incremental Learning](https://cvpr.thecvf.com/virtual/2025/poster/34859)** *Jing-Hao Sun, Qi-Wei Wang, Yi-Zhen Ji, Song-Hai Zhang.* CVPR'25
  * **[pFedMxF: Personalized Federated Class-Incremental Learning with Mixture of Frequency Aggregation](https://cvpr.thecvf.com/virtual/2025/poster/34489)** *Chen-Xuan Li, Ying-Hao Nan, Ming-Hui Zhang, Shao-Fan Jing.* CVPR'25

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

### NeurIPS
- 2025
  * **[Enhancing Training Data Attribution with Representational Optimization](https://openreview.net/forum?id=ESB924uT5Y)** *Zhuo Li, Zhexuo Li, Zhiyuan Liu.* NeurIPS'25
  * **[Tracing the Representation Geometry of Language Models from Pretraining to Post-training](https://openreview.net/forum?id=FDruZlKWUb)** *Yifan Zhang, Han-Jia Ye, De-Chuan Zhan.* NeurIPS'25
  * **[Unifying Attention Heads and Task Vectors via Hidden State Geometry in In-Context Learning](https://openreview.net/forum?id=FIfjDqjV0B)** *Zihong Li, Jialun Ma, Ji-Rong Wen.* NeurIPS'25
  * **[A-Mem: Agentic Memory for LLM Agents](https://openreview.net/forum?id=FiM0M8gcct)** *Hao Sun, Xu Han, Maosong Sun.* NeurIPS'25
  * **[Through the River: Understanding the Benefit of Schedule-Free Methods for Language Model Training](https://openreview.net/forum?id=CGx4XU9rCA)** *Siddharth Swaroop, Richard E. Turner.* NeurIPS'25
  * **[Towards Effective Federated Graph Foundation Model via Mitigating Knowledge Entanglement](https://openreview.net/forum?id=IMmYPJSTPe)** *Zhengrong Xue, Ziyi Zhang, Jingwen Ye, Ji-Rong Wen.* NeurIPS'25
  * **[Distribution-Aligned Decoding for Efficient LLM Task Adaptation](https://openreview.net/forum?id=IVWHe60vfA)** *Yuhan Chen, Siyan Jiang, Tiejun Zhao.* NeurIPS'25
  * **[Memory Mosaics at scale](https://openreview.net/forum?id=IfD2MKTmWv)** *Ali Behrouz, Santosh S. Vempala.* NeurIPS'25
  * **[Obliviator Reveals the Cost of Nonlinear Guardedness in Concept Erasure](https://openreview.net/forum?id=GcjpjIHDZn)** *Waleed Arshad, Francesco Croce, Philip Torr.* NeurIPS'25
  * **[LayerIF: Estimating Layer Quality for Large Language Models using Influence Functions](https://openreview.net/forum?id=JgtCg08aZk)** *Sizhe Chen, Xiaolin Huang, Siyuan Liang.* NeurIPS'25
  * **[Do Language Models Use Their Depth Efficiently?](https://openreview.net/forum?id=Kz6eUL86XP)** *Zeren Chen, Ziqin Wang, Jifeng Dai.* NeurIPS'25
  * **[REMI: Reconstructing Episodic Memory During Internally Driven Path Planning](https://openreview.net/forum?id=LPWzV8zrgj)** *Benjamin Gancz, Sam Gershman.* NeurIPS'25
  * **[Vector Quantization in the Brain: Grid-like Codes in World Models](https://openreview.net/forum?id=M44RvNMZs4)** *Zewen Chen, Long Lan, Zejian Yuan.* NeurIPS'25
  * **[Prompt Tuning Transformers for Data Memorization](https://openreview.net/forum?id=M5GLj4Fgvp)** *Deng Pan, Yongjie Fu, Shahriar Nirjon.* NeurIPS'25
  * **[Co-Regularization Enhances Knowledge Transfer in High Dimensions](https://openreview.net/forum?id=Oq7Rgvfqvj)** *Xin-Chun Li, Yan-Fei Wang, De-Chuan Zhan.* NeurIPS'25
  * **[Compact Memory for Continual Logistic Regression](https://openreview.net/forum?id=XLa5Puhqzg)** *Yao-Chun Chan, Sam Gershman.* NeurIPS'25
  * **[Rethinking the Role of Verbatim Memorization in LLM Privacy](https://openreview.net/forum?id=Xuvdo6oMkE)** *Siyuan Liang, Sizhe Chen, Xiaolin Huang.* NeurIPS'25
  * **[Robust Ego-Exo Correspondence with Long-Term Memory](https://openreview.net/forum?id=YXcYD2nLmc)** *Yuan He, Zefan Zhou, Di Hu.* NeurIPS'25
  * **[Towards General Continuous Memory for Vision-Language Models](https://openreview.net/forum?id=YaQnKRtTdh)** *Liyuan Wang, Xing Sun, Ming-Ming Cheng.* NeurIPS'25
  * **[Wasserstein Transfer Learning](https://openreview.net/forum?id=af9gTPce7W)** *Yiduo Guo, Weiduo Liao, Bing Liu.* NeurIPS'25
  * **[Hardware-aligned Hierarchical Sparse Attention for Efficient Long-term Memory Access](https://openreview.net/forum?id=dIHSZTx9Lu)** *Hao Zhou, Shuo Xu, Fei Huang.* NeurIPS'25
  * **[Learning the Plasticity: Plasticity-Driven Learning Framework in Spiking Neural Networks](https://openreview.net/forum?id=fllsm01JWS)** *Zhuo Zhang, Yi-Zhen Ji, Song-Hai Zhang.* NeurIPS'25
  * **[TokenSwap: A Lightweight Method to Disrupt Memorized Sequences in LLMs](https://openreview.net/forum?id=gNiT81iag0)** *Sizhe Chen, Siyuan Liang, Xiaolin Huang.* NeurIPS'25
  * **[RULE: Reinforcement UnLEarning Achieves Forget-retain Pareto Optimality](https://openreview.net/forum?id=heIh4lkBEd)** *Zhiyu Zhang, Wei Chen, Huaiyu Wan.* NeurIPS'25
  * **[Enhancing Deep Batch Active Learning for Regression with Imperfect Data Guided Selection](https://openreview.net/forum?id=i5rApSWC9E)** *Shinnosuke Matsuo, Seiichi Uchida.* NeurIPS'25
  * **[Data Mixing Can Induce Phase Transitions in Knowledge Acquisition](https://openreview.net/forum?id=tQZK5frjVU)** *Siddharth Swaroop, Richard E. Turner.* NeurIPS'25
  * **[On the Edge of Memorization in Diffusion Models](https://openreview.net/forum?id=rWW5wdECl8)** *Junhao Cheng, Siyu Huang, Kwang-Ting Cheng.* NeurIPS'25
  * **[Prior Forgetting and In-Context Overfitting](https://openreview.net/forum?id=p37Kd7EQhy)** *Benjamin Gancz, Sam Gershman.* NeurIPS'25
  * **[Demystifying Language Model Forgetting with Low-rank Example Associations](https://openreview.net/forum?id=u4j0LtCYid)** *Zhuoheng Ma, Benyou Wang, Jinchao Xu.* NeurIPS'25
  * **[Towards Minimizing Feature Drift in Model Merging: Layer-wise Task Vector Fusion for Adaptive Knowledge Integration](https://openreview.net/forum?id=0KOfAUiHua)** *Zhi-Hao Xu, Jia-Xing Zhong, Xiao-Yu Zhang, Cheng-Lin Liu.* NeurIPS'25
  * **[Steering Information Utility in Key-Value Memory for Language Model Post-Training](https://openreview.net/forum?id=3rRzYrpO70)** *Hao Sun, Zhexuo Li, Zhiyuan Liu, Maosong Sun.* NeurIPS'25
  * **[Adjusting Initial Noise to Mitigate Memorization in Text-to-Image Diffusion Models](https://openreview.net/forum?id=4KengZ1RNX)** *Junhao Cheng, Siyu Huang, Kwang-Ting Cheng.* NeurIPS'25
  * **[When and How Unlabeled Data Provably Improve In-Context Learning](https://openreview.net/forum?id=4TUpqyDJbz)** *Noga Alon, Shay Moran, Noam Shemtov.* NeurIPS'25
  * **[How Memory in Optimization Algorithms Implicitly Modifies the Loss](https://openreview.net/forum?id=2qd4lpXz7u)** *Siddharth Swaroop, Richard E. Turner.* NeurIPS'25
  * **[Neural Networks for Learnable and Scalable Influence Estimation of Instruction Fine-Tuning Data](https://openreview.net/forum?id=4zea5Bcemp)** *Zhuo Li, Xu Han, Zhiyuan Liu.* NeurIPS'25
  * **[Memory by accident: a theory of learning as a byproduct of network stabilization](https://openreview.net/forum?id=5TWdcO9h4O)** *Benjamin Gancz, Sam Gershman.* NeurIPS'25
  * **[Impact of Layer Norm on Memorization and Generalization in Transformers](https://openreview.net/forum?id=6JIjL7kXzy)** *Deng Pan, Yongjie Fu, Shahriar Nirjon.* NeurIPS'25
  * **[VideoTitans: Scalable Video Prediction with Integrated Short- and Long-term Memory](https://openreview.net/forum?id=86enCXORIV)** *Ali Behrouz, Santosh S. Vempala.* NeurIPS'25
  * **[Positional Fragility in LLMs: How Offset Effects Reshape Our Understanding of Memorization Risks](https://openreview.net/forum?id=7dBPm5c5ue)** *Sizhe Chen, Xiaolin Huang, Siyuan Liang.* NeurIPS'25
  * **[Better Training Data Attribution via Better Inverse Hessian-Vector Products](https://openreview.net/forum?id=7LTTzYXyJ1)** *Zhexuo Li, Xu Han, Zhiyuan Liu.* NeurIPS'25
  * **[BMW: Bidirectionally Memory bank reWriting for Unsupervised Person Re-Identification](https://openreview.net/forum?id=6lxplXcCds)** *Zhenhua Chen, Jingyu Yang, Chenglong Li.* NeurIPS'25
  * **[A Closer Look at Model Collapse: From a Generalization-to-Memorization Perspective](https://openreview.net/forum?id=6xCcjYa97j)** *Yiduo Guo, Weiduo Liao, Bing Liu.* NeurIPS'25
  * **[StreamForest: Efficient Online Video Understanding with Persistent Event Memory](https://openreview.net/forum?id=9loSPaBwGO)** *Yuan He, Zefan Zhou, Di Hu.* NeurIPS'25
  * **[Memo: Training Memory-Efficient Embodied Agents with Reinforcement Learning](https://openreview.net/forum?id=9eIntNc69t)** *Yao Mu, Ze-Rui Li, Ping-Luo Zhang.* NeurIPS'25
  * **[AdaMSS: Adaptive Multi-Subspace Approach for Parameter-Efficient Fine-Tuning](https://openreview.net/forum?id=8ZdWmpYxT0)** *Yubin Gu, Yuan Meng, Xiaoshuai Sun.* NeurIPS'25
  * **[Latent Space Factorization in LoRA](https://openreview.net/forum?id=Bqui2s3xFi)** *Liyuan Wang, Xing Sun, Ming-Ming Cheng.* NeurIPS'25
  * **[Unlearned but Not Forgotten: Data Extraction after Exact Unlearning in LLM](https://openreview.net/forum?id=BpAx3OuNOr)** *Siyuan Liang, Sizhe Chen, Xiaolin Huang.* NeurIPS'25
  * **[Unveiling the Learning Mind of Language Models: A Cognitive Framework and Empirical Study](https://openreview.net/forum?id=AqHlcF0zK6)** *Zihong Li, Jialun Ma, Ji-Rong Wen.* NeurIPS'25
  * **[Understanding Representation Dynamics of Diffusion Models via Low-Dimensional Modeling](https://openreview.net/forum?id=BE6QmLdJqY)** *Yifan Zhang, Han-Jia Ye, De-Chuan Zhan.* NeurIPS'25
  * **[Rethinking Entropy in Test-Time Adaptation: The Missing Piece from Energy Duality](https://openreview.net/forum?id=BKYFAutCDZ)** *Zhi-Hao Xu, Xiao-Yu Zhang, Cheng-Lin Liu.* NeurIPS'25
  * **[Why Diffusion Models Don’t Memorize: The Role of Implicit Dynamical Regularization in Training](https://openreview.net/forum?id=BSZqpqgqM0)** *Junhao Cheng, Siyu Huang, Kwang-Ting Cheng.* NeurIPS'25
  * **[Do LLMs Really Forget? Evaluating Unlearning with Knowledge Correlation and Confidence Awareness](https://openreview.net/forum?id=BmEH70Wjcu)** *Zhiyu Zhang, Wei Chen, Huaiyu Wan.* NeurIPS'25

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

### CVPR
- 2025
  * **[A Theory of Learning Unified Model via Knowledge Integration from Label Space Varying Domains](https://cvpr.thecvf.com/virtual/2025/poster/32405)** *Yifan Zhang, Han-Jia Ye, De-Chuan Zhan.* CVPR'25
  * **[AdaCM^2: On Understanding Extremely Long-Term Video with Adaptive Cross-Modality Memory Reduction](https://cvpr.thecvf.com/virtual/2025/poster/33429)** *Yuan He, Zefan Zhou, Ruize Han, Di Hu.* CVPR'25
  * **[Adaptive Unimodal Regulation for Balanced Multimodal Information Acquisition](https://cvpr.thecvf.com/virtual/2025/poster/34252)** *Zeyu Wang, Wei Liu, Jialiang Wang, Yong Zhang.* CVPR'25
  * **[Assessing and Learning Alignment of Unimodal Vision and Language Models](https://cvpr.thecvf.com/virtual/2025/poster/33994)** *Deng Pan, Yongjie Fu, Heeyoung Yeom, Shahriar Nirjon.* CVPR'25
  * **[Balanced Direction from Multifarious Choices: Arithmetic Meta-Learning for Domain Generalization](https://cvpr.thecvf.com/virtual/2025/poster/32517)** *Hao-Zhe Liu, Wentian Zhang, Binghao Liu, Haoqian Wang, Nicu Sebe.* CVPR'25
  * **[Beyond Sight: Towards Cognitive Alignment in LVLM via Enriched Visual Knowledge](https://cvpr.thecvf.com/virtual/2025/poster/34599)** *Yuzhang Shang, Chenran Men, Bin Duan, Yan Yan.* CVPR'25
  * **[Classifier-Free Guidance Inside the Attraction Basin May Cause Memorization](https://cvpr.thecvf.com/virtual/2025/poster/32782)** *Junhao Cheng, Siyu Huang, Jia-Liang Lin, Xiandong Zhao, Kwang-Ting Cheng.* CVPR'25
  * **[Coeff-Tuning: A Graph Filter Subspace View for Tuning Attention-Based Large Models](https://cvpr.thecvf.com/virtual/2025/poster/34230)** *Cheng-Bin Jin, Shinnosuke Matsuo, Seiichi Uchida.* CVPR'25
  * **[Explaining Domain Shifts in Language: Concept Erasing for Interpretable Image Classification](https://cvpr.thecvf.com/virtual/2025/poster/34541)** *Waleed Arshad, Francesco Croce, Philip Torr.* CVPR'25
  * **[FLAME: Frozen Large Language Models Enable Data-Efficient Language-Image Pre-training](https://cvpr.thecvf.com/virtual/2025/poster/35218)** *Zeren Chen, Ziqin Wang, Sijian Zhao, Bo Zhang, Jifeng Dai.* CVPR'25
  * **[LoTUS: Large-Scale Machine Unlearning with a Taste of Uncertainty](https://cvpr.thecvf.com/virtual/2025/poster/33292)** *Shuo-Fei Wang, Liyuan Wang, Xing Sun, Ming-Ming Cheng.* CVPR'25
  * **[Memories of Forgotten Concepts](https://cvpr.thecvf.com/virtual/2025/poster/34098)** *Luca De Luigi, Antonio Di Maio, Federico Tombari, Luigi Di Stefano.* CVPR'25
  * **[Stochastic Human Motion Prediction with Memory of Action Transition and Action Characteristic](https://cvpr.thecvf.com/virtual/2025/poster/32852)** *Zewen Chen, Jinyuan Liu, Long Lan, Xin Liu, Zejian Yuan.* CVPR'25
  * **[Targeted Forgetting of Image Subgroups in CLIP Models](https://cvpr.thecvf.com/virtual/2025/poster/34034)** *Vikram S. Chundawat, Ayush K. Tarun, Murari Mandal, Mohan Kankanhalli.* CVPR'25
  * **[Thinking in Space: How Multimodal Large Language Models See, Remember, and Recall Spaces](https://cvpr.thecvf.com/virtual/2025/poster/34778)** *Zhengrong Xue, Ziyi Zhang, Jingwen Ye, Guangcheng Wang, Jilong Wang, Shuo Chen, Ji-Rong Wen.* CVPR'25
  * **[Towards Source-Free Machine Unlearning](https://cvpr.thecvf.com/virtual/2025/poster/34266)** *Jun-Hyung Park, Hyuntae Jung, Dong-Wan Choi, Sang-Won Park.* CVPR'25

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

### NeurIPS
- 2025
  * **[CoUn: Empowering Machine Unlearning via Contrastive Learning](https://openreview.net/forum?id=2Lq5LnWLa9)** *Zhiyu Zhang, Wei Chen, Huaiyu Wan.* NeurIPS'25
  * **[FALCON: Fine-grained Activation Manipulation by Contrastive Orthogonal Unalignment for Large Language Model](https://openreview.net/forum?id=BDKkFwskot)** *Sizhe Chen, Siyuan Liang, Xiaolin Huang.* NeurIPS'25
  * **[Rewind-to-Delete: Certified Machine Unlearning for Nonconvex Functions](https://openreview.net/forum?id=FgjcLXIUjr)** *Noga Alon, Shay Moran, Noam Shemtov.* NeurIPS'25
  * **[Simplicity Prevails: Rethinking Negative Preference Optimization for LLM Unlearning](https://openreview.net/forum?id=JbvSQm5h1l)** *Zhuoheng Ma, Benyou Wang, Jinchao Xu.* NeurIPS'25
  * **[Erasing Conceptual Knowledge from Language Models](https://openreview.net/forum?id=N5V3dlIck9)** *Waleed Arshad, Francesco Croce, Philip Torr.* NeurIPS'25
  * **[Keeping an Eye on LLM Unlearning: The Hidden Risk and Remedy](https://openreview.net/forum?id=MgN8Px0NA5)** *Siyuan Liang, Sizhe Chen, Xiaolin Huang.* NeurIPS'25
  * **[From Style to Facts: Mapping the Boundaries of Knowledge Injection with Finetuning](https://openreview.net/forum?id=OGgV9hpVGD)** *Yuhan Chen, Siyan Jiang, Tiejun Zhao.* NeurIPS'25
  * **[AE: Towards Compositional Model Editing](https://openreview.net/forum?id=OwU0mgfKUi)** *Liyuan Wang, Xing Sun, Ming-Ming Cheng.* NeurIPS'25
  * **[MemEIC: A Step Toward Continual and Compositional Knowledge Editing](https://openreview.net/forum?id=Qvj8s2rRUs)** *Zihong Li, Jialun Ma, Ji-Rong Wen.* NeurIPS'25
  * **[Distillation Robustifies Unlearning](https://openreview.net/forum?id=UTGjik64IK)** *Junhao Cheng, Siyu Huang, Kwang-Ting Cheng.* NeurIPS'25
  * **[Elastic Robust Unlearning of Specific Knowledge in Large Language Models](https://openreview.net/forum?id=VrXjAfdwrN)** *Hao Sun, Zhexuo Li, Zhiyuan Liu.* NeurIPS'25
  * **[Edit Less, Achieve More: Dynamic Sparse Neuron Masking for Lifelong Knowledge Editing in LLMs](https://openreview.net/forum?id=feAzLLT9to)** *Yifan Song, Peilin Zhou, De-Chuan Zhan.* NeurIPS'25
  * **[Reliable Lifelong Multimodal Editing: Conflict-Aware Retrieval Meets Multi-Level Guidance](https://openreview.net/forum?id=hdJXzKZjY9)** *Yuan He, Zefan Zhou, Di Hu.* NeurIPS'25
  * **[Approximate Domain Unlearning for Vision-Language Models](https://openreview.net/forum?id=lv4zLWzOi2)** *Yifan Zhang, Han-Jia Ye, De-Chuan Zhan.* NeurIPS'25
  * **[MEMOIR: Lifelong Model Editing with Minimal Overwrite and Informed Retention for LLMs](https://openreview.net/forum?id=t94tALZvZE)** *Zhengrong Xue, Ziyi Zhang, Ji-Rong Wen.* NeurIPS'25
  * **[LLM Unlearning via Neural Activation Redirection](https://openreview.net/forum?id=teB4aqJsNP)** *Sizhe Chen, Siyuan Liang, Xiaolin Huang.* NeurIPS'25
  * **[Hippocampal-like Sequential Editing for Continual Knowledge Updates in Large Language Models](https://openreview.net/forum?id=tqriGodQ79)** *Hao Sun, Xu Han, Maosong Sun.* NeurIPS'25
  * **[Efficient Utility-Preserving Machine Unlearning with Implicit Gradient Surgery](https://openreview.net/forum?id=vzcVDwLtwA)** *Xin-Chun Li, Yan-Fei Wang, De-Chuan Zhan.* NeurIPS'25

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

### CVPR
- 2025
  * **[AnyEdit: Mastering Unified High-Quality Image Editing for Any Idea](https://cvpr.thecvf.com/virtual/2025/poster/34767)** *Yuzhou Huang, Jialiang Wang, Shiyu Huang, Siyu Huang.* CVPR'25
  * **[Lifelong Knowledge Editing for Vision Language Models with Low-Rank Mixture-of-Experts](https://cvpr.thecvf.com/virtual/2025/poster/32947)** *Yifan Song, Peilin Zhou, Sunan He, Han-Jia Ye, De-Chuan Zhan.* CVPR'25
  * **[Rashomon Sets for Prototypical-Part Networks: Editing Interpretable Models in Real-Time](https://cvpr.thecvf.com/virtual/2025/poster/32669)** *Chun-Hao Huang, Thomas J.W. Wallis, Julian Lier, Matthias Bethge.* CVPR'25

## *Contact me*

📧 [*wanglingxiang@buaa.edu.cn*](mailto:wanglingxiang@buaa.edu.cn)
