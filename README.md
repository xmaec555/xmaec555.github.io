微信公众号:  洪溪208  

最后更新版本号：pg.20240513-2114

接口： https://raw.githubusercontent.com/xmaec555/xmaec555.github.io/main/jsm.json

1.增加磁力播放高速加速功能開關，可以到網盤及彈幕配置中關閉高速加速，使用普通加速能力播放磁力。默認不打開高速加速能力。

2.为提高某堂某族JXX的离线成功率，把他们都加入了Push全家桶，因此json配置项的ext第一位必须是lib/tokenm.json了哦。优化离线策略，10分钟内不会离线第二次，防止循环尝试离线。

3.磁力無害化處理，網盤及彈幕設置中，增加“離綫播放使用PPGO”，該功能默認關閉，當打開此功能時，會使用PikPakGO直連方式播放磁力内容，完全不占用任何閃存空間，完全不用考慮限速問題和閃存損耗問題，是真正的曲率引擎。此項科技功能可以實現非人類的各種機動動作，油門刹車？不存在的，根本不需要油,磁力多個磁力鏈放到同一個源内時，排序優化，防止多集的劇集第一集擠在一起。
4.大幅优化磁力播放，解决不太灵，美剧迷等单个视频源内大量磁力链导致播放困难的问题。优化阿里播放。

4 .磁力播放支持關閉普通加速，在網盤及彈幕配置中，磁力設置中，可以選擇關閉普通加速功能，但請注意，如果關閉了普通加速，卻沒有打開高速/離綫加速，那麽磁力將直接播放失敗。
阿里云盘的token输入界面，夸克的cookie，迅雷PP的captchatoken输入界面都支持http://ip:9978/proxy?do=input的方式输入内容了。csp_AppYsV2支持自动去广告（未测试）
