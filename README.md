# llm-hallucination-survey
![](https://img.shields.io/badge/PRs-welcome-brightgreen) 

`Hallucination` refers to the generated content that is nonsensical or unfaithful to the provided source content or even world knowledge.

This issue can hinder the real-world adoption of LLMs in various applications and scenarios.

## News
We have uploaded a comprehensive survey about hallucination in large language models, which discussed the evaluation, explanation, and mitigation. Check it out!

[Siren's Song in the AI Ocean: A Survey on Hallucination in Large Language Models](https://arxiv.org/abs/2309.01219)


## Evaluation of Hallucination for LLMs
1. **TruthfulQA: Measuring How Models Mimic Human Falsehoods**
   
   *Stephanie Lin, Jacob Hilton, Owain Evans* [[paper]](https://aclanthology.org/2022.acl-long.229/) 2022.5
   
1. **A Token-level Reference-free Hallucination Detection Benchmark for Free-form Text Generation**
   
   *Tianyu Liu, Yizhe Zhang, Chris Brockett, Yi Mao, Zhifang Sui, Weizhu Chen, Bill Dolan* [[paper]](https://aclanthology.org/2022.acl-long.464/) 2022.5


1. **Towards Tracing Factual Knowledge in Language Models Back to the Training Data**
   
   *Ekin Akyürek, Tolga Bolukbasi, Frederick Liu, Binbin Xiong, Ian Tenney, Jacob Andreas, Kelvin Guu* [[paper]](https://arxiv.org/abs/2205.11482) 2022.5

1. **A Multitask, Multilingual, Multimodal Evaluation of ChatGPT on Reasoning, Hallucination, and Interactivity**
   
   *Yejin Bang, Samuel Cahyawijaya, Nayeon Lee, Wenliang Dai, Dan Su, Bryan Wilie, Holy Lovenia, Ziwei Ji, Tiezheng Yu, Willy Chung, Quyet V. Do, Yan Xu, Pascale Fung* [[paper]](https://arxiv.org/abs/2302.04023) 2023.2

1. **Why Does ChatGPT Fall Short in Providing Truthful Answers?**
   
   *Shen Zheng, Jie Huang, Kevin Chen-Chuan Chang* [[paper]](https://arxiv.org/abs/2304.10513) 2023.4

1. **HaluEval: A Large-Scale Hallucination Evaluation Benchmark for Large Language Models**
   
   *Junyi Li, Xiaoxue Cheng, Wayne Xin Zhao, Jian-Yun Nie, Ji-Rong Wen* [[paper]](https://arxiv.org/abs/2305.11747) 2023.5
   
1. **Automatic Evaluation of Attribution by Large Language Models**
   
   *Xiang Yue, Boshi Wang, Kai Zhang, Ziru Chen, Yu Su, Huan Sun* [[paper]](https://arxiv.org/abs/2305.06311) 2023.5
   
1. **Adaptive Chameleon or Stubborn Sloth: Unraveling the Behavior of Large Language Models in Knowledge Clashes**
   
   *Jian Xie, Kai Zhang, Jiangjie Chen, Renze Lou, Yu Su* [[paper]](https://arxiv.org/abs/2305.13300) 2023.5
   
1. **LLMs as Factual Reasoners: Insights from Existing Benchmarks and Beyond**
   
   *Philippe Laban, Wojciech Kryściński, Divyansh Agarwal, Alexander R. Fabbri, Caiming Xiong, Shafiq Joty, Chien-Sheng Wu* [[paper]](https://arxiv.org/abs/2305.14540) 2023.5
   
1. **Evaluating the Factual Consistency of Large Language Models Through News Summarization**
   
   *Derek Tam, Anisha Mascarenhas, Shiyue Zhang, Sarah Kwan, Mohit Bansal, Colin Raffel* [[paper]](https://aclanthology.org/2023.findings-acl.322/) 2023.5
   
1. **Methods for Measuring, Updating, and Visualizing Factual Beliefs in Language Models**
   
   *Peter Hase, Mona Diab, Asli Celikyilmaz, Xian Li, Zornitsa Kozareva, Veselin Stoyanov, Mohit Bansal, Srinivasan Iyer* [[paper]](https://aclanthology.org/2023.eacl-main.199/) 2023.5
   
1. **How Language Model Hallucinations Can Snowball**
   
   *Muru Zhang, Ofir Press, William Merrill, Alisa Liu, Noah A. Smith* [[paper]](https://arxiv.org/abs/2305.13534) 2023.5
   
1. **Self-contradictory Hallucinations of Large Language Models: Evaluation, Detection and Mitigation**
   
   *Niels Mündler, Jingxuan He, Slobodan Jenko, Martin Vechev* [[paper]](https://arxiv.org/abs/2305.15852) 2023.5
  
1. **Evaluating Factual Consistency of Texts with Semantic Role Labeling**
   
   *Jing Fan, Dennis Aumiller, Michael Gertz* [[paper]](https://arxiv.org/abs/2305.13309) 2023.5
   
1. **FActScore: Fine-grained Atomic Evaluation of Factual Precision in Long Form Text Generation**
   
   *Sewon Min, Kalpesh Krishna, Xinxi Lyu, Mike Lewis, Wen-tau Yih, Pang Wei Koh, Mohit Iyyer, Luke Zettlemoyer, Hannaneh Hajishirzi* [[paper]](https://arxiv.org/abs/2305.14251) 2023.5
   
1. **Sources of Hallucination by Large Language Models on Inference Tasks**
   
   *Nick McKenna, Tianyi Li, Liang Cheng, Mohammad Javad Hosseini, Mark Johnson, Mark Steedman* [[paper]](https://arxiv.org/abs/2305.14552) 2023.5
   
1. **KoLA: Carefully Benchmarking World Knowledge of Large Language Models**
   
   *Jifan Yu, Xiaozhi Wang, Shangqing Tu, Shulin Cao, Daniel Zhang-Li, Xin Lv, Hao Peng, Zijun Yao, Xiaohan Zhang, Hanming Li, Chunyang Li, Zheyuan Zhang, Yushi Bai, Yantao Liu, Amy Xin, Nianyi Lin, Kaifeng Yun, Linlu Gong, Jianhui Chen, Zhili Wu, Yunjia Qi, Weikai Li, Yong Guan, Kaisheng Zeng, Ji Qi, Hailong Jin, Jinxin Liu, Yu Gu, Yuan Yao, Ning Ding, Lei Hou, Zhiyuan Liu, Bin Xu, Jie Tang, Juanzi Li* [[paper]](https://arxiv.org/abs/2306.09296) 2023.6
   
1. **Generating Benchmarks for Factuality Evaluation of Language Models**
   
   *Dor Muhlgay, Ori Ram, Inbal Magar, Yoav Levine, Nir Ratner, Yonatan Belinkov, Omri Abend, Kevin Leyton-Brown, Amnon Shashua, Yoav Shoham* [[paper]](https://arxiv.org/abs/2307.06908) 2023.7
   
1. **Overthinking the Truth: Understanding how Language Models Process False Demonstrations**
   
   *Danny Halawi, Jean-Stanislas Denain, Jacob Steinhardt* [[paper]](https://arxiv.org/abs/2307.09476) 2023.7
      
1. **Fact-Checking of AI-Generated Reports**
   
   *Razi Mahmood, Ge Wang, Mannudeep Kalra, Pingkun Yan* [[paper]](https://arxiv.org/abs/2307.14634) 2023.7
      
1. **Evaluating Correctness and Faithfulness of Instruction-Following Models for Question Answering**
   
   *Vaibhav Adlakha, Parishad BehnamGhader, Xing Han Lu, Nicholas Meade, Siva Reddy* [[paper]](https://arxiv.org/abs/2307.16877) 2023.7
      
1. **Med-HALT: Medical Domain Hallucination Test for Large Language Models**
   
   *Logesh Kumar Umapathi, Ankit Pal, Malaikannan Sankarasubbu* [[paper]](https://arxiv.org/abs/2307.15343) 2023.7
      
1. **Head-to-Tail: How Knowledgeable are Large Language Models (LLM)? A.K.A. Will LLMs Replace Knowledge Graphs?**
   
   *Kai Sun, Yifan Ethan Xu, Hanwen Zha, Yue Liu, Xin Luna Dong* [[paper]](https://arxiv.org/abs/2308.10168) 2023.8
      
1. **Large Language Models on Wikipedia-Style Survey Generation: an Evaluation in NLP Concepts**
   
   *Fan Gao, Hang Jiang, Moritz Blum, Jinghui Lu, Yuang Jiang, Irene Li* [[paper]](https://arxiv.org/abs/2308.10410) 2023.8
   
## Mitigation of Hallucination for LLMs
1. **Factuality Enhanced Language Models for Open-Ended Text Generation**
   
   *Nayeon Lee, Wei Ping, Peng Xu, Mostofa Patwary, Pascale Fung, Mohammad Shoeybi, Bryan Catanzaro* [[paper]](https://arxiv.org/abs/2206.04624) 2022.6
   
1. **Check Your Facts and Try Again: Improving Large Language Models with External Knowledge and Automated Feedback**
   
   *Baolin Peng, Michel Galley, Pengcheng He, Hao Cheng, Yujia Xie, Yu Hu, Qiuyuan Huang, Lars Liden, Zhou Yu, Weizhu Chen, Jianfeng Gao* [[paper]](https://arxiv.org/abs/2302.12813) 2023.2

1. **SelfCheckGPT: Zero-Resource Black-Box Hallucination Detection for Generative Large Language Models**
   
   *Potsawee Manakul, Adian Liusie, Mark J. F. Gales* [[paper]](https://arxiv.org/abs/2303.08896) 2023.3

1. **Zero-shot Faithful Factual Error Correction**
   
   *Kung-Hsiang Huang, Hou Pong Chan, Heng Ji* [[paper]](https://arxiv.org/abs/2305.07982) 2023.5

1. **CRITIC: Large Language Models Can Self-Correct with Tool-Interactive Critiquing**
   
   *Zhibin Gou, Zhihong Shao, Yeyun Gong, Yelong Shen, Yujiu Yang, Nan Duan, Weizhu Chen* [[paper]](https://arxiv.org/abs/2305.11738) 2023.5

1. **PURR: Efficiently Editing Language Model Hallucinations by Denoising Language Model Corruptions**
   
   *Anthony Chen, Panupong Pasupat, Sameer Singh, Hongrae Lee, Kelvin Guu* [[paper]](https://arxiv.org/abs/2305.14908) 2023.5

1. **Mitigating Language Model Hallucination with Interactive Question-Knowledge Alignment**
   
   *Shuo Zhang, Liangming Pan, Junzhou Zhao, William Yang Wang* [[paper]](https://arxiv.org/abs/2305.13669) 2023.5

1. **Improving Factuality and Reasoning in Language Models through Multiagent Debate**
   
   *Yilun Du, Shuang Li, Antonio Torralba, Joshua B. Tenenbaum, Igor Mordatch* [[paper]](https://arxiv.org/abs/2305.14325) 2023.5

1. **Enabling Large Language Models to Generate Text with Citations**
   
   *Tianyu Gao, Howard Yen, Jiatong Yu, Danqi Chen* [[paper]](https://arxiv.org/abs/2305.14627) 2023.5

1. **Verify-and-Edit: A Knowledge-Enhanced Chain-of-Thought Framework**
   
   *Ruochen Zhao, Xingxuan Li, Shafiq Joty, Chengwei Qin, Lidong Bing* [[paper]](https://arxiv.org/abs/2305.03268) 2023.5

1. **Trusting Your Evidence: Hallucinate Less with Context-aware Decoding**
   
   *Weijia Shi, Xiaochuang Han, Mike Lewis, Yulia Tsvetkov, Luke Zettlemoyer, Scott Wen-tau Yih* [[paper]](https://arxiv.org/abs/2305.14739) 2023.5
   
1. **Self-Checker: Plug-and-Play Modules for Fact-Checking with Large Language Models**
   
   *Miaoran Li, Baolin Peng, Zhu Zhang* [[paper]](https://arxiv.org/abs/2305.14623) 2023.5

1. **Augmented Large Language Models with Parametric Knowledge Guiding**
   
   *Ziyang Luo, Can Xu, Pu Zhao, Xiubo Geng, Chongyang Tao, Jing Ma, Qingwei Lin, Daxin Jiang* [[paper]](https://arxiv.org/abs/2305.04757) 2023.5

1. **LLMs as Factual Reasoners: Insights from Existing Benchmarks and Beyond**
   
   *Philippe Laban, Wojciech Kryściński, Divyansh Agarwal, Alexander R. Fabbri, Caiming Xiong, Shafiq Joty, Chien-Sheng Wu* [[paper]](https://arxiv.org/abs/2305.14540) 2023.5
   
1. **LM vs LM: Detecting Factual Errors via Cross Examination**
   
   *Theodore Zhao, Mu Wei, J. Samuel Preston, Hoifung Poon* [[paper]](https://arxiv.org/abs/2305.13281) 2023.5

1. **Measuring and Modifying Factual Knowledge in Large Language Models**
   
   *Pouya Pezeshkpour* [[paper]](https://arxiv.org/abs/2306.06264) 2023.6

1. **Inference-Time Intervention: Eliciting Truthful Answers from a Language Model**
   
   *Kenneth Li, Oam Patel, Fernanda Viégas, Hanspeter Pfister, Martin Wattenberg* [[paper]](https://arxiv.org/abs/2306.03341) 2023.6

1. **LLM Calibration and Automatic Hallucination Detection via Pareto Optimal Self-supervision**
   
   *Theodore Zhao, Mu Wei, J. Samuel Preston, Hoifung Poon* [[paper]](https://arxiv.org/abs/2306.16564) 2023.6

1. **A Stitch in Time Saves Nine: Detecting and Mitigating Hallucinations of LLMs by Validating Low-Confidence Generation**

   *Neeraj Varshney, Wenlin Yao, Hongming Zhang, Jianshu Chen, Dong Yu* [[paper]](https://arxiv.org/abs/2307.03987) 2023.7

1. **FacTool: Factuality Detection in Generative AI -- A Tool Augmented Framework for Multi-Task and Multi-Domain Scenarios**

   *I-Chun Chern, Steffi Chern, Shiqi Chen, Weizhe Yuan, Kehua Feng, Chunting Zhou, Junxian He, Graham Neubig, Pengfei Liu* [[paper]](https://arxiv.org/abs/2307.13528) 2023.7

1. **Halo: Estimation and Reduction of Hallucinations in Open-Source Weak Large Language Models**

   *Mohamed Elaraby, Mengyin Lu, Jacob Dunn, Xueying Zhang, Yu Wang, Shizhu Liu* [[paper]](https://arxiv.org/abs/2308.11764) 2023.8

1. **PREFER: Prompt Ensemble Learning via Feedback-Reflect-Refine**

   *Chenrui Zhang, Lin Liu, Jinpeng Wang, Chuyuan Wang, Xiao Sun, Hongyu Wang, Mingchen Cai* [[paper]](https://arxiv.org/abs/2308.12033) 2023.8

