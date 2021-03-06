# API_internship
#### 介绍
本仓库存放“实习宝”产品文档： **在路上，我们为你提供更全面的实习信息。**  
#### 20x20带narration介绍
[https://github.com/Eddieda6/internship/blob/master/1.mp4](https://github.com/Eddieda6/internship/blob/master/1.mp4)
#### “实习宝”产品文档版本

| 产品状态         | 未完成          |
| ---------------- | --------------- |
| 产品负责人       | 唐颖欣          |
| 产品文档编辑     | 唐颖欣          |
| 最后修改时间     | 12.23 / 16：21 |
| 产品预计上线时间 | 2019.12.30      |

### “实习宝”产品文档概述

|PRD价值主张设计|原型设计|API输出|
| --- | --- | --- |
|<a href="#1">加值宣言</a>|<a href="#21">交互及界面设计</a>|<a href="#31">API(1)使用水平</a>|
|<a href="#2">核心价值</a>|<a href="#22">信息设计</a>|<a href="#32">API(2)使用水平</a>|
|<a href="#3">用户痛点</a>|<a href="#23">原型文档</a>|<a href="#35">API(3)使用水平</a>|
|<a href="#4">人工智能概率性</a>|<a href="#24">口头操作说明</a>|<a href="#33">使用比较分析</a>|
|<a href="#5">需求列表</a>|     |<a href="#34">使用后风险报告</a>|
|<a href="#6">版本迭代</a>|     |     |

### PRD价值主张设计

#### <a name="1">加值宣言</a>
运用高德精确定位API及百度图像识别API，再配合VR技术提前一步帮实习生探知公司的周边环境，为实习生提供更全面的实习信息。


#### <a name="2">核心价值</a>

1.  多：实习职位信息更全面
2.  快：用户打开软件可根据定位寻找实习公司
3.  好：直面公司周边环境更了解实习单位
4.  省：提前预知更省事省时

#### <a name="3">用户痛点</a>

1.  其他实习软件对于公司环境的信息不全面。
2.  市面上的实习软件公司信息并不全面，大部分没有公司实体照片及精确的定位信息，造成求职者与公司的信息不对称。
3.  在人生地不熟的城市里受到面试邀请时，大部分都没有去过这间公司，面试前因地理位置不熟悉等心理障碍会害怕。

<div align=center><img src="http://www.tryineapp.com/upload/201810/16/201810161058303415.jpg"></div>


#### <a name="4">人工智能概率性</a>
1.  图像识别的技术准确性高（之后配上百度api、azure的api对比分析）  
即使品牌logo识别API是基于百度海量数据，利用深度学习技术及高精度算法不断迭代模型，准确率业界领先，但此APP主要功能依附于品牌logo识别API上，因此失误率引发用户的负面情绪的可能性一般，用户体验的负面影响压过正面影响的机率较大。  
解决方案：仅使用一款API带来的用户负面情绪风险较大，我们将配合图像搜索API及通用物体和场景识别API多向分析，尽量减少失误率带来的用户负面情绪。  
2.  高德定位API的准确性逼近100%，在定位方面并不存在过多差异。即使定位信息出现了差错，因用户关心的并不是定位精确性的问题，用户在使用此软件过程中更多的是考虑附近公司与用户此刻的位置距离及附带的公司信息，由此API失误率引发用户的负面情绪的可能性较低，用户体验的负面影响压过正面影响的机率较低。

#### <a name="5">需求列表</a>
##### 百度图像识别API
1.  地标识别API————拍照识图  
将地标识别服务集成到识图APP/小程序中，识别照片中出现的中外著名地标、景点，广泛应用于综合识图场景。
2.  品牌logo识别API————品牌信息获取  
根据拍摄照片，识别图片中商品logo名称，加快品牌信息获取速度，给消费者轻松高效的信息获取体验，促进消费者向投资者转化，适用于需要快速获取品牌信息的业务场景中。

### 原型设计  
#### <a name="21">交互及界面设计</a>
 **1.总览**  
 
![总览](https://images.gitee.com/uploads/images/2019/1223/160113_c789e400_1831445.png "总览.png")  


**2.产品架构**    

![产品架构图](https://images.gitee.com/uploads/images/2019/1223/160708_e3528ccd_1831445.png "产品架构图.png") 

#### <a name="22">信息设计</a>
- 2.附近页面使用了高德定位API的加值—————  
  2.1用户定位信息与公司距离的定位信息，以地图的方式展现出来 及 2.2 步行距离路线推荐
- 4.公司信息使用了百度品牌logo及地标识别api的加值————  
  4.1用户可以拍照，从而识别出品牌及企业信息

#### <a name="23">原型文档</a>
[原型文档下载](https://gitee.com/NFUNM172015260/internship_rp)  
[原型文档查看](http://nfunm172015260.gitee.io/internship_rp/#g=1&p=%E5%B0%81%E9%9D%A2)

#### <a name="24">口头操作与说明</a>  
- 1.登陆页面—————1.1用户选择身份登入  
  1.2 首页界面—————用户可以在首页上得到至少四种核心信息：（1）搜索公司职位、（2）“附近”功能、（3）招聘信息、（4）社区、用户、定位菜单栏
- 2.附近页面—————点击卡片进入公司首页详情，以定位距离做排序  
  2.1用户定位信息与公司距离的定位信息，以地图的方式展现出来  
  2.2 步行距离路线推荐
- 3.公司详情————用户就可看到公司周边环境图片/ 联系方式  / 工商信息  
  3.1周边环境————用户可以看到公司的外部环境图，包括有什么便利店及出租房等信息   
  3.2沟通列表————以时间排序的沟通列表，缩略图可以看到投递进度   
- 4.拍照识图————用户可以拍照识别出品牌logo信息及企业信息    

### API输出
#### <a name="31">API(1)使用水平</a>  
- 百度品牌logo识别api：  
![1](https://images.gitee.com/uploads/images/2019/1226/155532_a12157f6_1831445.jpeg "捕获LOGO.JPG")

#### <a name="32">API(2)使用水平</a>  
- 百度地标识别api：  
![2](https://images.gitee.com/uploads/images/2019/1226/155551_e117f337_1831445.jpeg "捕获地标.JPG")  

#### <a name="35">API(3)使用水平</a>
- 百度通用物体及场景识别api：  
![3](https://images.gitee.com/uploads/images/2019/1226/155606_aaa4b710_1831445.jpeg "LOGO2.JPG")  

#### <a name="33">使用比较分析</a>
- 优缺点对比：  

|              | 百度图像识别api                                                                                                                                                                                                                                    | 微软Azure计算机视觉SDK                                                                                                                                                                                                                                   |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 技术文档链接 | <br>[地标识别](https://ai.baidu.com/ai-doc/IMAGERECOGNITION/jk3bcxbih)</br>   <br>[通用物体和场景识别高级版](https://ai.baidu.com/ai-doc/IMAGERECOGNITION/Xk3bcxe21)</br>    <br>[logo识别](https://ai.baidu.com/ai-doc/IMAGERECOGNITION/Ok3bcxc59)</br> | [快速入门：计算机视觉客户端库](https://docs.microsoft.com/zh-cn/azure/cognitive-services/computer-vision/quickstarts-sdk/python-sdk)                                                                                                                     |
| 优点         | 百度api对于代码小白十分照顾，教程十分全面文档简单易懂，代码简单好上手；类别丰富、图像识别的下栏有多于十种，服务器在国内，等待响应时间迅速                                                                                                                                                                                 | 一个SDK就涵盖了超过八种图像识别能力，包括获取图像说明/类别/标记、检测物体/人脸/品牌、检测色情或血腥内容，更有获取图像配色方案等高阶能力操作，只需要调用一个SDK就可以做到超过八种的识别分析能力。并提供了github上的源代码。 |
| 缺点         | 不够全面，多个API调用麻烦，需要分开调用，技术文档不够azure丰富                                                                                                                                                                                                            | 针对受众偏向欧美地区，中国地区相对较少人使用，甚至在定价上没有提供中国区域的服务；服务器在国外，等待响应时间较长；                                                                                                                                                                      |
 
 
- 定价对比：  

|            | 百度API            | Azure API                |
| ---------- | ------------------ | ------------------------ |
| 免费调用量 | 500次/天           | 20TPS /分钟              |
| 付费调用量 | 无限制             | 600TPS /分钟             |
| 付费价格   | 3元/千次（0-300M） | 2.88元 /千次（100-10M ） |

- 总体评价：  
百度API精确性跟Azure API差别很少，但Azure在人脸识别上的脸部情绪和细节掌握比较精确，但本产品用于品牌logo识别和场景检测上，在精确度和出错率都几乎可以看成一致的时候，我们将切回调用性价比和调用难易程度因素。百度api的技术文档比较多可供参考，对技术的要求较低。

#### <a name="34">操作后风险报告</a>
  - 技术文档：  
  [logo识别](https://ai.baidu.com/ai-doc/IMAGERECOGNITION/Ok3bcxc59)和[通用物体和场景识别](https://ai.baidu.com/ai-doc/IMAGERECOGNITION/Xk3bcxe21)  
  - 图像识别功能：  
  超过2万类商品logo，可准确识别图片中品牌logo的名称和所在图片中的位置，亦同时可以自建品牌logo图库，快速创建专属品牌logo图库，通过调用入库接口上传图片，支持海量图片入库。  
- 未来发展所需：  
微软最近公布了一篇关于图像识别的研究论文，在一项图像识别的基准测试中，电脑系统识别能力已经超越了人类。人类在归类数据库Image Net中的图像识别错误率为5.1%，而微软研究小组的这个深度学习系统可以达到4.94%的错误率。”从这则新闻中我们可以看出图像识别技术在图像识别方面已经有要超越人类的图像识别能力的趋势。这也说明未来图像识别技术有更大的研究意义与潜力。而且，计算机在很多方面确实具有人类所无法超越的优势，也正是因为这样，图像识别技术才能为人类社会带来更多的应用。
- API市场竞争程度：  
  百度的图像识别api在细节上跟Azure还是有出入的，在细节上Azure做到极致，将误差率减低到4.94%，在API市场上独领风骚，在这方面上百度还是要不断修改算法机制吧误差减低才可以在国际市场上打出名堂。  

  - 可替代的程序库：  
  本产品图像识别可替代的程序库还未实现，我们采用更加成熟的图像识别API；
  
  - 输入输出限制及定价： 
  ![输入输出限制及定价](https://images.gitee.com/uploads/images/2019/1226/212807_0a65949c_1831445.jpeg "price.JPG")





