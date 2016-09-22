### android debug的一些方法记录
1. 获取java stack `add shell kill -3 <pid>`
2. 获取native stack.Recent versions of Android include the native stack dumps automatically. You can generate a native stack dump of all threads in a process on a rooted device with `adb shell debuggerd -b <pid>` (assuming your device is recent enough to have that feature)
3. 关于死锁.见下面文章
[http://blog.csdn.net/oujunli/article/details/9102101][1]

[1]:	http://blog.csdn.net/oujunli/article/details/9102101