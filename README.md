# The-chat-room
  
使用Python3编写的聊天室

功能简介:<br>
 群聊功能: 一个聊天窗口发消息全部都能收到<br>
 私聊功能: 只能给特定的IP和端口或者用户名发消息<br>
 查看在线用户功能: 可以查看当前在线用户<br>
 上传下载功能: 用户可以从文件服务器上传下载文件<br>
 发送表情功能<br>
 发送图片功能<br>

步骤:<br>
 版本1-7 文字聊天室<br>
 版本8 将文字聊天室界面美化，加按钮、换文本框(用于显示的列表框不能贴图)<br>
 版本9 开始文件管理器的图形界面化<br>
 版本10 将文件功能加入聊天室(ftpDemo)<br>
 版本11 开始将发送表情功能加入聊天室<br>
 版本13-14 开始将发送图片功能加入聊天室<br>
 
PS:<br>
 对应的文件夹中有演示截图<br>
 版本号对应文件夹尾号<br>
 项目文件夹是按功能一个个分的<br>
 里面的代码如果有多个版本则是功能慢慢完善的过程<br>
 更多的具体看每个代码开头的注释说明<br>

- 优化了代码，封装了三个server
- 界面全部英文化
- 解决了无数个bug：
  - pictureServer和fileServer不能同时运行的问题
  - 截屏按钮不能正常工作的问题
  - 同用户名登录，仍显示不能自己与自己聊天的问题
  - 等等
- 新增功能：
  - 类似QQ小冰的AI聊天机器人
    - 群聊 @Robot
    - 私聊
  - 私聊点对点视频、音频聊天
    - 支持分辨率调节
    - 支持IPv4、IPv6
    - 可以选择是否在桌面上显示自己
- 待完善：
  - 视频聊天需要双方确认
  - 暂时通过重命名后加_2解决问题，不可靠
  - UI美化
