

# 开发人员提高开发效率的10个推荐工具

![在这里插入图片描述](https://img-blog.csdnimg.cn/287f402d92de4a99af65e1044d754ea3.jpeg#pic_center)


推荐10个能够提高开发人员开发效率的10个工具

### 腾讯云开发CloudBase

云开发（Tencent CloudBase，TCB）： Cloud Base是腾讯云提供的云原生一体化开发环境和工具平台，例如我们可以再这个平台上来搭建自己的网站，或者直接部署静态页面，它还支持域名的绑定和免费证书的申请，搭建一个自己的博客系统只需要十分钟

CloudBase的能力非常强大, 支持非常多的功能,具体的可以看看 [官网文档](https://cloud.tencent.com/document/product/876/18431)

但是我这里介绍一个非常常用的一个需求场景,那就是可以快速的部署一个静态网站。

例如我想搭建一个人博客系统, 按照普通流程,我们可能需要有自己的服务器来部署相应的博客系统
这里面涉及到运维精力和服务器成本,本来是一个简单的需求你可能需要花上几天,还有关注系统的稳定性。

当然你也可以用Hexo静态博客系统,但是把代码提交到Github上,然后Github的网速会非常影响你的博客相应速度。如果想要再自定义域名、 CDN、等等成本就上来了。

在这种场景下,CloudBase就很好的支持了这一场景,你可以直接把Hexo静态文件上传到CloudBase中,它的静态网站托管功能可以直接把你的静态文件部署到服务器上并访问。

最重要的是它居然**内部就支持了Hexo的命令**,也就是说可以通过Hexo Cli命令一键部署,非常简单快速。

[搭建Hexo](https://cloud.tencent.com/document/product/1210/43365)

当然对应静态网站的支持不仅仅是Hexo，还有支持了很多其他比如VuePress。

如果想**启动自定义域名并且开始HTTPS**,只需要一建绑定就行,如下：
![在这里插入图片描述](https://img-blog.csdnimg.cn/fb67e9af223149b99320099cc2903016.png)
**并且证书是免费的哦**

用CloudBase部署个人博客,10分钟就可以完成,可以看看我的个人博客就是用的CloudBase部署的

[石臻臻的杂货铺](https://www.szzdzhp.com/)


### KnowStreamin
KnowStreaming：Know Streaming脱胎于互联网公司内部多年的Kafka运营实践经验，是面向Kafka用户、Kafka运维人员打造的共享多租户Kafka管控平台，用这个平台免去了开发人员对Kafka运维的成本。

[knowstreaming 官网 ](knowstreaming.com)

### Alfred

**Alfred**：Mac电脑扔掉鼠标高效率操作电脑的必备神器，能够快去检索各种软件并打开，也可以直接操作各种文件，最重要的是它支持工作流，这就给了它无限空间，比如我们可以把开发者经常用的工作制作成工作流


Alfred是Mac必备的神器, 它可以简化你在Mac上的90%的操作,比如搜索软件并打开、不打开浏览器直接搜索、强大的文件搜索和操作能力、**最重要的工作流**。

工作流可以把你想要的功能集成到Mac中,比如直接**搜索翻译**、
![在这里插入图片描述](https://img-blog.csdnimg.cn/c02dc57e4e874c4faabda49d7f7058fb.png)
还用更多的功能,等待你去发掘


### Eolink

Eolink：Api管理,前后端联调的高端工具，可以降低前后端的沟通成本，提高开发效率

结合 API 设计、文档管理、自动化测试、监控、研发管理和团队协作的一站式 API 生产平台

API 文档与研发管理
API 监控和异常告警
API 快速测试与自动化测试
API 微服务网关


### Excalidraw

Excalidraw：优秀的工程师都需要一个优秀的画图工具,这款软件可以让你快速画出整洁美观的各种图

[Excalidraw](https://github.com/excalidraw/excalidraw) 就是这么一款开源软件 , 支持各种各样的图形,并且画出来的图不会那么刻板,颜值很高




### MDnice

MDnice：写文档是开发者必不可少的,用MarkDwon语句来写文档是工程师的主流,MdNice是一款优秀的MarkDown编辑器,还内置了各种丰富的主题，还可以一键复制样式到其他不支持MD样式的平台

![在这里插入图片描述](https://img-blog.csdnimg.cn/5f1eba9180de4975973e29124b7ca191.png)


### tool.lu

在线工具https://tool.lu/ ：开发过程少不了需要各种工具箱,例如 Json格式化、时间错转换、Cron时间计算等等,都在这个百宝箱里一应俱全


这个百宝箱里面包含了IT人员常用的在线工具, 合理快速的找到对应的工具,会让你的开发效率大大提升


### ToDesk

远程桌面ToDesk：为了应对突然情况,让开发者能够在家能够远程操控自己公司的电脑，一款稳定可靠的远程控制器必不可少

主要是免费,不仅免费,画质还清晰,对于需要经常远程改Bug的程序猿来说,用家里的电脑远程控制公司电话来修bug,稳定性非常重要。


### 印象笔记
印象笔记：在线协同笔记,开发者需要时刻记录一些笔记,并且能够远程存储并协调作业。

重要的是这款远程笔记也支持Markdown

### PrettyZoo

PrettyZoo：PrettyZoo是一款优秀的可视化zookeeper管理工具,能够对zookeeper方便的进行增删改查的操作。方便开发人员对zookeeper的了解。

相比于去服务器上用CLI, 这个简直就是开发人员的福音

![在这里插入图片描述](https://img-blog.csdnimg.cn/287f402d92de4a99af65e1044d754ea3.jpeg#pic_center)


