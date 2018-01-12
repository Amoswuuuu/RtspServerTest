# XRtspServer


## Rtsp服务器示例代码


## 示例代码：

	package main

	import "nqc.cn/XRtspServer/stream_server"

	func main() {

		ser := stream_server.NewStreamServer(":8554")

		ser.Run()

	}


## 目前已实现功能：

1、RTSP接收推流

2、RTSP直播

3、后台管理页面的API接口


## 下一步开发目标：


1、后台配置管理页面

2、视频流切片存储功能

3、HLS转发功能

4、RTMP推流功能

5、RTMP直播功能

6、MP4视频直播

## 欢迎有兴趣爱好者一起加盟开发

联系方式：24802117（QQ）

邮箱：24802117@qq.com



