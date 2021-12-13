## h5-plants-vs-zombies

利用原生js实现的h5小游戏

**demo**：[线上地址](https://z1511676208.github.io/h5-plants-vs-zombies/)


## Features：
-  Draw the game scene: background, sunlight scoreboard, plant card (for placing plants), plant (6 types), zombies (1 type)
-  Attack judgment and death judgment of plants and zombies
-  The character animation is realized by continuously switching and drawing frame by frame, which can draw smooth animation effects
-  The character animation automatically switches according to the character state. The plant animation includes (normal form, attack form), and the zombie animation includes (normal form, moving form, attack form, dying form, death form)
-  Sunlight is automatically generated, plants are placed to consume sunlight, and zombies are randomly generated
-  The game contains independent victory conditions for zombies and plants
- Game status: Loading, game running, game paused, game over (player victory), game over (zombie victory)

## 下载源码

``` bash
git clone https://github.com/z1511676208/h5-plants-vs-zombies.git
```

## 目录结构

```
.
├─ index.html                   // 首页html
│  
├─ css                          // css样式资源文件
├─ images                       // 图片资源文件  
└─ js
   ├─ common.js                 // 公共方法
   ├─ scene.js                  // 游戏场景相关类
   ├─ game.js                   // 游戏主要运行逻辑
   └─ main.js                   // 游戏运行主函数
```

* common.js => 引入公共方法
* scene.js => 引入游戏场景素材相关类，包括角色类、动画类
* game.js => 引入游戏引擎
* main.js => 游戏运行主函数

## 说明

如果对您有帮助，您可以点右上角 Star 支持一下 谢谢！
