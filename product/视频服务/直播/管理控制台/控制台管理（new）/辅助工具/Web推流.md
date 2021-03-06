## 操作场景
通过 Web 推流，快速生成推流地址，并实现在线推流功能。

## 前提条件
- 已登录 [云直播控制台](https://console.cloud.tencent.com/live)。
- 已添加 [推流域名](https://cloud.tencent.com/document/product/267/20381)。
- 您的设备已安装摄像头，并浏览器支持 Flash 插件调用摄像头权限。

## 操作步骤
1. 登录云直播控制台，选择【辅助工具】>[【Web推流】](https://console.cloud.tencent.com/live/addrgenerator/addrgenerator)。
2. 在 Web 端推流的页面进行以下设置：
	- 选择推流域名。
	- 填写自定义的流名称 StreamName，例如：`test`。
	- 选择过期时间，例如：`2019-10-30 23:59:59`。
	- 编辑 AppName，用于区分同一个域名下多个 App 的地址路径，默认值为 live。
3. 单击【开始推流】，授权允许调用摄像头，即可开始推流。
![](https://main.qcloudimg.com/raw/eba0fea9864f2379332165c27fc911bb.png)
4. 若您在【域名管理】中已添加播放域名，即可在下方查看对应生成的播放地址。其中，播放地址由以下4部分组成：
 ![img](https://main.qcloudimg.com/raw/714f5dba41877e5c2900ec73472c0326.png)
支持 RTMP、FLV 和 HLS 协议，可以单击播放地址后的二维码，通过 [精简版 Demo](https://cloud.tencent.com/document/product/454/6555#.E7.B2.BE.E7.AE.80.E7.89.88-demo) 扫码查看播放地址：
![](https://main.qcloudimg.com/raw/fa0e65dfabf31a889aeec64a16de7f34.png)
