<h2 align="center">Z-Blog 百度小程序源码</h2>
<p align="center">注意：下载使用的时候，不要把 img 文件夹上次到小程序内</p>
<p align="center">此为开源版本，可以二次开发，不提供任何技术支持和安装咨询</p>

<p align="center">
<img src="https://img.shields.io/badge/yuran%20zixun-By%20二%20马%20食%20槽%20-gray.svg?colorA=655BE1&amp;colorB=4F44D6&amp;style=for-the-badge">
</p>

<p align="center">⬇⬇⬇需要配合一下后台插件使用⬇⬇⬇</p>
<p align="center">https://github.com/gaojima/yuran_zixun</p>

<h3>图片展示</h3>

<img src="https://github.com/gaojima/zblog-baiduboxapp/blob/main/img/202111211583.jpg?raw=true">
<img src="https://github.com/gaojima/zblog-baiduboxapp/blob/main/img/202111214074.jpg?raw=true">
<img src="https://github.com/gaojima/zblog-baiduboxapp/blob/main/img/202111217094.jpg?raw=true">
<img src="https://github.com/gaojima/zblog-baiduboxapp/blob/main/img/202111217210.jpg?raw=true">
<img src="https://github.com/gaojima/zblog-baiduboxapp/blob/main/img/202111217542.jpg?raw=true">

<h3>新版支持的功能</h3>

<p>接入 swan-sitemap 动态库，一站式互动组件，小程序一键关注，文章语音朗读，小程序云加速缓存，swan.setPageInfo 动态库，云端一体组件。</p>

<p>引入 mp-html组件，完善文章页内视频、音频展示方式，优化pre标签展示，table表格展示，增加独立分享按钮。</p>

<p>小程序内支持 轮播图、列表页、独立页，文章页，可无限复制增加，依赖 Z-blog 1.7.1 原生接口，支持后台开启 API限流 和 Cache框架组件的 Memcached 扩展。</p>

<h3>音乐播放器使用方法</h3>
<p>需要在 audio 标签内增加：name="音频名字"，author="音频演唱者"，poster="音频封面"，src="音频封面"，controls="" 是否显示默认控件，默认为：false</p>

<h3>视频播放器使用方法</h3>

<p>需要在 video 增加 title="{{ result.Title }}"，src="视频地址"，poster="视频封面"，controls="" 是否显示默认控件，默认为：false</p>

<p>enable-danmu="" 是否展示弹幕，只在初始化时有效，不能动态变更，默认为：false，danmu-btn="" 是否显示弹幕按钮，只在初始化时有效，不能动态变更，默认为：false</p>

<p>show-no-wifi-tip="{{ true }}" 非 wifi 环境下是否显示继续播放浮层，默认为：true</p>