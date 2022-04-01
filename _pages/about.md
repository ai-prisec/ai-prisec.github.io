---
permalink: /
author_profile: true
image: ../images/ai-sec.png
title: AI Privacy and Security Seminars
---

<br>This is the homepage of the **AI Privacy & Security (AI-PriSec) Interest Group**. It brings together researchers and practitioners around the world broadly interested in this topic. For the time being, it features recurring seminars, a couple of times a month, always on Sunday, around 10 AM (HK Time).  

### Get Involved
- Subscribe to our **[WeChat Public Account]()** to receive to seminar and job announcements
- Join our **[WeChat Group](https://drive.google.com/file/d/1SC-7k0xuDVc7r8B9nFeDPQVoxMQdPOGe/view?usp=sharing)** &ndash; this is particularly useful for students, who maintain an active working group with monthly (virtual) meet-ups
- Subscribe to our **[Bilibili Channel](https://space.bilibili.com/341626036?spm_id_from=333.337.0.0)** where we live stream and keep recordings of the talks




### Upcoming Seminars

<img src="../images/linzheng.png" style="float:right;width:100px;height:100px;margin-top:00px">
- 3 April 2022, 10:00 ([HK time](https://www.timeanddate.com/worldclock/fixedtime.html?msg=Seminar&iso=20220320T10&p1=102))  
**Lin Zheng (University of Hong Kong)**  
Information Bottleneck in Graph Structured Data     
[[WeMeet Registration](https://meeting.tencent.com/dw/Zjc8HaUveNK6)] [[Live Stream](https://meeting.tencent.com/dw/Zjc8HaUveNK6)]<details><br>**Abstract:** Graph Neural Networks (GNNs) are powerful to fuse information from network structure and node features. However, noise and redundancy in graph data make: 1) the prediction results lack interpretation; 2)GNNs are fragile to adversarial attacks. The theory of **information bottleneck (IB)** to can provide an effective way to optimally balances expressiveness and robustness of the learned representation of graph data. In this talk, the presenter will introduce enlightening instances in using IB to prune graph data to improve the robustness and maintain expressiveness at the same time.<br><br>**Bio:** Chenhan Zhang received B.E. degree and M.S degree from University of Wollongong and City University of Hong Kong and now is a PhD candidate at University of Technology Sydney. His research interests include graph neural networks, and robustness of machine learning, etc.<br></details>


<!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/Dn_NkH-IEVA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->



### Past Seminars

<img src="../images/chenhan.jpg" style="float:right;width:100px;height:100px;margin-top:00px">
- 20 March 2022, 10:00 ([HK time](https://www.timeanddate.com/worldclock/fixedtime.html?msg=Seminar&iso=20220320T10&p1=102))  
**Chenhan Zhang (University of Technology Sydney)**  
Linear Complexity Randomized Self-attention Mechanism    
[[WeMeet Registration](https://meeting.tencent.com/dm/oYHLplEriEmZ)] [[Live Stream](https://meeting.tencent.com/dm/oYHLplEriEmZ)]<details><br>**Abstract:** Attention mechanism is the core building block in many state-of-the-art models across various domains. It is powerful and expressive in capturing complicated and long-range dependencies within the input elements. Nevertheless, it does not scale efficiently to long sequences due to its quadratic time and space complexity in terms of the sequence length. In this talk, we will first discuss current strategies on reducing the time/space complexity of attention, and then focus on RFA, a particular linear attention variant that uses random feature methods to approximate the softmax function. Finally, we introduce a novel perspective to understand the approximation bias in RFA from the perspective of self-normalized importance sampling.<br><br>**Bio:** Lin Zheng received his B.E. degree from Sun Yat-sen University (SYSU) and now is a Ph.D. student at the University of Hong Kong (HKU), supervised by Lingpeng Kong. His research interests include machine learning and probabilistic inference.<br></details>


<img src="../images/yiliu.jfif" style="float:right;width:100px;height:100px;margin-top:00px">
- 6 March 2022, 10:00 ([HK time](https://www.timeanddate.com/worldclock/fixedtime.html?msg=Seminar&iso=20220206T10&p1=102))  
**Yi Liu (CityU)**  
BadBatch: Practical Data Poisoning Attack against Federated Learning via Manipulating Local Training Batch    
[[WeMeet Registration](https://meeting.tencent.com/dw/mD5ht1WOQQbQ)] [[Live Stream](https://meeting.tencent.com/dw/mD5ht1WOQQbQ)]<details><br>**Abstract:** Federated learning (FL) as a privacy-friendly collaborative learning framework benefits machine learning powered systems and services. Despite its advantages, FL is known to be vulnerable to poisoning attacks, where the adversary controls a set of clients to poison either the local training dataset or the local model update to degrade the global model performance. Existing poisoning attacks have demonstrated vast damage to FL, but they either require strong adversarial assumption on model and dataset knowledge of a certain number of clients, or rely on optimization-based attack methods that are normally expensive in a decentralized environment. In this paper, we propose a new practical poisoning attack against FL, named BadBatch, which can be launched in realistic settings of FL and does not rely on optimization. Our key observation is that by simply manipulating the local training batch, an adversary is capable of influencing global model performance and convergence. We propose gradient-oriented and model update-oriented attack strategies that focus on increasing the stochastic error of stochastic gradient descent and forcing the model to forget learned generalization features by finding bad batches. We also theoretically analyze the error upper bound and time complexity of our attack. Finally, we perform extensive experiments on two public datasets for convex and non-convex models, and evaluate our attacks against the latest defense, i.e., Byzantine robust aggregation. Our evaluation results show that Badbatch can achieve high attack performance than existing methods in a practical FL setting, shedding light on data poisoning attacks against practical FL.<br><br>**Bio:** Yi Liu received the B.Eng. degree in Network Engineering from Heilongjiang University, Harbin, China, in 2019. He is currently pursuing the Ph.D. degree with the Department of Computer Scince, City University of Hong Kong, Hong Kong, China. His research interests include security and privacy, federated learning, edge computing, and blockchain. Home: [https://yiliucs.github.io/](https://yiliucs.github.io/)<br></details>


<img src="../images/Zijing.jpg" style="float:right;width:100px;height:100px;margin-top:00px">
- 27 February 2022, 10:00 ([HK time](https://www.timeanddate.com/worldclock/fixedtime.html?msg=Seminar&iso=20220228T10&p1=102))  
**Zijing Ou (Tencent AI Lab)**  
Model Explanation with Shapley Values  
[[Recording](https://space.bilibili.com/341626036?spm_id_from=333.337.0.0)] [[Slide](https://drive.google.com/file/d/1L6idiKFWLioqKesi7zZ2qu5ewB9doEY6/view?usp=sharing)]<details><br>**Abstract:** Deep neural networks (DNNs) become increasingly important in many applications while lacking explanations for their excellent performance. **Shapley Value** provides a theoretical and practical explainer for DNNs. In this talk, the presenter will introduce the most recent progress in model explanation with Shapley value, including its estimation, uncertainty, and potential research areas.<br><br>**Bio:** Zijing Ou recently graduated with a B.E. degree from Sun Yat-sen University and now works as an intern in Tencent AI Lab. His research interests include approximate inference, energy-based models, and interpretable AI. His research has been published at venues including IJCAI, ACL, EMNLP, etc. He also works as a reviewer for ICML, IJCAI, ACL, etc. Home: [https://j-zin.github.io/](https://j-zin.github.io/)<br>


### Organizers
- Prof. Yi Wu, HLJU, Harbin
- [Prof. Jiawen Kang](https://teacher.gdut.edu.cn/kangjiawen/zh_CN/index/204229/list/index.htm), GUDT, Guangzhou
- [Mr. Yi Liu](https://yiliucs.github.io/), CityU, Hong Kong
- [Mr. Zijing Ou](https://j-zin.github.io/), Tencent AI Lab, Shenzhen
- TBA


