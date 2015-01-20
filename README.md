《 iOS 开发进阶》随书示例程序和勘误
=======

<!-- 
![图书封面](https://raw.githubusercontent.com/tangqiaoboy/iOS-Pro/master/BookCover.jpg)
-->

##重要信息

 * [主要内容目录](https://github.com/tangqiaoboy/iOS-Pro/blob/master/TableOfContents.md)
 * [相关评语](https://github.com/tangqiaoboy/iOS-Pro/blob/master/Recommendation.md)

##图书购买链接

 * [京东购书地址](http://item.jd.com/11598468.html)
 * [亚马逊购书地址](http://www.amazon.cn/iOS%E5%BC%80%E5%8F%91%E8%BF%9B%E9%98%B6-%E5%94%90%E5%B7%A7/dp/B00R43XG9S/ref=sr_1_2?ie=UTF8&qid=1418997212&sr=8-2&keywords=ios%E5%BC%80%E5%8F%91%E8%BF%9B%E9%98%B6)
 * [china-pub购买地址](http://product.china-pub.com/3770871)
 * [签名版图书（限量99本）](http://product.china-pub.com/3999453)

## 随书示例程序说明

文件路径 | 文件说明 | 下载链接
----- | ----- | -----
`/DemoProjects/Flurry.zip` | 统计工具Flurry 章节示例程序 | [下载](https://raw.githubusercontent.com/tangqiaoboy/iOS-Pro/master/DemoProjects/Flurry.zip)
`/DemoProjects/CoreText.zip` | 基于CoreText的排版引擎 章节示例程序 | [下载](https://raw.githubusercontent.com/tangqiaoboy/iOS-Pro/master/DemoProjects/CoreText.zip)
`/DemoProjects/UIWindow.zip`| UIWindow 章节示例程序 | [下载](https://raw.githubusercontent.com/tangqiaoboy/iOS-Pro/master/DemoProjects/UIWindow.zip)
`/DemoProjects/RetainCount.zip`| 理解内存管理-引用计数 章节示例程序 | [下载](https://raw.githubusercontent.com/tangqiaoboy/iOS-Pro/master/DemoProjects/RetainCount.zip)
`/DemoProjects/RetainCycle.zip`| 理解内存管理-循环引用问题 章节示例程序| [下载](https://raw.githubusercontent.com/tangqiaoboy/iOS-Pro/master/DemoProjects/RetainCycle.zip)
`/DemoProjects/CreateClass.zip`| Objective-C对象模型-动态创建对象 章节示例| [下载](https://raw.githubusercontent.com/tangqiaoboy/iOS-Pro/master/DemoProjects/CreateClass.zip)
`/DemoProjects/TaggedPointer.zip`| Tagged Pointer对象 章节示例程序| [下载](https://raw.githubusercontent.com/tangqiaoboy/iOS-Pro/master/DemoProjects/TaggedPointer.zip)


## 勘误

 * 第3页，`我使用的是Newsfy`一句中单词拼写错误，应该是 `Newsify`。
 * 第10页，`occhina`拼写错误，应该是`oschina`。
 * 第108页，UIWindow章节中的示例代码中使用了`resignKeyWindow`方法，但是苹果不推荐直接调用该方法，推荐的改法是，隐藏的时候将window.hiden=YES，然后设置为nil，再把原来的window makeKeyWindow。
 * 第136页，第一行末尾，"一嗨租车虽然已经修改了登录协议"一句。应该将`一嗨租车`改成`神州租车`。
 * 第192页，18.2.8小节，"而master分支增加了一个名为ApeDropDownRightArrow.png的资源文件"一句。应该将`ApeDropDownRightArrow.png`改为`gDifficultyBar.pn`。
 * 第202页，生成ipa除了可以使用书中介绍的方法外，更好的方法是用 `xcodebuild` 自己的 `-exportArchive -exportFormat ipa` 命令。

## 本书对应的“iOS开发”微信公共帐号

![iOS开发](http://blog.devtang.com/images/weixin-qr.jpg)


