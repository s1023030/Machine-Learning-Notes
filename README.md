# Machine-Learning-Notes(加载图片较慢，请耐心等待,只显示一部分)
周志华《机器学习》手推笔记~持续更新中

## by 【计算机视觉联盟】 王博（Kings）、Sophia

## 手推笔记已经  129页 A4纸，可直接打印 ！！

*Last updated: 2020/05/22*   **更新第三版**

## 【计算机视觉联盟】回复【西瓜书手推笔记】即可获得百度云pdf下载链接

#### Update log
* 2019/09/13 * - 更新第一章
* 2019/09/20 * - 更新第二章
* 2019/10/03 * - 更新第三章
* 2019/11/05 * - 更新第四章
* 2019/11/30 * - 更新第五章  46页
* 2019/12/17 * - 更新第六章  62页
* 2019/01/02 * - 更新第七章  75页
* 2019/01/28 * - 更新第八章  96页 
* 2019/02/14 * - 更新第九章  105页
* 2019/03/27 * - 更新第十章  116页
* 2019/04/14 * - 更新为第三版
* 2019/05/16 * - 更新第十一章   129页

## Table of Contents
- [第一章绪论](https://github.com/Sophia-11/Machine-Learning-Notes/)
- [第二章模型评估与选择](https://github.com/Sophia-11/Machine-Learning-Notes/)
- [第三章线性模型](https://github.com/Sophia-11/Machine-Learning-Notes/)
- [第四章决策树](https://github.com/Sophia-11/Machine-Learning-Notes/)
- [第五章神经网络](https://github.com/Sophia-11/Machine-Learning-Notes/)
- [第六章支持向量机](https://github.com/Sophia-11/Machine-Learning-Notes/)
- [第七章贝叶斯分类器](https://github.com/Sophia-11/Machine-Learning-Notes/)
- [第八章集成信息](https://github.com/Sophia-11/Machine-Learning-Notes/)
- [第九章聚类](https://github.com/Sophia-11/Machine-Learning-Notes/)
- [第十章降维与度量学习](https://github.com/Sophia-11/Machine-Learning-Notes/)
- [第十一章特征选择与稀疏学习](https://github.com/Sophia-11/Machine-Learning-Notes/)
- [第十二章计算学习理论](https://github.com/Sophia-11/Machine-Learning-Notes/)
- [第十三章半监督学习](https://github.com/Sophia-11/Machine-Learning-Notes/)
- [第十四章概率图模型](https://github.com/Sophia-11/Machine-Learning-Notes/)
- [第十五章规则学习](https://github.com/Sophia-11/Machine-Learning-Notes/)
- [第十六章强化学习](https://github.com/Sophia-11/Machine-Learning-Notes/)


## 手推笔记作者简介--王博Kings
微信号（Kingsplus）备注：单位/学校+研究方向 ，分享最新的AI思维导图和笔记

985AI博士，CSDN博客专家

已连载系列《机器学习》西瓜书手推笔记

已完结待更笔记：《深度学习-花书手推笔记》、《无人驾驶手推笔记》、《SLAM 十四讲》

| 下载地址 | 博士私人微信 |
|:-----------:|:-----------:|
|![](./cvQD.jpg)|![](./Kingsplus.jpg)| 
|【计算机视觉联盟】回复【西瓜书手推笔记】即可获得百度云pdf下载链接|985AI博士，CSDN博客专家| 


## 第一章 绪论

![image](https://github.com/Sophia-11/Machine-Learning-Notes/blob/master/ch1/%E5%91%A8%E5%BF%97%E5%8D%8E%E3%80%8A%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0%E3%80%8B%E7%AC%AC%E4%B8%80%E7%AB%A0%20%E3%80%90%E8%AE%A1%E7%AE%97%E6%9C%BA%E8%A7%86%E8%A7%89%E8%81%94%E7%9B%9F%E3%80%91.jpg)


### 数学符号
| 1 | 2 | 3 |4 |
|:-----------:|:--------:|:---------:|:---------:|
|![](./ch/0000.jpg)| ![](./ch/0001.jpg)| ![](./ch/0002.jpg)|  ![](./ch/0003.jpg)| 

## 第二章  模型评估与选择
| 1 | 2 | 3 |4 |
|:-----------:|:--------:|:---------:|:---------:|
|![](./ch2/%E6%89%AB%E6%8F%8F_%E5%89%AF%E6%9C%AC.jpg)| ![](./ch2/%E6%89%AB%E6%8F%8F0001_%E5%89%AF%E6%9C%AC.jpg)| ![](./ch2/%E6%89%AB%E6%8F%8F0002_%E5%89%AF%E6%9C%AC.jpg)|  ![](./ch2/%E6%89%AB%E6%8F%8F0003_%E5%89%AF%E6%9C%AC.jpg)| 
|![](./ch2/%E6%89%AB%E6%8F%8F0004_%E5%89%AF%E6%9C%AC.jpg)| ![](./ch2/%E6%89%AB%E6%8F%8F0005_%E5%89%AF%E6%9C%AC.jpg)| ![](./ch2/%E6%89%AB%E6%8F%8F0006_%E5%89%AF%E6%9C%AC.jpg)|  ![](./ch2/%E6%89%AB%E6%8F%8F0007_%E5%89%AF%E6%9C%AC.jpg)| 
|![](./ch2/%E6%89%AB%E6%8F%8F0008_%E5%89%AF%E6%9C%AC.jpg)| ![](./ch2/%E6%89%AB%E6%8F%8F0009_%E5%89%AF%E6%9C%AC.jpg)| ![](./ch2/%E6%89%AB%E6%8F%8F0010_%E5%89%AF%E6%9C%AC.jpg)|  ![](./ch2/%E6%89%AB%E6%8F%8F0011_%E5%89%AF%E6%9C%AC.jpg)| 
|![](./ch2/%E6%89%AB%E6%8F%8F0012_%E5%89%AF%E6%9C%AC.jpg)|||| 



## 第三章  线性模型
| 1 | 2 | 3 |4 |
|:-----------:|:--------:|:---------:|:---------:|
|![](./ch3/%E6%89%AB%E6%8F%8F0014_%E5%89%AF%E6%9C%AC.jpg)| ![](./ch3/%E6%89%AB%E6%8F%8F0015_%E5%89%AF%E6%9C%AC.jpg)| ![](./ch3/%E6%89%AB%E6%8F%8F0016_%E5%89%AF%E6%9C%AC.jpg)|  ![](./ch3/%E6%89%AB%E6%8F%8F0017_%E5%89%AF%E6%9C%AC.jpg)| 
|![](./ch3/%E6%89%AB%E6%8F%8F0018_%E5%89%AF%E6%9C%AC.jpg)| ![](./ch3/%E6%89%AB%E6%8F%8F0019_%E5%89%AF%E6%9C%AC.jpg)| ![](./ch3/%E6%89%AB%E6%8F%8F0020_%E5%89%AF%E6%9C%AC.jpg)|  ![](./ch3/%E6%89%AB%E6%8F%8F0021_%E5%89%AF%E6%9C%AC.jpg)| 
|![](./ch3/%E6%89%AB%E6%8F%8F0022_%E5%89%AF%E6%9C%AC.jpg)| ![](./ch3/%E6%89%AB%E6%8F%8F0023_%E5%89%AF%E6%9C%AC.jpg)|| | 



## 第四章   决策树
![image](https://github.com/Sophia-11/Machine-Learning-Notes/blob/master/ch4/%E6%89%AB%E6%8F%8F0024_%E5%89%AF%E6%9C%AC.jpg)
![image](https://github.com/Sophia-11/Machine-Learning-Notes/blob/master/ch4/%E6%89%AB%E6%8F%8F0025_%E5%89%AF%E6%9C%AC.jpg)
![image](https://github.com/Sophia-11/Machine-Learning-Notes/blob/master/ch4/%E6%89%AB%E6%8F%8F0026_%E5%89%AF%E6%9C%AC.jpg)
![image](https://github.com/Sophia-11/Machine-Learning-Notes/blob/master/ch4/%E6%89%AB%E6%8F%8F0027_%E5%89%AF%E6%9C%AC.jpg)
![image](https://github.com/Sophia-11/Machine-Learning-Notes/blob/master/ch4/%E6%89%AB%E6%8F%8F0028_%E5%89%AF%E6%9C%AC.jpg)
![image](https://github.com/Sophia-11/Machine-Learning-Notes/blob/master/ch4/%E6%89%AB%E6%8F%8F0029_%E5%89%AF%E6%9C%AC.jpg)
![image](https://github.com/Sophia-11/Machine-Learning-Notes/blob/master/ch4/%E6%89%AB%E6%8F%8F0030_%E5%89%AF%E6%9C%AC.jpg)
![image](https://github.com/Sophia-11/Machine-Learning-Notes/blob/master/ch4/%E6%89%AB%E6%8F%8F0031_%E5%89%AF%E6%9C%AC.jpg)
![image](https://github.com/Sophia-11/Machine-Learning-Notes/blob/master/ch4/%E6%89%AB%E6%8F%8F0032_%E5%89%AF%E6%9C%AC.jpg)
![image](./ch4/%E6%89%AB%E6%8F%8F0033_%E5%89%AF%E6%9C%AC.jpg)
![image](./ch4/%E6%89%AB%E6%8F%8F0034_%E5%89%AF%E6%9C%AC.jpg)

## 第五章   神经网络
![image](./ch5/%E6%89%AB%E6%8F%8F0035_%E5%89%AF%E6%9C%AC.jpg)
![image](./ch5/%E6%89%AB%E6%8F%8F0036_%E5%89%AF%E6%9C%AC.jpg)
![image](./ch5/%E6%89%AB%E6%8F%8F0037_%E5%89%AF%E6%9C%AC.jpg)
![image](./ch5/%E6%89%AB%E6%8F%8F0038_%E5%89%AF%E6%9C%AC.jpg)
![image](./ch5/%E6%89%AB%E6%8F%8F0039_%E5%89%AF%E6%9C%AC.jpg)
![image](./ch5/%E6%89%AB%E6%8F%8F0040_%E5%89%AF%E6%9C%AC.jpg)
![image](./ch5/%E6%89%AB%E6%8F%8F0041_%E5%89%AF%E6%9C%AC.jpg)
![image](./ch5/%E6%89%AB%E6%8F%8F0042_%E5%89%AF%E6%9C%AC.jpg)
![image](./ch5/%E6%89%AB%E6%8F%8F0043_%E5%89%AF%E6%9C%AC.jpg)
![image](./ch5/%E6%89%AB%E6%8F%8F0044_%E5%89%AF%E6%9C%AC.jpg)
![image](./ch5/%E6%89%AB%E6%8F%8F0045_%E5%89%AF%E6%9C%AC.jpg)


## 第六章   支持向量机
![image](./ch6/%E6%89%AB%E6%8F%8F_%E5%89%AF%E6%9C%AC.jpg)
![image](./ch6/%E6%89%AB%E6%8F%8F0001_%E5%89%AF%E6%9C%AC.jpg)
![image](./ch6/%E6%89%AB%E6%8F%8F0002_%E5%89%AF%E6%9C%AC.jpg)
![image](./ch6/%E6%89%AB%E6%8F%8F0003_%E5%89%AF%E6%9C%AC.jpg)
![image](./ch6/%E6%89%AB%E6%8F%8F0004_%E5%89%AF%E6%9C%AC.jpg)
![image](./ch6/%E6%89%AB%E6%8F%8F0005_%E5%89%AF%E6%9C%AC.jpg)
![image](./ch6/%E6%89%AB%E6%8F%8F0006_%E5%89%AF%E6%9C%AC.jpg)
![image](./ch6/%E6%89%AB%E6%8F%8F0007_%E5%89%AF%E6%9C%AC.jpg)
![image](./ch6/%E6%89%AB%E6%8F%8F0008_%E5%89%AF%E6%9C%AC.jpg)
![image](./ch6/%E6%89%AB%E6%8F%8F0009_%E5%89%AF%E6%9C%AC.jpg)
![image](./ch6/%E6%89%AB%E6%8F%8F0010_%E5%89%AF%E6%9C%AC.jpg)
![image](./ch6/%E6%89%AB%E6%8F%8F0011_%E5%89%AF%E6%9C%AC.jpg)
![image](./ch6/%E6%89%AB%E6%8F%8F0012_%E5%89%AF%E6%9C%AC.jpg)
![image](./ch6/%E6%89%AB%E6%8F%8F0013_%E5%89%AF%E6%9C%AC.jpg)
![image](./ch6/%E6%89%AB%E6%8F%8F0014_%E5%89%AF%E6%9C%AC.jpg)
![image](./ch6/%E6%89%AB%E6%8F%8F0015_%E5%89%AF%E6%9C%AC.jpg)

## 第七章    贝叶斯分类器
![image](./ch7/062.jpg)
![image](./ch7/063.jpg)
![image](./ch7/064.jpg)
![image](./ch7/065.jpg)
![image](./ch7/066.jpg)
![image](./ch7/067.jpg)
![image](./ch7/068.jpg)
![image](./ch7/069.jpg)
![image](./ch7/070.jpg)
![image](./ch7/071.jpg)
![image](./ch7/072.jpg)
![image](./ch7/073.jpg)
![image](./ch7/074.jpg)
