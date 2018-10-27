# WXML Specification (WIP)

WXML（WeiXin Markup Language）是微信团队设计的一个类似 XML 的标签语言，用于微信小程序开发。这份规范并非出自微信官方，而是严重参考了 [Facebook JSX](https://github.com/facebook/jsx) 进行设计的。

```
// WXML
<view wx:if="{{visible}}" bindtap="ontap">
  <text>Hello World !</text>
</view>
```

* [AST Specificaion](./ast-spec.md): WXML AST 规范
* [WXML Parser](./parser): 将 WXML 解析成标准的 AST
* [WXML Transform Plugins](./transformer): babel 插件，将 WXML AST 转换成 Vue/React 渲染函数

# License

MIT
