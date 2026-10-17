# 洲哥的客户看板

基于开源后台模板 Gentelella v4（MIT 协议）改造的客户数据看板。

## 这是什么

一个后台管理界面的骨架，包含 58 个页面（仪表盘、客户表、图表、日历、收件箱等），
用于搭建客户数据可视化看板的界面原型。目前展示的是模板自带的演示数据。

## 怎么跑起来

需要先装 Node.js，然后：

```bash
npm install --registry=https://registry.npmmirror.com
npm run dev
```

启动后访问：http://localhost:9173/production/index.html

## 来源

- 原项目：https://github.com/ColorlibHQ/gentelella
- 协议：MIT
- 改造内容：页面标题与品牌名改为「洲哥的客户看板」，其余保持原样

## 待办

- [ ] 把演示数据换成真实客户数据（本地，不入库）
- [ ] 定制配色与品牌风格
- [ ] 接入实际数据源
