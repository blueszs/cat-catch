## 简介
猫抓 Chrome资源嗅探扩展

## Chrome 安装地址
https://chrome.google.com/webstore/detail/%E7%8C%AB%E6%8A%93/jfedfbgedapdagkghmgibemcoggfppbb

Chrome扩展审核很漫长 导致版本号会滞后一些 如果差别太多 可以先使用源码加载办法使用GitHub版。

接下来还是GitHub版本为主 避免官方再次下架扩展。

## 源码加载方法
1. https://github.com/xifangczy/cat-catch/releases 下载 Source code 并解压。
2. Chrome扩展管理页面 chrome://extensions/ 右上角 打开 "开发者模式"。
3. 左上角点击 "加载已解压的扩展程序" 然后选中你解压好的猫抓的目录即可。

## 更新说明
### 1.0.19
重写导致的巨多BUG修复
### 1.0.18
增加application/octet-stream选项，继续部分代码重写
### 1.0.17
Manifest 更新到 V3 部分代码重写，增加“使用PotPlayer预览媒体”选项。

## 幽灵数据？
之前版本经常出现某条资源不属于任何网页（具体原因不详，有可能是因为通过JS加载的视频 Chrome无法判断来源页面），老版本会丢弃该数据。1.0.17之后得到修复并称这部分数据称为“幽灵数据”。

## License
MIT