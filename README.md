# DZMeBookRead

本次更新 : 

1.上下滚动的内存问题 现在只要看不见的章节都会进行清理内存 不会占用内存

2.修改了一个BUG  上下滚动模式中 左侧滑栏切换章节之后 往上滚会快速切换章节问题 已修复

重要BUG: 上下滚动之后 切换字体 往上滚动 由于字体变化 那么cell的高度也会变化 这个时候滚动上去显示新的章节 会造成tableview 上移或者下推问题 这个也是上下滚动模式最麻烦的BUG 已修复

已更新Swift3.0 Xcode版本: Xcode8.1 该Demo仅供参考思路

原作者DZM 最完整小说阅读器Demo 

翻页效果(无效果,覆盖,仿真,上下滚动) 

时间 电池 章节尾部占位广告图片(可取消) 

支持字体 字体大小切换 背景颜色切换 书签功能 等等.. 

阅读记录保存与下次阅读定位 亮度调整 

Txt格式解析 别的格式也可以解析 需要的可以联系我 我这里只做了一种（由于存放字体文件会导致文件太大 我这里面的字体就随便用了几个系统的代替下 这样下载包也小,由于先写完公司项目则文件名用的是公司前缀没时间改将就啦) 

小说《覆盖效果》DZMCoverAnimation: https://github.com/dengzemiao/DZMCoverAnimation


                                                                            ---------------- 技术QQ群:52181885

#Demo效果GIF：

![CarouselView in action](Untitled.gif)

#书签使用效果GIF：

![CarouselView in action](bookMark.gif)
