# Vue

1. vue双向绑定
MVVM 
2. vue响应式原理

3. vue2和vue3的区别

1）应用创建方式不同

```js
vue2: new Vue
vue3: createApp
```

2）组合式代码和选项式代码

4. MVVM在Vue和react中的体现

5. MVVM,响应式和双向绑定的区别

[以用不同的方式使用 Vue](https://cn.vuejs.org/guide/extras/ways-of-using-vue.html#standalone-script)：

无需构建步骤，渐进式增强静态的 HTML
在任何页面中作为 Web Components 嵌入
单页应用 (SPA)
全栈 / 服务端渲染 (SSR)
Jamstack / 静态站点生成 (SSG)
开发桌面端、移动端、WebGL，甚至是命令行终端中的界面

命令式和声明式

一个框架：

1. 输出产物
2. 输入体积控制
3. tree-shaking
4. 错误机制
5. typescript规范支持
6. 特性开关
7. 用户体验


VDOM: 使用Javascript对象描述DOM结构

template -> 编译器（complier） -> render函数 -> VDOM -> 渲染器(renderer) -> 真实DOM

所谓组件是对一组VDOM的封装，使用VDOM描述组件，其tag可以是一个函数（render函数）或者一个包含render函数的对象，执行render返回VDOM

## 响应系统

Watcher: 在new Watcher时,主要完成 步： 1. 把window.target = this（等于自身）, 2. 读取属性的值，就会触发该属性的getter方法，收集依赖（window.target）,  3. 标记
Observer
Dep

## 渲染器

## 编译器

## 组件化

## 服务端渲染
