# OBS直播背景装饰页

![bg4obs2](https://blog.siitake.cn/usr/uploads/2022/04/4240259048.svg)

* 新增动态背景图
* ~新增渐变背景色~ (已砍)
* 新增圆形头像区域
* ~新增视频与头像区域绿幕抠像通道~ (已砍，使用mask替代)
* 修改绿幕通道为mask全透明通道，可直接使用，不用再抠像
* 修改为纯前端执行，纯静态web服务器即可上线
* 新增可视化配置页面，实时预览效果，不再需要要手动修改url参数
* 其他不明显的修改

以上内容(建议使用桌面浏览器)访问网址体验：[https://siitake.cn/tools/bililive/game/init.html](https://siitake.cn/tools/bililive/game/init.html)

OBS(或直播姬等)的使用方式没有什么变化，复制配置页面生成的网址添加为“来源”，尺寸设置为 `1920*1080`即可，因为添加了透明通道，主画面和头像可置于下层。
