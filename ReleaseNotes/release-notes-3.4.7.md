# PLPlayerKit Release Notes for 3.4.7

## 内容

- [简介](#简介)
- [问题反馈](#问题反馈)
- [记录](#记录)

## 简介

PLPlayerKit 为 iOS 开发者提供直播播放 SDK。

## 问题反馈

当你遇到任何问题时，可以通过在 GitHub 的 repo 提交 ```issues``` 来反馈问题，请尽可能的描述清楚遇到的问题，如果有错误信息也一同附带，并且在 ```Labels``` 中指明类型为 bug 或者其他。

[通过这里查看已有的 issues 和提交 Bug](https://github.com/pili-engineering/PLPlayerKit/issues)

## 记录

### Player

- 3.4.7 ([Release Notes](https://github.com/pili-engineering/PLPlayerKit/blob/master/ReleaseNotes/release-notes-3.4.7.md) && [API Diffs](https://github.com/pili-engineering/PLPlayerKit/blob/master/APIDiffs/api-diffs-3.4.7.md)）

- 优化

     - 支持图片色彩空间 BT709

- 缺陷
     - 修复边下边播没有全部缓存结束，断网。播放缓存不流畅 bug
     - 修复精准 seek 后多次缓存回调 bug
     - 修复弱网 h265 花屏 bug
     
- 其他

     - 更新第三方依赖库

     

        
