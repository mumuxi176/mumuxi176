# README

<p>
        <img src="https://img.shields.io/badge/Typora-v0.11.18-green?style=for-the-badge">
    <a href="https://github.com/mumuxi176"><img src="https://img.shields.io/badge/%E4%BD%9C%E8%80%85-mumuxi176-blue?style=for-the-badge&logo=github"></a>
</p>


## 制作github主页的readme文件

主页截图如下：

![image-20220725121005463](https://i0.hdslb.com/bfs/album/781f246ab96e137f17ae16e01530e35f10cdf6f0.png)





### 1.github统计卡片

:rocket:  [教程](https://github.com/anuraghazra/github-readme-stats/blob/master/docs/readme_cn.md)

> 统计卡片的代码如下，直接写进markdown文件即可

```
<img align="right" src="https://github-readme-stats.vercel.app/api?username=mumuxi176&show_icons=true&icon_color=CE1D2D&text_color=718096&bg_color=ffffff&hide_title=true" />
```



### 2.github徽标

:rocket:  [教程](https://zhuanlan.zhihu.com/p/217540872)

:rocket:  [教程2](https://zhuanlan.zhihu.com/p/258117972)

:rocket: [制作徽标](https://shields.io/)

> 动态徽标
>
> ```
> https://img.shields.io/badge/dynamic/json?color=000000&label=Github&query=%24.data.totalSubs&suffix=%20%20%20%20%20%20followers&url=https%3A%2F%2Fapi.spencerwoo.com%2Fsubstats%2F%3Fsource%3Dgithub%26queryKey%3Dmumuxi176?style=for-the-badge&logo=github
> ```

![image-20220725112929140](https://i0.hdslb.com/bfs/album/1793b15bbb8c44b5de6d71bfd8a553bbea766211.png)

要添加风格，只需要在网址的最后面添加语句即可，例如添加"?style=for-the-badge&logo=github"，即为徽标添加github的logo

