# changeset-comment-suggestion

[English](#English) | [简体中文](#简体中文)

Add translation because mentioned in [RfC: deprecate hashtag-only changeset comments](https://community.openstreetmap.org/t/rfc-deprecate-hashtag-only-changeset-comments/105770/25)

---

## **English**

### Project Description

TL;DR

### in principle

1. Don’t abuse hashtags
2. Express enough information
3. Everything should be convenient for editors
4. Can support quickly and insensible translation into multiple languages ​​to cope with target readers whose native language is not their own

### Combination method

#### Optional tags

+ **`#Organization or Team`**
Such as: `Central_South_University`, `Mapbox`

+ **`#City`**
Such as: `Beijing`, `Changsha`

+ **`#Drawing Project`**
Such as: `Jinan_Bus_Improvement`, `Energy_China`, `Yama-no-Katachi_Project`, `hotosm-xxx`

+ **`#Edit main type`**
Such as: `Align Offset`, `New Draw`, `Delete Obsolete`, `Repair`, `Adjust`, `Refinement`, `Rewind`

+ **`#Work details`**
Such as: `bus routes`, `architecture`, `fine mapping`, `NSI-POI`, `land type`, `natural mountains and rivers`, `administrative divisions`, `railway`, `3D and indoor`

#### Commonly used combination structures suggestion

+ `#organization or team`+`#drawing project`
+ `#City or {{detect.city}}`+`#Edit main type`+`{{detect.most_offen_name}} or {{detect.place_name}}` (main editing content or main editing area)

---

## **简体中文**

### 项目简介

略

### 原则

1. 不滥用hashtag
2. 表达足够的信息
3. 一切以方便编辑者为要
4. 可以支持快速同步翻译多语言以应对目标读者非母语

### 组合方式

#### 可选标签

+ **`#机构或团队`**
如：`中南大学`，`Mapbox`

+ **`#城市`**
如：`北京`，`长沙`

+ **`#绘图项目`**
如：`济南公交完善`，`能源中国`，`Yama-no-Katachi_Project`，`hotosm-xxx`

+ **`#编辑主要类型`**
如：`对齐偏移`、`全新绘制`、`删除过时`、`修复`、`调整`、`细化`、`回退`

+ **`#工作细节`**
如：`公交路线`、`建筑`、`精细制图`、`NSI`、`用地类型`、`自然山川`、`行政区划`、`铁路`、`3D与室内`

#### 常用组合结构推荐

+ `#机构或团队`+`#绘图项目`
+ `#城市 or {{detect.city}}`+`#编辑主要类型`+`{{detect.most_offen_name}} or {{detect.place_name}}` （主要编辑内容或主要编辑的区域）
