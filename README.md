# 简介
Android studio 项目，针对于mt6771 联发科的设备，有系统签名设置，当然项目也可以不是用系统签名，程序本身实现了对Android 扬声器的录制，以及Android屏幕的录制，并将录制的 内容 转码为h264+aac
并封装成flv格式，发送出去，
发送的方式为rtmp协议，

另外一层是涉及到指令，键盘鼠标事件的控制， 需要有服务器来处理该事件。


程序的最终结果希望有网页端来远程控制手机。