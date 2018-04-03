# Ranorex Studio - 布局

这个先导课程将会介绍Ranorex Studio环境的几个主要组成部分。

## Studio的开始页面

当打开Ranorex Studio，开始页展示如下页面

- 访问最近打开过的项目页面
- 直接创建新测试解决方案页面
- 访问产品例子页面（见下图）
- 直接打开现有的解决方案
- 获取关于已安装许可证的详细信息
- 下载最新版本的Ranorex 
- 观看最新的公告


![Ranorex Studio Startpage](http://p6g5m4isy.bkt.clouddn.com/image/layout/001-ranorex-studio-startpage.png-yellowWM)

## 产品样品-桌面端、Web端、移动端和跨平台

在Ranorex Studio的开始页面提供了几个产品例子，仔细研究他们，你可以学会如何创建桌面端、Web端和移动端的自动化测试。除此之外，还提供了一个跨平台样本，在一个测试脚本中对上述提及的平台进行测试

可以在开始页“样例项目”部分直接获取这些样例（见下述截图）

![Access Ranorex Product Samples](http://p6g5m4isy.bkt.clouddn.com/image/layout/002-ranorex-product-samples.png-whiteWM)

![Desktop Sample](http://p6g5m4isy.bkt.clouddn.com/image/layout/003-product-samples-desktop.png)

### 桌面端样例

此示例对桌面程序KeePass进行自动化测试       

#### 可以学到的内容：

- 变量绑定
- 数据连接
- 用户代码操作
- 参数
- 可选操作
- 嵌套测试用例
- 模块组
- 全局设置
- 结束区域 ~~（不知道怎么翻译）~~

![Web Sample](http://p6g5m4isy.bkt.clouddn.com/image/layout/004-product-samples-web.png)

### Web端样例 

此示例对在线博客工具WordPress进行自动化测试

#### 可以学到的内容

- 模块库
- 弹出式监视器
- 工程组织
- 报告截图
- 验证操作
- web测试
- 处理弹出式彩蛋
- 开始/结束区域
- 数据绑定


![Android Sample](http://p6g5m4isy.bkt.clouddn.com/image/layout/005-product-samples-android.png)
![iOS Sample](http://p6g5m4isy.bkt.clouddn.com/image/layout/006-product-samples-ios.png)


### Android和iOS移动端App样例

这些样例对Android和iOS平台的移动App KeePass进行自动化测试

#### 可以学到的内容

- 移动测试
- android
- ios
- 部署移动app
- 模块组
- 用户代码操作
- 开始/结束区域
- 数据连接
- 参数

![CrossPlatform Sample](http://p6g5m4isy.bkt.clouddn.com/image/layout/007-product-samples-crossplatform.png)

### 跨平台样例

此样例在桌面端、Web端和移动端进行自动化测试

### 可以学到的内容

- 跨平台测试
- 端对端测试
- ios
- android
- 部署移动app
- 模块库
- 项目组织
- 弹出式监视器
- web测试
- 移动测试
- 开始/结束区域
- 数据绑定

## 工作环境

在你开始使用Ranorex Studio创建你的第一个测试用例前，你需要知道Ranorex Studio的主要视图和布局

![Ranorex Studio main views](http://p6g5m4isy.bkt.clouddn.com/image/layout/008-ranorex-studio-main-views.png-blackWM)


> 小贴士：  
> 你可以在在这找到一个介绍[视频][1]（可以快速上手Ranorex测试自动化）,在每个视频之前，你将学到Ranorex Studio提供的不同视图。

ps:上面的视频是链接到油管的，不方便访问的可以点击这个百度云的[视频][2]~~还没有下载~~~



## 项目视图

Ranorex Studio的一个项目是基于文件的并且使用和Microsoft Visual Studio 2008/2010一样的项目文件格式。项目视图显示所有文件和目前项目关联的引用。一个Ranorex Studio项目会有如下文件类型

测试套件  表示项目中的测试套件（*.rxtst）
模块组    表示项目中的模块组（*rxtmg）
控件库    用来管理UI元素（*.rxrep）
录制文件  表示一个基于捕获/回访的自动化模块（*.rxrec）
代码文件  任何C#和VB.NET的文件，用来创建自动化模块的代码

项目视图主要用来添加新的文件，例如录制文件，控件库，模块组或是代码模块。

## 模块浏览器

模块浏览器根据项目的代码文件列出所有可用的模块（代码模块和录制模块）和基于项目模块组文件的模块组。此外，也列出了有模块和模块组中定义的所有变量。这个视图主要用来在测试套件视图中拖放和重复使用自动化模块和模块组。

项目视图中的制定文件夹（例如录制文件）用来对模块进行分组。可以使用模块浏览器的搜索区域来查找现有的模块。

## 文件视图

当在工程视图或是模块浏览器视图中双击打开一个文件或是模块时，与之关联的文件将在Studio的文件视图中打开，这个视图主要用来下图中的操作

- 创建或调整录制模块  
  ![Craeating or adapting a recording module](http://p6g5m4isy.bkt.clouddn.com/image/layout/009-Recording-with-Repository.png-blackWM)

- 使用控件库
  ![Working with the repository](http://p6g5m4isy.bkt.clouddn.com/image/layout/010-Repository.png-blackWM)

- 使用项目的模块组
  ![Working with the project's module groups](http://p6g5m4isy.bkt.clouddn.com/image/layout/011-Module-Groups.png-blackWM)

- 写代码模块
  ![Writing code modules](http://p6g5m4isy.bkt.clouddn.com/image/layout/012-Code-Module.png-blackWM)

- 阅读一份测试报告
  ![Viewing a test report](http://p6g5m4isy.bkt.clouddn.com/image/layout/013-viewing-a-test-report.png-blackWM)

- 使用项目的测试套件
  ![Working with the project's test suite](http://p6g5m4isy.bkt.clouddn.com/image/layout/014-working-with-the-test-suite.png-blackWM)


[1]:http://youtube.com/watch?v=0S_YC7uwI-s

[2]:http://taylortaurus.top


































