# 产品名称：Robot-Delivery
# 产品描述：一款利用机器人配送快递的app，实现快递最后一公里的自动配送     
# 一、加值宣言
* 我认为目前市场上机器人配送快递的产品还没有广泛运用，本产品快递机器人能够在很大程度上节省人力成本，解决快递行业在分装配送方面的痛点。作为整个快递系统中末端配送的最后一环，快递机器人所具备的高负荷、全天候工作、智能等优点，为快递行业的“最后一公里”带来了解决方案。
# 二、需求概述
## 产品背景
- 随着人工智能时代的到来，在快递产业高速发展的今天，机器人配送的运用程度已经决定企业间相互竞争和未来发展的重要因素。配送机器人作为行业发展的大趋势，一方面将提高快递配送行业门槛，规范行业监管，为行业建立技术壁垒；另一方面，配送机器人也将有效提高行业服务效率，为市场提供更加个性化服务，也符合市场对于快递配送市场的期待。
## 产品市场
- 随着智慧物流大风的席卷，各企业的智能配送机器人已实现落地化，虽然配送机器人还处于风口浪尖上，但是我国在数据、视觉技术、语音识别等技术上的创新，未来配送机器人的发展将实现常态化的运营。我国人口红利逐渐慢慢消失，劳动力成本不断上涨，工业机器人代替人力成为发展趋势。物流行业是劳动密集型产业，在此背景下，物流市场对智能物流机器人的需求愈发迫切。在物流行业无人化、智能化发展的趋势下，我国物流机器人市场前景广阔。
# 三、核心价值
- 本产品Robot-Delivery为快递解决最后一公里配送的问题，智能规划配送路线，与百度地图API对接，规划最优配送路径，将包裹及时高效的送到指定位置，用户通过人脸识别提取包裹，完成取件。
# 四、行业、用户痛点 
|序号|行业痛点|用户痛点|
|:---:|:---:|:---:|
|1|配送环境的复杂：天气原因影响配送、道理交通的复杂性|快递配送过程中需要等待，消耗时间|
|2|配送需求增多：消费者对多样性配送服务的需求、配送场景和货品变得越来越复杂|天气条件影响收快递|
|3|配送人员的良莠不齐：无法对配送服务进行标准化|会有快递配送员态度恶劣的情况出现|
# 五、用户分析
## 目标用户群
- 
## 用户画像及使用场景
![avatar](https://gitee.com/Kevin-Kevin/image/raw/master/Robot%20Delivery/Robot-Delivery%E7%94%A8%E6%88%B7%E7%94%BB%E5%83%8F1.png)
- Joe:一位上班族男子，因工作日白天上班，不在家无法取快递，快递员也有工作时间，晚上也会下班，于是Joe在手机上打开Robot-Delivery app，在app查看自己的快递件，在app上预约取件时间，机器人就会根据Joe预约的时间准时送货上门，这样Joe就可以在下班后取快递了。
- Erin:
# 七、人工智能概率性与用户痛点
- 人工智能比以往的技术冲击范围更广、力度更大、持续性更长，甚至可能导致极化。人工智能未来30年内将几乎完全取代人力，根据牛津大学提供的数据：未来职业中快递员被人工智能取代的概率为90%。
## Robot-Delivery中百度地图开放平台API和百度AI开放平台的人脸识别，有一下优势：
- 地图中定位机器人与取件人的位置、以及机器人配送过程中的路况
|百度地图定位的优势/用户痛点|人脸识别取件人的人像的优势/用户痛点|
|:---:|:---:|
|1|2|
|1|2|
|1|2|
# 八、需求列表与人工智能API加值
|序号| API技术|用户场景|
|:---:|:---:|:---:|
|123455678|212345567|312345567|

# 九、产品结构图
# 十、数据推理
# 十一、产品原型及交互界面设计
# 十二、信息设计
# 十三、原档设计
# 十四、操作说明
# 十五、API的运用
# 十六、竞品分析
||菜鸟小G|Loomo Go|
|:---:|:---:|:---:|
|简介|机器人小G由菜鸟E.T.物流实验室研发，是一款可以在陆地上行走的机器人，并能配送大概10-20个包裹的机器人|一款由自平衡车开创者赛格威&纳恩博的SegwayRobotics机器人部门打造的送货机器人|
|优势|拥有像强大的独立思考能力和计算能力，自己会上电梯、感知电梯的拥挤程度|在室内室外能够达到厘米级定位精度；人脸识别功能，能够在公众环境认出主人和其它人物，并可以进行自主跟踪；应用场景不会局限的物流交付领域，它还可以执行巡检、监控等任务，可以应用到零售、医疗等一系列场景中|
|技术|采用了激光与视觉并行的SLAM方案，能够观察周边的复杂环境，并在系统中建立自己的多维世界，运用自适应粒子滤波算法，能够对动态实体进行准确的轨迹预测，避让行人、车辆，自己乘坐电梯，感知电梯的拥挤程度，选择乘坐（应用了自主感知、智能识别、运动规划等多项关键智能技术）|采用英特尔RealSense实感技术，使得机器人可以在现实世界中具备一定“视觉”。事实上RealSense实感技术包括精确的手势追踪，可以检测所有手关节的运动，以3D扫描周围的环境，通过面部识别来对人类面孔进行识别，并监测人们的情绪|
# 十七、API使用风险评估
# 十八、该产品未来的发展路线构想
