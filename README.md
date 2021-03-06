TimLiu-Android
==============

自己总结的Android开源项目及库。 github排名 [https://github.com/trending](https://github.com/trending),github搜索：[https://github.com/search](https://github.com/search)

###  目录
- [UI](#UI)
  
    - [卫星菜单](#卫星菜单)
    - [节选器](#节选器)
    - [下拉刷新](#下拉刷新)
    - [模糊效果](#模糊效果)
    - [HUD与Toast](#HUD与Toast)
    - [进度条](#进度条)
    
- [动画](#动画)


- [网络相关](#网络相关)
- [响应式编程](#响应式编程)
- [地图](#地图)
- [数据库](#数据库)
- [图像浏览及处理](#图像浏览及处理)
- [视频音频处理](#视频音频处理)
- [测试及调试](#测试及调试)
- [消息推送](#消息推送)
- [完整项目](#完整项目) 
- [插件](#插件)
- [出名框架](#出名框架)
- [其他](#其他)
- [好的文章](#好的文章)
- [收集android上开源的酷炫的交互动画和视觉效果](#收集android上开源的酷炫的交互动画和视觉效果)
- [UI资源](#UI资源)
- [开发资源](#开发资源)
    - [他人开源总结](#他人开源总结)
    - [中文开发博客列表](#中文开发博客列表)

========
### 具体内容 =============================
========
##### UI
* [Awesome-MaterialDesign](https://github.com/lightSky/Awesome-MaterialDesign) - MaterialDesignCenter改名为Awesome-MaterialDesign，优化了布局，新增了不少库。
* [awesome-android-ui](https://github.com/wasabeef/awesome-android-ui) - ui库，非常多的ui及特效。
* [ChipsLibrary](https://github.com/AndroidDeveloperLB/ChipsLibrary) - 在Android EditText中实现打Tag功能。
* [bitmapMesh](https://github.com/7heaven/bitmapMesh) - 拉窗帘效果。
* [ObservableScrollView](https://github.com/ksoichiro/Android-ObservableScrollView) - 在滚动的视图观测滚动事件的Android库
它易于与在Android 5.0 Lollipop中引入的工具条Toolbar相交互，并能够帮助实现Material Design apps的外观。
* [iconify](https://github.com/JoanZapata/android-iconify) - iconify 图片与文字同一行显示。
* [iosched](https://github.com/google/iosched) - The Google I/O 2014 Android App，Android 5.0 and Material Design。
* [MaterialList](https://github.com/dexafree/MaterialList) - MaterialList 。
* [material design card](https://dribbble.com/search?q=material+design+card) - material design card 。 
* [InstaMaterial](https://github.com/frogermcs/InstaMaterial) - InstalMaterial 项目(非常多的UI样式：ViewAnimator、RecyclerView、拍照)， [InstalMaterial学习笔记之Reveal效果](http://www.jianshu.com/p/35492fb2c269)。  
* [NavigationDrawer-MaterialDesign](https://github.com/rudsonlive/NavigationDrawer-MaterialDesign) - 一个Material Design的抽屉模板库，分分钟搭起一个程序框架。
* [MaterialEditText](https://github.com/rengwuxian/MaterialEditText) - 直接继承EditText，无需修改Java文件即能实现自定义控件颜色， [直接拿来用！十大Material Design开源项目](http://www.csdn.net/article/2014-11-21/2822753-material-design-libs)。
* [fab](https://github.com/shell-software/fab) - Floating Action Button library for Android。
* [labelview](https://github.com/linger1216/labelview) - 贴纸效果，如：淘宝商品侧贴折扣。
* [SearchMenuAnim](https://github.com/kongnanlive/SearchMenuAnim) - 一个很棒的带动画的搜索框。
* [SearchAnimation](https://github.com/NiaNingXue/SearchAnimation) - 一个很棒的带动画的搜索框，支持低版本。
* [快速支持emoji表情显示](http://www.eoeandroid.com/thread-567299-1-1.html) - 让项目快速支持emojicon表情的显示，并可判断用户输入的内容中是否含有emojicon表情以及过滤掉emojicon。
* [Context-Menu.Android](https://github.com/Yalantis/Context-Menu.Android) - 可以方便快速集成漂亮带有动画效果的上下文菜单。
* [Pull-to-Refresh.Rentals-Android](https://github.com/Yalantis/Pull-to-Refresh.Rentals-Android) - 提供一个简单可以自定义的下拉刷新实现。
* [Pull-to-Refresh.Tours](https://github.com/Yalantis/Taurus) - Taurus，很精美的下拉刷新。
* [Titanic](https://github.com/RomainPiel/Titanic) - 可以显示水位上升下降的TextView。
* [AndroidSwipeLayout](https://github.com/daimajia/AndroidSwipeLayout) - 滑动Layout，支持单个View，ListView，GridView，[demo-apk](https://github.com/daimajia/AndroidSwipeLayout/releases/download/v1.0.0/AndroidSwipeLayout-Demo-1.0.1-snapshot.apk)。
* [android-typeface-helper](https://github.com/norbsoft/android-typeface-helper) - Android Typeface Helper 可以帮你轻松实现自定义字体的库。
* [android-lockpattern](https://code.google.com/p/android-lockpattern/) - Android的图案密码解锁, [文档介绍](https://code.google.com/p/android-lockpattern/wiki/QuickUse)。
* [ToggleButton](https://github.com/zcweng/ToggleButton) - 状态切换的 Button，类似 iOS，用 View 实现。
* [android-typeface-helper](https://github.com/norbsoft/android-typeface-helper) - Android Typeface Helper 可以帮你轻松实现自定义字体的库。
* [GuideBackgroundColorAnimation](https://github.com/TaurusXi/GuideBackgroundColorAnimation) - 实现滑动ViewPager渐变背景色。
* [Toolbar](https://github.com/xamarin/monodroid-samples/tree/master/android_l/Toolbar) - Toolbar替换Android Toolbar，[说明](http://blog.xamarin.com/android-tips-hello-toolbar-goodbye-action-bar/)。
* [PagerSlidingTabStrip](https://github.com/jpardogo/PagerSlidingTabStrip) - 一个支持Material Design的PagerSlidingTabStrip。
* [MaterialViewPager](https://github.com/florent37/MaterialViewPager) - 一个易于使用的 Material Design ViewPager 库。
* [PinnedListView](http://www.eoeandroid.com/thread-567853-1-1.html) - PinnedListView悬浮Head效果修改，[github pinned-section-listview](https://github.com/beworker/pinned-section-listview)。
* [APP启动引导页](http://www.eoeandroid.com/thread-564018-1-1.html) - APP应用中最常用的APP启动引导页，常见的4种引导项目方式：splash，viewpage，viewflipper，scrollview。
* [AwesomeText](https://github.com/JMPergar/AwesomeText) - 简化TextViews中Spans使用的库。 
* [dialogplus](https://github.com/orhanobut/dialogplus) - 一个简单容易使用的对话框——DialogPlus。 
* [material-dialogs](https://github.com/afollestad/material-dialogs) - Material Design风格Dialogs。 
* [CardView](https://github.com/chiemy/CardView) - 3d卡片效果-国人。
* [FilterMenu](https://github.com/linroid/FilterMenu) - 这是一个自定义的圆形菜单，效果非常酷。
* [GridPasswordView](https://github.com/Jungerr/GridPasswordView) - 类似微信，支付宝支付时候的输入密码页面效果，带格子的密码输入框。
* [PersistentSearch](https://github.com/Quinny898/PersistentSearch) - 模仿Google Now, Google Maps Google Play的SearchBar，下拉列表匹配、录音。
* [Droppy](https://github.com/shehabic/Droppy) - Android 下简洁好看的 Dropdown 菜单。
* [UltimateRecyclerView](https://github.com/cymcsg/UltimateRecyclerView) - 这是一个终极的 RecyclerView，有下拉刷新、滑动删除、拖拽、加载更多、丰富动画等功能。
* [SmartTabLayout](https://github.com/ogaclejapan/SmartTabLayout) - SmartTabLayout实现viewpgaer页面导航效果，简化并实现android的TabHost效果，顶部滑动tab，引导页，可以自定义tab样式，过渡效果 实现网易tab，微博tab，微信tab等so easy。 集成了SpringIndicator拖拽效果 。
* [richeditor](https://github.com/wasabeef/richeditor-android) - RichEditor for Android 是 Android 平台下一个所见即所得的文本编辑器控件。

* [StatedFragment](https://github.com/nuuneoi/StatedFragment) - 保存Fragment的状态。
* [PopoverView](https://github.com/lupidan/PopoverView) - 一个模仿iOS UIPopoverController效果的控件。
* [CreditsRoll](https://github.com/frakbot/CreditsRoll) - 实现星球大战字幕效果。
* [MatchView](https://github.com/Rogero0o/MatchView) - 电影级TextView动画效果，绝对惊艳你的双眼！。
* [SwipeMenuListView](https://github.com/baoyongzhang/SwipeMenuListView) - listView侧滑删除效果：SwipeMenuListView。
* [Side-Menu.Android](https://github.com/Yalantis/Side-Menu.Android) - 分类侧滑菜单。
* [SlidingMenu](https://github.com/xudafeng/SlidingMenu) - 炫酷侧滑菜单布局框架，iOS版本的实现：[SlideMenuView](https://github.com/xudafeng/SlideMenuView)。
* [ParallaxSwipeBack](https://github.com/bushijie/ParallaxSwipeBack) - 带视觉差的侧滑返回，类似于新版微信和lofter的侧滑返回效果。核心代码小于50行。
* [AndroidFlowLayout](https://github.com/LyndonChin/AndroidFlowLayout) - A flow layout for Android。
* [ViewPagerIndicator](https://github.com/LuckyJayce/ViewPagerIndicator) - 取代TabHost，实现滑动tab，引导页等效果。
* [Android-ScreenSlidePager](https://github.com/LyndonChin/Android-ScreenSlidePager) - Full screen slide pager to display images fetched from Internet by Picasso。
* [MaterialViewPager](https://github.com/florent37/MaterialViewPager) - MaterialViewPager。
* [FlipViewPager.Draco](https://github.com/Yalantis/FlipViewPager.Draco) - FlipViewPager.Draco。
* [android-shape-imageview](https://github.com/siyamed/android-shape-imageview) - 图片圆角、三角、五角、圆形、多角。
* [NotBoringActionBar](https://github.com/flavienlaurent/NotBoringActionBar) - 隐藏图片的导航栏。
* [MultiCardMenu](https://github.com/wujingchao/MultiCardMenu) - 仿QQ手机管家首页菜单写的一个开源组件MultiCardMenu。
* [fit-chart](https://github.com/txusballesteros/fit-chart) - fit-chart 一个类似于谷歌健康应用的轮子（wheel view）视图，效果很不错。
* [BGABadgeView-Android](https://github.com/bingoogolapple/BGABadgeView-Android) - Badge控件分享，各式各样的徽章控件。
* [Android-ItemTouchHelper-Demo](https://github.com/iPaulPro/Android-ItemTouchHelper-Demo) - 可拖拽 RecyclerView, [讲解](http://www.devtf.cn/?p=795)。
* [浮动操作按钮详解](http://www.jcodecraeer.com/a/anzhuokaifa/androidkaifa/2015/0718/3197.html) - 讲解浮动操作按钮，从官方的和第三方库[makovkastar/FloatingActionButton](https://github.com/futuresimple/android-floating-action-button) 和 [futuresimple/android-floating-action-button](https://github.com/makovkastar/FloatingActionButton) 这样的第三方库。的两方面讲解，同时还讲到了如何自定义CoordinatorLayout Behavior。
* [advanced-textview](https://github.com/chiuki/advanced-textview) -  advanced-textview各种高级功能的textview，包括动画，阴影，各种字体，艺术字，HTML格式显示，表情等。
* [QuickReturn](https://github.com/lawloretienne/QuickReturn) - 给几乎所有可以滑动的 View 加上快速返回的 Header 或者 Footer，使用非常方便。
* [Android-PickerView](https://github.com/saiwu-bigkoo/Android-PickerView) - 仿iOS的PickerView控件，有时间选择和选项选择并支持一二三级联动效果。
* [DraggedViewPager](https://github.com/yueban/DraggedViewPager) - 可以在多个 Page 之间可以拖放元素的控件。
* [MultiViewPager](https://github.com/Pixplicity/MultiViewPager) - 对 ViewPager 的一个扩展，Page 可宽可窄，表现很像 Gallelry。
* [Android-Week-View](https://github.com/alamkanak/Android-Week-View) - Android Week View是一种用于应用程序中显示日历的安卓库。它支持自定义样式。。

##### 卫星菜单
* [android-satellite-menu](https://github.com/siyamed/android-satellite-menu) - 点击主按钮，会弹出多个围绕着主按钮排列的子按钮，从而形成一个弹出式菜单。子按钮弹出和消失的动画效果都很棒。这种弹出式菜单按钮应用在Path app中。
* [ArcMenu](https://github.com/daCapricorn/ArcMenu) - 实现弹出式按钮群（菜单）。点击主按钮，会在住按钮旁边弹出多个按钮（菜单）。弹出的按钮有两种排列形式，一种是围绕着主按钮成圆弧形排列，一种是和主按钮并排成一字型排列， 仿Path 2.0 (for iOS)。
* [Radial Menu Widget](http://d.apkbus.com/android/Radial-Menu-Widget/52405aca6803fa2822000002) - 实现各种圆形或者半圆形菜单，以及圆形进度条。
* [android-circlebutton](https://github.com/markushi/android-circlebutton) - 圆形按钮，有动画点击效果。 
* [CircularFloatingActionMenu](https://github.com/oguzbilgener/CircularFloatingActionMenu) - 卫星菜单。
* [ElasticDownload](https://github.com/Tibolte/ElasticDownload) -  挺酷的下载进度条。

##### 节选器
* [SegmentView](https://github.com/bboyfeiyu/SegmentView) - 类似iOS的Segment Control控件，第一种方式是使用 RadioGroup 实现，O网页链接。
* [SHSegmentControl](https://github.com/7heaven/SHSegmentControl) - 类似iOS的Segment Control控件，此种方式的可定制化更好。
* [android-segmentedradiobutton](https://github.com/vinc3m1/android-segmentedradiobutton) - 在Android中实现类似iOS的分段单选按钮（segmented control），本人以前项目一直使用，值得拥有。
* [android-segmented-control](https://github.com/hoang8f/android-segmented-control) - RadioGroup实现类似ios的分段选择(UISegmentedControl)控件。


##### 下拉刷新
* [Android-PullToRefresh](https://github.com/chrisbanes/Android-PullToRefresh) - 最经典、最多人用的下拉刷新、加载更多。
* [PullDownListView](https://github.com/guojunyi/PullDownListView) - 一个下拉刷新的控件，实现了仿微信下拉中眼睛动画的效果。
* [DragTopLayout](https://github.com/chenupt/DragTopLayout) - 实现整个layout下拉刷新。
* [ZrcListView](https://github.com/zarics/ZrcListView) - 一个顺滑又漂亮的Android下拉刷新与加载更多列表组件，增加下拉刷新及滚动到底部自动加载的功能；增加越界回弹效果；增加自定义列表项动画的功能。
* [TwitterCover-Android](https://github.com/cyndibaby905/TwitterCover-Android) - Twitter Android客户端的下拉封面模糊效果。
* [android-Ultra-Pull-To-Refresh](https://github.com/liaohuqiu/android-Ultra-Pull-To-Refresh) - 实现整个layout下拉刷新，没有加载更过，[Demo](https://github.com/android-cn/android-open-project-demo/tree/master/android-ultra-pull-to-refresh-demo)， [源码分析](http://codekk.com/open-source-project-analysis/detail/Android/Grumoon/android-Ultra-Pull-To-Refresh%20%E6%BA%90%E7%A0%81%E8%A7%A3%E6%9E%90)。
* [StikkyHeader](https://github.com/carlonzo/StikkyHeader) - 【Android控件源码：头部固定的控件列表效果】这是一个可以支持头部固定的控件列表功能，源码StikkyHeader，StikkyHeader是一个可以在滚动的时候将头部固定的控件，还可以将动画效果和StikkyHeader一起使用，api非常简单， 支持ListView,RecyclerView,ScrollView。[支持2.3一下设备使用的StikkyHeader](https://github.com/yangwuan55/StikkyHeader)
* [PullDownListView](https://github.com/guojunyi/PullDownListView) - 实现了模仿微信眼睛下拉效果，源码PullDownListView，下拉刷新，上拉加载，模仿微信眼睛。 
* [CircleRefreshLayout](https://github.com/tuesda/CircleRefreshLayout) - 又一个下拉刷新的实现，水滴效果。
* [BGARefreshLayout-Android](https://github.com/bingoogolapple/BGARefreshLayout-Android) - 多种下拉刷新效果、上拉加载更多、可配置自定义头部广告位。

##### 模糊效果
* [BlurNavigationDrawer](https://github.com/charbgr/BlurNavigationDrawer) - 背景模糊的Navigation Drawer。
* [Android Wheel](https://code.google.com/p/android-wheel/) - 带有刻度的旋转器：日历、三级联动

##### HUD与Toast

##### 进度条
* [easyloadingbtn](https://github.com/DevinShine/easyloadingbtn) - 模仿了一个Dribbble上的Material Design效果，环形loading， 进度条、进度圈。
* [android-square-progressbar](https://github.com/mrwonderman/android-square-progressbar) - 一个不错的方形进度条。
* [Radial Menu Widget](http://d.apkbus.com/android/Radial-Menu-Widget/52405aca6803fa2822000002) - 实现各种圆形或者半圆形菜单，以及圆形进度条。
* [AnimatedCircleLoadingView](https://github.com/jlmd/AnimatedCircleLoadingView) - 一个有限／无限加载动画效果。基于Nils Banner的android-watch-loading-animation设计图。该设计本来是针对智能手表的。
* [circular-progress-button](https://github.com/dmytrodanylyk/circular-progress-button) - 带动态效果的Button(按钮)可要比静态的按钮炫酷的多了，大家看到效果图就知道了。
* [CircularBarPager](https://github.com/OrangeGangsters/CircularBarPager) - Android实现的动态效果，一个数字圆圈进度效果，源码CircularBarPager，material 风格的数字圆圈进度显示库（api10 +）。

========
#### 动画
* [SwitchLayout](http://blog.csdn.net/jay100500/article/details/42227365) - 国内开发者， Android的Activity切换动画特效库SwitchLayout，视图切换动画库，媲美IOS。 
* [ActivityOptionsICS](https://github.com/tianzhijiexian/ActivityOptionsICS) - 一个低版本activity动画兼容库——ActivityOptionsICS，可以很好的实现MD的动画效果。
* [SwipeBack](https://github.com/liuguangqiang/SwipeBack) - 一个可以通过手势返回到上一个Activity的开源库，支持上下左右四个方向返回，支持多个View为Child。
* [SpringIndicator](https://github.com/chenupt/SpringIndicator) - 模仿Morning Routine的引导页效果SpringIndicator；基于模仿红点拖拽的Demo实现：[BezierDemo](https://github.com/chenupt/BezierDemo)；sample中使用到 快速创建ViewPager和ListView等的第三方库：[MultipleModel](https://github.com/chenupt/MultipleModel)。
* [XhsWelcomeAnim](https://github.com/w446108264/XhsWelcomeAnim) - 国内开发者， 华丽酷炫欢迎引导界面 动画没有之一。 
* [Material-Animations](https://github.com/lgvalle/Material-Animations) - Material风格动画，可以定义两个Activity之间的动画。
* [android-shapeLoadingView](https://github.com/zzz40500/android-shapeLoadingView) - android-shapeLoadingView实现高仿新版58 加载动画，loading。
* [动画特效大全](http://www.eoeandroid.com/thread-562739-1-1.html) - Android 动画特效大全。
* [一个绚丽的loading](http://blog.csdn.net/tianjian4592/article/details/44538605) - 一个绚丽的loading动效分析与实现。

========
#### 网络相关
##### 网络连接
* [ion](https://github.com/koush/ion) - 一个异步网络请求和图片加载的库，一个库能搞定几乎所有的网络请求。
* [多线程下载](http://www.eoeandroid.com/thread-564501-1-1.html) - Android 实现多线程下载 完美代码。
* [opandroid](https://github.com/openpeer/opandroid) - android p2p的开源实现。
* [okio](https://github.com/square/okio) - square出的Okio这个库，尤其擅长处理二进制数据。如果觉得Java的输入输出流实在太复杂啰嗦，不妨试试Okio。
* [Android-Download-Manager-Pro](https://github.com/majidgolshadi/Android-Download-Manager-Pro) - 一个下载管理库，如果你的 App 有大量的下载工作，这个库能帮到你。

========
##### 网络测试
* [augmented-traffic-control](https://github.com/facebook/augmented-traffic-control) - Facebook宣布开源移动网络测试工具ATC，该工具支持利用Wi-Fi网络模拟2G、2.5G、3G以及LTE 4G移动网络环境，让测试工程师们能够快速对智能手机和App在不同国家地区和应用环境下的性能表现进行测试。

========
##### 图像获取
* [glide](https://github.com/bumptech/glide) - glide 。
* [Universal Image Loader](https://github.com/nostra13/Android-Universal-Image-Loader) - Universal Image Loader 是一个强大的、可高度定制的图片缓存，简称：UIL，可以高度配置的网络图片缓存库，非常灵活，用户量最多 。
* [picasso](https://github.com/square/picasso) - picasso 功能单一，没有缓存过期，同androidQuery一样链式调用，载入本地文件速度慢（没有生成thumbnails） ,[Picasso and Android-Universal-Image-Loader](http://donal-tong.github.io/blog/2014/05/21/picasso-and-auil/),另外的一些诸如裁剪图片：Picasso.with(context)  .load(url)  .resize(50, 50)  .centerCrop()  .into(imageView)。
* [fresco](https://github.com/facebook/fresco) - Facebook 又放出的一个新项目，一个类似 Picasso, Glide 的库，不过比他们做的更好。 强烈推荐！
* [tape](http://square.github.io/tape/) - 类似于图片加载库（例如UIL、Picasso等）实现异步加载，但是加载的不一定是图片。！
* [ImageLoader](https://github.com/novoda/ImageLoader) - ImageLoader 。
* [Volley](https://github.com/mcxiaoke/android-volley) - Volley 综合框架,包含图片部分。
* [enif](code.google.com/p/enif/) - enif 。
* [wqgallery](https://github.com/wqandroid/wqgallery) - wqgallery实现类似微信选择照片功能，可以通过相机或相册选择，支持单张裁剪，支持单选模式、支持多选模式。

#### 响应式编程
* [RxAndroid](https://github.com/ReactiveX/RxAndroid/) - RxAndroid：函数响应式编程 。



========
#### 地图
* [百度地图](http://www.eoeandroid.com/thread-568507-1-1.html) - Android百度地图 线路规划，模拟运动轨迹，及全景效果。
* [AirMapView](https://github.com/airbnb/AirMapView) - 支持多个本地地图提供者包括谷歌地图V2和亚马逊地图V2。如果设备没有任何受支持的本地地图提供者,AirMapView会回退到基于web的地图提供者(目前谷歌地图)。

========
#### 数据库
* [ORMLite](http://ormlite.com/sqlite_java_android_orm.shtml) - ORMLite做的最棒但是学习成本有点儿高，ORMLite的文档有点儿烂。
* [SugarORM](http://satyan.github.io/sugar/index.html) - SugarORM比较轻便， 支持Has a 和 Has many映射，但无法保存集合，没有映射关系。
* [GreenDAO](http://greendao-orm.com/) - GreenDAO要先建立一个java项目来生成对应的表，一变动又要生成，很不方便。
* [ActiveDriod](https://github.com/pardom/ActiveAndroid) - ActiveDriod也不错 [官网](http://www.activeandroid.com/)。
* [ORMDroid](https://github.com/roscopeco/ormdroid) - ormdroid 。
* [sqlbrite](https://github.com/square/sqlbrite) - 良心企业Square的又一开源项目，当你不想给用ContentProvider，只想简单监听SQLite表增删改的数据变更时可以试试它。
* [sqlbrite](https://github.com/LuckyJayce/DBExecutor) - DBExecutor android ORM数据库 1.使用了读写锁，支持多线程操作数据。 2.支持操作多个数据库 3.支持事务 4.缓存Sql，缓存表结构。

========
#### 图像浏览及处理
* [MPAndroidChart](https://github.com/ggchxx/MPAndroidChart) - MPAndroidChart是一个功能强大的图表开源类库：曲线图、柱形图、环形图。
* [XCL-Charts](https://github.com/xcltapestry/XCL-Charts) - (国人开发)基于Android Canvas来绘制各种图表,使用简便,定制灵活。
* [WilliamChart](https://github.com/diogobernardino/WilliamChart) - 绘制图表的库，支持LineChartView、BarChartView和StackBarChartView三中图表类型，并且支持 Android 2.2及以上的系统。
* [CropImageView](https://github.com/cesards/CropImageView) - 原生ImageView只支持centerCrop，这里有支持9个方向裁剪的ImageView。
* [DrawableView](https://github.com/PaNaVTEC/DrawableView) - DrawableView实现画板功能，可以改变画笔粗细，颜色，支持撤销功能。
* [ImageCoverFlow](https://github.com/dolphinwang/ImageCoverFlow) - ImageCoverFlow效果不错的画廊控件 可以设置画廊一次可见图片的张数，和其他第三方Gallery控件不同的是，该控件直接继承自View，而不是sdk中的Gallery控件。
* [FancyCoverFlow](https://github.com/davidschreiber/FancyCoverFlow) - 支持Item切换动画效果的类似Gallery View。[改进版本](https://github.com/LittleLiByte/GlFancyCoverFlow)可以无限轮播，可以选择自动轮播或者 手动滑动。
* [BGABanner-Android](https://github.com/bingoogolapple/BGABanner-Android) - demo中演示了引导页、以及通过fresco、android-async-http、gson实现广告条的自动轮播效果（splash 、 ViewPager切换动画） 。
* [RecyclerViewPager](https://github.com/lsjwzh/RecyclerViewPager) - 重写后的 RecyclerViewPager 完全继承自RecyclerView，可以自定义触发翻页的距离，可自定义翻页速度，支持VerticalViewPager，支持Fragment。
* [StickerCamera](https://github.com/Skykai521/StickerCamera) - 可以说是一个完整的相机、图片编辑的 APP，集成了大部分市面上有的同类 APP 的功能，裁剪、滤镜、贴纸应有尽有。
* [demo6_PhotoRiver](https://github.com/debolee/demo6_PhotoRiver) - 图片流动显示的demo，可以点击流动中的图片放大显示，双击空白处图片以九宫格排列。

========
#### 视频音频处理
* [ijkplayer](https://github.com/Bilibili/ijkplayer) - B站开源的视频播放器，支持Android和iOS。
* [DanmakuFlameMaster](https://github.com/Bilibili/DanmakuFlameMaster) - 这里是Android上最好的开源弹幕引擎·烈焰弹幕使。

========
#### 测试及调试
* [DevelopQuickSetting](https://github.com/kyze8439690/DevelopQuickSetting) - 快速开启关闭开发者设置的工具，提供了app界面和桌面widget，能快速打开关闭overdraw，layout border，gpu rendering，adb wifi，不保存activity实例等功能。
* [decompileandroid](http://www.decompileandroid.com/) - 在线反编译apk文件。
* [jadx](https://github.com/skylot/jadx) - 一个Android反编译神器，不同于常见的dex2jar，这个反编译器生成代码的try/catch次数更少，View也不再是数字id了，可读性更高。
* [Androguard](https://github.com/androguard/androguard) - Androguard使用Python写的一系列逆向工具集，功能很强大哦，对逆向工程感兴趣的小伙伴可以这个系列，[教程](http://www.technotalkative.com/part-1-reverse-engineering-using-androguard/)。
* [logger](https://github.com/orhanobut/logger) - 一个简单、漂亮、功能强大的Android日志程序。
* [stf](https://github.com/openstf/stf) - WEB 端批量移动设备管理控制工具 STF 的环境搭建和运行，[使用说明](https://testerhome.com/topics/2988) 。

========
#### 消息推送
##### 客户端

##### 服务器端

========
#### 完整项目
* [SuesNews新闻客户端](https://github.com/sues-lee/SuesNews) - 腾飞新闻，一个符合 Google Material Design 的 Android 校园新闻客户端 ，[新闻客户端说明](http://www.eoeandroid.com/thread-569074-1-1.html) 。
* [新闻客户端](http://bbs.aiyingli.com/forum.php?mod=viewthread&tid=12170) - Android应用源码比较不错的新闻客户端，本项目启动引导登录注册用户中心列表显示文章分页下拉刷新文章收藏更新反馈等新闻客户端常见的功能都有，项目分层合理，代码质量较高。  
* [materialistic](https://github.com/hidroh/materialistic) - Material Desgin风格的Hacker News客户端。
* [Telegram](https://github.com/DrKLO/Telegram) - Telegram 是一款专注于速度、安全的短信息应用，快速、简单、免费。Telegram 支持群组聊天，最高200人，最高支持分享1GB的视频，其它图片等等更是不在话下。而且所有信息全部支持同步。由于频发的隐私问题，所以 Telegram 也很注重通信安全。
* [SuZhouTong-client-for-android](https://github.com/liuch930/SuZhouTong-client-for-android) - 苏州通android客户端，非常多的UI效果。
* [ele_demo](https://github.com/guxun12/ele_demo) - 仿【饿了么】订餐软件的一个demo。
* [MD-BiliBili](https://github.com/Qixingchen/MD-BiliBili) - Material Design 版 BiliBili Android 客户端。
* [AisenWeiBo](https://github.com/wangdan/AisenWeiBo) - Aisen微博是新浪微博的第三方客户端，UI遵循Material Design：遵循Material Design、发布多图、离线下载、私信（触屏版、颜色主题切换、手势返回，4.4、5.0状态栏变色、离线编辑，定时发布
多图、gif、长微博预览。[FrescoDemo](https://github.com/06peng/FrescoDemo) 。
* [快递查询](http://bbs.aiyingli.com/forum.php?mod=viewthread&tid=12274) -  使用了爱查快递[www.ickd.cn](http://www.ickd.cn/)的api接口，可以查询申通、EMS、顺风、圆通、中通、韵达、天天、汇通、全锋、德邦、宅急送等11种快递的单号信息，支持手动输入单号和扫描单号(红米测试的时候扫描单号有点问题)，可以保存单号查询记录方便下次查询，，另外还包括了网络状态判断、快递自动更新、软件更新等功能，项目完美运行，有很详细的中文注释和逻辑分层。
* [SmartCall](http://git.oschina.net/yso/SmartCall) - SmartCall Android 企业通讯录。
* [Android-高仿大众点评客户端源码](http://download.jikexueyuan.com/detail/id/539.html#0-tsina-1-72241-397232819ff9a47a7b7e80a40613cfe1) - Android-高仿大众点评客户端源码。

========
### 插件
* [Android Studio 插件和工具](http://stormzhang.com/android/2015/05/26/android-tools/) -  5个  推荐几个有用的 Android Studio 插件和工具（ButterKnife、selectorChapek、GsonFormat、ParcelableGenerator、LeakCanary）。
* [ 8 个最优秀的 Android Studio 插件](http://www.imooc.com/article/1148) -  8 个最优秀的 Android Studio 插件（H.A.X.M（硬件加速执行管理器）、Genymotion、Android Drawable Importer、Android ButterKnife Zelezny、Android Holo Colors Generator、Robotium Recorder、jimu Mirror、Strings-xml-tools）。
* [smalidea](https://github.com/JesusFreke/smali/wiki/smalidea) - 一款 IntelliJ IDEA/Android Studio 的 smali 插件～ ，[Smalidea 无源码调试 Android 应用](http://drops.wooyun.org/tips/7181)。

========
### 出名框架
* [xUtils](https://github.com/wyouflf/xUtils) - xUtils 包含了很多实用的android工具。支持大文件上传，更全面的http请求协议支持(10种谓词)，拥有更加灵活的ORM，更多的事件注解支持且不受混淆影响。最低兼容android 2.2 (api level 8)。目前xUtils主要有四大模块：DbUtils模块、ViewUtils模块、HttpUtils模块、BitmapUtils模块。
* [afinal](http://git.oschina.net/fuhai/afinal) - Afinal是一个android的ioc，orm框架，内置了四大模块功能：FinalAcitivity,FinalBitmap,FinalDb,FinalHttp。 
* [EventBus](https://github.com/greenrobot/EventBus) - EventBus是一款针对Android优化的发布/订阅事件总线。主要功能是替代Intent,Handler,BroadCast在Fragment，Activity，Service，线程之间传递消息.优点是开销小，代码更优雅。以及将发送者和接收者解耦。
* [dexposed](https://github.com/alibaba/dexposed) - 支付宝的Android底层技术团队即将为Dexposed开源项目贡献一个重要的扩展能力 —— 方法粒度的完整替换，大幅度降低基于AOP方式替换大型方法的开发成本，[使用教程](http://www.apkbus.com/android-244457-1-1.html)。

========
#### 其他
* [java-zhconverter](http://code.google.com/p/java-zhconverter/) - java-zhconverter是一个简繁体中文互换的Java开源类库。
* [joda-time-android](https://github.com/dlew/joda-time-android) - 一个超赞的时间处理的库，Joda-Time ！ 他能帮你轻松处理时区，处理时间加减，计算到期时间等等场景下的问题。[java版本](http://www.joda.org/joda-time/key_partial.html)
* [AssistiveTouch](https://github.com/luozi/AssistiveTouch) - 配合Android手机沉浸式隐藏虚拟按键后快捷操作 (Nexus5屏幕变大了)。
* [S-Tools](https://github.com/naman14/S-Tools) - S-Tools一个可以实时查看的CPU状态和手机各类传感器数据，还有一些例如颜色选择、指南针和设备信息等功能。
* [JsBridge](https://github.com/lzyzsd/JsBridge) - 模仿微信webview的JsBridge，安全方便的实现js和Java的互相调用，主要通过loadUrl和shouldOverrideUrl实现。
* [Sample Of All Samples](https://github.com/MostafaGazar/soas) - 提供大部分Android5.0组件的示例应用。
* [Android-Package-Channel](https://github.com/s1rius/Android-Package-Channel) - 美团网做的把Android多渠道打包工具，打包时间缩短到一分钟，python脚本。
* [fast-apk-packaging](http://www.race604.com/fast-apk-packaging/) - Android不需要重新编译打渠道包。
* [android_gradle_script](https://github.com/lihei12345/android_gradle_script) - gradle批量打包脚本，用txt配置一下，就可以支持多个渠道打包，适合国内这种动不动上百个渠道包的环境。目前有个问题，一次打包脚本超过80个就会GC问题。
* [Gradle-Plugin-User-Guide-Chinese-Verision](http://avatarqing.github.io/Gradle-Plugin-User-Guide-Chinese-Verision/) - Gradle插件使用指南中文版。
* [Android-package_tool](https://github.com/ahui2823/package_tool) - 该工程用于编译多渠道Android应用，替换相应的标签，然后重新打包，用perl脚本实现。
* [兰贝壳儿](http://www.orchidshell.com/) - Android多渠道打包解决方案(兰贝壳儿)，eclipse插件。 
* [Algorithms](https://github.com/pedrovgs/Algorithms) - 常见算法问题的Java实现。
* [java-design-patterns](https://github.com/iluwatar/java-design-patterns) - 一个常见设计模式的java实现。
* [PreferenceInjector](https://github.com/denley/PreferenceInjector) - SharedPreference注入开源库，SharedPreference key与某个变量绑定、监听key变化、初始化key都可以通过注解完成。
* [prettytime](http://www.ocpsoft.org/prettytime/) - 一个实用的人性化的时间显示，比如：几分钟前，几天前。
* [Material-Movies](https://github.com/saulmm/Material-Movies) - Material Design 下的Movie App（电影展示），可供学习，或者直接二次开发。
* [Clean-Contacts](https://github.com/PaNaVTEC/Clean-Contacts) - 充满技术含量的一个 Contact App（联系人）。
* [RedEnvelopeAssistant](https://github.com/waylife/RedEnvelopeAssistant) - 完全免费开源的抢红包软件、做这个软件纯粹是发现Android的模拟点击十分好玩，然后顺道写了一个，有此基础，可以再扩展其他的很多模拟点击程序 。
* [superCleanMaster](https://github.com/joyoyao/superCleanMaster) -  一键清理开源版，包括内存加速，缓存清理，自启管理，软件管理等。
* [LoadViewHelper](https://github.com/LuckyJayce/LoadViewHelper) - 切换加载中，加载失败，加载成功布局，定义一个LoadViewHelper所有界面通用。
* [android-best-practices](https://github.com/futurice/android-best-practices) - android最佳实践
* [Android最佳实践](http://android.jobbole.com/80684/) - 安卓最佳实践（1）：安卓开发--中文。
* [Android最佳实践](https://github.com/futurice/android-best-practices/blob/master/translations/Chinese/README.cn.md) - 从Futurice公司Android开发者中学到的经验。 遵循以下准则，避免重复发明轮子。若您对开发iOS或Windows Phone 有兴趣， 请看iOS Good Practices 和 Windows client Good Practices 这两篇文章。 
* [如何安装ACRA](http://blog.csdn.net/chen52671/article/details/44751347) - 如何安装ACRA-一个Android应用Crash跟踪系统—在自己的服务器上。 
* [Android ocr识别文字介绍](http://blog.csdn.net/love_xsq/article/details/44616925) - Android ocr识别文字介绍 。 
* [DaVinci](https://github.com/florent37/DaVinci) - DaVinci是一个适用于Android Wear平台的图片下载和缓存library。
* [Point-of-Android](https://github.com/FX-Max/Point-of-Android) - Android 一些重要知识点解析整理 。
* [AppStoreLibrary](https://github.com/mcsong/AppStoreLibrary) - 检测是否在appstore安装了应用，搜索应用。
* [LeakCanary](https://github.com/liaohuqiu/leakcanary-demo) - 利用此类库，排查内存泄露变得非常简单，[LeakCanary 中文使用说明](http://www.liaohuqiu.net/cn/posts/leak-canary-read-me/)，[LeakCanary: 让内存泄露无所遁形](http://www.liaohuqiu.net/cn/posts/leak-canary/) 。
* [anko](https://github.com/JetBrains/anko) - 快速开发框架。
* [CommonAdapter](https://github.com/tianzhijiexian/CommonAdapter) - 通过对于原生Adapter的封装，产生了支持ListView，GridView，RecyclerView的简单通用的Adapter。这种方式将item变成独立的“视图”对象，方便操作，又增加了可扩展性。
* [MVPAndroidBootstrap](https://github.com/richardradics/MVPAndroidBootstrap) - 一个Android MVP 模式实例项目。
* [json2notification](https://github.com/8tory/json2notification) - 一个多功能方便好用的notification通知栏通知开源库。

========
#### 好的文章
* [高效抽取loading](http://www.apkbus.com/android-244454-1-1.html) - 高效抽取loading，再多的加载页面也不怕。
* [修复bug的12个关键步骤](http://www.imooc.com/wenda/detail/209282) - 修复bug的12个关键步骤。
* [Android开发技术前线](https://github.com/bboyfeiyu/android-tech-frontier) - 里面是安卓的一些外国前沿文章的翻译，想课余时间学习 Android 的看看，已经收录了。

========
### 收集android上开源的酷炫的交互动画和视觉效果
* [酷炫的交互动画和视觉效果](https://github.com/Rano1/Interactive-animation/blob/master/README.md) - 描述：收集android上开源的酷炫的交互动画和视觉效果。1.交互篇，2.视觉篇。
* [Android酷炫实用的开源框架（UI框架）](http://www.androidchina.net/1992.html) - Android酷炫实用的开源框架（UI框架）25个。 


交互篇
------
1.SlidingUpPanelLayout
项目介绍：他的库提供了一种简单的方式来添加一个可拖动滑动面板(由谷歌音乐推广,谷歌地图和Rdio)你的Android应用程序。
项目地址：https://github.com/umano/AndroidSlidingUpPanel  

2.FoldableLayout
项目介绍：折叠展开点击的ITEM
项目地址：https://github.com/alexvasilkov/FoldableLayout 

3.android-flip
项目介绍：折叠翻页效果
项目地址：https://github.com/openaphid/android-flip

4.SwipeBackLayout
项目介绍：拖动关闭当前活动窗体
项目地址：https://github.com/Issacw0ng/SwipeBackLayout

5.AndroidImageSlider
项目介绍：一个漂亮的Slider，可以通过自定义达到更好的效果
项目地址：https://github.com/daimajia/AndroidImageSlider

6.Android-ParallaxHeaderViewPager
项目介绍：栏目展示动画，自动播放，滚动下方列表时候，收缩效果
项目地址：https://github.com/kmshack/Android-ParallaxHeaderViewPager

7.FragmentTransactionExtended
项目介绍：
项目地址：https://github.com/DesarrolloAntonio/FragmentTransactionExtended

8.FragmentTransactionExtended
项目介绍：Android按钮可以化身进度
项目地址：https://github.com/dmytrodanylyk/circular-progress-button

9.floatlabelededittext
项目介绍：简单的实现浮动标签EditText:Android视图使用EditText之上,并提示EditText时填充文本。
项目地址：https://github.com/wrapp/floatlabelededittext

10.QuickReturn
项目介绍：Showcases QuickReturn view as a header, footer, and both header and footer. 给几乎所有可以滑动的 View 加上快速返回的 Header 或者 Footer，使用非常方便。
项目地址：https://github.com/lawloretienne/QuickReturn

11.VNTNumberPickerPreference
项目介绍：这是一个易于使用的自定义偏好,打开一个对话框中有许多选择。的值被自动保存,你可以设置默认,min -和maxValue方便地在XML。
项目地址：https://github.com/vanniktech/VNTNumberPickerPreference

12.CircularFloatingActionMenu
项目介绍：动画,可定制的圆形浮动菜单为Android,
项目地址：https://github.com/oguzbilgener/CircularFloatingActionMenu

13.NiftyDialogEffects
项目介绍：Dialog的各种打开动画，Nifty Modal Dialog Effects look like this(Nifty Modal Window Effects)
项目地址：https://github.com/sd6352051/NiftyDialogEffects

14.material-menu
项目介绍：变形安卓菜单,返回和删除按钮
项目地址：https://github.com/balysv/material-menu

15.AndroidViewHover
项目介绍：我们需要一个悬停视图,显示菜单,显示消息。
项目地址：https://github.com/daimajia/AndroidViewHover

16.PagedHeadListView
项目介绍：图片轮转切换
项目地址：https://github.com/JorgeCastilloPrz/PagedHeadListView

17.android-movies-demo
项目介绍：电影列表3级联动，交互
项目地址：https://github.com/dlew/android-movies-demo

18.NiftyNotification
项目介绍：提示通知栏的各种动画
项目地址：https://github.com/sd6352051/NiftyNotification

19.SwipeBack
项目介绍：拖动关闭，模范：kicker app（https://play.google.com/store/apps/details?id=com.netbiscuits.kicker）
项目地址：https://github.com/sockeqwe/SwipeBack

20.AndroidSwipeLayout
项目介绍：类似微信的测拉菜单
项目地址：https://github.com/daimajia/AndroidSwipeLayout

21.SnackBar
项目介绍：
项目地址：https://github.com/MrEngineer13/SnackBar

22.Swipecards
项目介绍：A Tinder-like cards effect as of August 2014. You can swipe left or right to like or dislike the content. The library creates a similar effect to Tinder's swipable cards with Fling animation.
项目地址：https://github.com/Diolor/Swipecards

23.LDrawer
项目介绍：Android抽屉与材料设计动画图标
项目地址：https://github.com/ikimuhendis/LDrawer

视觉篇
------
1.android-stackblur
项目介绍：毛玻璃，朦胧美
项目地址：https://github.com/kikoso/android-stackblur  
DEMO演示：

2.BlurEffectForAndroidDesign
项目介绍：实现模糊图形技巧
项目地址：https://github.com/PomepuyN/BlurEffectForAndroidDesign

3.Shimmer-android
项目介绍：闪动的文字
项目地址：https://github.com/RomainPiel/Shimmer-android

4.WizardPager
项目介绍：它提供了一个示例实现的Android手机上安装一个向导界面
项目地址：https://github.com/TechFreak/WizardPager

5.FloatingActionButton
项目介绍：浮动的按钮
项目地址：https://github.com/FaizMalkani/FloatingActionButton

6.JumpingBeans
项目介绍：跳动的文本
项目地址：https://github.com/frakbot/JumpingBeans

7.android_maskable_layout
项目介绍：可屏蔽的布局
项目地址：https://github.com/christophesmet/android_maskable_layout

8.activityanimation
项目介绍：Activit之间切换动画
项目地址：https://github.com/flavienlaurent/activityanimation

9.android-shape-imageview
项目介绍：提供了一组自定义形状的android imageview组件,和一个框架来定义更多的形状。实现着色器和位图基于掩模图像视图。
项目地址：https://github.com/siyamed/android-shape-imageview

10.RippleView
项目介绍：认为模仿的连锁反应在单击推出了Android L
项目地址：https://github.com/siriscac/RippleView

11.android-ui
项目介绍：一个小部件可以定义的行为之间的动态变化
项目地址：https://github.com/markushi/android-ui

12.FlatUI
项目介绍：
项目地址：https://github.com/eluleci/FlatUI

========
### UI资源
* [fontawesome](http://fontawesome.io/icons/) - Font-Awesome图标。
* [material-design-responsive-design](http://www.uisdc.com/material-design-responsive-design) - 深聊Material Design复杂响应式设计，[comprehensive-material-design-note](http://www.uisdc.com/comprehensive-material-design-note) - 帮你全面彻底搞定Material design的学习笔记。
* [Iconics](https://github.com/mikepenz/Android-Iconics) - 这是一个可以让你在你的项目中使用几乎任何字体图标的库。默认包含 FontAwesome 和 Material Design Icons 还包含 Meteocons 插件。你甚至可以添加任何你自定义的字体图标（typeface）。 


========
#### 开发资源
##### 他人开源总结
* [awesome-java](https://github.com/akullpp/awesome-java) - java库列表，[中文版](http://app.memect.com/doc/android.html)。
* [material design 的android开源代码整理](https://github.com/soyoungboy/android-material-design-Open-source-projects/blob/master/README.md) - material design 的android开源代码整理。
* [Android开源项目分类汇总](https://github.com/Trinea/android-open-project) - [Trinea](http://www.trinea.cn/) 国内最多好的开源库总结。  [Android 开源库获取途径整理](http://www.trinea.cn/android/android-open-project-summary/)
* [Android开源库源码分析](https://github.com/android-cn/android-open-project-analysis) - [Trinea](http://www.trinea.cn/) 我们从 Android 开始建了了协作项目，从简介、总体设计、流程图、详细设计全方面分析开源库源码。目前第一期完成，包括10个开源库及5个公共技术点的全面介绍。  [在线网页](http://www.codekk.com/open-source-project-analysis)

* [年薪30万的Android程序员必须知道的帖子](http://www.itlanbao.com/forum.php?mod=viewthread&tid=45&fromuid=1) - Android开源项目汇总，带效果gif图。


* [Android官方培训课程中文版](https://github.com/kesenhoo/android-training-course-in-chinese) - Google Android官方培训课程中文版。


* [GitHub优秀Android开源项目](http://www.cnblogs.com/hawkon/p/3593709.html) - GitHub 优秀的 Android 开源项目,很多中文现成项目。

* [Android开发工具及文档](http://www.androiddevtools.cn/) - 收集整理Android开发所需的Android SDK、开发中用到的工具、Android开发教程、Android设计规范，免费的设计素材等。

* [material_design](https://github.com/1sters/material_design_zh) - eoeAndroid Material Design 中文协同翻译。
* [Android Design Support Library](http://www.jianshu.com/p/1078568e859f) - Android Design Support Library 的 代码实验——几行代码，让你的 APP 变得花俏。
* [Android-Open-Sourse-Library](https://github.com/1sters/Android-Open-Sourse-Library/) - eoeAndroid 开源组件深度剖析: 1.Http请求组件:Volley\android-async-http\okhttp 2.json数据解析组件:Gson\fast-json\json-smart\Jackson。
* [wiki-eoeandroid](http://wiki.eoeandroid.com/) - wiki-eoeandroid : Android Develop - 开发技术、Android Design - 设计规范、Android Distribute - 软件发布。

* [Java资源大全](http://www.importnew.com/14429.html) - 国外程序员整理的Java资源大全。

* [Android开发技术前线](https://github.com/bboyfeiyu/android-tech-frontier) - Android开发技术前线 ( android-tech-frontier )，一个定期翻译、发布国内外Android优质的技术、开源库、软件架构设计、测试等文章的开源项目,让我们的技术跟上国际步伐。。
* [10个常用工具类](http://android.jobbole.com/80826/) - Android快速开发系列 10个常用工具类：1、日志工具类L.java；2、Toast统一管理类；3、SharedPreferences封装类SPUtils；4、单位转换类 DensityUtils；5、SD卡相关辅助类 SDCardUtils；6、屏幕相关辅助类 ScreenUtils；7、App相关辅助类；8、软键盘相关辅助类KeyBoardUtils；9、网络相关辅助类 NetUtils；10、Http相关辅助类 HttpUtils。
* [19个Android开发工具](http://blog.jobbole.com/67169/) - 19个Android 开发工具：1、XAppDbg；2、ChkBugReport；3、APKAnalyser；4、AppXplore；5、Memory Analyzer（MAT）；6、Eclipse插件SQLiteManger；7、Robotium；8、ACRA；9、Android Layout Binder；10、Spoon；11、Android Content Provider代码生成器；12、AndroidKickStartR；13、Android Holo颜色生成器；14、ActionBar风格生成器；15、Asset Studio；16、little eye labs；17、Droid Inspector；18、Android Button Maker；19、jsonschema2pojo。

* [apkbus](http://d.apkbus.com/) - code4app 与 apkbus整理的Android开源资源分类， [
Android源代码](http://www.apkbus.com/plugin.php?id=codesrc&modo=all)。
* [open-source-android-apps](https://github.com/pcqpcq/open-source-android-apps) - 他人收集的开源代码：Android Wear、Communication 、Education、Finance、Game、Multi-Media、News & Magazines、Personalization、Productivity、Social Network、Tools、Travel & Local。
* [android-developer-tools-list](http://codingfish.top/2015/07/07/android-developer-tools-list/) - Android 常用开发工具 （Android Studio 插件、Android 网站、Android 系统性能调优工具、Android测试工具）。


##### 中文开发博客列表
* [donal-tong](http://donal-tong.github.io/) - Android [ListView or GridView for ScrollView](http://donal-tong.github.io/blog/2014/05/28/listview-for-scrollview/)。
* [Longdw ](http://www.longdw.com/listview-category-getitemviewtype-getviewtypecount/) - ListView中的分类getItemViewType和getViewTypeCount的使用详解。 
* [脉脉不得语](http://www.inferjay.com/) - Android开发周报。
* [Chad.cym的专栏](http://blog.csdn.net/cym492224103) - Chad.cym的专栏:android5.0新特性分析。

* [搜索最好的 Android 代码——Codota](http://www.imooc.com/article/1086) -  从这里搜索超过七百万精品代码实例——Codota,，不仅只有Github，而且还有知名博客和开发者网站，让你搜索一个东西，不用在找上半天.
 

