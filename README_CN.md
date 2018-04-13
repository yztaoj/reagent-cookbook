# Reagent 菜谱

![Reagent-Project](logo-rounded.jpg)

本知识库的目的是提供如何在[reagent](https://github.com/reagent-project/reagent)网络应用中完成某项任务的“配方”。

如需要更新提醒请在twitter上follow：[@ReagentProject](https://twitter.com/ReagentProject)。如果要tweet我们，请在开头包含`#reagent #cljs`

需要视频教程的，在油管上[订阅](https://www.youtube.com/channel/UC1UP5LiNNNf0a45dA9eDA0Q)我们。

## 基础

* [基础组件](https://github.com/reagent-project/reagent-cookbook/tree/master/basics/basic-component)
* [组件级别的状态](https://github.com/reagent-project/reagent-cookbook/tree/master/basics/component-level-state)
* [游标](https://github.com/reagent-project/reagent-cookbook/tree/master/basics/cursors)

## 配方

* 动画
    * [mojs animation](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/mojs-animation)
    * [ReactCSSTransitionGroup](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/ReactCSSTransitionGroup)
* 引导
    * [bootstrap modal window](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/bootstrap-modal)
    * [bootstrap-datepicker](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/bootstrap-datepicker)
* Canvas画布
    * [Canvas fills div](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/canvas-fills-div)
* 绘图
    * [highcharts](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/highcharts)
    * [morris](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/morris)
* 图像
    * [google-street-view](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/google-street-view)
* jQuery UI
    * [autocomplete](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/autocomplete)
    * [draggable element](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/draggable)
    * [droppable element](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/droppable)
    * [sortable portlets](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/sortable-portlets)
* 地图
    * [Leaflet](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/leaflet)
    * [Google Maps](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/google-maps)
* 杂项.
    * [compare argv](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/compare-argv)
    * [Live Markdown Editor](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/markdown-editor)
	* [server-side-rendering](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/reagent-server-rendering)
	* [toggle class](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/toggle-class)
	* [file upload with filestack](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/file-upload)
	* [typeahead](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/typeaheadjs)
	* [editable label](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/editable-label)
* 路由
    * [add routing](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/add-routing) with secretary
* 侧边栏
    * [Simple Sidebar](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/simple-sidebar)
* 状态
    * [local-storage](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/local-storage) with storage-atom
    * [undo](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/undo) with historian
* 表格
    * [DataTables](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/data-tables)
	* [sortable table](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/sort-table)
	* [filter table](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/filter-table)
* 测试
    * [test-example with lein-doo](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/test-example)
    * [test-example with lein-doo and ReactTestUtils](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/test-example-with-ReactTestUtils)
	* [test-example with lein-doo and test.check](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/test-example-with-test-check)
* 验证
    * [input validation (color-coded)](https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/input-validation)

## 通常配方的起点

The starting point for reagent-cookbook recipes is [reagent-cookbook-template](https://github.com/gadfly361/reagent-cookbook-template).

```
$ lein new rc <name of recipe>
```

Note: reagent-cookbook-template was made specifically for following along with recipes.  If you are interested in starting a new reagent application with some batteries included, then [reagent-template](https://github.com/reagent-project/reagent-template) provides a good starting configuration: `$ lein new reagent <name of app>`.

## 贡献

Recipes are welcomed!  Please fork, branch, and submit a pull request.

Also, I would love a PR for:

* Adding the right externs for advanced compilation of the *nvd3* recipe (it's inside old-recipes for now)
* Adding the right externs for advanced compilation of the *mermaid* recipe (it's inside old-recipes for now)

## 许可

Copyright © 2015 Matthew Jaoudi

Distributed under the The MIT License (MIT).
