# StockView
[![](https://jitpack.io/v/yangsanning/StockView.svg)](https://jitpack.io/#yangsanning/StockView)
[![API](https://img.shields.io/badge/API-19%2B-orange.svg?style=flat)](https://android-arsenal.com/api?level=19)

## 效果预览

| [FenShiView]                      | [CapitalView]                     | [MiniFenShiView]                  |
| ------------------------------- | ------------------------------- | ------------------------------- |
| <img src="images/fenshiview.gif" height="512" /> | <img src="images/capitalview.png" height="512"/> | <img src="images/minifenshiview.gif" height="512"/> |


## 主要文件
| 名字             | 摘要           |
| ---------------- | -------------- |
| [FenShiView] | 普通分时图  |
| [CapitalView] | 资金趋势图  |
| [MiniFenShiView] | 迷你分时图  |


### 添加方法

#### 1. 添加仓库

在项目的 `build.gradle` 文件中配置仓库地址。

```android
allprojects {
	repositories {
		...
		maven { url 'https://jitpack.io' }
	}
}
```

#### 2. 添加项目依赖

在需要添加依赖的 Module 下添加以下信息，使用方式和普通的远程仓库一样。

```android
implementation 'com.github.yangsanning:StockView:1.0.7'
```

### 注
其中走马灯效果，可参考我的 [RecyclerViewFlipper]

[FenShiView]:https://github.com/yangsanning/StockView/blob/master/FenShiView.md
[CapitalView]:https://github.com/yangsanning/StockView/blob/master/CapitalView.md
[MiniFenShiView]:https://github.com/yangsanning/StockView/blob/master/MiniFenShiView.md
[RecyclerViewFlipper]:https://github.com/yangsanning/RecyclerViewFlipper
