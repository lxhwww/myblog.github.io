# The impact of an epidemic on people's mood
## Demo
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/PPPHUB/twitter-emotion-recognition/HEAD)

## techniques
Granger causality： [Granger causality](https://en.wikipedia.org/wiki/Granger_causality)
covariance maritx (https://en.wikipedia.org/wiki/Covariance)
### aim
project we need to use on github
[a nlp project](https://github.com/PPPHUB/twitter-emotion-recognition)

we want to find the relation between epidemic and people's emotion.

## idea
First, load the model and predict all tweets in the data set.(Still need to debug)<-we are here now

Second,calcuate the gradient 

thrid,plot the picture by histgram, plot, hotmap, and try to compare the cruve.

At last, find the relationship by mathematics method such as Granger causality.

## paper we use
### Association between Physical Activity and Mood States of Children and Adolescents in Social Isolation during the COVID-19 Epidemic
The COVID-19 epidemic adversely affects the lifestyle of people. This study aimed to examine the impacts of social isolation on physical activity (PA) levels and mood states of children and adolescents and to explore the correlation between them during the COVID-19 epidemic. A total of 9979 children and adolescents (11.63 ± 1.23 years old) from Yan’an, China volunteered to participate in this study and completed online questionnaires. PA and mood states were measured by International Physical Activity Questionnaire Short Form (IPAQ-SF) and Profile of Mood States (POMS), respectively. The results showed that the mean of students’ moderate-to-vigorous PA (MVPA) was 23.19 min per day. The total mood disturbance in the moderate and high-level PA groups were significantly lower than those in the low-level PA group (p < 0.05). Additionally, boys and girls had significant differences in PA levels (p < 0.01), and the PA levels of students in different grades were also significantly different (p < 0.01). Meanwhile, boys’ mood states were worse than girls’. The Grade 4 in primary schools had the worst mood states while Grade 5 had the best mood states. The results suggested that the MVPA of students has dropped badly, compared with the results of previous studies investigated in normal times. In addition, the PA level had a significantly positive impact on the mood states of children and adolescents during the COVID-19 epidemic. Sex and grades were factors which affected the PA levels and mood states. This study can help policymakers and healthcare professionals understand PA and mood states of Chinese children and adolescents during the epidemic. We should pay attention to the changes in PA levels and mood states of children and adolescents.
https://www.mdpi.com/1660-4601/17/20/7666
### 社交网络舆情事件中用户行为影响力分析——以"长春长生疫苗事件"为例，2020
舆情事件中用户行为直接决定了舆论导向,研究用户行为特征与影响力对于舆情监测有着重要意义.对"长春长生疫苗事件"中的微博用户行为特征进行统计分析,结合机器学习中的朴素贝叶斯分类器对舆情文本数据进行情感分析,建立实时影响力模型对微博用户行为的影响力进行实证研究.结果表明,微博用户行为中转发行为相比于点赞,评论,更具有影响力.用户情感倾向极性越大,传播的影响力越大,而且情感极性为负向的博文比正向的博文传播更快,影响力更大.
https://xueshu.baidu.com/usercenter/paper/show?paperid=1v1c00x0s7510g20pd6u0gs0tu435884&site=xueshu_se 


### 基于BP神经网络的突发传染病舆情热度趋势预测模型研究，2018
目的 /意义]研究突发传染病舆情热度的发展趋势,能够为制定舆情引导策略提供参考,具有重要的理论意义.[方法 /过程]本文首先构建微博舆情热度评价指标体系,基于信息熵确定各个指标的权重,然后对求得的舆情热度趋势值进行分类,在此基础上,建立基于BP神经网络的突发传染病舆情热度趋势预测模型.以新浪微博为例,选取"MERS病毒卫生突发事件"的舆情热度数据进行实例分析,预测该突发传染病事件的发展趋势,从而验证模型的可行性.[结果/结论]实验结果表明,该模型能有效预测突发传染病舆情热度趋势,进而为舆情管控提供决策支持.
https://xueshu.baidu.com/usercenter/paper/show?paperid=eee83a3c0dc1f318853a86fdb5d4c3c0&site=xueshu_se

### 基于正负反馈的微博舆情传染病模型的研究

近年来,随着科技的进步以及互联网技术的发展,社交网络以其高度联通互动性,用户覆盖面广,信息传播快捷迅速等优势,已经成为社会舆情的主要阵地.而现阶段网络舆情中出现的网络水军和僵尸粉两大新的影响因素,对舆情传播有较大影响.针对传统自顶向下模型的反复识别建模的复杂性和局限性,难以准确阐明社交话题传播的影响因素和真实过程,本文提出了将微博水军和僵尸粉作为舆情传播系统中正负反馈的传染病动力学社交网络舆情话题传播模型.对理解真实舆情的传播机理和过程,掌握现阶段网络传播规律,为舆情调控提供有效指导建议具有重要的理论和现实意义.由于社交网络中话题的传播,受众的感染和医学中传染病的感染传播治愈有很大的相似之处,符合同样的社会学规律.因此本文结合传染病动力学模型研究了带有网络水军和僵尸粉作为舆情系统正负反馈的舆情传播模型,主要内容可归纳如下:(1)研究社交网络的社会特征,为后续的舆情传播研究奠定研究基础.考虑到研究模型的现实对应及意义,研究了ws动态小世界模型,验证舆情传播网络符合现实社会社交网络的特征.(2)研究了基于综合指数熵值法的微博水军识别和基于朴素贝叶斯的微博僵尸粉识别.对照提取正常用户与微博水军及僵尸粉的特征,分别构建了对应的判别模型,有效实现了正负反馈因素的判别.(3)分析了带有正负反馈的微博舆情传染病动力学模型.
https://xueshu.baidu.com/usercenter/paper/show?paperid=1w6n0j904h7a0e70mp240m60cx386323&site=xueshu_se


### 基于辟谣微博的互动及热门评论情感倾向的辟谣效果研究——以新冠疫情相关辟谣微博为例
[目的/意义]增强社交媒体平台上的辟谣效果可以为辟谣提供新的思路,加快辟谣过程,减轻谣言的危害.[方法/过程]提出了辟谣效果指数(REI).搜集2020年1月1日至2020年4月20日由"微博辟谣"转发的辟谣信息,应用自然语言处理(NLP)方法,以提取辟谣微博的文本特征,分析辟谣微博文本,热门评论的情感倾向.采用人工标注法验证了REI对辟谣效果评价的有效性,并探索REI与辟谣微博的内容特征与背景特征之间的关系,建立了四种回归模型,基于综合拟合表现最优的XGBoost回归模型,利用SHapley Additive exPlanations(SHAP)对回归结果进行可视化和分析.[结果/结论]基于分析结果,为不同辟谣情景(如辟谣者的影响力,话题热度等)提出了如何组织辟谣信息以增强辟谣效果的决策建议,REI也可应用于其他社交媒体平台.
https://xueshu.baidu.com/usercenter/paper/show?paperid=1b650ee0hu780210804a0ad0bu321476&site=xueshu_se 

### 基于Twitter社交网络数据的流感预测应用研究

随着全球气候变化,流感的发病人数大幅增加,严重流感的死亡率接近50%,因此对流感暴发进行预测研究愈发重要.现有研究中,已将社交媒体用于地震灾害检测和趋势预测,本研究将机器学习算法和大数据方法结合应用于流感暴发的预测.通过文本分类模型实现Twitter社交网络数据预处理,利用时间序列预测模型对澳大利亚昆士兰州的流感疫情进行趋势预测.本文主要研究内容如下:1)应用XGBoost算法实现流感数据文本分类,解决了传统机器学习算法对于文本分类效果较差的问题.为了验证该方法的性能,以Twitter数据为研究对象,首先通过关键词过滤技术提取疑似流感数据,然后采用XGBoost算法对疑似流感数据进行分类预测,并与传统的朴素贝叶斯算法进行对比.实验结果表明,XGBoost算法对Twitter数据的分类结果正确率为90%,明显优于朴素贝叶斯算法的分类结果,可用于Twitter数据中流感发病频率及发病时间的提取.2)提出基于Twitter数据和温度数据的多元时间序列预测模型,解决了一元时间序列预测模型时效性差,预测结果相对误差较高的问题。
https://xueshu.baidu.com/usercenter/paper/show?paperid=1x0g0ab0sv5b0c60fx360tm0mw479088&site=xueshu_se 

### 基于朴素贝叶斯分类与群智感知实现对传染病与相应舆论的实时监控

[背景/意义]将微博用户看作感知单元,形成群智网络,从公众情感角度对传染病的分布、传播与发展进行简洁直观、可视化的描述。[方法/过程]研究分五个部分。首先,爬取与事件相关的微博帖集;其次,利用数据过滤模型α过滤与事件关联度不高的帖集;同时,基于OpenStreetMap查询并检测位置以返回真实位置集;然后,基于Python的JIEBA分词系统,进行分词和词频处理,并基于朴素贝叶斯算法实现对关键词的情感预测,得到情感集;最后,通过情感反馈模型μ与疫情监控模型э产生情感曲线与疫情地图,并进行案例研究。[结果/结论]通过这种方法(内含四个模型),可以从微博上生成传染病事件的疫情情感地图与公众情感曲线。其中,地图展示了各位置集的疫情严重情况与传播情况,情感曲线给出了公众反馈随时间的变化。研究发现,病例数越多与人口流动性较大的地区情绪表现更为消极,优良的医疗条件和积极的社交媒体宣传对公众情绪有一定积极效果。
https://xueshu.baidu.com/usercenter/paper/show?paperid=9696e3deea24a5ce7297d1b7b5635300&site=xueshu_se
