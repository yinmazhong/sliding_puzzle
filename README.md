# 滑块拼图小游戏

## 简介

一个微信小程序游戏，滑动进行方块拼接

## 源码目录介绍

``` text
./js
├── base                                   // 定义游戏开发基础类
│   ├── button.js                          // 帧动画的简易实现
│   └── eventUtil.js                       // 游戏基本元素精灵类
├── libs
│   ├── bezier.js                          // 用于进行淡入淡出动画的类库 <https://github.com/gre/bezier-easing>
│   ├── symbol.js                          // ES6 Symbol简易兼容
│   └── weapp-adapter.js                   // 小游戏适配器
├── models
│   └── piece.js                           // 拼图方块类
├── runtime
│   ├── background.js                      // 背景类
│   ├── gameinfo.js                        // 游戏菜单、按钮和分数
│   ├── gameMap.js                         // 用于提供游戏的随机地图
│   └── music.js                           // 全局音效管理器
├── databus.js                             // 管控游戏状态
└── main.js                                // 游戏入口主函数

```