---
title: GlobalEventHandlers.oncuechange
slug: Web/API/TextTrack/cuechange_event
tags:
  - API
  - Event Handler
  - GlobalEventHandlers
  - 事件处理函数
translation_of: Web/API/GlobalEventHandlers/oncuechange
original_slug: Web/API/GlobalEventHandlers/oncuechange
---
{{ ApiRef("HTML DOM") }}**`oncuechange`** 属性属于{{domxref("GlobalEventHandlers")}}，是一个处理{{event("cuechange")}}事件的{{event("Event_handlers", "event handler")}}。当{{domxref("TextTrack")}}更改了当前显示的提示时，`cuechange` 事件将会触发。

## 语法

```plain
element.oncuechange = handlerFunction;
var handlerFunction = element.oncuechange;
```

`handlerFunction` 可以为 `null`，也可以是一个处理指定事件的[JavaScript 函数](/zh-CN/docs/Web/JavaScript/Reference/Functions)。

## 规范

{{Specifications}}

## 浏览器兼容性

{{Compat}}

## 查看更多

- {{event("cuechange")}}
- [DOM 事件处理函数](/zh-CN/docs/Web/Guide/Events/Event_handlers)
