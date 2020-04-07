---
title: 我的世界coloryml配置
background_music: '<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=330 height=86 src="//music.163.com/outchain/player?type=2&id=29207835&auto=1&height=66"></iframe>'
tags:
- 灵感
---
# 有很多同学因为配置服务器标题而导致服务器很难看，这是我的配置欢迎参考！
```javascript
Motd:
- |2-
                &f&l&m---&8&l&m[- &6&gamers服务器 &e&l| &a&l起床战争 &8&l&m-]&f&l&m---&0
               &e&l* &d&l1.8.8 &e&l*  &e&l* &c&l欢迎加入 &e&l*
OnlineMsg: '&a在线人数 &6%ONLINE%&7/&6%MAXPLAYER%'
Players:
- '&b这里是默认的悬浮文字信息'
- '&e可以显示多行'
- '&a支持变量,比如%TIME%'
ServiceModeMOTD: '&c服务器维护中,请等待维护完成...'
ServiceModeKickCause: '&c服务器维护中,请等待维护完成再进入服务器!'
useBungeeCord: false
redisBungee: false
AttributionServer: kaifuxia
TPSFormat: '0.0'
showDelay: true
UpdateChecker: true
}
```
```sequence
命令方块->数据: 分数为多少了?
Note right of 数据: 数据储存
数据--命令方块: 数据到了!
```

#看了不懂可以留言

<script src="https://utteranc.es/client.js"
        repo="hongchenkai/plcc"
        issue-term="pathname"
        theme="github-dark-orange"
        crossorigin="anonymous"
        async>
</script>
