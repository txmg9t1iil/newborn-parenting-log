# Nature Communications丨基于简并甲基化技术的原发灶不明肿瘤溯源模型（BELIVE）的建立

> 更新时间：2026-09-11 (UTC+8)

近日，由杭州市第一人民医院肺癌转化研究团队牵头，联合中国科学院健康与医学技术研究所、分子细胞科学卓越创新中心、浙江省肿瘤医院等国内多名临床与转化研究专家，在国际知名期刊Nature Communications（IF=16.6）在线发表了“DNA methylation profiling to determine the primary sites of metastatic cancers using formalin-fixed paraffin-embedded tissues”的研究。杭州市第一人民医院转化医学中心**张仕蓉**主任为本文第一作者，**马胜林**教授为共同通讯作者。研究团队利用简化甲基化测序技术（RRBS），优化了针对石蜡包埋FFPE样本RRBS建库方法，基于机器学习及大样本多中心的系统评估，成功建立了原发灶不明肿瘤溯源模型（BELIVE）及新型诊断方法。

**研究背景**

原发灶不明肿瘤（CUP）是指经病理检查确诊为恶性肿瘤，但是其原发部位经影像、病理、生化等检查仍难以确定的一类肿瘤，占癌症病例的3-5%，发病率位列第7，死亡率位列第4。具有发病隐匿、早期转移、侵袭性强的特点，患者中位生存少于11个月，死亡率明显高于基于原发部位进行针对性治疗的肿瘤患者。因此，准确识别肿瘤的原发部位，对指导原发灶不明肿瘤患者的临床诊疗至关重要。基于“转移组织保留了原发部位分子特征”的理论，既往研究利用 qRT-PCR 或微阵列技术检测转移性肿瘤原发部位的方法，检测准确率从 52.5% 到 87% 不等，尤其是针对 RNA高度降解的FFPE样本在实际临床应用中具有较大挑战。

**研究设计**

本研究共纳入789名癌症患者，覆盖了10种常见恶性肿瘤，并建立了4个独立队列进行模型建立及验证。

**图1. 研究流程图**

CUP分类器的构建和评估

498例10种常见肿瘤患者原发灶（收集其FF样本）作为训练集队列，215转移性肿瘤患者的转移灶（收集其FFPE样本）作为验证集队列。整合4种甲基化评分方法（Beta、CHALM、MHL、PDR）和7种机器学习方法（Adaboost、KNN、LGR、LinearSVC、NB、RF、SVM），构建了28个分类器。基于Beta值的LinearSVC 分类器——BELIVE，综合性能最佳，总体预测准确率为81%，AUC值为0.95。对所有肿瘤的Top-3预测准确率93%，灵敏度为0.92。

**图2. 28个分类器预测性能的比较及BELIVE分类器的预测性能**

外部队列验证BELIVE分类器的性能

使用来自TCGA数据库的4702例患者的微阵列数据来评估BELIVE分类器的性能。除胃癌（0.64）外，BELIVE分类器对所有肿瘤类型的预测准确率均不小于0.91。对所有癌症的Top-1总体预测准确率为92%，AUC值为0.99；Top-3总体预测准确率高达98%，AUC值为0.99。

**图3. BELIVE分类器在TCGA DNA甲基化微阵列数据集上的性能**

BELIVE分类器对CUP患者原发组织的预测性能

使用68例CUP患者的FFPE样本对BELIVE分类器进行了验证。BELIVE分类器Top-1预测准确率为81%（55/68），Top-3预测准确率约为93%（63 / 68）（表2）。

**表2.BELIVE分类器对68名CUP患者的预测准确率**

**临床价值及意义**

基于优化的简并甲基化技术及机器学习方法构建的**BELIVE模型及诊断方法可以有效识别原发灶不明肿瘤的的原发部位**，帮助临床制定针对性治疗方案，为CUP患者带来生存获益。

后续研究团队计划将更多肿瘤类型纳入BELIVE溯源模型，以进一步扩大BELIVE模型的临床应用，并即将启动基于BELIVE模型的原发灶不明肿瘤治疗的**前瞻性临床研究**（ChiCTR2300073699），进一步确认BELIVE模型的临床应用性能。

**杭州市第一人民医院转化医学中心临床分子检测平台介绍**

集分子检测、试剂研发及临床转化为一体的检测平台，长期致力于肿瘤的早期诊断、治疗靶点精准检测及诊断技术开发。目前已搭建NGS，ddPCR，Luminex等多个分子检测平台，开展了基于高通量测序为主的肿瘤用药基因检测，遗传基因检测及多项肿瘤早筛项目。平台以患者为中心、以服务为根本、以质量为保证、为临床和患者提供准确、客观的优质检测服务。

本文由杭州市第一人民医院发布，版权归医院所有

未经允许，严禁转载

如需转载，请留言申请，转载请注明出处

## 相关阅读

- [惠州三代试管婴儿生小孩医院名单](https://github.com/xeatwgpqt3/child-care-essays/blob/main/20260910klje/zzbifkfsxo.md)
- [哈萨克斯坦试管婴儿攻略大全？](https://github.com/r4g9jglfod/baby-food-notes/blob/main/20260911rvrv/smxstryycv.md)
- [医万个为什么 | 张信华：为什么胃肠间质瘤要做基因检测？](https://github.com/l9lvqnbe4d/baby-product-notes/blob/main/20260911ifkc/kkmviltymt.md)
- [泰国试管婴儿费用报销政策解析，省钱又省心！](https://github.com/n9ugyolxwj/baby-care-journal/blob/main/20260910hsft/ilcwqwpamh.md)
- [福建省三代试管包成功医院优惠吗？](https://github.com/l5q2j5iic2/family-health-notes/blob/main/20260910oncu/caqqeiowbu.md)
- [常州做试管婴儿**的过程是怎么样的](https://github.com/nih9jzz6yi/pregnancy-care-hub/blob/main/20260910shmn/phiwwpqtgw.md)
- [台州医院可以做试管婴儿吗？附带全套费用！](https://github.com/j4q35mmgu2/child-care-essays/blob/main/20260910xkja/yfrmitevhu.md)
- [打了降调针可以推迟试管或者等一个月吗？附试管排队时长！](https://github.com/xeatwgpqt3/family-health-notes/blob/main/20260910gyzs/kvkqhkfrlf.md)
- [马鞍山妇幼做试管成功率怎么样](https://github.com/y9qvvxks1i/mommy-baby-notes/blob/main/20260910mfuo/eskdbvimzk.md)
- [不宜吃叶酸的人群有哪些](https://github.com/g6iv5x0e8m/child-care-essays/blob/main/20260910vzev/ikaeawtxkq.md)
- [海南现代妇女儿童医院试管婴儿指南，助孕费用及成功率公布](https://github.com/l0mxvbb0j0/pregnancy-care-hub/blob/main/20260910vuxy/ihsixrliqe.md)
- [老年人预防“脑梗”，叶酸很关键？如何补充叶酸，医生给你讲清楚](https://github.com/b38lymdomu/pregnancy-nutrition-notes/blob/main/20260911enwf/kclopvpsem.md)

## 推荐站点

- [['https://www.gyzhixiao.cn/182.html', '供卵包男孩：igm和igg哪个影响怀孕']](https://www.gyzhixiao.cn/182.html)
- [['https://www.cheguangfu.cn/242.html', '想试管生男孩,什么是第二代试管婴儿？泰国二代试管婴儿*率多少']](https://www.cheguangfu.cn/242.html)
- [['https://www.zhangruiqing.cn/208860784351.html', '试管移植日的流程和注意事项']](https://www.zhangruiqing.cn/208860784351.html)
- [['https://www.mimi567.com/389.html', '在南宁二医院做试管婴儿需要审核结婚证吗？']](https://www.mimi567.com/389.html)
- [['https://www.zrbbavaq.cn/10782519522013.html', '江苏做代生公司服务的医院排行,江苏代生公司服务成功率最高的医院']](https://www.zrbbavaq.cn/10782519522013.html)
- [['https://www.lianhuahushengqun.cn/104691828424.html', '天津代生机构试管代怀孕,天津试管婴儿成功率最高的医院是哪家']](https://www.lianhuahushengqun.cn/104691828424.html)
- [['https://www.njxxwcr.cn/shiguandaishenggongluan/162.html', '畸形精子率高会导致胎儿畸形吗？试管技术如何筛选优质精子']](https://www.njxxwcr.cn/shiguandaishenggongluan/162.html)
- [['https://www.chengyanghg.cn/335.html', '厦门2026试管助孕生子机构成功率排名top3强推！如何选择合适的供卵试管机构']](https://www.chengyanghg.cn/335.html)
- [['https://www.afa2019.com/206742226542.html', '石家庄代怀网-代孕公司电话是多少,石家庄最好的三代试管医院排行榜单揭晓！石家庄做试管哪家医院成功率最高！']](https://www.afa2019.com/206742226542.html)
- [['https://www.btwtjx.cn/wuhangongluanshiguanqun/20250314/6235.html', '全球视野：新孕国际如何整合海外生殖资源，助力精准求子？']](https://www.btwtjx.cn/wuhangongluanshiguanqun/20250314/6235.html)
- [['https://www.xnnpbhdz.cn/12039834425293.html', '西安三甲🏥预约挂号攻略,代孕哪里技术好&国内的供卵机构有哪些']](https://www.xnnpbhdz.cn/12039834425293.html)
- [['https://www.sjzgwfjwzhs.cn/11415299846353.html', '试管日记🧪｜必须夸夸自己，在家打大果👌拿捏,代孕的费用多少']](https://www.sjzgwfjwzhs.cn/11415299846353.html)
- [['https://www.jmxmintuhg.cn/20250511-171.html', '做试管代孕费用, 高龄试管婴儿的优势是提高受孕率，风险是什么？']](https://www.jmxmintuhg.cn/20250511-171.html)
- [['https://www.cxit.com.cn/chenggonganli/20251016/14153.html', '代孕成功几率:为什么着床期间会感觉宫缩呢']](https://www.cxit.com.cn/chenggonganli/20251016/14153.html)
- [['https://www.xmxinyhwzhs.cn/14559487504685.html', '2026年深圳去柬埔寨有哪些代生机构中介怎么选择(柬埔寨有哪些代生机构成功率高不)']](https://www.xmxinyhwzhs.cn/14559487504685.html)
- [['https://www.toothree006.cn/224662491405.html', '代孕套餐介绍-精子冷冻8年是否还能用，揭秘精子库中冻公细胞的存活时间！']](https://www.toothree006.cn/224662491405.html)
- [['https://www.dyqlsu.com/20251014-5.html', '云南试管婴儿医院/费用/成功率介绍']](https://www.dyqlsu.com/20251014-5.html)
- [['https://www.liangzimayi.com/20.html', '武汉服务贴心的助孕医院有哪些？金牌管家全程服务']](https://www.liangzimayi.com/20.html)
- [['https://www.cmanrxrr.cn/1716013365563.html', '男生取jing时的，超全注意事项~,比较代孕机构,国内借卵试管私立机构']](https://www.cmanrxrr.cn/1716013365563.html)
- [['https://www.monpun.com/6337111614674.html', '供卵助孕医院精选：正规试管医院排行揭晓']](https://www.monpun.com/6337111614674.html)
- [['https://www.hs52.cc/sandaigongluandaihuai/75.html', '着床不稳的征兆']](https://www.hs52.cc/sandaigongluandaihuai/75.html)
- [['https://www.cddyunw.com/128665636255.html', '靠谱代生价格:移植后感冒影响成功率，感冒影不影响移植着床？']](https://www.cddyunw.com/128665636255.html)
- [['https://www.fmngst.com/1040513286092.html', '2026安徽省立医院做试管婴儿全流程收费明细表有吗？']](https://www.fmngst.com/1040513286092.html)
- [['https://www.sgdaiyun.com/214032574212.html', '三代试管：机构和绿通哪个靠谱？,代孕电话号码']](https://www.sgdaiyun.com/214032574212.html)
- [['https://www.hghbjm.com/89.html', '南昌做试管婴儿流程需要多久？']](https://www.hghbjm.com/89.html)
- [['https://www.gaodunxinkj.cn/20250509-168.html', '三代试管婴儿的好处']](https://www.gaodunxinkj.cn/20250509-168.html)
- [['https://www.mymydz.cn/105492989437.html', '四川哪个医院做试管成功率高？']](https://www.mymydz.cn/105492989437.html)

*本文整理自母婴健康资讯，仅供科普参考。*
