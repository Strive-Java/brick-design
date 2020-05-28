---
title: Brick Design - 基于 React的组件可视化拖拽页面搭建源码生成工具
order: 10
hero:
  title: Brick Design
  desc: 基于 React的组件可视化拖拽页面搭建源码生成工具
  actions:
    - text: 快速上手
      link: /guide/getting-started
features:
  - icon: https://gw.alipayobjects.com/zos/bmw-prod/881dc458-f20b-407b-947a-95104b5ec82b/k79dm8ih_w144_h144.png
    title: 简单集成
    desc: 考究的默认配置和简单的组件式集成
  - icon: https://gw.alipayobjects.com/zos/bmw-prod/d60657df-0822-4631-9d7c-e7a869c2f21c/k79dmz3q_w126_h126.png
    title: 高性能
    desc: 高性能的组件渲染
  - icon: https://gw.alipayobjects.com/zos/bmw-prod/d1ee0c6f-5aed-4a45-a507-339a4bfe076c/k7bjsocq_w144_h144.png
    title: 为组件开发而生
    desc: 独特的 Markdown 扩展，可嵌入 Demo、可导入外部 Demo 甚至插入自定义 React 组件，使得组件的文档不仅能看，还好用
footer: Open-source MIT Licensed | Copyright © 2019-present<br />Powered by self
---

## 轻松上手
### Install
```bash
yarn add brickd brickd-core bricks-web
//或者
npm install brickd brickd-core bricks-web
```
### Usage
```
import { LegoProvider } from 'brickd-core';
import {BrickDesign} from 'brickd';
import {BrickTree,BrickPreview} from 'bricks-web'

const App = () => (
  <LegoProvider config={{...}}>
<div>
    <BrickPreview componentsCategory={...}/>
    <BrickDesign />
<BrickTree/>
</div>
  </LegoProvider>

);
```