# 腾讯云实时音视频终端组件 TRTC SDK

## SDK 下载
访问 Github 较慢的客户可以考虑使用国内下载地址： [DOWNLOAD](https://cloud.tencent.com/document/product/647/32689) 。

| 所属平台 | Zip下载 | Demo运行说明 | SDK集成指引 | API 列表 |
|:---------:| :--------:|:--------:| :--------:|:--------:|
| iOS | [下载](http://liteavsdk-1252463788.cosgz.myqcloud.com/TXLiteAVSDK_TRTC_iOS_latest.zip)| [DOC](https://cloud.tencent.com/document/product/647/32396)| [DOC](https://cloud.tencent.com/document/product/647/32173) | [API](https://cloud.tencent.com/document/product/647/32258) |
| Android | [下载](http://liteavsdk-1252463788.cosgz.myqcloud.com/TXLiteAVSDK_TRTC_Android_latest.zip)| [DOC](https://cloud.tencent.com/document/product/647/32166)| [DOC](https://cloud.tencent.com/document/product/647/32175) | [API](https://cloud.tencent.com/document/product/647/32267) |
| Win(C++)| [下载](http://liteavsdk-1252463788.cosgz.myqcloud.com/TXLiteAVSDK_TRTC_Win_latest.zip)| [DOC](https://cloud.tencent.com/document/product/647/32397)| [DOC](https://cloud.tencent.com/document/product/647/32178) | [API](https://cloud.tencent.com/document/product/647/32268) |
| Win(C#)| [下载](http://liteavsdk-1252463788.cosgz.myqcloud.com/TXLiteAVSDK_TRTC_Win_latest.zip)| [DOC](https://cloud.tencent.com/document/product/647/32397)| [DOC](https://cloud.tencent.com/document/product/647/32178) | [API](https://cloud.tencent.com/document/product/647/36776) |
| Mac| [下载](http://liteavsdk-1252463788.cosgz.myqcloud.com/TXLiteAVSDK_TRTC_Mac_latest.tar.bz2)| [DOC](https://cloud.tencent.com/document/product/647/32396)| [DOC](https://cloud.tencent.com/document/product/647/32176) |[API](https://cloud.tencent.com/document/product/647/32258) |
| Web | [下载](https://liteavsdk-1252463788.cosgz.myqcloud.com/H5_latest.zip)| [DOC](https://cloud.tencent.com/document/product/647/32398)| [DOC](https://cloud.tencent.com/document/product/647/16863) |[API](https://cloud.tencent.com/document/product/647/17249) |
| Electron | [下载](http://liteavsdk-1252463788.cosgz.myqcloud.com/TXLiteAVSDK_TRTC_Electron_latest.zip) | [DOC](https://cloud.tencent.com/document/product/647/38548) | [DOC](https://cloud.tencent.com/document/product/647/38549) |[API](https://cloud.tencent.com/document/product/647/38551) |
| 微信小程序 | [下载](http://liteavsdk-1252463788.cosgz.myqcloud.com/TRTC_WXMini_latest.zip) | [DOC](https://cloud.tencent.com/document/product/647/32399) | [DOC](https://cloud.tencent.com/document/product/647/32183) |[API](https://cloud.tencent.com/document/product/647/17018) |

## Version 8.2 @ 2020.12.23

**欢迎加入**

团队技术氛围浓厚，培训体系完善，产品线多样，有经验丰富的“老司机”手把手帮你入门音视频技术。<br>
北京、上海、深圳、广州均有岗位，如果您对音视频技术感兴趣，欢迎加入我们 [腾讯云 TRTC 研发团队](https://careers.tencent.com/jobdesc.html?postId=1297858141983088640) 。

**功能新增**
iOS & Android 新增回调混合本地采集与所有播放的音频数据，本地音频录制更方便啦
Android 本地渲染支持 TextureView，本地画面也可以应用动画效果
Android 自定义渲染支持 RGBA 格式
Windows 支持视频截图能力
Windows 窗口分享支持设置白名单，仅分享目标窗口与白名单窗口。窗口分享超灵活
Mac 自定义渲染支持截图

**质量优化**
Android 在线直播画质优化，直播更加美美哒
windows 优化回声消除算法，降低漏回声的概率

**问题修复**
iOS 修复 VODPlayer 和 TRTC 同时使用时，偶现音频播放异常的问题
Android 修复自定义美颜处理本地黑屏的问题
Windows 修复偶现进程无法退出的问题
各平台修复近期反馈的严重bug，进一步提升稳定性


更早期的版本更新历史请点击  [More](https://cloud.tencent.com/document/product/647/46907)...

## Demo 体验地址

### iOS
> [APPStore 体验地址](https://itunes.apple.com/cn/app/id1400663224?mt=8)
![](https://main.qcloudimg.com/raw/fa84e7c632b74483e9dc91dc04a8255e.jpg)

### Android
> [应用宝体验地址](https://android.myapp.com/myapp/detail.htm?apkName=com.tencent.trtc&ADTAG=mobile)
![](https://main.qcloudimg.com/raw/913eecbf69577de4e27d9bfe45acf80e.jpg)

### Mac OS
> [下载后解压体验](http://trtc-1252463788.cosgz.myqcloud.com/TXLiteAVSDK_Mac_Demo.tar.bz2)
![](https://main.qcloudimg.com/raw/8d146afb3b2dd07d5b5f1ca4432a9411.jpg)

### Windows
> [下载后安装体验](http://trtc-1252463788.cosgz.myqcloud.com/TXLiteAVSDK_Win_Demo.exe)
![](https://main.qcloudimg.com/raw/00ec3ebc86902044c51a5487c18dcd0c.jpg)

### 微信小程序
>![](https://main.qcloudimg.com/raw/81662cce932b2500addac28baf6a83b3.jpg)

### Web 网页
> [Chrome 打开体验](https://trtc-1252463788.file.myqcloud.com/web/demo/official-demo/index.html)
![](https://main.qcloudimg.com/raw/56e2bbc928a11bac85e5b78ac171b3bc.jpg)


