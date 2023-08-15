<h1 align="center"> Awesome Table Question Answering </h1>

<p align="center">
  <a href="https://github.com/RenzeLou/awesome-instruction-learning"><img src="https://awesome.re/badge.svg" alt="Awesome" /></a>
</p>

<p align="center">
🔥🔥🔥 An awesome paper list of <b>Table-based Question Answering</b>. 
</p>


## Paper

### Dataset

#### Single-Turn

1. **Compositional Semantic Parsing on Semi-Structured Tables** `WikiTableQuestions` 2015
  
    [[Paper](https://arxiv.org/abs/1508.00305)] [[Code](https://ppasupat.github.io/WikiTableQuestions/)] *EPanupong Pasupat, Percy Liang* 
   
2. **Seq2SQL: Generating Structured Queries from Natural Language using Reinforcement Learning** `WikiSQL` 2017

    [[Paper](https://arxiv.org/abs/1709.00103)] [[Code](https://github.com/salesforce/WikiSQL)] *Victor Zhong, Caiming Xiong, Richard Socher*

3. **Spider: A Large-Scale Human-Labeled Dataset for Complex and Cross-Domain Semantic Parsing and Text-to-SQL Task** `Spider` <ins>EMNLP</ins> 2018

    [[Paper](https://arxiv.org/abs/1809.08887)] [[Code](https://github.com/taoyds/spider)] *Tao Yu, Rui Zhang, Kai Yang, Michihiro Yasunaga, Dongxu Wang, Zifan Li, James Ma, Irene Li, Qingning Yao, Shanelle Roman, Zilin Zhang, Dragomir Radev*
   
4. **HybridQA: A Dataset of Multi-Hop Question Answering over Tabular and Textual Data** `HybridQA` <ins>EMNLP-Findings</ins> 2020
    
    [[Paper](https://aclanthology.org/2020.findings-emnlp.91/)] [[Code](https://github.com/wenhuchen/HybridQA)]*Wenhu Chen, Hanwen Zha, Zhiyu Chen, Wenhan Xiong, Hong Wang, William Yang Wang*

5. **TSQA: tabular scenario based question answering** `GeoTSQA` <ins>AAAI</ins> 2021
    
    [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/17570)] [[Code](https://github.com/nju-websoft/TSQA)]*Xiao Li, Yawei Sun, Gong Cheng*

6. **TAT-QA: A Question Answering Benchmark on a Hybrid of Tabular and Textual Content in Finance** `TAT-QA` <ins>ACL</ins> 2021
    
    [[Paper](https://aclanthology.org/2021.acl-long.254/)] [[Code](https://github.com/NExTplusplus/TAT-QA)]*Fengbin Zhu, Wenqiang Lei, Youcheng Huang, Chao Wang, Shuo Zhang, Jiancheng Lv, Fuli Feng, Tat-Seng Chua*


7. **Open Domain Question Answering over Tables via Dense Retrieval** `NQ-table` <ins>NAACL</ins> 2021
   
    [[Paper](https://aclanthology.org/2021.naacl-main.43/)] [[Code](https://github.com/google-research/tapas)]*Jonathan Herzig, Thomas Müller, Syrine Krichene, Julian Eisenschlos* 

8. **Open Question Answering over Tables and Text** `OTT-QA` <ins>ICLR</ins> 2021
   
    [[Paper](https://arxiv.org/abs/2010.10439)] [[Code](https://github.com/wenhuchen/OTT-QA)]*Wenhu Chen, Ming-Wei Chang, Eva Schlinger, William Wang, William W. Cohen* 

9. **MultiModalQA: complex question answering over text, tables and images** `MultimodalQA` <ins>ICLR</ins> 2021
   
    [[Paper](https://openreview.net/forum?id=ee6W5UgQLa)] [[Code](https://github.com/allenai/multimodalqa)]*Alon Talmor, Ori Yoran, Amnon Catav, Dan Lahav, Yizhong Wang, Akari Asai, Gabriel Ilharco, Hannaneh Hajishirzi, Jonathan Berant* 

10. **Finqa: A dataset of numerical reasoning over financial data** `FinQA` <ins>EMNLP</ins> 2021
   
    [[Paper](https://arxiv.org/abs/2109.00122)] [[Code](https://github.com/czyssrs/FinQA)] *Zhiyu Chen, Wenhu Chen, Charese Smiley, Sameena Shah, Iana Borova, Dylan Langdon, Reema Moussa, Matt Beane, Ting-Hao Huang, Bryan Routledge, William Yang Wang* 

11. **HiTab: A Hierarchical Table Dataset for Question Answering and Natural Language Generation** `HiTab` <ins>ACL</ins> 2022
    
    [[Paper](https://aclanthology.org/2022.acl-long.78/)] [[Code](https://github.com/microsoft/hitab)]*Zhoujun Cheng, Haoyu Dong, Zhiruo Wang, Ran Jia, Jiaqi Guo, Yan Gao, Shi Han, Jian-Guang Lou, Dongmei Zhang*

12. **FeTaQA: Free-form Table Question Answering** `FeTaQA` <ins>TACL</ins> 2022
    
    [[Paper](https://aclanthology.org/2022.tacl-1.3/)] [[Code](https://github.com/Yale-LILY/FeTaQA)]*Linyong Nan, Chiachun Hsieh, Ziming Mao, Xi Victoria Lin, Neha Verma, Rui Zhang, Wojciech Kryściński, Hailey Schoelkopf, Riley Kong, Xiangru Tang, Mutethia Mutuma, Ben Rosand, Isabel Trindade, Renusree Bandaru, Jacob Cunningham, Caiming Xiong, Dragomir Radev, Dragomir Radev

13. **MultiHiertt: Numerical Reasoning over Multi Hierarchical Tabular and Textual Data** `MultiHiertt` <ins>ACL</ins> 2022
    
    [[Paper](https://aclanthology.org/2022.acl-long.454)] [[Code](https://github.com/psunlpgroup/MultiHiertt)]*Yilun Zhao, Yunxiang Li, Chenying Li, Rui Zhang*

14. **Learning to Imagine: Integrating Counterfactual Thinking in Neural Discrete Reasoning** `TAT-HQA` <ins>ACL</ins> 2022
    
    [[Paper](https://aclanthology.org/2022.acl-long.5.pdf)]*Moxin Li, Fuli Feng, Hanwang Zhang, Xiangnan He, Fengbin Zhu, Tat-Seng Chua*

15. **Towards Complex Document Understanding By Discrete Reasoning** `TAT-DQA` <ins>ACM MM</ins> 2022
    
    [[Paper](https://dl.acm.org/doi/abs/10.1145/3503161.3548422)]*Fengbin Zhu, Wenqiang Lei, Fuli Feng, Chao Wang, Haozhou Zhang, Tat-Seng Chua*

16. **AIT-QA: Question Answering Dataset over Complex Tables in the Airline Industry** `AIT-QA` <ins>NAACL</ins> 2022
    
    [[Paper](https://aclanthology.org/2022.naacl-industry.34/)] [[Code](https://github.com/IBM/AITQA)]*Yannis Katsis, Saneem Chemmengath, Vishwajeet Kumar, Samarth Bharadwaj, Mustafa Canim, Michael Glass, Alfio Gliozzo, Feifei Pan, Jaydeep Sen, Karthik Sankaranarayanan, Soumen Chakrabarti*

#### Multiple-Turn

1. **PACIFIC: Towards proactive conversational question answering over tabular and textual data in finance** `Pacific` <ins>EMNLP</ins> 2022
    
    [[Paper](https://arxiv.org/abs/2210.08817)] [[Code](https://github.com/dengyang17/PACIFIC/)]*Yang Deng, Wenqiang Lei, Wenxuan Zhang, Wai Lam, Tat-Seng Chua*

2. **ConvFinQA: Exploring the Chain of Numerical Reasoning in Conversational Finance Question Answering** `ConvFinQA` <ins>EMNLP</ins> 2022
    
    [[Paper](https://aclanthology.org/2022.emnlp-main.421/)] [[Code](https://github.com/czyssrs/ConvFinQA)]*Zhiyu Chen, Shiyang Li, Charese Smiley, Zhiqiang Ma, Sameena Shah, William Yang Wang*

3. **HybriDialogue: An Information-Seeking Dialogue Dataset Grounded on Tabular and Textual Data** `HybriDialogue` <ins>EMNLP-Findings</ins> 2022
    
    [[Paper](https://aclanthology.org/2022.findings-acl.41/)] [[Code](https://github.com/entitize/HybridDialogue)]*Kai Nakamura, Sharon Levy, Yi-Lin Tuan, Wenhu Chen, William Yang Wang*
   

4. **MMCoQA: Conversational Question Answering over Text, Tables, and Images** `MMCoQA` <ins>ACL</ins> 2022
    
    [[Paper](https://aclanthology.org/2022.acl-long.290/)] [[Code](https://github.com/liyongqi67/mmcoqa)]*Yongqi Li, Wenjie Li, Liqiang Nie*



### Methods






### Existing Survey
1. **A survey on table question answering: recent advances** 2022
   
   [[Paper](https://arxiv.org/pdf/2207.05270.pdf)]*Nengzheng Jin, Joanna Siebert, Dongfang Li, Qingcai Chen*

2. **A Survey on Table-and-Text HybridQA: Concepts, Methods, Challenges and Future Directions** 2022.12
   
   [[Paper](https://arxiv.org/abs/2212.13465)]*Dingzirui Wang, Longxu Dou, Wanxiang Che*















