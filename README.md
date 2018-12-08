## 这是什么？

这是由ApacheCN翻译的Statsmodels的中文文档

## Statsmodels是什么？

Statsmodels是一个Python包，为统计计算的scipy提供补充，包括描述性统计和统计模型的估计和推断。

### 英文文档

最新的稳定版文档位于

[https://www.statsmodels.org/stable/](https://www.statsmodels.org/stable/)

开发版文档位于

[https://www.statsmodels.org/dev/](https://www.statsmodels.org/dev/)

Recent improvements are highlighted in the release notes

[https://www.statsmodels.org/stable/release/version0.9.html](https://www.statsmodels.org/stable/release/version0.9.html)

有关文档的备份请访问-[https://statsmodels.github.io/stable/](https://statsmodels.github.io/stable/)
和 [https://statsmodels.github.io/dev/](https://statsmodels.github.io/dev/).

### 主要内容

 - 线性回归模型：
    - 普通最小二乘
    - 广义最小二乘法
    - 加权最小二乘法
    - 具有自回归误差的最小二乘法
    - 分位数回归
    - 递归最小二乘法
 - 具有混合效应和方差分量的混合线性模型
 - GLM：支持所有单参数指数族分布的广义线性模型
 - 用于二项式和泊松的贝叶斯混合GLM
 - GEE：单向聚类或纵向数据的广义估计方程
 - 离散模型：
    - Logit和Probit
    - 多项logit（MNLogit）
    - 泊松和广义Poisson回归
    - 负二项式回归
    - 零膨胀计数模型
 - RLM：强大的线性模型，支持多个M估计器。
 - 时间序列分析：时间序列分析模型
    - 完成StateSpace建模框架
        - 季节性ARIMA和ARIMAX模型
        - VARMA和VARMAX型号
        - 动态因子模型
        - 未观察到的组件模型
    - 马尔可夫切换模型（MSAR），也称为隐马尔可夫模型（HMM）
    - 单变量时间序列分析：AR，ARIMA
    - 矢量自回归模型，VAR和结构VAR
    - 矢量误差修正模型，VECM
    - 指数平滑，Holt-Winters
    - 时间序列的假设检验：单位根，协整等
    - 时间序列分析的描述性统计和过程模型
 - 生存分析：
    - 比例风险回归（Cox模型）
    - 幸存者函数估计（Kaplan-Meier）
    - 累积发生率函数估计
 - 多因素：
    - 缺少数据的主成分分析
    - 旋转因子分析
    - MANOVA
    - 典型相关
 - 非参数统计：单变量和多变量核密度估计
 - 数据集：用于示例和测试的数据集
 - 统计：广泛的统计测试
    - 诊断和规范测试
    - 拟合优度和正态性测试
    - 用于多个测试的功能
    - 各种额外的统计测试
 - MICE估算，秩序统计回归和高斯插补
 - 调解分析
 - 图形包括用于数据和模型结果的可视分析的绘图功能
 - I / O
    - 用于读取Stata .dta文件的工具，但是pandas具有更新版本
    - 表输出为ascii，latex和html
 - Miscellaneous models(各种各样的模型）
 - Sandbox：statsmodels包含一个沙箱文件夹，其中的代码处于开发和测试的各个阶段，不被视为“生产就绪”。这包括其中之一
    - 广义矩量法（GMM）估计量
    - 核回归
    - scipy.stats.distributions的各种扩展
    - 面板数据模型
    - 信息理论措施

## ApacheCN是什么？

* 主页：[apachecn.org](http://www.apachecn.org)
* Github：[@ApacheCN](https://github.com/apachecn)
* 社区：[community.apachecn.org](http://community.apachecn.org)
* 知识库：[cwiki.apachecn.org](http://cwiki.apachecn.org/)
* 自媒体平台：
    * [微博：@ApacheCN](https://weibo.com/u/6326715527)
    * [知乎：@ApacheCN](https://www.zhihu.com/people/apachecn)
    * [CSDN](https://blog.csdn.net/wizardforcel/article/category/8437073)、[简书](https://www.jianshu.com/c/4ee721d0c474)、[OSChina](https://my.oschina.net/repine/)、[博客园](https://www.cnblogs.com/wizardforcel/category/1352397.html)
* **我们不是 Apache 的官方组织/机构/团体，只是 Apache 技术栈（以及 AI）的爱好者！**
* 如有侵权，请联系邮箱：【片刻】<jiang-s@163.com>（如果需要合作，也可以私聊我）

## 参与翻译 & 发现错误

    1. 在 github 上 fork 该 repository.
    2. 翻译 docs/zh/source 或者根目录 下面的 rst或txt 文件即可, 例如, gettingstarted.rst.
    3. 然后, 在你的 github 发起 New pull request 请求.

## 角色分配
目前有如下可分配的角色:

* 翻译: 负责文章内容的翻译.
* 校验: 负责文章内容的校验, 比如格式, 正确度之类的.
* 负责人: 负责整个 Projcet

有兴趣参与的朋友, 可以看看最后的联系方式.

## Statsmodels负责人
* [@FontTian](https://github.com/FontTian)（Font Tian）

## 贡献者

贡献者可自行编辑如下内容（排名不分先后）.

### Statsmodels-0.9
**翻译者(人人皆大佬~):**

* [@FontTian](https://github.com/FontTian)（Font Tian）


## 联系方式
有任何建议反馈, 或想参与文档翻译, 麻烦联系下面的企鹅:

* 企鹅: 2404846224((FontTian)

## 其它中文文档

1. [sklearn 中文文档](https://github.com/apachecn/scikit-learn-doc-zh)
2. [pytorch 0.3 中文文档](https://github.com/apachecn/pytorch-doc-zh)
3. [TensorFlow R1.2 中文文档](http://cwiki.apachecn.org/pages/viewpage.action?pageId=10030122)
4. [xgboost 中文文档](https://github.com/apachecn/xgboost-doc-zh)
5. [lightgbm 中文文档](https://github.com/apachecn/lightgbm-doc-zh)
6. [fasttext 中文文档](https://github.com/apachecn/fasttext-doc-zh)
7. [gensim 中文文档](https://github.com/apachecn/gensim-doc-zh)
1. [Spark 中文文档](https://github.com/apachecn/spark-doc-zh)
2. [Storm 中文文档](https://github.com/apachecn/storm-doc-zh)
3. [Kafka 中文文档](https://github.com/apachecn/kafka-doc-zh)
4. [Flink 中文文档](https://github.com/apachecn/flink-doc-zh)
5. [Beam 中文文档](https://github.com/apachecn/beam-site-zh)
6. [Zeppelin 0.7.2 中文文档](https://github.com/apachecn/zeppelin-doc-zh)
7. [Elasticsearch 5.4 中文文档](https://github.com/apachecn/elasticsearch-doc-zh)
8. [Kibana 5.2 中文文档](https://github.com/apachecn/kibana-doc-zh)
9. [Kudu 1.4.0 中文文档](https://github.com/apachecn/kudu-doc-zh) 
0. [Spring Boot 1.5.2 中文文档](https://github.com/apachecn/spring-boot-doc-zh)
1. [Airflow 中文文档](https://github.com/apachecn/airflow-doc-zh)
1. [Solidity 中文文档](https://github.com/apachecn/solidity-doc-zh)
1. [numpy 中文文档](https://github.com/apachecn/numpy-ref-zh)
1. [pandas 中文文档](https://github.com/apachecn/pandas-doc-zh)
1. [matplotlib 中文文档](https://github.com/apachecn/matplotlib-user-guide-zh)
1. 等等