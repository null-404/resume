#iOS开发工程师
##联系方式
- 手机：
- Email：timelessg@hotmail.com
- Wechat：

##个人信息
- 郭锐/男/1992
- 硕士/非全日制/武汉大学/软件工程&本科/齐鲁师范学院/计算机科学与技术
- 工作年限：3年
- Github：http://github.com/timelessg
- Blog：http://www.jianshu.com/u/151ba12c22e5

##开源项目
- [TLStoryCamera](https://github.com/timelessg/TLStoryCamera)：一套短视频拍摄框架，参照instagram，使用Swift开发，支持拍摄视频照片、贴图贴字涂鸦、滤镜选择、美颜等。目前拥有300+Start，40+Fork。
- [TLMessage](https://github.com/timelessg/TLMessage)：一套即时通讯框架，支持文字/图片/语音/地理位置消息收发，高可扩展性。
- [TLSegmentedControl](https://github.com/timelessg/TLSegmentedControl)：一套分页控制框架，参照Weibo，支持CocoaPods。

##工作经历
###浙江齐聚科技有限公司北京分公司 呱呱事业部（2017.3 - 2018.3）
####呱呱直播
1、配合公司BI平台开发了一套App Analytics Framework，主要负责调研主流统计SDK实现、框架总体设计、核心代码编写以及开发文档编写。支持基础信息统计、自定义事件统计、页面访问统计。基于AOP，配合runtime实现非侵入式统计，有效降低与业务代码耦合，同时还支持统计数据持久化、上报时机控制、网络状态监听等特性。上线后运行稳定，实现了三方数据统计平台的大部分功能。

2、负责直播间小游戏开发，使用SpriteKit框架完成了两个2D小游戏，期间遇到了某些特定机型掉帧严重，对此查阅Stack Overflow与Apple Developer Documentation等资料，优化了贴图加载以及动画展示方式，很好的解决了以上问题。

3、主导项目重构工作，剥离不再使用的代码、静态库与资源文件，整理优化代码，修复了多处memory leak，有效降低了代码耦合，提高了代码质量。优化后编译时间从2-3min降低至40-50s，warning从近300个减少到个位数，平均内存占用从120M降低至95MB，打包体积减少近50%。

4、承担团队中部分code review工作。

###北京聚星在线科技有限公司（2016.5 - 2017.1）
####聚星直播
1、设计开发了一套高性能的礼物弹幕框架，利用NSOperation队列控制礼物弹幕优先级与并发，参考UITableView的注册复用机制，实现了礼物与弹幕View的复用。优化后的礼物动画稳定在50-60fps，CPU与Memory占用率峰值较之前版本分别降低15%，20%。在老版本iPhone手机上亦可以流畅运行，基本没有再出现卡顿掉帧的情况。新版本上线后，获得了用户与主播的一致好评。

2、负责直播间K歌功能开发，期间遇到主播反馈使用耳机时伴奏无法收录，对此研究了CoreAudio以及官方文档，将麦克风采集的AudioBuffer与混音数据根据一定算法进行加权求和，附带还实现了音效混音，变声器等特色功能，早于七牛直播SDK解决了以上问题。

3、研究直播美颜，查阅OpenGL ES与GPUImage相关资料，调研主流美颜实现方式，最终使用双波、亮度以及饱和度滤镜组，并尝试调整参数平衡性能与观感。最终实现了比较不错的效果，优于大部分竞品直播美颜滤镜。



###北京盛夏网络科技有限公司（2015.6-2016.5）
####演员圈
1、在2.x版本全面重构，基于MVVM+ReactiveCocoa，设计了一套总线VM+分线VM架构，以及配套的响应式网络层与持久化层，很好的拆分了Controller中的业务逻辑，引入了Route进一步实现模块化，实现了UI与业务逻辑的解耦合，单元测试覆盖率达30%。根据Bugly统计，新版本上线后崩溃率控制在1%内，较1.x版本降低25%，获得了用户一致好评。

2、设计开发了一套[表单框架](https://www.jianshu.com/p/c137dafe8f90)，利用runtime机制动态解析配置文件，通过服务端下发配置文件无需发版即可更新，实现了表单的展示、编辑、缓存、上传等功能。框架逻辑清晰，耦合度低，高可复用。协助Android端同事移植框架实现。

##技能清单
- 熟练使用ObjC、Swift编写高质量iOS/OSX代码。
- 熟悉常用设计模式，掌握函数式、响应式编程思想，可以熟练使用RAC、RxSwift框架。
- 有PHP、MySQL、Linux、Shell等开发经验，能够独立开发前后端应用。
- 英文阅读水平良好，CET4，基本无障碍阅读Apple Developer Documentation、Stack Overflow、Objc.io等技术站点。
