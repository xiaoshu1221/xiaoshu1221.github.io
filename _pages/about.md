---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='About-Me'></span>

Hi! I am Yalun Wu (吴亚伦 in Chinese). I am a Ph.D. student in the [School of Computer and Information Techonoly](https://scit.bjtu.edu.cn/)  at [Beijing Jiaotong University](https://bjtu.edu.cn/), and affiliated with the Beijing Key Laboratory of Security and Privacy in Intelligent Transportation. I am advised by Prof. [Zhen Han](http://faculty.bjtu.edu.cn/5608/), [Wenjia Niu](http://faculty.bjtu.edu.cn/9120/) and Assistant Prof. [Endong Tong](http://faculty.bjtu.edu.cn/9306/). Prior to my Ph.D. career, I received the B.S. degree in communication engineering from [Qingdao Agricultural University](https://www.qau.edu.cn/) in 2017, and the M.S. degree in software engineering from [Beijing Jiaotong University](https://bjtu.edu.cn/) in 2022.

Currently, my research has centered on:

- **AI Security:** backdoor attacks and defenses, adversarial attacks and defenses.

* **Safety Testing**:  testing and evaluation for autonomous driving algorithms, modules, and systems.

* **Data Augmentation**: image or video generation, especially focus on generative data augmentation (GDA) in autonomous driving scenarios.

* **Autonomous Driving Security**: attacks and defenses against the physical world, sensors, algorithms and automonous driving systems.

* **Reinforcement Learning**: safety reinforcement learning (SRL), robustness reinforcement learning and offline reinforcement learning for autonomous driving systems.

📮: I am always looking for related colaboration. If you are interested to chat with me, feel free to drop me an <a href="mailto:wuyalun1@bjtu.edu.cn" target="_blank">email</a>.

<span class='anchor' id='News'></span>
# 🔥 新闻动态
- *2024.05:* 祝贺！我与团队成员合作的一篇论文被国际学术会议 KSEM 2024 （CCF-C）录用！🎉🎉🎉
- *2024.02:* 一篇论文被国际学术期刊IEEE Network（JCR Q1/中科院二区，影响因子9.3）录用.
- *2023.12:* 祝贺！我们班（计算机学院22级博士2班）荣获“北京市先进班集体”荣誉称号. 🎉🎉🎉
- *2023.12:* 祝贺！我们班（计算机学院22级博士2班）荣获北京交通大学“研究生先进班集体”荣誉称号. 🎉🎉🎉
- *2023.12:* 我荣获北京交通大学“企业专项奖学金”.
- *2023.12:* 我荣获北京交通大学校级“社会工作优秀奖学金”.
- *2023.12:* 我荣获北京交通大学校级“优秀研究生干部”荣誉称号.
- *2023.09:* 一篇论文被国际学术期刊Applied Sciences（JCR Q2/中科院四区）录用.
- *2022.12*: 我荣获北京交通大学2022-2023学年“优秀兼职辅导员”荣誉称号.
- 2022.08: 祝贺！我们“六出祁山”战队在第30届DEFCON自动驾驶CTF全球挑战赛中荣获亚军！相关团队新闻链接：[[“六出祁山”战队@北京交通大学](https://scit.bjtu.edu.cn/cms/item/5040.html)], [[白泽战队@复旦大学](https://secsys.fudan.edu.cn/ff/46/c26973a458566/page.htm)]. 🎉🎉🎉 
- *2022.06*: 我从[北京交通大学](https://bjtu.edu.cn/)毕业（软件工程专业），荣获电子信息硕士专业学位！
- *2022.02:* 祝贺！我与团队成员参加国家重大网络安全试验测试活动，荣获鹏城实验室、中国网络空间安全人才教育论坛（“网教盟”）、中国网络空间新兴技术安全创新论坛（“新安盟”）感谢信！ 🎉 [[新闻链接](https://scit.bjtu.edu.cn/cms/item/4891.html)]
- *2022.01:* 祝贺！我与团队成员参加国家重大活动安全测试，为相应信息系统加固及安全运行作出了贡献，荣获团体一等奖！ 🎉🎉🎉 [[新闻链接](https://scit.bjtu.edu.cn/cms/item/4906.html)]
- 2021.08: 祝贺！我们“六出祁山”战队在第29届DEFCON自动驾驶CTF全球挑战赛中荣获亚军！相关团队新闻链接：[[“六出祁山”战队@北京交通大学](http://scit.bjtu.edu.cn/mobile/item/4790.html)], [[Cacti@纽约州立大学布法罗分校](https://engineering.buffalo.edu/computer-science-engineering/news-and-events/news.host.html/content/shared/engineering/home/articles/news-articles/2021/team-cacti-places-5th-at-baidu-autodriving-capture-the-flag-comp.detail.html)], [[Redbud@清华大学](https://netsec.ccert.edu.cn/eng/hacking/2021-08-06-autodrive-defcon)]！🎉🎉🎉 

<span class='anchor' id='Publications'></span>

# 📝 代表性成果

1. **Yalun Wu**, Yingxiao Xiang, Endong Tong, Yuqi Ye, Zhibo Cui, Yunzhe Tian, Lejun Zhang, Jiqiang Liu, Zhen Han. Wenjia Niu. Improving the Robustness of Pedestrian Detection in Autonomous Driving with Generative Data Augmentation. IEEE Network, 2024 (early access). <font color="#E56701"><b>(JCR Q1/中科院二区, IF: 9.3)</b></font> 
2. **Yalun Wu**, Yanfeng Gu, Yuanwan Chen, Xiaoshu Cui, Qiong Li, Yingxiao Xiang, Endong Tong, Jianhua Li, Zhen Han, Jiqiang Liu. Camouflage Backdoor Attack against Pedestrian Detection. Applied Sciences, 2023, 13(23):12752. <font color="#E56701"><b>(JCR Q2/中科院四区)</b></font> 
3. Xiaoshu Cui, **Yalun Wu**, Yanfeng Gu, Qiong Li, Endong Tong, Jiqiang Liu, Wenjia Niu. Lurking in the Shadows: Imperceptible Shadow Black-Box Attacks against Lane Detection Models. International Conference on Knowledge Science, Engineering and Management (KSEM), 2024. <font color="#E56701"><b>(KSEM'2024, CCF-C)</b></font> 
4. Qiong Li, **Yalun Wu**, Yingqi Cai, Xiaoshu Cui, Yanfeng Gu, Yuanwan Chen, Endong Tong, Jiqiang Liu, Wenjia Niu. Caution: Pedestrian Ahead! Revealing Deceptive Threats to Pedestrian Detectors.  IEEE Consumer Electronics Magazine, in press, 2024. <font color="#E56701"><b>(JCR Q1/中科院四区)</b></font> 
5. Ziyan Qiao, Yingxiao Xiang, t.shamsa, Gang Li, **Yalun Wu**, Endong Tong, Shuanghe Peng, Ye Zhu, Dongwei Xu, Wenjia Niu. Reinforcement Learning-based Security Enhancement for Controlled Optimization of Phases in Intelligent Traffic Signal System. IEEE Transactions on Industrial Cyber-Physical Systems, in press, 2024. <font color="#E56701"><b>(IEEE汇刊)</b></font>
6. Yike Li, Jiayin Song, Yunzhe Tian, Endong Tong, Yuling Liu, Guozhu Meng, **Yalun Wu**, jianhua Li, Wenjia Niu, jiqiang Liu. Towards Preventing Imitation Learning Attack via Policy Confusion Defense. Transactions on Dependable and Secure Computing (TDSC), in press, 2023. <font color="#E56701"><b>(IEEE汇刊, JCR Q1/中科院二区, CCF-A)</b></font> 
7. Pengna Liu, Ziyan Qiao, **Yalun Wu**, Kang Chen, Jiasong Hou, Yingqi Cai, Liqun Chu, Endong Tong, Wenjia Niu, Jiqiang Liu. Traffic Signal Timing Optimization Based on Intersection Importance in Vehicle-Road Collaboration. International Conference on Machine Learning for Cyber Security (ML4CS), 2023.
8. Yingqi Cai, Pengna Liu, Dongyue Xu, Xuyan Fan, **Yalun Wu**, Kang Chen, Liqun Chu, Qiong Li, Endong Tong, Wenjia Niu, Jiqiang Liu. Backdoor Attack Influence Assessment and Analysis on Multi-Agent Training. 2023 China Automation Congress (CAC). IEEE, 2023: 8885-8890.
9. Yike Li, Yunzhe Tian, Endong Tong, Wenjia Niu, Yingxiao Xiang, Tong Chen, **Yalun Wu**, Jiqiang Liu. Curricular Robust Reinforcement Learning via GAN-based Perturbation through Continuously Scheduled Task. Tsinghua Science and Technology, 2022, 28(1): 27-38.  <font color="#E56701"><b>(JCR Q1/中科院一区)</b></font> 
10. Yike Li, Wenjia Niu, Yunzhe Tian, Tong Chen, Zhiqiang Xie, **Yalun Wu**, Yingxiao Xiang, Endong Tong, Thar Baker and Jiqiang Liu. Multi-Agent Reinforcement Learning-based Signal Planning for Resisting Congestion Attack in Green Transportation. IEEE Transactions on Green Communications and Networking. 6(3):1448-1458. 2022.  <font color="#E56701"><b>(IEEE汇刊, JCR Q2/中科院二区)</b></font> 
11. Tong Chen, Jiqiang Liu, Baker Thar, **Yalun Wu**, Yingxiao Xiang, Yike Li, Wenjia Niu, Endong Tong. A Mutual Information-based Assessment of Reverse Engineering on Rewards of Reinforcement Learning. IEEE Transactions on Artificial Intelligence, 2022 (early access).  <font color="#E56701"><b>(IEEE汇刊)</b></font> 
12. Shuang Zhao, **Yalun Wu**, Rui Sun, Xiaoai Qian, Dong Zi, Zhiqiang Xie, Endong Tong, Wenjia Niu, Jiqiang Liu, Zhen Han. Blockchain-Based Decentralized Federated Learning: A Secure and Privacy-Preserving System. In IEEE International Conference on High Performance Computing and Communications (HPCC) 2021: 941-948. <font color="#E56701"><b>(HPCC'2021, CCF-C)</b></font>  
13. **Yalun Wu**, Minglu Song, Yike Li, Yunzhe Tian, Endong Tong, Wenjia Niu, Bowei Jia, Haixiang Huang, Qiong Li, Jiqiang Liu. Improving Convolutional Neural Network-Based Webshell Detection Through Reinforcement Learning. International Conference on Information and Communications Security (ICICS)  2021: 368-383. <font color="#E56701"><b>(ICICS'2021, CCF-C, Acceptance rate: 49/202≈24.25%)</b></font> 
14. Yingxiao Xiang, Wenjia Niu, Endong Tong, Yike Li, Bowei Jia, **Yalun Wu**, Jiqiang Liu, Liang Chang, Gang Li. Congestion Attack Detection in Intelligent Traffic Signal System: Combining Empirical and Analytical Methods. Security and Communication Networks, 2021, 2021: 1-17. <font color="#E56701"><b>(中科院四区, CCF-C)</b></font> 
15. Tong Chen, Jiqiang Liu, **Yalun Wu**, Yunzhe Tian, Endong Tong, Wenjia Niu, Yike Li, Yingxiao Xiang, Wei Wang. Survey on Astroturfing Detection and Analysis from an Information Technology Perspective. Security and Communication Networks, 2021, 2021: 1-16. <font color="#E56701"><b>(中科院四区, CCF-C)</b></font> 
16. Yike Li, Yunzhe Tian, Endong Tong, Wenjia Niu, Yingxiao Xiang, Tong Chen, **Yalun Wu** and Jiqiang Liu. Curricular Robust Reinforcement Learning via GAN-based Perturbation through Continuously Scheduled Task. Chinese Conference on Trusted Computing and Information Security (CTCIS), 2021.
17. Yingxiao Xiang, Tong Chen, Yike Li, Yunzhe Tian, Wenjia Niu, Endong Tong, Jiqiang Liu, Bowei Jia, **Yalun Wu**, Xinyu Huang. Predicting Congestion Attack of Variable Spoofing Frequency for Reliable Traffic Signal System. International Conference on Security and Privacy in New Computing Environments (EAI-SPNCE), 2021.

<span class='anchor' id='Patents'></span>
# 🔍 发明专利

- **吴亚伦**, 崔晓澍, 陈渊婉, 李琼, 古砚锋, 蔡英琪, 韩臻, 刘吉强, 童恩栋, 牛温佳. 一种基于文本驱动的数据增强方法. 中国专利, 2024. ZL202410218732.1.
- 刘朋娜, 乔紫嫣, **吴亚伦**, 陈渊婉, 崔晓澍, 古砚锋, 贾敬淇, 李琼, 童恩栋, 牛温佳. 一种面向多点异步攻击的快速区域复用方法. 中国专利, 2024. CN202410026966.6
- 乔紫嫣, 陈渊婉, 刘朋娜, 古砚锋, 崔晓澍, **吴亚伦**, 李琼, 童恩栋, 牛温佳. 一种双向模型迁移的多主体联合强化学习方法. 中国专利, 2024. CN202311627677.3
- 程殿景, 田蕴哲, 卢西义, 陈康, 徐冬月, **吴亚伦**, 武兴宇, 李轶珂, 李琼, 童恩栋, 牛温佳, 刘吉强. 一种结合预训练和监督微调的多任务分类器构建方法. 中国专利, 2024. ZL2024102243853.
- 陈康, 田蕴哲, 徐冬月, **吴亚伦**, 武兴宇, 李轶珂, 童恩栋, 牛温佳. 一种对无线信号进行信号调制样式与技术体制识别方法. 中国专利, 2024. CN202311198519.0

<span class='anchor' id='Honor-and-Reward'></span>
# 🎖 荣誉与获奖
**团体奖项：**
- *2023.12:* 服务班级获评北京市“先进班集体”荣誉称号. (班长)
- *2023.12:* 服务班级获评北京交通大学“研究生先进班集体”荣誉称号. (班长)
- *2023.10:* 作为群众代表参加中国残疾人联合会第八次全国代表大会开幕会，以精神饱满、热情洋溢的态度展现了北京交通大学良好的精神风貌，为大会营造了浓厚热烈的氛围，荣获中国残疾人联合会办公厅“感谢信”.
- *2022.08:* 荣获第30届DEFCON自动驾驶CTF全球挑战赛团体亚军. (队长, 排名: 3/9)
- *2022.05:* 服务班级获评北京交通大学计算机与信息技术学院“青春绽放, 梦由芯生”班级风采大赛二等奖. (班长)
- *2021.08:* 荣获第29届DEFCON自动驾驶CTF全球挑战赛团体亚军. (队长, 排名: 1/10)
- *2022.01:* 荣获国家重点活动安全测试活动团体一等奖. (队长)

**个人奖项：**

- *2023.12:* 荣获北京交通大学“企业专项奖学金”.
- *2023.12:* 荣获北京交通大学“社会工作优秀奖学金”.
- *2023.12:* 荣获北京交通大学“优秀研究生干部”.
- *2023.07:* 荣获中国网络空间安全人才教育联盟“A级安全众测专业人员认证”.
- *2023.01:* 荣获阿里云开发者社区乘风者计划“专家博主”荣誉称号.
- *2022.12*: 获评北京交通大学“优秀兼职辅导员”荣誉称号.
- *2022.11:* 荣获北京交通大学研究生骨干培训班“结业证书”.

<span class='anchor' id='Education'></span>
# 📖 教育经历
- *2022.09 - 至今:* 博士, 北京交通大学, 计算机科学与技术学院/计算机与信息技术学院.
- *2020.09 - 2022.06:* 硕士, 北京交通大学, 计算机与信息技术学院.
- *2013.09 - 2017.06:* 本科, 青岛农业大学, 理学与信息科学学院.

<span class='anchor' id='Project'></span>
# ⚙️ 项目经历
- *2023 - 至今:* 中央引导地方资金项目, 基于边缘计算的智能交通拥堵治理系统研发, 15万.
- *2023 - 至今:* 自然科学横向项目(石家庄“揭榜挂帅”项目), 基于数字孪生的自动驾驶半实物仿真, 100万.
- *2022 - 2023:* 红果园横向项目, OMS功能及算法研发, 50万.
- *2020 - 2023:* 国家自然科学基金“面上”项目, 智能交通信号灯系统中数据投毒攻击的多主体协同防护研究, 60万.
- *2020 - 2023:* 国家重点研发计划-项目, 城市智能系统可信任机理与关键技术.
- *2022 - 2022:* 红果园省部级“企事业”项目, 某领域标准化问题预研究项目.
