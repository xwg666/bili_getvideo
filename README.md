#直接需要下载器的，可以用现成的：
下载地址：[https://github.com/xwg666/bili_getvideo/blob/master

[![image](https://github.com/xwg666/bili_getvideo/assets/95574231/4248e4e8-9664-40b3-bd91-363bc9c4345f)](https://github.com/xwg666/bili_getvideo/tree/master)

# bili_getvideo
爬取B站【首页，游戏，动画，鬼畜，生活，娱乐】板块及游研社，V9AG博主的视频，另外还可以爬最右，云段子网站
请求方式：
http://127.0.0.1:6666/one_bili   表示单个视频下载，可自行判断

http://127.0.0.1:6666/all_bili   下载【首页，游戏，动画，鬼畜，生活，娱乐】板块

http://127.0.0.1:6666/zuiyou     下载最右，默认下拉页面10次在爬取，可自行定义页数：http://127.0.0.1:6666/zuiyou?page=15

http://127.0.0.1:6666/A9VG       下载A9VG博主的视频，默认1页，可自定义页数：http://127.0.0.1:6666/A9VG?page=2

http://127.0.0.1:6666/youyanshe  下载游研社的视频，默认1页，未定义参数，因更新太慢

http://127.0.0.1:6666/yunduanzi  下载云段子，默认30个，可自定义参数：http://127.0.0.1:6666/yunduanzi?n=50

http://127.0.0.1:6666/refuse     刷新页面，需要安装nginx。

http://127.0.0.1:6666/upload     上传到数据库。

PS:需要下载BBDown,ffmpeg来合并B站视频：

下载链接：（直接解压到D盘即可，里面包含BBDwon和ffmpeg）
链接：https://pan.baidu.com/s/1Bao_Q2SYhXwhq4vX9d6oSQ?pwd=1234
提取码：1234

![image](https://github.com/xwg666/bili_getvideo/assets/95574231/a0649ff3-ea8c-4a2b-8cb6-2a77eb6b92da)


请求示例：
![image](https://github.com/xwg666/bili_getvideo/assets/95574231/f0fffe4e-7ea3-4e07-8b54-c9ad3a1808d9)
