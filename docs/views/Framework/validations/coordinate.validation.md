---
title: 坐标验证方法说明
date: 2020-04-17
author: 赵致喜
categories:
 - 验证
tags:
 - javascript
 - validation
 - coordinate
---
## coordinateValidation

验证坐标在有效范围内

| 名称  |  类型  | 默认值 | 必须 |                         说明                          |
| :---: | :----: | :----: | :--: | :---------------------------------------------------: |
| east  | Number |   0    | true |                    被检测东经坐标                     |
| north | Number |   0    | true |                    被检测北纬坐标                     |
| area  | String |  ' '   | true | 被校验地区（目前只支持天津'tianjin'，默认为空是中国） |

```js
import validations from '@/validations'

validations.coordinateValidation(east, north, area)
```
