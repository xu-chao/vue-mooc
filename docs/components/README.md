# 介绍
::: tip 目录
根据[指南](/guide/)部分提到的项目结构，基础公共组件放置在：`src/base/`；业务公共组件放置在：`src/components/`。
:::

## 参考
`vue-mooc`公共组件大概有如下两类：
* 基础公共组件：一些项目中共用的组件，我们称之为基础公用组件，这部分组件可以完美迁移到另外一个项目，例如：`Star`星级评分组件。
* 业务公共组件：在做一个项目的过程中，例如`PC`端项目，一些业务公共组件非常明显，这类公共组件只贴合此项目，往往不能被迁移到另外一个项目中，例如：`Header`组件和`Footer`组件。

## 说明
此页面只作为公共组件的组件说明文档，它包含了一个组件必须的`用法`、`属性`和`事件`等案例。<br/>
如果你对于基础公共组件是如何封装的很兴趣的话，请移步[组件封装](/guide/components/)了解更多。