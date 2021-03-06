---
title: e-control组件使用说明
date: 2020-05-25
categories:
 - 组件
tags:
 - vue
 - element
 - component
---

## e-control
本组件为列表上方的控制组件，包含`e-search`、`e-operation`两个组件。

## props

属性|说明|类型|默认值
-|-|-|-
searchFormOptions|查询表单配置，详见`e-search`组件说明|Array|[]
searchLabelWidth|查询表单label宽度，详见`e-search`组件说明|String|'80px'
searchRefreshShow|查询区是否显示重置按钮，详见`e-search`组件说明|Boolean|true
btns|需要渲染的按钮数组，详见`e-operation`组件说明|Array|[]
searchShow|是否显示查询区|Boolean|true
operationShow|是否显示操作区|Boolean|true

## events

名称|说明|参数
-|-|-
on-search|点击查询按钮时触发的方法|表单数据
on-refresh|点击重置按钮时触发的方法|表单数据
change-height|点击展开或关闭按钮时触发的方法|表单占用的高度
on-insert|点击新增按钮时触发的方法|无
on-update|点击编辑按钮时触发的方法|无
on-delete|点击删除按钮时触发的方法|无
on-import|点击导入按钮时触发的方法|无
on-export|点击导出按钮时触发的方法|无
