# bookmarks-hub

一个汇聚浏览器书签的前端工具

![](https://github.com/jelif-zhang/bookmarks-hub/blob/master/media/screenshot.png)

## 功能

1. 聚合展示来自多个浏览器的书签信息
1. 一键搜索所有浏览器里的书签条目

## 交互

1. 输入
   1. 直接在搜索框键入关键词
   1. Ctrl+F快速聚焦到搜索框，输入关键词
1. 查询
   1. 直接点击查询按钮
   1. 在搜索框输入关键词后，按下回车键

## 注意事项

数据源和搜索功能由后端提供，此工具需要搭配后端工具使用：

1. 解析Safari书签的工具： [safari-bookmarks-parser](https://github.com/jelif-zhang/safari-bookmarks-parser)
1. 解析FireFox书签的工具：[firefox-bookmarks-parser](https://github.com/jelif-zhang/firefox-bookmarks-parser)

> 对于其他浏览器，需自行实现解析工具，数据格式参看[safari-bookmarks-parser](https://github.com/jelif-zhang/safari-bookmarks-parser)项目的README

