![Gardennias' Github Stats](https://github-readme-stats.vercel.app/api?username=Gardennias&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515&hide=[%22contribs%22])

[TOC]

## Typora+PicGo+Github-plus搭建图床

1. Github上创建一个公开项目

2. 生成token（记得在电脑备份保存）

   > 点击GitHub头像 —>选择 settings —> Developer settings —>Personal access tokens —> Generate a personal access token

3. 下载`Picgo`，传送门 https://hub.fastgit.org/Molunerfinn/PicGo/releases

   - 设置图床，插件 `github-plus`, PicGo中插件设置中搜索下载

     - > PicGo中内置的Github图床支持，但是**不支持同步删除**，所以推荐`github-plus`

     自定义域名设置：https://cdn.jsdelivr.net/gh/用户名/仓库名@latest

     > jsDelivr 缓存刷新方式 https://cdn.jsdelivr.net/ `替换` 成 https://purge.jsdelivr.net/ 
     >
     > 即可实时刷新。刷新成功后，浏览器会返回缓存刷新成功的信息

     [![img](https://cdn.jsdelivr.net/gh/Gardennias/Personal-gallery@latest/images/202108231735360.png)](https://cdn.jsdelivr.net/gh/Gardennias/Personal-gallery@main/images/202108231735360.png)

   - 设置Typora

     [![img](https://cdn.jsdelivr.net/gh/Gardennias/Personal-gallery@main/images/202108231743173.png)](https://cdn.jsdelivr.net/gh/Gardennias/Personal-gallery@main/images/202108231743173.png)

4. 下载`Typora`，传送门[https://www.typora.io](https://www.typora.io/)

## GitHub加速访问

- [https://github.com.cnpmjs.org](https://github.com.cnpmjs.org/)

- [https://hub.fastgit.org](https://hub.fastgit.org/)

- 无需下载像vscode一样在线阅读代码，只需要在GitHub 仓库域名后面加上 `1s`（1 秒内）

  https://github1s.com/Gardennias/Personal-gallery

## GitHub搜索技巧

1. `in:name xxx // 按照项目名搜索`
2. `in:readme xxx // 按照README搜索`
3. `in:description xxx // 按照description搜索`

在此基础可以增加筛选条件

1. `stars:>xxx // stars数大于xxx`
2. `forks:>3000 // forks数大于xxx`
3. `language:xxx // 编程语言是xxx`
4. `pushed:>YYYY-MM-DD // 最后更新时间大于YYYY-MM-DD`



## Changelog

Detailed changes for each release are documented in the [release notes](https://hub.fastgit.org/Gardennias/Personal-gallery/releases).

## Contribution

