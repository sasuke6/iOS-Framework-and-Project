# iOS-Framework-and-Project
### 目录
- [UI](#UI)
    - [文本](#文本)
    - [菜单](#菜单)
    - [过场](#过场)
    - [键盘处理](#键盘处理)
    - [AutoLayout](#AutoLayout)
    - [UITableView](#UITableView)
    - [UIScrollView](#UIScrollView)
    - [侧滑](#侧滑)
    - [下拉刷新](#下拉刷新)
    - [整体UI](#整体UI)
    - [其他UI](#其他UI)


- [网络](#网络)

- [Model](#Model)

- [动画](#动画)
  - [框架](#框架)
  - [进度](#进度)



- [集大成](#集大成)

- [音视频处理](#音视频处理)

- [摄影照片](#摄影照片)

- [聊天](#聊天)

- [数据存储](#数据存储)

- [单元测试](#单元测试)

- [第三方接入](#第三方接入)

- [Xcode插件](#Xcode插件)

- [模式](#模式)

- [开源项目](#开源项目)

- [其他](#其他)



#### UI

##### 文本
* [JVFloatLabeledTextField](https://github.com/jverdi/JVFloatLabeledTextField) 编辑文本`UITextFiled`和`UITextView`时会有动画效果
* [TTTAttributedLabel](https://github.com/TTTAttributedLabel/TTTAttributedLabel) 高度可定制化的UILabel
* [SlackTextViewController](https://github.com/slackhq/SlackTextViewController) 自动处理输入框的库
* [DTCoreText](https://github.com/Cocoanetics/DTCoreText) 允许Text使用HTML的框架

##### 菜单
* [AwesomeMenu](https://github.com/levey/AwesomeMenu) 使用了CoreAnimation的菜单，效果不错
* [QBPopupMenu](https://github.com/questbeat/QBPopupMenu) 弹出式菜单库
* [NirKxMenu](https://github.com/zpz1237/NirKxMenu) 类似微信的弹出菜单
* [KTDropdownMenuView](https://github.com/tujinqiu/KTDropdownMenuView) 类似新浪微博的下拉菜单

##### 过场
* [urlmanager](https://github.com/gaosboy/urlmanager) URL Scheme为基础的NavigationController，让ViewController实现松耦合，不依赖
* [SVProgressHUD](https://github.com/SVProgressHUD/SVProgressHUD) 著名的动画提示库
* [FDFullscreenPopGesture](https://github.com/forkingdog/FDFullscreenPopGesture) 全屏手势框架
* [MBProgressHUD](https://github.com/jdg/MBProgressHUD) 最多人用的提示库

##### 键盘处理
* [IQKeyboardManager](https://github.com/hackiftekhar/IQKeyboardManager) 自从用了它处理键盘事件，腰不疼，腿也不酸了
* [TPKeyboardAvoiding](https://github.com/michaeltyson/TPKeyboardAvoiding) xib的键盘处理

##### AutoLayout
* [Masonry](https://github.com/SnapKit/Masonry) 最著名的AutoLayout库
* [HandyAutoLayout](https://github.com/casatwy/HandyAutoLayout) 系统自身的AutoLayout的封装
* [PureLayout](https://github.com/PureLayout/PureLayout) 另一个AutoLayout框架
* [SnapKit](https://github.com/SnapKit/SnapKit) swift版本的Masonry，事实意义上的swift适配库。
* [Cartography](https://github.com/robb/Cartography) Cartography 是用来声明 Swift 中的 Auto Layout，无需输入任何 stringly 就可设置自己 Auto Layout 的约束声明
* [Neno.swift](https://github.com/mamaral/Neon) 功能强大的 UI 布局神器。
* [EasyPeasy.swift](https://github.com/nakiostudio/EasyPeasy) 编程方式自动布局框架库。

##### UITableView
* [CYLTableViewPlaceHolder](https://github.com/ChenYilong/CYLTableViewPlaceHolder) 一行代码完成“空TableView占位视图”管理
* [UITableView-FDTemplateLayoutCell](https://github.com/forkingdog/UITableView-FDTemplateLayoutCell) 自动计算UITableViewCell的高度，减少很多烦恼
* [FXForms](https://github.com/nicklockwood/FXForms) 一个快速建立表格的库，大量减少代码
* [XLForm](https://github.com/xmartlabs/XLForm) 又一个快速简历表格的库


##### UIScrollView
* [LTInfiniteScrollView](https://github.com/ltebean/LTInfiniteScrollView) 基于UIScorllView的框架，动画效果酷炫
* [ScrollviewParallax](https://github.com/BillCarsonFr/ScrollviewParallax) 顶部具有伸缩效果ScollView的封装库
* [HYBLoopScrollView](https://github.com/CoderJackyHuang/HYBLoopScrollView) App中的广告轮播图组件
* [Onboard](https://github.com/mamaral/Onboard) 非常酷炫的滑动第三方库，同时支持Objective-C和Swift
* [CSStickyHeaderFlowLayout](https://github.com/jamztang/CSStickyHeaderFlowLayout) Header处理的第三方库
* [XWPageViewController](https://github.com/shnuzxw/XWPageViewController) 分页显示库，UIControl
* [XBScrollPageController](https://github.com/changjianfeishui/XBScrollPageController) iOS分页控制器,只需传入标题数组和控制器类名数组即可
* [CorePagesView](https://github.com/CharlinFeng/CorePagesView) 列表滚动视图，性能王者！

##### 侧滑
* [ECSlidingViewController](https://github.com/ECSlidingViewController/ECSlidingViewController) 界面侧滑的封装库，简单好用，定制性强
* [MMDrawerController](https://github.com/mutualmobile/MMDrawerController) 又一个左侧滑框架，可以在UINavigation中使用
* [SWTableViewCell](https://github.com/CEWendel/SWTableViewCell) cell右滑动的库
* [RESideMenu](https://github.com/romaonthego/RESideMenu) QQ在以前版本的侧滑模式

##### 下拉刷新
* [sspulltorefresh](https://github.com/soffes/sspulltorefresh) 高度可定制化的下拉刷新框架
* [EGOTableViewPullRefresh](https://github.com/enormego/EGOTableViewPullRefresh) stars数比较多的下拉刷新框架
* [MJRefresh](https://github.com/CoderMJLee/MJRefresh) 最著名下拉刷新框架

##### 整体UI
* [SSToolkit](https://github.com/soffes/sstoolkit) 包含一整套UI和Category的框架
* [Atlas-iOS](https://github.com/layerhq/Atlas-iOS) UI Interface Design库
* [FlatUIKit](https://github.com/Grouper/FlatUIKit) 一整套UI组件

##### 其他UI
* [RKNotificationHub](https://github.com/cwRichardKim/RKNotificationHub) 红点处理的框架，好用
* [TLYShyNavBar](https://github.com/telly/TLYShyNavBar) UINavigation动效优秀第三方框架
* [Chameleon](https://github.com/ViccAlexander/Chameleon) 颜色处理库，OC&Swift同时支持
* [TSMessages](https://github.com/KrauseFx/TSMessages) iOS上的自定义消息UI
* [KMNavigationBarTransition](https://github.com/MoZhouqi/KMNavigationBarTransition) 维持Navigation一致颜色
* [DZNEmptyDataSet](https://github.com/dzenbot/DZNEmptyDataSet) 空白View页面的提示，常用
* [FDStackView](https://github.com/forkingdog/FDStackView) 使UIStackView支持到iOS6
* [XHSetting](https://github.com/JackTeam/XHSetting) 设置界面的快速部署

#### 网络
* [AFNetworking](https://github.com/AFNetworking/AFNetworking) App必备框架
* [RNCachingURLProtocol](https://github.com/rnapier/RNCachingURLProtocol) 封装HTTP协议的框架
* [PonyDebugger](https://github.com/square/PonyDebugger) 一个优秀的网络连接debug库
* [OHHTTPStubs](https://github.com/AliSoftware/OHHTTPStubs) HTTP验证库，同时支持Objective-C和Swift
* [UICKeyChainStore](https://github.com/kishikawakatsumi/UICKeyChainStore) HTTPS验证的第三方库，简单实用
* [Valet](https://github.com/square/Valet) keychain验证的库
* [GroundControl](https://github.com/mattt/GroundControl) App远程控制框架
* [SocketRocket](https://github.com/square/SocketRocket) WebSocket框架
* [SVWebViewController](https://github.com/TransitApp/SVWebViewController) 简单的内置Web浏览器
* [DeepLinkKit](https://github.com/usebutton/DeepLinkKit) 处理多URL的库
* [CTJSBridge](https://github.com/casatwy/CTJSBridge) javascript与iOS混编的框架
* [WHCNetWorkKit](https://github.com/netyouli/WHCNetWorkKit) 目前封装最好使用最简单的文件下载(支持后台下载)iOS网络开源库 
* [WebViewJavascriptBridge](https://github.com/marcuswestin/WebViewJavascriptBridge) WebView与JavaScript交互的框架，比较多人使用
* [SSKeychain](https://github.com/soffes/SSKeychain)  另一个链接验证库
* [AFOAuth2Manager](https://github.com/AFNetworking/AFOAuth2Manager) OAuth验证框架
* [NetworkEye](https://github.com/coderyi/NetworkEye) App内的网络调试框架
* [Reachability](https://github.com/tonymillion/Reachability) 手机网络检测库，常用
* [CocoaAsyncSocket](https://github.com/robbiehanson/CocoaAsyncSocket) Socket的第三方框架，最好用
* [JSPatch](https://github.com/bang590/JSPatch) JavaScript交互的库
* [YTKNetwork](https://github.com/yuantiku/YTKNetwork) 对AFNetworking的二次封装

#### Model
* [RestKit](https://github.com/RestKit/RestKit) 将网络处理
和ORM结合的库
* [Underscore](https://github.com/robb/Underscore.m) OC数据结构转换库
* [DDModel](https://github.com/openboy2012/DDModel) 一个框架包括HTTP、JSON、ORM处理
* [CTPersistance](https://github.com/casatwy/CTPersistance) Model Layer层处理框架
* [FastEasyMapping](https://github.com/Yalantis/FastEasyMapping) 快速转换Model库
* [MJExtension](https://github.com/CoderMJLee/MJExtension) 非常强大的转换框架
* [Mantle](https://github.com/Mantle/Mantle) Github出品的模型转换库


#### 动画
##### 框架
* [JazzHands](https://github.com/IFTTT/JazzHands) UIKit动画框架，可以通过手势，KVO，ReactiveCocoa进行控制
* [Canvas](https://github.com/CanvasPod/Canvas) 无需太多的代码即可制作动画，超级好用的动画库
* [Shimmer](https://github.com/facebook/Shimmer) Facebook开源的动画框架，让你的文字炫起来
* [A-GUIDE-TO-iOS-ANIMATION](https://github.com/KittenYang/A-GUIDE-TO-iOS-ANIMATION) iOS动画指南，Demo值得参考
* [iCarousel](https://github.com/nicklockwood/iCarousel) 强大的旋转场库
* [ARAnimation](https://github.com/AugustRush/ARAnimation) 强大的动画库，满足很多需求

##### 进度
* [DACircularProgress](https://github.com/danielamitay/DACircularProgress) Progress动画，环形进度
* [M13ProgressSuite](https://github.com/Marxon13/M13ProgressSuite) 进度条动画库
* [WaveLoadingView](https://github.com/liuzhiyi1992/WaveLoadingView) 波形动画的进度库
* [Waver](https://github.com/kevinzhow/Waver) Kevin的波形库
* [PNChart](https://github.com/kevinzhow/PNChart) 图表库的库，Kevin大神

#### 集大成
* [YYKit](https://github.com/ibireme/YYKit) YYKit是一组庞大、功能丰富的iOS组件，包含YYModel、YYWebImage等等 
* [FLEX](https://github.com/Flipboard/FLEX) 集Debug和体验于一身的框架
* [tapkulibrary](https://github.com/devinross/tapkulibrary)  

#### 音视频处理
* [prankPro](https://github.com/huijimuhe/prankPro) 一个短视频的开源工程，值得参考
* [EZAudio](https://github.com/syedhali/EZAudio) 音频处理库，适用iOS和OS X


#### 摄影图片处理
* [SDWebImage](https://github.com/rs/SDWebImage) 图片展示下载的框架
* [FastImageCache](https://github.com/path/FastImageCache) 图片下载的缓存库
* [GPUImage](https://github.com/BradLarson/GPUImage) 强大的第三方框架处理图片
* [FLAnimatedImage](https://github.com/Flipboard/FLAnimatedImage) Gif引擎
* [QRCodeReaderViewController](https://github.com/yannickl/QRCodeReaderViewController) 二维码扫描框架
* [JTSImageViewController](https://github.com/jaredsinclair/JTSImageViewController) 图层模糊的库，前清晰后模糊
* [CTAssetsPickerController](https://github.com/chiunam/CTAssetsPickerController) 图片多选框架

#### 聊天
* [MessageDisplayKit](https://github.com/xhzengAIB/MessageDisplayKit) 一个类似微信App的IM应用，拥有发送文字、图片、语音、视频、地理位置消息，管理本地通信录、分享朋友圈、漂流交友、摇一摇和更多有趣的功能。
* [SMSNinja](https://github.com/iosre/SMSNinja) SMS, MMS, iMessages, phone calls and FaceTime on stock Phone and Message Apps
* [JSQMessagesViewController](https://github.com/jessesquires/JSQMessagesViewController) 著名的聊天框架
* [XMPPFramework](https://github.com/robbiehanson/XMPPFramework) XMPP聊天框架，你懂的

#### 数据存储
* [fmdb](https://github.com/ccgus/fmdb) 封装SQLite的库，最多人用
* [YapDatabase](https://github.com/yapstudios/YapDatabase) 数据存储库
* [realm-cocoa](https://github.com/realm/realm-cocoa) 代替CoreData和SQLite的数据库
* [MagicalRecord](https://github.com/magicalpanda/MagicalRecord) 代替CoreData另一个方案
* [MTLFMDBAdapter](https://github.com/tanis2000/MTLFMDBAdapter) FMDB转换库
* [GVUserDefaults](https://github.com/gangverk/GVUserDefaults) NSUserDefaults存储的框架

#### 单元测试
* [Kiwi](https://github.com/kiwi-bdd/Kiwi) Kiwi,BDD测试框架
* [ios-snapshot-test-case](https://github.com/facebook/ios-snapshot-test-case) Facebook开源的单元测试框架
* [KIF](https://github.com/kif-framework/KIF) 另一个单元测试框架，同时支持OC和Swift
* [specta](https://github.com/specta/specta) 一款轻量级的测试框架，TDD/BDD最佳实践
* [gh-unit](https://github.com/gh-unit/gh-unit) 同时支持iOS和OS X的测试框架
* [NSLogger](https://github.com/fpillet/NSLogger) log的信息更为全面
* [CocoaLumberjack](https://github.com/CocoaLumberjack/CocoaLumberjack) 另一个log库

#### 第三方接入
* [openshare](https://github.com/100apps/openshare) 不用官方SDK，利用社交软件移动客户端(微信/QQ/微博/人人/支付宝)分享/登录/支付

#### Xcode插件
* [Dash Plugin for Xcode](https://github.com/omz/Dash-Plugin-for-Xcode) 文档查询工具Dash的Xcode插件
* [Alcatraz](https://github.com/alcatraz/Alcatraz) 界面图形安装Xcod插件
* [Crayons](https://github.com/Sephiroth87/Crayons) Xcode调色板增强插件
* [injectionforxcode](https://github.com/johnno1962/injectionforxcode) 无需编译即可调整UI
* [ZLGotoSandboxPlugin](https://github.com/MakeZL/ZLGotoSandboxPlugin) 直接进入模拟器的沙盒
* [RTImageAssets](https://github.com/rickytan/RTImageAssets) 用来生成 @3x 的图片资源对应的 @2x 和 @1x 版本
* [XAlign](https://github.com/qfish/XAlign) 代码对齐插件
* [ColorSense-for-Xcode](https://github.com/omz/ColorSense-for-Xcode) Color显示插件
* [VVDocumenter-Xcode](https://github.com/onevcat/VVDocumenter-Xcode) 注释插件

#### 模式
* [RxSwift](https://github.com/ReactiveX/RxSwift) 实践MVVM模式的框架，非常牛逼（Swift）
* [Aspects](https://github.com/steipete/Aspects) AOP实践的第三方框架
* [objc-singleton](https://github.com/oc-ios/objc-singleton) 单例模式参考资料
* [ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa) Reactive库，不多说

#### 开源项目
* [react-native-gitfeed](https://github.com/xiekw2010/react-native-gitfeed) React-Native开发成的Github客户端，值得学习
* [Yep](https://github.com/CatchChat/Yep) 周大神的开源作品，赶快趴下来学习（Swift）
* [SoundCloudSwift](https://github.com/pepibumur/SoundCloudSwift) 号称音频处理的兵工厂，强大，满足任何需求。(Swift)
* [cannonball-ios](https://github.com/twitterdev/cannonball-ios) cannonball客户端
* [LXZEALER](https://github.com/LonelyTown/LXZEALER) 模仿Zealer客户端
* [iosarticles](https://github.com/gaosboy/iosarticles) iOS开发者专题
* [WNXHuntForCity](https://github.com/ZhongTaoTian/WNXHuntForCity) iOS高仿城觅项目
* [phphub-ios](https://github.com/Aufree/phphub-ios) PHPHub的iOS客户端
* [v2ex](https://github.com/singro/v2ex) v2ex的客户端




#### 其他
* [KVOController](https://github.com/facebook/KVOController) Facebook的开源框架，使用KVO可以借鉴
* [appirater](https://github.com/arashpayan/appirater) 提醒用户为自己的App打分的库
*  [ZipArchive](https://github.com/ZipArchive/ZipArchive) iOS和Mac都可使用的解压库
* [Tweaks](https://github.com/facebook/Tweaks) 同样是Facebook开源的库，快速原型开发工具，可以帮助 iOS 开发者在应用上实时调整参数并测试效果的框架
* [nimbus](https://github.com/jverkoey/nimbus) TableViewController的另一种方式
* [dot-vimrc](https://github.com/humiaozuzu/dot-vimrc) Vim配置文件，个人正在使用，好用酷炫，媲美IDE
* [spf13-vim](https://github.com/spf13/spf13-vim) 目前比价受欢迎的Vim配置
* [KZPlayground](https://github.com/krzysztofzablocki/KZPlayground) 同时支持OC和Swift的Playground 
* [EKAlgorithms](https://github.com/EvgenyKarkan/EKAlgorithms) OC算法实现案例
* [ObjectiveSugar](https://github.com/supermarin/ObjectiveSugar) OC语法糖库
* [MMMarkdown](https://github.com/mdiep/MMMarkdown) 将Markdown转换HTML
* [Reader](https://github.com/vfr/Reader) PDF阅读器
* [DateTools](https://github.com/MatthewYork/DateTools) 时间工具框架

