### 1、脚本可针对任意一个存在于网易云音乐的歌单内的歌曲进行下载，需要提供对应歌单的网页链接<br>
### 2、脚本只下载歌单内的歌曲，非是将任意数量的歌单打包批量下载<br>
### 3、脚本借用了一个网易云音乐下载地址解析网站，网址：https://music.liuli.lol/ <br>
### 4、可能会出现部分歌曲下载失败，这是解析出来的下载链接404了，与脚本无关<br>
### 5、初版比较简陋，不存在缓存校验，不支持设置下载地址，不支持错误重试。我会慢慢改善。<br>
### 6、脚本随时可能因为用于搜索的网站挂了而失效<br>
### 7、请支持正版。<br>

# 使用方法：<br>
#####  python3 <br>
#####  import GetMusic <br>
#####  from GetMusic import Get_Music <br>
#####  Get_Music('http://example.example.com') <br>
