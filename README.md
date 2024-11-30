# EBReader电子阅读器基础功能使用说明
## 安装
下载地址：https://plugins.jetbrains.com/plugin/download?rel=true&updateId=642178  
支持idea版本 2022.2.5以上
插件初次开发，正在审核中，插件市场里搜不到，可以直接从这个地址下载。
## 功能介绍
1   打开电子书,快捷键 ALT + o  
2   调出历史阅读列表,快捷键 ALT + l(注意这里是小写的字母L)  
3   移除一个历史阅读列表中的电子书,快捷键 ALT + d  
4   阅读下一行,快捷键 ALT + z  
5   阅读上一行,快捷键 ALT + a  
6   阅读当前行,快捷键 ALT + c  
7   阅读上一章,快捷键 ALT + g  
8   阅读下一章,快捷键 ALT + v  
9   调出本书的章节列表,快捷键 ALT + m  
10  领导来了赶紧隐藏,快捷键 ALT + x  
11  设置字符集和每行的字符数,快捷键 ALT + p  
12  建立章节索引,快捷键 ALT + i  
以上快捷键可以在IDE的快捷键里根据自己的喜好进行设置，如下图所示  
![image](https://github.com/user-attachments/assets/4a919505-0806-4ebb-b69a-b633f60425b3)  

## 功能演示
## 一.打开电子书，按组合键 ALT + o  
![image](https://github.com/user-attachments/assets/8c64453f-2420-4f73-97b2-9cf8b715e287)  
选择你想要阅读的电子书，这里只支持阅读txt和epub格式的电子书。  
如果你打开的电子书是乱码的话，请使用组合键 ALT + p 调出设置界面设置正确的编码后重新打开一次就可以了，如下图所示：  
![image](https://github.com/user-attachments/assets/5f0ec1a8-ab07-4f1d-8ec8-23c4b25d46b5)  
成功打开电子书后，电子书的内容会在IDE的最下方展示出来，这时可以使用功能介绍里面的快捷键翻阅电子书，如下图所示：  
![image](https://github.com/user-attachments/assets/7e69fa3f-7b2f-40fb-a6d3-4dd70ac9023f)  
如果你的下方没有正常显示的话，请按照下图操作一遍，如果还没有效果请联系作者。
![image](https://github.com/user-attachments/assets/bf83ca48-30a9-40fc-badc-d2f7bd8d84b6)  

## 二.建立章节索引，按组合键 ALT + i
建立章节索引的原理是你提供一个正则表达式用来匹配章节的位置  
此功能通常用于打开txt格式的电子书，如果epub格式的电子书里没有按标准提供章节信息，也需要用此功能建立章节索引。  
本插件的默认章节表达式为：  ^[第]{1}.*(章|回){1}.*  
如果你的电子书不符合这个表达式的话，请使用快捷键 ALT + i 调出设置章表达式的界面，如下：  
![image](https://github.com/user-attachments/assets/99b7ccff-a32c-4b49-b88d-328cffe4b01a)  
然后输入正确的正则表达式点OK即可。  
## 三.阅读历史管理  
如果你打开了多个电子书的话，你想要换一个电子书阅读请使用快捷键 ALT + l(注意这里是小写的字母L) ，如下图：  
![image](https://github.com/user-attachments/assets/fa49fc2a-de9e-438b-921c-d0571d03f4ce)  
然后选择你要阅读的电子书就可以完成切换了  
如果你想要移除一个电子书的话，使用快捷键 ALT + d 会调出与 ALT + l 相同的界面，然后选择你要移除的电子书即可。
## 本插件的基础功能介绍至此完，如果你喜欢本软件的话，打赏激励作者持续更新维护  
![企业微信截图_20241130115101](https://github.com/user-attachments/assets/ab66f392-fd61-4df5-85ac-270cc867ae5c)
![企业微信截图_20241130115141](https://github.com/user-attachments/assets/83b5d748-68b6-405f-8558-eaaa1e6ee917)
