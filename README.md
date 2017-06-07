# Homework
# **“超跑俱乐部”网页——期末作业报告**

标签（空格分隔）： html css 期末作业 网页

---
&emsp;&emsp;本学期选修了WEB前端课程，掌握了一定的WEB开发技术，从前期Xampp的搭建，wordpress的使用，markdown文本的书写，到html语言，css样式，JavaScript的学习，接着最后的Github的使用。我根据老师的要求，一步一步的完成布置的任务。
&emsp;&emsp;一个学期又将结束，为了检验我们的学习成果，便布置了一个网页书写的期末大作业。为此耗费了三个星期，终于完成了该作业。
**（注：该网页请使用IE8以上浏览器访问！）**

--------
##*作业介绍*

一、主页

在开始此次作业之前思考了很久，最后敲定了超级跑车这个主题，灵感来自于《速度与激情》电影。虽然主题敲定了，但是页面的风格并没有确定，这的确是特别的伤脑筋啊。参考了百度、谷歌、淘宝、京东、杭电等网站，最后决定来模仿Apple的网站风格，修改为自己所用，只是模仿，并非抄袭，很多的地方都有自己的创意的。

![主页][1]

首先，应为我做的网页是一个俱乐部的介绍网页，所以在开头就表明了该俱乐部的名字，而这个俱乐部是会员制的，所以也加入了有“登录/注册按钮”.

接下来的部分便是作业要求中所需要的**轮播图**，该轮播图**是基于jquery插件**而成的，有自动播放功能。

![介绍][2]

然后便是社团的简介部分，采用了类似书签的设计思路，点击书签便会跳转到相应的div页面，此时其他的div页面便会消失，这里采用了**js**设计，运用**了onclick的方法**。而在书签上也加入了**伪类标签**，当鼠标放上后便会有不同的效果。书签的导航栏底部也采用的border样式进行修饰。

本网站的所有背景使用了老师提供的WWW.OPENXY.COM网站中提供的纹理背景图


---------------
二、详细介绍页

选择任意的汽车品牌的书签后，点击“了解更多”便进入了详细的跑车介绍页面，采用了lykan hypersport为例子。

![此处输入图片的描述][3]

除导航栏外，第一眼边能看到一个视频，这是根据作业的要求而设置的，改视频是自动播放的功能，打开该网页**便自动播放**了

![排版][4]

接下来的便是根据div属性，进行排版，对该车进行了较为详细的介绍，其中运用了**shadow元素修饰部分div边框**

另外应为页面过长，便添加了一个置顶按钮，**使用position=fixed进行**定位，而该按钮便是采用**百度百科中sprite图**，进行移动后所得。


----------------------
三、登录页面

![登录][5]

若你点击了“登录/注册”按钮，便进入了登录页面，基本框架还是那样，但该页面中的“登录”部分的div除了使用shadow修饰外还**添加了border-radius元素**，使其四角变为弧形

![注册][6]

其次，点击注册，也会通过js跳转至另一div板块
在此不但按照要求使用了**6种表单元素**，还加入了图标字体，**图标字体**是阿里巴巴的素材。另外，部分表单中也加入了js脚本，**形成了“点击文本框文字消失”的效果。**
两个按钮的**背景颜色运用了渐变的属性**
并且运用js脚本，将**输入进去的内容进行保存**，避免刷新后消失。


------------------
四、个人介绍页

![个人介绍][7]
最后，个人介绍的页面的导航栏也采用了**fixed定位**的方法使其固定在浏览器顶端，另外也采用了诸多的上述方法，还添加了有**表格**的元素。在邮箱的元素中，采用了“mailto:”方法，但点击邮箱时即可发送邮件。


  [1]: http://a2.qpic.cn/psb?/V10s8mvk0BESLR/u5dVj02yD5wKRX0BuhwFQTgho9nojIJdtluZRgUUPdA!/b/dGwBAAAAAAAA&bo=0QSAAgAAAAADAHI!&rf=viewer_4
  [2]: http://a2.qpic.cn/psb?/V10s8mvk0BESLR/HGz20bfXCGpy.eYQCB67ItgjllM3chjN3gBWCWG1pzY!/b/dGwBAAAAAAAA&bo=qwSAAgAAAAADAAg!&rf=viewer_4
  [3]: http://a2.qpic.cn/psb?/V10s8mvk0BESLR/N08JvgRSmXTjVPzkeop5jnZjdj82.QgbrjyQhjgGadY!/b/dGwBAAAAAAAA&bo=LQWAAgAAAAADB4g!&rf=viewer_4
  [4]: http://a2.qpic.cn/psb?/V10s8mvk0BESLR/tljKaDzTo9xPe.mEjLKuO91yj4RFXIHB6x1c48ITiNY!/b/dG0BAAAAAAAA&ek=1&kp=1&pt=0&bo=9gWAAgAAAAADVwM!&tm=1496131200&sce=60-4-3&rf=viewer_4
  [5]: http://a1.qpic.cn/psb?/V10s8mvk0BESLR/2zXH455HvbwYf4rDlEm4bWNLbZU0uebzu610fwzW94E!/b/dG4BAAAAAAAA&bo=NwWAAgAAAAADAJU!mvk0BESLR/tljKaDzTo9xPe.mEjLKuO91yj4RFXIHB6x1c48ITiNY!/b/dG0BAAAAAAAA&ek=1&kp=1&pt=0&bo=9gWAAgAAAAADVwM!&tm=1496131200&sce=60-4-3&rf=viewer_4
  [6]: http://a1.qpic.cn/psb?/V10s8mvk0BESLR/hBjkBht7P*cgm0CrdFOUaIBKdETkZU3G9eYSIDFkuWA!/b/dG4BAAAAAAAA&bo=CQWAAgAAAAADAKs!&rf=viewer_4
  [7]: http://a3.qpic.cn/psb?/V10s8mvk0BESLR/zNemkPjXfZeCJUoCaubep1zodZaYkJsAYPBoN7nPUeU!/b/dIIBAAAAAAAA&bo=0gOAAgAAAAADB3E!&rf=viewer_44
