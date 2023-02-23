# 浏览器书签很不方便检索 用Github来帮助收集
只是用来收集网址,建议还是使用notion 印象笔记等收集文章做备份,以防文章打不开 丢失等情况


Table of Contents
- [Blog](#blog)
- [公开课](#公开课)
- [Unity](#unity)
  - [Unity Editor](#unity-editor)
  - [Post Processing](#post-processing)
  - [多光源优化](#多光源优化)
  - [程序化天空球](#程序化天空球)
  - [阴影](#阴影)
  - [大气散射](#大气散射)
  - [优化](#优化)
  - [NPR](#NPR)
  - [框架&开源库](#框架)
- [Util](#util)
- [Code](#code)
- [资源](#资源)



# Blog
- [烟雨迷离半世殇](https://www.lfzxb.top/archives/) :
- [恶毒的狗](https://baddogzz.github.io/) :
- [Catlike Coding](https://catlikecoding.com/) :
- [苍白的茧](http://dreamfairy.cn/blog/) :
- [BRONSON ZGEB](https://bronsonzgeb.com/) :
- [walkingfat 行尸走油](http://walkingfat.com/) :
- [Simon schreibt.](http://simonschreibt.de/) :
- [MA YIDONG](http://ma-yidong.com/category/blog/) :
- [陆泽西](http://www.luzexi.com/tag/Unity3D/) : <Unity3D高级编程-主程手记>作者
- [冯乐乐](http://candycat1992.github.io/)
- [L's Blog](http://www.liuocean.com/)
- [zznewclear13](https://zznewclear13.github.io/posts/) : 
- [GDC Vault](https://www.gdcvault.com/browse/)
- [UWA 开源库](https://lab.uwa4d.com/)

# 公开课
- [Games101](https://www.bilibili.com/video/BV1X7411F744) : 现代计算机图形学入门-闫令琪
- [Games202](https://www.bilibili.com/video/BV1YK4y1T7yY) : 高质量实时渲染
- [庄懂](https://space.bilibili.com/6373917/channel/collectiondetail?sid=185897) : 技美入门课 特别特别推荐
- [Games104](https://www.bilibili.com/video/BV1oU4y1R7Km) : 游戏引擎导论


# Unity
## Unity Editor 
编辑器相关
- [Odin插件](https://aihailan.com/archives/466) : 
- [Unity编辑器拓展基础总结](https://www.lfzxb.top/unity-editor-extension-base/)
- [自定义UnityToolbar](https://blog.csdn.net/u011428080/article/details/106689329) : 可以实现自定义面板功能按钮

## Post Processing
后处理相关
- [X-PostProcessing-URP](https://github.com/tkonexhh/X-PostProcessing-URP) : 我搬运毛星云到URP 同时加入了很多其他后处理
- [高质量泛光（bloom）从理论到实战](https://zhuanlan.zhihu.com/p/525500877) : 

### TAA
- https://zhuanlan.zhihu.com/p/46841906 : Unity Temporal AA的改进与提高
- https://zhuanlan.zhihu.com/p/112565771 : TAA的各种artifact及解决方案

## 多光源优化
### Cluster Based Light
- https://zhuanlan.zhihu.com/p/108688512 :
- https://zhuanlan.zhihu.com/p/464099000 : Unity SRP 实战（四）Cluster Based Lighting
- https://zhuanlan.zhihu.com/p/72252279 : Cluster_Unity实现详解(一)预计算AABB

## 程序化天空球
- https://feralpug.github.io/OtherPages/Code/Pages/ExtendingUnitySkybox/ExtendingSkybox.html
- https://timcoster.com/2019/09/03/unity-shadergraph-skybox-quick-tutorial/
- [Unity 卡通渲染 程序化天空盒](https://zhuanlan.zhihu.com/p/540692272) : 这篇文章很喜欢

## 阴影
- https://zhuanlan.zhihu.com/p/460945398 : 级联阴影贴图 CSM
- https://zhuanlan.zhihu.com/p/462371147 : PCSS 软阴影与性能优化

## 体积光
- https://zhuanlan.zhihu.com/p/573203289 :
- https://zhuanlan.zhihu.com/p/124297905 : 
- https://github.com/MaxwellGengYF/Unity-Volumetric-Light :

## 大气散射
- https://zhuanlan.zhihu.com/p/36498679 : 冯乐乐的
- https://zhuanlan.zhihu.com/p/548799663 : 游戏魔法编程：unity实现完整大气散射
- https://zhuanlan.zhihu.com/p/127026136 : 基于物理的大气散射 in Unity URP
- https://github.com/SlightlyMad/AtmosphericScattering : 非常完备的实现
- https://zhuanlan.zhihu.com/p/237502022 : 从零实现一套完整单次大气散射
- https://github.com/AKGWSB/RealTimeAtmosphere : 

## 优化
- https://www.bilibili.com/video/BV1AL4y1b75c/ 很好的渲染向优化系列 是市面上比较少的良心教程

## NPR
- https://zhuanlan.zhihu.com/p/435005339 : 原神Shader渲染还原解析

## 框架
- https://github.com/DonnYep/CosmosFramework 
- https://github.com/EllanJiang/GameFramework
- https://github.com/egametang/ET : ET 框架
- https://github.com/tuyoogame/YooAsset : YooAsset Unity 资源框架 非常推荐
- https://github.com/526077247/TaoTie : 基于YooAsset资源管理的轻量级UI框架
- https://github.com/tuyoogame/huatuo : 配表自动生成工具 非常推荐
- https://github.com/focus-creative-games/hybridclr : 热更新

# Util
- [图形计算器 graphtoy](https://graphtoy.com/) : https://graphtoy.com/
- [图形计算器 desmos](https://www.desmos.com/calculator?lang=zh-CN) : 可以登录 然后保存图形公式
- [.Net Reference Source](https://referencesource.microsoft.com/) : 可以查看C#的具体实现
- [UnityCsReference](https://github.com/Unity-Technologies/UnityCsReference) : 可以查看Unity一些组件的C#实现 常看常新


# Code
- [设计模式](https://refactoringguru.cn/design-patterns/catalog)
- [Unity下设计模式](https://github.com/su9257/DesignPatternsFamilyBucket)

# 资源
- [OpenGameArt](https://opengameart.org/) : 啥都有 图片音乐模型 质量不一
- [Mixamo](https://www.mixamo.com/) : 有大量动作
- https://itch.io/game-assets : 免费 付费的都有 质量不错
- [原神MMD资源](https://www.aplaybox.com/u/680828836) : 
