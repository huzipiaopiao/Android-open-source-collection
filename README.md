# Android-open-source-collection
由于自己一直在收藏别人的开源项目，到现在已经有几百个收藏的项目了，以至于每次需要某个开源项目时很难找到，所以做了这个统计分类日常用到的开源项目的项目，主要是Android相关的

# 推荐几款管理github，star的工具
- [Astral](https://app.astralapp.com/auth) 用了以下，可以给自己star的项目加标签，通过标签就可以方便管理
- [Git Constellation](http://gitconstellation.com/) 不是很会用这个
- [OhMyStar2](https://ohmystarapp.com/)只有Mac版的

# github搜索工具：
- [CODELF](http://unbug.github.io/codelf/) github的搜索，会出来很多分类，根据需要进入对应项目

# 国内优秀开源作者(一些都认识的大神，后面再慢慢补上)：
- [廖子尧](https://github.com/jeasonlzy)
- [代码家](https://github.com/daimajia) 
- [王浩](https://github.com/bingoogolapple)
- [马天宇](https://github.com/litesuits)
- [Zhenjie Yan](https://github.com/yanzhenjie)
- [Blankj](https://github.com/Blankj)

# 国外优秀开源作者
- [JakeWharton](https://github.com/JakeWharton)
- [florent37](https://github.com/florent37)
- [amitshekhariitbhu](https://github.com/amitshekhariitbhu)
- [Antonio Leiva](https://github.com/antoniolg) 很多Kotlin的介绍

# 他人做的开源总结库：
- XXApple [AndroidLibs](https://github.com/XXApple/AndroidLibs)
- Trinea [android-open-project](https://github.com/Trinea/android-open-project)
- SenhLinsh [Android-Hot-Libraries](https://github.com/SenhLinsh/Android-Hot-Libraries#android-hot-libraries)
- wasabeef [awesome-android-ui](https://github.com/wasabeef/awesome-android-ui)  UI库清单
- wasabeef [awesome-android-libraries](https://github.com/wasabeef/awesome-android-libraries)  常用库清单
- Hack-with-Github [Awesome-Hacking](https://github.com/Hack-with-Github/Awesome-Hacking) 为黑客，测试人员和安全研究人员提供的各种精彩列表

# 网络类:
- square [okhttp](https://github.com/square/okhttp)
- square [retrofit](https://github.com/square/retrofit)
- jeasonlzy [okhttp-OkGo](https://github.com/jeasonlzy/okhttp-OkGo) 文档很全面，该库是基于 Http 协议，封装了 OkHttp 的网络请求框架，比 Retrofit 更简单易用，支持 RxJava，RxJava2，支持自定义缓存，支持批量断点下载管理和批量上传管理功能
- amitshekhariitbhu [Fast-Android-Networking](https://github.com/amitshekhariitbhu/Fast-Android-Networking) 网络请求类
- facebook [stetho](https://github.com/facebook/stetho) 可以通过浏览器，配合Okhttp的拦截器查看网络请求（抓包），并且可以查看app的DB和Sp的内容
- loopj [android-async-http](https://github.com/loopj/android-async-http) 基于回调的异步Android Http客户端，构建在Apache的Httpclient库之上。
- litesuits [android-lite-http](https://github.com/litesuits/android-lite-http) LiteHttp 只需要一行代码即可完美实现网络连接，它全面支持 GET, POST, PUT, DELETE, HEAD, TRACE, OPTIONS 和 PATCH 八种基本类型。 LiteHttp 能将 Java Model 转化为请求参数，也能将响应的 json 语句智能转化为 JavaModel ，这种全自动解析策略将节省你大量的构建请求、解析响应的时间。 并且，你能自己继承重新实现 Dataparser 这个抽象类并设置给 Request，来将原始的 InputStream 转化为任何你想要的东西。
- yanzhenjie [NoHttp](https://github.com/yanzhenjie/NoHttp) Android实现Http标准协议框架，支持缓存（提供五种缓存模式）、代理、重定向，底层可动态切换OkHttp、URLConnection。
- yanzhenjie [Kalle](https://github.com/yanzhenjie/Kalle) NoHttp作者，应该是比NoHttp封装的更好吧
- stealthcopter [AndroidNetworkTools](https://github.com/stealthcopter/AndroidNetworkTools) 并非我们常用的Http网络工具库，而是一个针对端口扫描、子网设备查询、Ping等功能的库

# 网络辅助类：
- ihsanbal [LoggingInterceptor](https://github.com/ihsanbal/LoggingInterceptor)okhttp的log拦截器
- facebook [stetho](https://github.com/facebook/stetho) 可以通过浏览器，查看app的DB和Sp的内容 ，并且有配合Okhttp的拦截器，可以查看网络请求（抓包）

# 视频类:
- Bilibili [ijkplayer](https://github.com/Bilibili/ijkplayer)
- google [ExoPlayer](https://github.com/google/ExoPlayer)
- yixia [VitamioBundleStudio](https://github.com/yixia/VitamioBundleStudio) Vitamio [官网首页](https://www.vitamio.org/)
- lipangit [JiaoZiVideoPlayer](https://github.com/lipangit/JiaoZiVideoPlayer) 视频播放，支持一行代码将系统的播放器换成Ijkplayer Exoplayer Vitamio等
- lipangit [JiaoZiVideoPlayer](https://github.com/lipangit/JiaoZiVideoPlayer) 
- daniulive [SmarterStreaming](https://github.com/daniulive/SmarterStreaming) 直播类，当然包含视频播放
- tcking [GiraffePlayer2](https://github.com/tcking/GiraffePlayer2) 基于ijkplayer，这个挺好用的
- danylovolokh [VideoPlayerManager](https://github.com/danylovolokh/VideoPlayerManager) 帮助控制Android MediaPlayer的，会更加方便
- huyongli [huyongli](https://github.com/huyongli/TigerVideo) Android播放视频library，支持小窗口，全屏模式播放，支持手势控制前进，后退，音量，亮度等操作，支持视频缓存，支持自定义显示视图。视频播放控制与界面展示完全解耦，支持自定义基于不同内核(MediaPlayer, ExoPlayer, PLDroidPlay...)的播放器，对界面操作无任何影响
- yangchong211 [YCVideoPlayer](https://github.com/yangchong211/YCVideoPlayer) 视频播放器封装库案例，仿照优酷，爱奇艺视频播放器，可以添家视频观看权限，试看模式，类似优酷试看功能。基于ijkplayer，支持网络视频或者本地视频播放，滑动调节亮度或者音量，快进快退，记录播放位置。可以设置边观看变缓存，支持全屏播放，小窗口，正常播放等模式；还支持列表播放，切换分辨率，还可以自定义视频播放器，拓展性强
- EasyDSS [EasyPlayer](https://github.com/EasyDSS/EasyPlayer) EasyPlayer是一款精炼、高效、稳定的流媒体播放器，分为RTSP版、RTMP版和Pro版本，支持各种各样的流媒体音视频播放！
- pili-engineering [PLDroidPlayer](https://github.com/pili-engineering/PLDroidPlayer) 是七牛推出的一款免费的适用于 Android 平台的播放器 SDK，采用全自研的跨平台播放内核，拥有丰富的功能和优异的性能，可高度定制化和二次开发。
- dueeeke [dkplayer](https://github.com/dueeeke/dkplayer) 基于IjkPlayer的视频播放器，支持直播点播，悬浮窗播放，广告播放，边播边缓存；支持重力感应自动全屏；完美实现ListView和RecyclerView列表播放；支持清晰度切换；支持一行代码切换MediaPlayer和ExoPlayer；
- jiajunhui [PlayerBase](https://github.com/jiajunhui/PlayerBase) Android播放器基础库，专注于播放视图组件的高复用性和组件间的低耦合，轻松处理复杂业务。
## demo类：
- iknow4 [Android-Video-Trimmer](https://github.com/iknow4/Android-Video-Trimmer) 视频裁剪功能的demo
- maimingliang [WxRecoderVideo](https://github.com/maimingliang/WxRecoderVideo) 基于VCamera，仿微信录制短视频,demo

# MVP框架:
- sockeqwe [mosby](https://github.com/sockeqwe/mosby) [官网](http://hannesdorfmann.com/android/mosby)
- konmik [nucleus](https://github.com/konmik/nucleus)
- square [mortar](https://github.com/square/mortar) 
- JessYanCoding [MVPArms](https://github.com/JessYanCoding/MVPArms) 国人做的，提供了中文文档，一个整合了大量主流开源项目高度可配置化的 Android MVP 快速集成框架
## demo类:
- ljqloveyou123 [perfect-mvp](https://github.com/ljqloveyou123/perfect-mvp) mvp的demo，也可以直接拿来用

# MVVM框架：
- goldze [MVVMHabit](https://github.com/goldze/MVVMHabit) 基于谷歌最新AAC架构，MVVM设计模式的一套快速开发库，整合Okhttp+RxJava+Retrofit+Glide等主流模块，满足日常开发需求。使用该框架可以快速开发一个健壮、易维护的Android应用。

# 滚动布局
- CymChad [BaseRecyclerViewAdapterHelper](https://github.com/CymChad/BaseRecyclerViewAdapterHelper) 更方便的recyclerView
- janishar [PlaceHolderView](https://github.com/janishar/PlaceHolderView) android recyclerview的包装，包含堆栈视图，简单和超快的动态视图创建与动画预建！
- airbnb [epoxy](https://github.com/airbnb/epoxy) Epoxy是一个用于在RecyclerView中构建复杂视图的Android库
- xmuSistone [AndroidPileLayout](https://github.com/xmuSistone/AndroidPileLayout) [中文简单用法](http://www.jcodecraeer.com/a/opensource/2017/0517/7955.html)

# 下拉刷新：
- scwang90 [SmartRefreshLayout](https://github.com/scwang90/SmartRefreshLayout)下拉刷新、上拉加载、二级刷新、淘宝二楼、RefreshLayout、OverScroll，Android智能下拉刷新框架，支持越界回弹、越界拖动，具有极强的扩展性，集成了几十种炫酷的Header和 Footer。
- liaohuqiu [android-Ultra-Pull-To-Refresh](https://github.com/liaohuqiu/android-Ultra-Pull-To-Refresh) 这是现在已经停止维护的下拉刷新项目的替代方案。继承于ViewGroup可以包含任何View。功能比SwipeRefreshLayout强大。使用起来非常简单。良好的设计，如果你想定制自己的UI样式，非常简单，就像给ListView加一个Header View那么简单。
- jdsjlzx [LRecyclerView](https://github.com/jdsjlzx/LRecyclerView) RecyclerView下拉刷新，自动加载更多；仿IOS侧滑Item删除菜单
- cundong [HeaderAndFooterRecyclerView](https://github.com/cundong/HeaderAndFooterRecyclerView) RecyclerView下拉刷新，自动加载更多；仿IOS侧滑Item删除菜单
- yanzhenjie [SwipeRecyclerView](https://github.com/yanzhenjie/SwipeRecyclerView) RecyclerView侧滑菜单，Item拖拽，滑动删除Item，自动加载更多，HeaderView，FooterView，Item分组黏贴。

# 条目Item侧滑效果:
- daimajia [AndroidSwipeLayout](https://github.com/daimajia/AndroidSwipeLayout) 侧滑布局
- anzaizai [EasySwipeMenuLayout](https://github.com/anzaizai/EasySwipeMenuLayout) 左右均可添加侧拉按钮
- mcxtzhang [SwipeDelMenuLayout](https://github.com/mcxtzhang/SwipeDelMenuLayout) 史上最简单侧滑菜单，0耦合，支持任意ViewGroup。一步集成侧滑(删除)菜单，高仿QQ、IOS。

# 页面侧滑：
- bingoogolapple [BGASwipeBackLayout-Android](https://github.com/bingoogolapple/BGASwipeBackLayout-Android) Android Activity 滑动返回。支持微信滑动返回样式、横屏滑动返回、全屏滑动返回
- ikew0ng [SwipeBackLayout](https://github.com/ikew0ng/SwipeBackLayout) 一个Android库，可帮助您通过向后滑动手势构建应用程序。

# 轮播图：
- youth5201314 [banner](https://github.com/youth5201314/banner) Android广告图片轮播控件，支持无限循环和多种主题，可以灵活设置轮播样式、动画、轮播和切换时间、位置、图片加载框架等！
- ImmortalZ [StereoView](https://github.com/ImmortalZ/StereoView) Android 3D立体无限旋转容器。

# 设置view（基本上每个app都会有的settingview）
- leonHua [LSettingView](https://github.com/leonHua/LSettingView)
- zxyaust [SettingItem](https://github.com/zxyaust/SettingItem)
- jeff-sun [SettingView](https://github.com/jeff-sun/SettingView)

# 下载辅助
- MindorksOpenSource [PRDownloader](https://github.com/MindorksOpenSource/PRDownloader)
- bingoogolapple [BGAUpdate-Android](https://github.com/bingoogolapple/BGAUpdate-Android) RxJava + Retrofit 下载新版 apk 文件，RxBus 监听下载进度 适配 Android 8.+ 系统,检测新版 apk 文件是否已经下载过,RxJava1.x + Retrofit2.x 下载新版 apk 文件,RxBus 监听下载进度,安装 apk 文件,删除之前升级时下载的老的 apk 文件
- lingochamp [FileDownloader](https://github.com/lingochamp/FileDownloader) Android 文件下载引擎，稳定、高效、灵活、简单易用
- lingochamp [okdownload](https://github.com/lingochamp/okdownload) 上面下载工具的升级版

# 主题换肤（皮肤）类:
- ximsfei [Android-skin-support](https://github.com/ximsfei/Android-skin-support) 一款用心去做的Android 换肤框架, 极低的学习成本, 极好的用户体验. 一行代码就可以实现换肤, 你值得拥有!!!
- Bilibili [MagicaSakura](https://github.com/Bilibili/MagicaSakura) 方便切换主题
- hongyangAndroid [AndroidChangeSkin](https://github.com/hongyangAndroid/AndroidChangeSkin) 一种完全无侵入的换肤方式，支持插件式和应用内，无需重启Activity

# 图片选择器:
- 知乎  [Matisse](https://github.com/zhihu/Matisse)
bate版有选择视频的功能，有没有录制视频的功能还没去研究，图片选择挺好用的。 
- Bilibili [boxing](https://github.com/Bilibili/boxing)
- bingoogolapple [BGAPhotoPicker-Android](https://github.com/bingoogolapple/BGAPhotoPicker-Android) Android 图片选择、预览、九宫格图片控件、拖拽排序九宫格图片控件
- LuckSiege [PictureSelector](https://github.com/LuckSiege/PictureSelector)
支持从相册或拍照选择图片或视频、音频，支持动态权限获取、裁剪(单图or多图裁剪)、压缩、主题自定义配置等功能、适配android 6.0+系统的开源图片选择框架，用的是glide4.0以上版本，会与项目起冲突，具体还没有使用。
- FinalTeam [RxGalleryFinal](https://github.com/FinalTeam/RxGalleryFinal)
Android图片单选/多选、拍照、裁剪、压缩。视频选择和录制。
- crazycodeboy [TakePhoto](https://github.com/crazycodeboy/TakePhoto)
在Android设备上获取照片（拍照或从相册、文件中选择）、裁剪图片、压缩图片的开源工具库。（没有选视频的功能）
- donglua [PhotoPicker](https://github.com/donglua/PhotoPicker) 
用的是glide4.0以上版本
- jeasonlzy [ImagePicker](https://github.com/jeasonlzy/ImagePicker)
廖子尧的库，可以试用下，但是没有选视频的功能，且已经停止维护了
- guoxiaoxing [phoenix](https://github.com/guoxiaoxing/phoenix) Android平台上图片/视频选择，编辑和压缩的一站式解决方案，这个也挺好用的，而且作者问题反馈率很高
- Werb [PickPhotoSample](https://github.com/Werb/PickPhotoSample) 图片选择库
- lijunguan [AlbumSelector](https://github.com/lijunguan/AlbumSelector) 图片选择库，可以用来选择头像，或者多张图片选择， material design
- lovetuzitong [MultiImageSelector](https://github.com/lovetuzitong/MultiImageSelector)比较老

# 数据库:
- greenrobot [greenDAO](https://github.com/greenrobot/greenDAO)
- LitePalFramework [LitePal](https://github.com/LitePalFramework/LitePal)
- agrosner [DBFlow](https://github.com/Raizlabs/DBFlow) [文档](https://github.com/agrosner/DBFlowDocs)
- objectbox[objectbox-java](https://github.com/objectbox/objectbox-java) 好像也是出自greenrobot，号称比SQLite快10倍

# 动画效果
- airbnb [lottie-android](https://github.com/airbnb/lottie-android) 在Android和iOS，Web和React Native上使用After Effects动画
- facebook [rebound](https://github.com/facebook/rebound) 弹簧效果（没有仔细用过，不清楚还有没有其他效果）
- facebook [shimmer-android](https://github.com/facebook/shimmer-android) 一闪一闪的效果
- daimajia [AndroidViewAnimations](https://github.com/daimajia/AndroidViewAnimations) 可爱的视图动画集合。
- daimajia [AnimationEasingFunctions](https://github.com/daimajia/AnimationEasingFunctions) 根据作者的意思，这个库是从上面这个库升级而来的。Android动画缓和功能。 让动画更真实！
- yyued [SVGAPlayer-Android](https://github.com/yyued/SVGAPlayer-Android) 使用 SVGAPlayer 在 Android、iOS、Web中播放 After Effects / Animate CC (Flash) 动画。
- florent37 [ViewAnimator](https://github.com/florent37/ViewAnimator) 很多中动画

# 图片压缩:
- Curzibn [Luban](https://github.com/Curzibn/Luban) 图片压缩，微信压缩后的图片逆向推算出来的压缩算法
- zetbaitsu [Compressor](https://github.com/zetbaitsu/Compressor) 

# ImageView相关：
- chrisbanes [PhotoView](https://github.com/chrisbanes/PhotoView) 支持缩放，手势操作。
- hdodenhof [CircleImageView](https://github.com/hdodenhof/CircleImageView) 圆形的ImageView
- vinc3m1 [RoundedImageView](https://github.com/vinc3m1/RoundedImageView) 支持圆角，椭圆和圆ImageView。
- boycy815 [PinchImageView](https://github.com/boycy815/PinchImageView) 这是一个手势体验极棒但使用简单的ImageView控件，实现了手势放大缩小，平移等功能。PinchImageView继承于ImageView，可以在所有ImageView可以使用的情况下使用。全部的程序仅一个类文件，没有依赖任何特殊的外部库，非常易于集成。
- cnlkl [TransformativeImageView](https://github.com/cnlkl/TransformativeImageView) 自定义ImageView，可以旋转，翻译和缩放图像。[原理](https://www.jianshu.com/p/938ca88fb16a)
- sephiroth74 [ImageViewZoom](https://github.com/sephiroth74/ImageViewZoom) Android ImageView小部件，具有缩放和平移功能
- stfalcon-studio [MultiImageView](https://github.com/stfalcon-studio/MultiImageView) Android库在一个ImageView中显示几个图像，例如群聊的头像
- Piasy [BigImageViewer](https://github.com/Piasy/BigImageViewer) 基于Subsampling Scale Image View, Fresco, Glide, 和 Picasso的大图加载，支持缩放，可以使用不同的加载库，加载进度，支持下载。
- davemorrissey [subsampling-scale-image-view](https://github.com/davemorrissey/subsampling-scale-image-view) Android库（AAR）。 高度可配置，易于扩展的深度缩放视图，可显示巨大图像而不会损失细节。 适合照片画廊，地图，建筑计划等。
- flavioarfaria [KenBurnsView](https://github.com/flavioarfaria/KenBurnsView) 带动画的imageview
- florent37 [DiagonalLayout](https://github.com/florent37/DiagonalLayout) 可以给imageview切斜边
- wasabeef [Blurry](https://github.com/wasabeef/Blurry) 毛玻璃效果

# 图片显示相关：
- bumptech [glide](https://github.com/bumptech/glide) 官方推荐加载图片库
- wasabeef [glide-transformations](https://github.com/wasabeef/glide-transformations) 为Glide提供各种图像转换的Android转换库。
- sephiroth74 [ImageViewZoom](https://github.com/sephiroth74/ImageViewZoom) ImageView，具有缩放和平移功能
- alexvasilkov [GestureViews](https://github.com/alexvasilkov/GestureViews) ImageView和FrameLayout手势控制和位置动画
- stfalcon-studio [FrescoImageViewer](https://github.com/stfalcon-studio/FrescoImageViewer) 可自定义的Android全屏图像查看器，支持“捏缩放”和“轻扫以消除”手势的Fresco库
- MostafaGazar [CustomShapeImageView](https://github.com/MostafaGazar/CustomShapeImageView) 一个库，用于支持自定义形状的图像和使用svgs和绘制形状
- irimiaionut [ParallaxImageView](https://github.com/irimiaionut/ParallaxImageView) 3D效果
- koral-- [android-gif-drawable](https://github.com/koral--/android-gif-drawable) gif播放

# 图片处理相关：
- pqpo [SmartCropper](https://github.com/pqpo/SmartCropper)智能图片裁剪框架。自动识别边框，手动调节选区，使用透视变换裁剪并矫正选区；适用于身份证，名片，文档等照片的裁剪。
- ArthurHub [Android-Image-Cropper](https://github.com/ArthurHub/Android-Image-Cropper)适用于Android的图像裁剪库，针对相机/图库进行了优化。

# 图表类：
- PhilJay [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart)一个强大的Android图表视图/图形视图库，支持线条形 - 雷达 - 泡沫和烛台图表，以及缩放，拖动和动画。
- huangyanbin [SmartChart](https://github.com/huangyanbin/SmartChart)一款android 图表框架，支持图表N配置，支持缩放,旋转手势。
- lecho [hellocharts-android](https://github.com/lecho/hellocharts-android) [使用方法](http://jcodecraeer.com/a/anzhuokaifa/androidkaifa/2014/1107/1930.html)适用于Android的图表/图表库兼容API 8+，多种图表类型，支持缩放，滚动和动画 
- xcltapestry [XCL-Charts](https://github.com/xcltapestry/XCL-Charts) 国内开源的，所以有中文文档
- whataa [SuitLines](https://github.com/whataa/SuitLines) 一个小巧且高效的线性图表组件。
- wordplat [ikvStockChart](https://github.com/wordplat/ikvStockChart) 一个简单的Android股票图表库，支持时间线，K线，MACD，KDJ，RSI，BOLL指数和交互式手势操作，包括左右滑动刷新，缩放，突出显示
- linheimx [LChart](https://github.com/linheimx/LChart) 一个折线图，它提供了几个非常实用的功能，并且非常简单，易于使用。
- ZuYun [Jgraph](https://github.com/ZuYun/Jgraph) 一个视觉效果还不错的图表控件
- DmitriyZaitsev [RadarChartView](https://github.com/DmitriyZaitsev/RadarChartView) 用于渲染径向图的Android视图（小部件）能力图
- hrules6872 [Charter](https://github.com/hrules6872/Charter) [使用方法](http://www.jcodecraeer.com/a/opensource/2015/1020/3599.html)柱状图 
- panpf [spider-web-score-view](https://github.com/panpf/spider-web-score-view) SpiderWebScoreView 是 Android 上的一个蛛网评分控件
- txusballesteros [snake](https://github.com/txusballesteros/snake) Snake View是Android的一个简单和动画线性图表。
- Geek-1001 [MagnificentChart](https://github.com/Geek-1001/MagnificentChart) 用于圆形图表的简单的开源Android库。[效果图](http://www.jcodecraeer.com/a/opensource/2014/1224/2210.html)
- Erzer [polonium-chart-view](https://github.com/Erzer/polonium-chart-view) Android库，方便创建图表和自定义视觉风格。主要是折线图
- johnjohndoe [AFreeChart](https://github.com/johnjohndoe/AFreeChart) AFreeChart是基于JFreeChart 1.0.13的Android免费图表库
- svenkapudija [Android-FancyChart](https://github.com/svenkapudija/Android-FancyChart) 折线图
- blackfizz [EazeGraph](https://github.com/blackfizz/EazeGraph) EazeGraph是一个轻量级简洁扁平风格的开源图表库，目前有Bar Chart，Stacked Bar Chart，Pie Chart，Line Chart四种图表可选择，每一种图表都带有动画效果。只有lib包
- appsthatmatter [GraphView](https://github.com/appsthatmatter/GraphView) Android图形库，用于创建可缩放和可滚动的线条和条形图。
- diogobernardino [WilliamChart](https://github.com/diogobernardino/WilliamChart) [使用方法](http://www.jcodecraeer.com/a/opensource/2014/1011/1738.html)Android库创建图表。
- bmarrdev [android-DecoView-charting](https://github.com/bmarrdev/android-DecoView-charting) 一个实现了各种圆环动画效果的library
- dlazaro66 [WheelIndicatorView](https://github.com/dlazaro66/WheelIndicatorView) 圆环进度图表
- txusballesteros [fit-chart](https://github.com/txusballesteros/fit-chart)  Fit Chart 是一个类似于谷歌健康应用的轮子（wheel view）视图。
- evrencoskun [TableView](https://github.com/evrencoskun/TableView)  类似Excel的一个view
- huangyanbin [smartTable](https://github.com/huangyanbin/smartTable)一款android自动生成表格框架。
# demo：
- PaoloConte [smooth-line-chart](https://github.com/PaoloConte/smooth-line-chart) 与绘制折线图不同，smooth-line-chart能根据两点绘制平滑的曲线，使用的是贝赛尔曲线的原理。项目比较简单，但是如果你还不知道贝塞尔曲线如何绘制的话可以学习一下。

# 拍摄类：
- wonderkiln [CameraKit-Android](https://github.com/wonderkiln/CameraKit-Android) [中文说明](http://www.jcodecraeer.com/a/opensource/2017/0228/7173.html)方便控制拍摄的库 如果报关于ExifInterface的错，添加一个依赖：compile 'com.android.support:exifinterface:25.+'
- afollestad [material-camera](https://github.com/afollestad/material-camera) 拍摄库
- CJT2325 [CameraView](https://github.com/CJT2325/CameraView) 仿微信拍照Android控件（轻触拍照，长按摄像）

# app美化类：
- elye [loaderviewlibrary](https://github.com/elye/loaderviewlibrary) 在显示任何文本或图像之前，提供textview和imageview两种显示微光（动画加载器）的功能。等待数据从网络加载时很有用。![例如](https://camo.githubusercontent.com/ad3e2fed505b8ae48e2a407f1e21361473605639/68747470733a2f2f7374617469632e7769787374617469632e636f6d2f6d656469612f6437343863335f32383338316330663131306634646336386663643334306235303366383661322537456d76322e676966)
- Bearded-Hen [Android-Bootstrap](https://github.com/Bearded-Hen/Android-Bootstrap) 引导程序样式小部件的android，具有标志符号图标，自带小图标的textview、button、下拉选择等等。[图标库地址](https://fontawesome.com/cheatsheet)

# 悬浮类：
- yhaolpz [FloatWindow](https://github.com/yhaolpz/FloatWindow) Andorid 任意界面悬浮窗
- txusballesteros [bubbles-for-android](https://github.com/txusballesteros/bubbles-for-android) Bubbles for Android是一个Android库，为您的应用程序提供聊天头功能.可以任何界面悬浮
- afollestad [material-dialogs](https://github.com/afollestad/material-dialogs) 一个美丽，流畅，可定制的对话框API。
- wangjiegulu [RapidFloatingActionButton](https://github.com/wangjiegulu/RapidFloatingActionButton) FloatingActionButton，可以弹出很多子选项

# 提示Tip
- GrenderG[Toasty](https://github.com/GrenderG/Toasty)
- Muddz [StyleableToast](https://github.com/Muddz/StyleableToast)   
- Tapadoo [Alerter](https://github.com/Tapadoo/Alerter) 超漂亮的一个顶部提示

# 角标类(Badger)：
- leolin310148 [ShortcutBadger](https://github.com/leolin310148/ShortcutBadger) 桌面图标的消息数角标
- xuyisheng [ShortcutHelper](https://github.com/xuyisheng/ShortcutHelper) 桌面图标的消息数角标
- beiliao-mobile [BadgeNumberManager](https://github.com/beiliao-mobile/BadgeNumberManager) 桌面图标的消息数角标，Huawei, Xiaomi, OPPO, vivo 
- bingoogolapple [BGABadgeView-Android](https://github.com/bingoogolapple/BGABadgeView-Android) app内的消息数角标，类似qq的未读消息数
- nekocode [Badge](https://github.com/nekocode/Badge) 一个可以设置成类似![开源协议背景](https://raw.githubusercontent.com/nekocode/Badge/master/art/two_text_complementary.png)的那种textview

# 导航类(类似TableLayout和ViewPager)：
- Devlight [NavigationTabBar](https://github.com/Devlight/NavigationTabBar) 导航标签栏与丰富多彩的互动。
- hackware1993 [MagicIndicator](https://github.com/hackware1993/MagicIndicator) 强大、可定制、易扩展的 ViewPager 指示器框架。是ViewPagerIndicator、TabLayout、PagerSlidingTabStrip的最佳替代品。支持角标，更支持在非ViewPager场景下使用
- bingoogolapple [BGARefreshLayout-Android](https://github.com/bingoogolapple/BGARefreshLayout-Android) 多种下拉刷新效果、上拉加载更多、可配置自定义头部广告位

# 二维码：
- yipianfengye [android-zxingLibrary](https://github.com/yipianfengye/android-zxingLibrary) 几行代码快速集成二维码扫描功能
- bingoogolapple [BGAQRCode-Android](https://github.com/bingoogolapple/BGAQRCode-Android) QRCode 扫描二维码、扫描条形码、相册获取图片后识别、生成带 Logo 二维码、支持微博微信 QQ 二维码扫描样式
- dm77 [barcodescanner](https://github.com/dm77/barcodescanner) 
- SumiMakito [AwesomeQRCode](https://github.com/SumiMakito/AwesomeQRCode) 二维码生成器

# HTML:
- jhy [jsoup](https://github.com/jhy/jsoup) Java的HTML解析器，最好的DOM，CSS和jQuery

# 文件查看：
- 腾讯 [TBS](https://x5.tencent.com/tbs/index.html) 腾讯的浏览服务，可以查看各种文件（包括office的文件）
- barteksc [AndroidPdfViewer](https://github.com/barteksc/AndroidPdfViewer) 查看PDF

# 日历
- huanghaibin-dev [CalendarView](https://github.com/huanghaibin-dev/CalendarView?utm_source=gold_browser_extension) Android上一个优雅、万能自定义UI、支持周视图、性能高效的日历控件，支持热插拔实现的UI定制！支持标记、自定义颜色、农历、自定义月视图各种显示模式等。Canvas绘制，速度快、占用内存低，你真的想不到日历居然还可以如此优雅！

# 其他类自定义view
- hackware1993 [WaveView](https://github.com/hackware1993/WaveView) 一个简单的、巧妙的水波纹扩散效果
- tyrantgit [ExplosionField](https://github.com/tyrantgit/ExplosionField) 天女散花的效果
- tyrantgit [HeartLayout](https://github.com/tyrantgit/HeartLayout) 点赞的心
- glomadrian [Grav](https://github.com/glomadrian/Grav) 基于点的可配置动画，各种光离子的动画
- glomadrian [material-code-input](https://github.com/glomadrian/material-code-input) material的输入框
- glomadrian [RoadRunner](https://github.com/glomadrian/RoadRunner) 带动画的加载svg图像
- JorgeCastilloPrz [AndroidFillableLoaders](https://github.com/JorgeCastilloPrz/AndroidFillableLoaders) Android可填充的进度视图使用SVG路径。如果你想为你的应用程序创建一个有趣的品牌标志，这也是一个不错的选择。
- glomadrian [loading-balls](https://github.com/glomadrian/loading-balls) 一个高度可配置的库，用动画球来加载进度
- glomadrian [material-animated-switch](https://github.com/glomadrian/material-animated-switch) material的切换开关
- alibaba [vlayout](https://github.com/alibaba/vlayout)VirtualLayout是一个针对RecyclerView的LayoutManager扩展, 主要提供一整套布局方案和布局间的组件复用的问题。
- niniloveyou [StateButton](https://github.com/niniloveyou/StateButton) 一个可以用代码设置selector背景（按下去背景颜色更改，样式变化等等）的button, 再也不用写selector了
- lguipeng [BubbleView](https://github.com/lguipeng/BubbleView) 聊天中消息气泡的view
- daimajia [AndroidViewHover](https://github.com/daimajia/AndroidViewHover) 一个优雅的方式来显示您的菜单或消息。菜单都是悬浮出来的
- lguipeng [AnimCheckBox](https://github.com/lguipeng/AnimCheckBox) 带动画的checkbox 
- stfalcon-studio [ChatKit](https://github.com/stfalcon-studio/ChatKit) IM的UI库
- Rance935 [ChatUI](https://github.com/Rance935/ChatUI) IM的UI库
- jpush [aurora-imui](https://github.com/jpush/aurora-imui) IM的UI库
- DuanJiaNing[ColorPicker](https://github.com/DuanJiaNing/ColorPicker) 进度条”水平、竖直颜色选择器。
- DuanJiaNing[MediaView](https://github.com/DuanJiaNing/MediaView) 带阴影点击效果，可自定义属性的媒体播放控制按钮。包括【播放(暂停)】按钮，【下一曲(上一曲)】按钮。
- florent37 [ShapeOfView](https://github.com/florent37/ShapeOfView) 给任何android视图定制形状
- HpWens [MeiWidgetView](https://github.com/HpWens/MeiWidgetView) 几个自定义控件的集合
- JustKiddingBaby [RollingLayout](https://github.com/JustKiddingBaby/RollingLayout) 一个可以让自己子视图自动滚动的view,仿淘宝头条
- xmuSistone [DragRankSquare](https://github.com/xmuSistone/DragRankSquare) 编辑个人资料，图片可拖拽排序。有点像可拖拽的gridView，但是会更流畅。
- DingMouRen [LayoutManagerGroup](https://github.com/DingMouRen/LayoutManagerGroup) 给RecyclerView设置自定义的LayoutManager
- etsy [AndroidStaggeredGrid](https://github.com/etsy/AndroidStaggeredGrid) 一个Android交错网格视图，它支持具有不同大小的行的多个列。瀑布流
- shellljx [TagViewGroup](https://github.com/shellljx/TagViewGroup) Android 仿小红书图片标签Group
- developer-shivam [Crescento](https://github.com/developer-shivam/Crescento) 在ImageView和relative layout的底部添加曲线。
- Quatja [Vorolay](https://github.com/Quatja/Vorolay) VoronoiView是一个视图(视图组)，允许您在Voronoi图区域内添加和显示视图。会是菱形显示
- scwang90 [MultiWaveHeader](https://github.com/scwang90/MultiWaveHeader) Android 炫酷的多重水波纹

# 流式布局
- hongyangAndroid [FlowLayout](https://github.com/hongyangAndroid/FlowLayout) Android流式布局，支持单选、多选等，适合用于产品标签等。
- bingoogolapple [BGAFlowLayout-Android](https://github.com/bingoogolapple/BGAFlowLayout-Android) Android 流式布局，可配置是否将每一行的空白区域平均分配给子控件


# 透明指示层 (HUD)
- TakuSemba [Spotlight](https://github.com/TakuSemba/Spotlight)
- wooplr [Spotlight](https://github.com/wooplr/Spotlight)
- huburt-Hu [NewbieGuide](https://github.com/huburt-Hu/NewbieGuide) 中文文档
- hongyangAndroid [Highlight](https://github.com/hongyangAndroid/Highlight) 一个用于app指向性功能高亮的库

# 进度条
- daimajia [NumberProgressBar](https://github.com/daimajia/NumberProgressBar) 一个好看的的Android进度条。
- castorflex [SmoothProgressBar](https://github.com/castorflex/SmoothProgressBar) 一个小型Android库，允许您拥有平滑且可定制的水平不确定ProgressBar
- akexorcist [Android-RoundCornerProgressBar](https://github.com/akexorcist/Android-RoundCornerProgressBar) 带圆角和图标的进度条
- AnderWeb [discreteSeekBar](https://github.com/AnderWeb/discreteSeekBar) 带气泡的进度条
- bingoogolapple [BGAProgressBar-Android](https://github.com/bingoogolapple/BGAProgressBar-Android)带百分比数字的水平、圆形进度条
- lingochamp [MagicProgressWidget](https://github.com/lingochamp/MagicProgressWidget)  渐变的圆形进度条与轻量横向进度条
- JessYanCoding [ProgressManager](https://github.com/JessYanCoding/ProgressManager) ProgressManager 一行代码即可监听 App 中所有通过okhttp网络链接的上传以及下载进度,包括 Glide 的图片加载进度
- sfsheng0322 [GlideImageView](https://github.com/sfsheng0322/GlideImageView) 基于Glide V4.0封装的图片加载库，可以监听加载图片时的进度
- peng8350 [LoadingProgress](https://github.com/peng8350/LoadingProgress) 特别方便的在View上，注入一个进度条，改进度条和view绑定，所以一个页面上如果有很多view都需要进度条显示，用这个库会很方便

# 加载类：
- 81813780 [AVLoadingIndicatorView](https://github.com/81813780/AVLoadingIndicatorView) 适合Android的漂亮的加载动画 
- zyao89 [ZLoading](https://github.com/zyao89/ZLoading) 很多图案的加载动画
- Rogero0o [GifLoadingView](https://github.com/Rogero0o/GifLoadingView) 

# 折叠式view:
- Ramotion [folding-cell-android](https://github.com/Ramotion/folding-cell-android) [使用方法](http://www.jcodecraeer.com/a/opensource/2016/0414/4145.html)
- worldline [FoldableLayout](https://github.com/worldline/FoldableLayout) 


# 权限申请：
- googlesamples [easypermissions](https://github.com/googlesamples/easypermissions) 辅助动态申请权限
- yanzhenjie [AndPermission](https://github.com/yanzhenjie/AndPermission) 辅助动态申请权限
- tbruyelle [RxPermissions](https://github.com/tbruyelle/RxPermissions) Android运行时权限通过RxJava2
- florent37 [RuntimePermission](https://github.com/florent37/RuntimePermission) 在Android上请求运行时权限的最简单方式，不需要扩展类或覆盖权限结果方法，选择您的方式: Kotlin / Coroutines / RxJava / Java 7 / Java 8
- yewei02538 [HiPermission](https://github.com/yewei02538/HiPermission) 一个简单易用的漂亮权限申请库
- Karumi [Dexter](https://github.com/Karumi/Dexter) 

# 框架架构类：
- googlesamples [android-architecture-components](https://github.com/googlesamples/android-architecture-components) 谷歌官方 Android 应用架构库。这个新的架构库旨在帮助我们设计健壮、可测试的和可维护的应用程序。关注分离,模型驱动UI，优先持久化模型
- JumeiRdGroup  [Router](https://github.com/JumeiRdGroup/Router)一款单品、组件化、插件化全支持的Andoid端路由框架,简单来说.即通过一行url去指定打开指定页面Activity的框架.充分做到页面间解耦.

# Fragment类：
- YoKeyword [Fragmentation](https://github.com/YoKeyword/Fragmentation) 为Android管理Fragment的强大库
- JustKiddingBaby [FragmentRigger](https://github.com/JustKiddingBaby/FragmentRigger) 这可能是使用成本最低的Fragment框架。无需继承!在使用FragmentRigger的时候，使用成本只有一行注解！！！
 
# 适配类:
- JessYanCoding [AndroidAutoSize](https://github.com/JessYanCoding/AndroidAutoSize) (今日头条屏幕适配方案终极版，一个极低成本的 Android 屏幕适配方案
- 鸿阳大神 [AndroidAutoLayout](https://github.com/hongyangAndroid/AndroidAutoLayout) 很遗憾的，停止更新了

# 时间相关
- dlew [joda-time-android](https://github.com/dlew/joda-time-android) 解决时区不断变化，没有用过，待研究

# 沉浸式
- gyf-dev [ImmersionBar](https://github.com/gyf-dev/ImmersionBar) android 4.4以上沉浸式状态栏和沉浸式导航栏管理，包括状态栏字体颜色，一句代码轻松实现，以及对bar的其他设置
- liyuhaolol [LightImmersionMode](https://github.com/liyuhaolol/LightImmersionMode) 纯色沉浸式状态栏开发，兼容浅色状态栏自适应深色字体
- matrixxun [ImmersiveDetailSample](https://github.com/matrixxun/ImmersiveDetailSample) 一个示例应用程序展示了如何实现身临其境的视差效果标题，如谷歌商店
- jgilfelt [SystemBarTint](https://github.com/jgilfelt/SystemBarTint) 已过时
- H07000223 [FlycoSystemBar](https://github.com/H07000223/FlycoSystemBar)
- yanzhenjie [Sofia](https://github.com/yanzhenjie/Sofia)SystemBar一体化，状态栏和导航栏均支持设置颜色、渐变色、图片、透明度、内容入侵。状态栏支持设置深色字体，以上特性兼容国产魅族、小米手机（包括7.0及以上）和其它标准模式的手机。
- laobie [StatusBarUtil](https://github.com/laobie/StatusBarUtil)
- Jude95 [FitSystemWindowLayout](https://github.com/Jude95/FitSystemWindowLayout) 适应Statusbar与NavigationBar的各种Layout

# 标签：
- robertlevonyan [materialChipView](https://github.com/robertlevonyan/materialChipView) material视图。 可以用作类别，联系人或创建文本云的标签
- BelooS [ChipsLayoutManager](https://github.com/BelooS/ChipsLayoutManager) ANDROID。 ChipsLayoutManager（SpanLayoutManager，FlowLayoutManager）。 RecyclerView的一个自定义的布局管理器，它模仿TextView跨越行为，流动布局的行为，支持惊人的recyclerView功能
- DoodleScheduling [android-material-chips](https://github.com/DoodleScheduling/android-material-chips) ANDROID。 ChipsLayoutManager（SpanLayoutManager，FlowLayoutManager）。 RecyclerView的一个自定义的布局管理器，它模仿TextView跨越行为，流动布局的行为，支持惊人的recyclerView功能

# 更改字体:
- chrisjenx [Calligraphy](https://github.com/chrisjenx/Calligraphy) 自定义字体的库

# EditText:
- xujinyang [BiuEditText](https://github.com/xujinyang/BiuEditText)从上或下，飞进来的字
- alphamu [AnimatedEditText](https://github.com/alphamu/AnimatedEditText)Androids EditText动画输入的文本。 EditText被扩展为创建AnimatedEditText和PinEntryEditText。
- mrmilu [WPEditText](https://github.com/mrmilu/WPEditText)Material design风格的EditText ，带图标和验证功能。
- Pombo [material-edit-text](https://github.com/Pombo/material-edit-text)Material Design风格的输入框控件，可以设置图标，支持悬浮文字提示。
- mabbas007 [TagsEditText](https://github.com/mabbas007/TagsEditText)标签输入控件。
- pchmn [MaterialChipsInput](https://github.com/pchmn/MaterialChipsInput)这个库实现了Material Design中的Chips component ，分为可编辑的ChipsInput和ChipView。
- Rogero0o [PasswordLoadingView](https://github.com/Rogero0o/PasswordLoadingView)当完成密码时提供动画
- MindorksOpenSource [EditDrawableText](https://github.com/MindorksOpenSource/EditDrawableText) 带图标的edittext

# button
- Bearded-Hen [Android-Bootstrap](https://github.com/Bearded-Hen/Android-Bootstrap) 用于Android的引导样式小部件，带有字形图标

# 线程任务相关
- BoltsFramework [Bolts-Android](https://github.com/BoltsFramework/Bolts-Android) 可以方便的在线程间执行各种任务

# 特殊功能类：
- stfalcon-studio [SmsVerifyCatcher](https://github.com/stfalcon-studio/SmsVerifyCatcher) 用于在您的应用中验证电话号码的Android库。 自动将验证码从SMS复制到应用程序中。
- luckybilly [PreLoader](https://github.com/luckybilly/PreLoader) android页面启动速度优化利器：在页面打开之前就预加载数据
- githubwing [ByeBurger](https://github.com/githubwing/ByeBurger) 这是一个极其简便的快速实现隐藏标题栏和导航栏的库
- jarryleo [SingleClick](https://github.com/jarryleo/SingleClick) 安卓点击事件防重库

# 缓存存储相关
- yangfuhai [ASimpleCache](https://github.com/yangfuhai/ASimpleCache) 是一个为android制定的 轻量级的 开源缓存框架。轻量到只有一个java文件，可以缓存普通的字符串、JsonObject、JsonArray、Bitmap、Drawable、序列化的java对象，和 byte数据。
- anupcowkur [Reservoir](https://github.com/anupcowkur/Reservoir) Android库轻松使用键/值对将对象序列化并缓存到磁盘。

# Socket相关
- TooTallNate [Java-WebSocket](https://github.com/TooTallNate/Java-WebSocket) 用100％Java编写的准系统WebSocket客户端和服务器实现

# 表情类:
- w446108264 [XhsEmoticonsKeyboard](https://github.com/w446108264/XhsEmoticonsKeyboard) 开源表情键盘解决方案

# 键盘类:
- w446108264 [XhsEmoticonsKeyboard](https://github.com/w446108264/XhsEmoticonsKeyboard) 开源表情键盘解决方案

# 蓝牙
- Jasonchenlijian [FastBle](https://github.com/Jasonchenlijian/FastBle) 蓝牙快速开发框架
- dingjikerbo [BluetoothKit](https://github.com/dingjikerbo/BluetoothKit) Android BLE蓝牙通信库
- Alex-Jerry [Android-BLE](https://github.com/Alex-Jerry/Android-BLE) AndroidBLE蓝牙框架，包括扫描、连接、设置通知、发送数据、读取、接收数据和OTA升级以及各种直观的回调，近乎一行代码植入项目，可扩展配置蓝牙相关操作。
- litesuits [android-lite-bluetoothLE](https://github.com/litesuits/android-lite-bluetoothLE) LiteBle 能让你稳定高效的完成蓝牙设备的查询、连接和读写等操作。它适合和低功耗的蓝牙设备通信，比如传感器，心率检测仪，智能穿戴设备等。

# 序列化：
- johncarl81 [parceler](https://github.com/johncarl81/parceler)Android Parcelables通过代码生成变得容易

# 加密：
- google [tink](https://github.com/google/tink) Tink是一个多语言，跨平台的库，提供安全，易于正确使用和难以滥用的加密API。

# 常用类：
- Xiaofei-it [Hermes](https://github.com/Xiaofei-it/Hermes) Hermes是一套新颖巧妙易用的Android进程间通信IPC框架。这个框架使得你不用了解IPC机制就可以进行进程间通信，像调用本地函数一样调用其他进程的函数
- elemers [HermesEventBus](https://github.com/elemers/HermesEventBus) HermesEventBus是一个基于EventBus的、能在进程间发送和接收event的库，在IPC或者插件开发中非常有用。

# 代码工具类：
- Blankj [AndroidUtilCode](https://github.com/Blankj/AndroidUtilCode) 各种工具类，你能想到的工具类，基本都有了这个库
- vondear [RxTools](https://github.com/vondear/RxTools) Android开发人员不得不收集的工具类集合 | 支付宝支付 | 微信支付（统一下单） | 微信分享 | Zip4j压缩（支持分卷压缩与加密） | 一键集成UCrop选择圆形头像 | 一键集成二维码和条形码的扫描与生成 | 常用Dialog | WebView的封装可播放视频 | 仿斗鱼滑动验证码 | Toast封装 | 震动 | GPS | Location定位 | 图片缩放 | Exif 图片添加地理位置信息（经纬度） | 蛛网等级 | 颜色选择器 | 
- greenrobot [essentials](https://github.com/greenrobot/essentials) greenrobot出品，工具类
- wenmingvs [AndroidProcess](https://github.com/wenmingvs/AndroidProcess) 判断App位于前台或者后台的6种方法
- Trinea [android-common](https://github.com/Trinea/android-common) 主要包括：缓存(图片缓存、预取缓存、网络缓存)、公共View(下拉及底部加载更多ListView、底部加载更多ScrollView、滑动一页Gallery)及Android常用工具类(网络、下载、Android资源操作、shell、文件、Json、随机数、Collection等等)。
- yangfuhai [afinal](https://github.com/yangfuhai/afinal) Afinal是一个android的ioc，orm框架，内置了四大模块功能：FinalAcitivity,FinalBitmap,FinalDb,FinalHttp。通过finalActivity，我们可以通过注解的方式进行绑定ui和事件。通过finalBitmap，我们可以方便的加载bitmap图片，而无需考虑oom等问题。通过finalDB模块，我们一行代码就可以对android的sqlite数据库进行增删改查。通过FinalHttp模块，我们可以以ajax形式请求http数据。
- yangfuhai [ASimpleCache](https://github.com/yangfuhai/ASimpleCache) 是一个为android制定的 轻量级的 开源缓存框架。轻量到只有一个java文件。可以缓存普通的字符串、JsonObject、JsonArray、Bitmap、Drawable、序列化的java对象，和 byte数据
- lfkdsk [JustWeTools](https://github.com/lfkdsk/JustWeTools) 画图工具，代码编辑，文件管理器，进度条/环形进度条，绘制时钟，以及常用工具
- litesuits [android-common](https://github.com/litesuits/android-common) 其中包括 shell 命令，静默安装，bitmap 处理，文件操作，加密存储器，计数器，均值器，吐司，日志，校验，提示，网络监测等基础功能。 以及一些 Base64、MD5、Hex、Byte、Number、Dialog、Filed、Class、Package、Telephone、Random 等工具类。

# 混淆辅助工具：
- Blankj [FreeProGuard](https://github.com/Blankj/FreeProGuard) 该库利用了 consumerProguardFiles 来传递 aar 中的防混淆配置到主工程中，所以依赖了该库后常用的主流三方库便不再需要开发者们手动配置了

# 日志Log辅助类：
- JakeWharton [timber](https://github.com/JakeWharton/timber)
- orhanobut [logger](https://github.com/orhanobut/logger)
- Blankj [ALog](https://github.com/Blankj/ALog)
- JakeWharton [hugo](https://github.com/JakeWharton/hugo) 调试版本的注释触发方法调用日志记录。

# 开发辅助工具类:
- facebook [stetho](https://github.com/facebook/stetho) 可以通过浏览器，查看app的DB和Sp的内容 ，并且有配合Okhttp的拦截器，可以查看网络请求（抓包）
- amitshekhariitbhu [Android-Debug-Database](https://github.com/amitshekhariitbhu/Android-Debug-Database) 可以通过浏览器，查看app的DB和Sp的内容，挺好用的（AS3.0好像已经可以在工具内看DB了）
- uber [NullAway](https://github.com/uber/NullAway) 一个有助于消除Java代码中的NullPointerException（NPE）的工具，具有较低的构建时间开销
- yogkin [LogUtil](https://github.com/yogkin/LogUtil) Android日志上传 使用服务通过HTTP或E-MAIL方式，压缩文件上传，支持加密
- JZ-Darkal [AndroidHttpCapture](https://github.com/JZ-Darkal/AndroidHttpCapture)AndroidHttpCapture网络诊断工具 是一款Android手机抓包软件 主要功能包括：手机端抓包、PING/DNS/TraceRoute诊断、抓包HAR数据上传分享。你也可以看成是Android版的"Fiddler"
- Kyson [AndroidGodEye](https://github.com/Kyson/AndroidGodEye) AndroidGodEye是一个可以在PC浏览器中实时监控Android数据指标（比如性能指标，但是不局限于性能）的工具，你可以通过wifi/usb连接手机和pc，通过pc浏览器实时监控手机性能。
- Godeyes [Godeyes](http://godeyes.duapp.com/index.jsp) 用来检测代码中可能出去的crash隐患
- google [guetzli](https://github.com/google/guetzli) 貌似是一个图片压缩的工具
- BolexLiu [AutoEx](https://github.com/BolexLiu/AutoEx) 帮助Android开发者，让项目在崩溃时从异常堆栈中，自动寻找Stack Overflow的回答。
- willowtreeapps [Hyperion-Android](https://github.com/willowtreeapps/Hyperion-Android) 适用于Android的应用程序调试和检测工具
- eleme [UETool](https://github.com/eleme/UETool) UETool 是一个各方人员（设计师、程序员、测试）都可以使用的UI调试工具。它可以作用于任何显示在屏幕上的 view，比如 Activity/Fragment/Dialog/PopupWindow 等等。

# 看起来很厉害的东东：
- alibaba [ARouter](https://github.com/alibaba/ARouter)一个安卓路由器中间件，帮助应用程序导航到活动和自定义服务。
- android-hacker [VirtualXposed](https://github.com/android-hacker/VirtualXposed) VirtualXposed 是基于VirtualApp 和 epic 在非ROOT环境下运行Xposed模块的实现（支持5.0~8.1)。
- asLody [VirtualApp](https://github.com/asLody/VirtualApp) VirtualApp在你的App内创建一个虚拟空间，你可以在虚拟空间内任意的安装、启动和卸载APK，这一切都与外部隔离，如同一个沙盒。

# 开源的整体项目:
- 1c7 [chinese-independent-developer](https://github.com/1c7/chinese-independent-developer) 中国独立开发者项目大集合
- pockethub [PocketHub](https://github.com/pockethub/PocketHub)
- fanturbo [Kanzhibo](https://github.com/fanturbo/Kanzhibo) 聚集了斗鱼，熊猫，全民，虎牙和战旗5个平台的直播小助手
- MindorksOpenSource [android-mvp-architecture](https://github.com/MindorksOpenSource/android-mvp-architecture) 这个库包含一个详细的示例应用程序，它使用Dagger2，GreenDao，RxJava2，FastAndroidNetworking和PlaceholderView实现MVP体系结构
- Horrarndoo [YiZhi](https://github.com/Horrarndoo/YiZhi)   MVP+RxJava2+Retrofit2+Glide+Rxbus，主要实现日报、新闻、干货、影视等资讯，个人项目
- lovetuzitong [MaterialBaiduImage](https://github.com/lovetuzitong/MaterialBaiduImage)基于MaterialDesign的百度图片浏览客户端
- lovetuzitong [android-GzLibrary](https://github.com/lovetuzitong/android-GzLibrary)这是广州图书馆的Android客户端实现项目
- yangchong211 [LifeHelper](https://github.com/yangchong211/LifeHelper) 综合案例训练，包含新闻，视频，图片，音乐，记事本等等模块。采用MVP+Rx+Retrofit+Desgin+Dagger2+阿里VLayout+腾讯X5等架构模式。很详细的开源项目，推荐
- lguipeng [Notes](https://github.com/lguipeng/Notes) 一个极简的笔记app
- daimajia [AnimeTaste](https://github.com/daimajia/AnimeTaste) 全球动画精选
- DuanJiaNing [Musicoco](https://github.com/DuanJiaNing/Musicoco) 【我的音乐-Musicoco】 音乐播放器，功能：通过耳机和通知栏快捷控制音乐播放、创建歌单、本地歌曲搜索、记忆播放、自动切换到夜间模式、定时停止播放、应用主题自定义以及播放界面风格选择等功能。
- ruzhan123 [awaker](https://github.com/ruzhan123/awaker) 地理杂志阅读类Android App，项目采用 LiveData + Room + RXJava2 + Retrofit + OKHttp + Material Design + Base + Glide 构建
- babylikebird [owspace](https://github.com/babylikebird/owspace) 高仿单读APP：owspace是基于MVP+Dagger2+Retrofit2.0+Rxjava的APP
- LRH1993[Eyepetizer-in-Kotlin](https://github.com/LRH1993/Eyepetizer-in-Kotlin) 使用Kotlin撸一款Eyepetizer，学习Kotlin语言
- miaoMiaoDaShi [YangYanNew](https://github.com/miaoMiaoDaShi/YangYanNew) kotlin+MVPArms版本

# Demo类:
- googlesamples [android-architecture-components](https://github.com/googlesamples/android-architecture-components) Android体系结构组件的示例。
- amitshekhariitbhu [RxJava2-Android-Samples](https://github.com/amitshekhariitbhu/RxJava2-Android-Samples) Rxjava2的demo
- reallin [Android_Mail](https://github.com/reallin/Android_Mail) 在android中发送邮件的demo（lib的jar包）

# 书籍类：
- justjavac [free-programming-books-zh_CN](https://github.com/justjavac/free-programming-books-zh_CN) 免费的编程中文书籍索引
- julycoding [The-Art-Of-Programming-By-July](https://github.com/julycoding/The-Art-Of-Programming-By-July) 编程之法：面试和算法心得   
- xitu [gold-miner](https://github.com/xitu/gold-miner) 掘金翻译计划，可能是世界最大最好的英译中技术社区，最懂读者和译者的翻译平台
- 1c7 [crash-course-computer-science-chinese](https://github.com/1c7/crash-course-computer-science-chinese) 计算机科学速成课
- tuvtran [project-based-learning](https://github.com/tuvtran/project-based-learning) 各类语音的学习资料
- EasyKotlin [EasyKotlin](https://github.com/EasyKotlin) kotlin资料

# 知识体系：
- guoxiaoxing [android-open-source-project-analysis](https://github.com/guoxiaoxing/android-open-source-project-analysis) android 源码分析
- lzyzsd [Awesome-RxJava](https://github.com/lzyzsd/Awesome-RxJava) RXjava中文的详细说明
- DONGChuan [GradleUserGuide](https://github.com/DONGChuan/GradleUserGuide) Gradle User Guide 中文版
- android-cn [android-open-project-analysis](https://github.com/android-cn/android-open-project-analysis/) 各种开源库原理解析
- francistao [LearningNotes](https://github.com/francistao/LearningNotes) 总结了大量的Android开发知识
- JsonChao [Awesome-Android-Interview](https://github.com/JsonChao/Awesome-Android-Interview) 从十几份顶级面试仓库和200多篇高质量面经中总结出一份全面而详尽的Android面试题集
- xfhy [notes](https://github.com/xfhy/notes) 非常详细的笔记
- simple-android-framework [android_design_patterns_analysis](https://github.com/simple-android-framework/android_design_patterns_analysis) 设计模式
- iluwatar [java-design-patterns](https://github.com/iluwatar/java-design-patterns) 设计模式

# 开发指南:
- codepath [android_guides](https://github.com/codepath/android_guides) Android开发者指南，这个作者下有很多android的demo
- futurice [android-best-practices](https://github.com/futurice/android-best-practices) 为Android开发做的和不该做的事的建议

# 刷题题库总结([LeetCode](https://leetcode.com/)和[LintCode ](http://www.lintcode.com/zh-cn/#))：
- awangdev [LintCode](https://github.com/awangdev/LintCode)
- Blankj [awesome-java-leetcode](https://github.com/Blankj/awesome-java-leetcode)
- scottszb1987 [LeetCodeInCSharp](https://github.com/scottszb1987/LeetCodeInCSharp) 
- [牛客网](https://www.nowcoder.com/)

# 打包：
- Tencent [VasDolly](https://github.com/Tencent/VasDolly) VasDolly是一种快速多渠道打包工具，同时支持基于V1签名和V2签名进行多渠道打包。

# 构建工具：
- fastlane [fastlane](https://github.com/fastlane/fastlane) 自动构建和发布您的iOS和Android应用程序的最简单方法

# 调试相关：
- hehonghui [mockito-doc-zh](https://github.com/hehonghui/mockito-doc-zh) 
- Tencent [GT](https://github.com/Tencent/GT) GT（随身调）是APP的随身调试平台，它是直接运行在手机上的“集成调试环境”

# ADB相关
- mzlogin [awesome-adb](https://github.com/mzlogin/awesome-adb) 中文详细的介绍了，adb命令

# 反编译及脱壳工具类：
- skylot [jadx](https://github.com/skylot/jadx) 反编译app的工具，只能说超牛
- DrizzleRisk [drizzleDumper](https://github.com/DrizzleRisk/drizzleDumper) 是一款基于内存搜索的Android脱壳工具。
- WrBug [dumpDex](https://github.com/WrBug/dumpDex) 一款Android脱壳工具，需要xposed支持

# 组件化开发：
- luckybilly[CC](https://github.com/luckybilly/CC) 使用简单但功能强大的安卓组件化框架,此组件化与业内的插件化（如：Atlas, RePlugin等）不是同一个概念

# androidStudio插件：
- githubwing [MVPHelper](https://github.com/githubwing/MVPHelper) 一款Intellj IDEA 和Android Studio 自动生成MVP模式所需接口以及实现类的插件。
- lingochamp [okcheck](https://github.com/lingochamp/okcheck) 差量扫描，自动集成Lint、KtLint、UnitTest、Checkstyle、Findbugs、Pmd 强大且灵活的Android Gradle插件

# Android相关有趣的东西
- Genymobile [scrcpy](https://github.com/Genymobile/scrcpy) 开源的投屏项目，[知乎上的使用介绍](https://zhuanlan.zhihu.com/p/34695060)
- 电脑控手机屏幕软件 [Total Control](http://www.sigma-rt.com/) 电脑能控制手机，投屏手机屏幕（做Android开发的应该都用过Vysor投屏，但是免费版画质太低了），但这个免费版的画质和响应速度都比Vysor要好，满足日常使用了

# 跨平台应用（android和ios）开发：
- flutter [flutter](https://github.com/flutter/flutter) google开发的，基于Dart 语言开发（从网上讨论，蛮多人看好这个的，说比react-native更优）
- facebook [react-native](https://github.com/facebook/react-native) facebook开发的，JS 结合 XML 开发
- alibaba [weex](https://github.com/alibaba/weex) 阿里巴巴开发
- NativeScript [NativeScript](https://github.com/NativeScript/NativeScript) NativeScript是一个用JavaScript构建真正的本地移动应用程序的开源框架。 使用网络技能，如Angular，FlexBox和CSS，并在iOS和Android上获取原生UI和性能。
- framework7io [framework7](https://github.com/framework7io/framework7) 全功能的HTML框架，用于构建iOS和Android应用程序
 
# flutter
- yubo725 [flutter-osc](https://github.com/yubo725/flutter-osc) 基于Google Flutter的开源中国客户端，支持Android和iOS。
- flutter [plugins](https://github.com/flutter/plugins) 官方插件
- OpenFlutter [Flutter-Notebook](https://github.com/OpenFlutter/Flutter-Notebook) 日更的FlutterDemo合集
 
# react-native
- xujinyang [react-native-android-guide](https://github.com/xujinyang/react-native-android-guide) 致力于帮助Android开发者转react-native开发。多点一个技能树，多一份天地。

# 在线API管理
- swagger-api [swagger-ui](https://github.com/swagger-api/swagger-ui) 
- thx [RAP](https://github.com/thx/RAP) Web接口管理工具，开源免费，接口自动化，MOCK数据自动生成，自动化测试，企业级管理。阿里妈妈MUX团队出品！阿里巴巴都在用！2代已出，下面这个
- thx [rap2-delos](https://github.com/thx/rap2-delos) 阿里妈妈前端团队出品的开源接口管理工具RAP第二代