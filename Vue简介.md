### Vue简介
#### Vue 中文官方文档：https://cn.vuejs.org/v2/guide/
Vue (读音 /vjuː/，类似于 view) 是一套用于构建用户界面的渐进式框架。与其它大型框架不同的是，Vue 被设计为可以自底向上逐层应用。Vue 的核心库只关注视图层，不仅易于上手，还便于与第三方库或既有项目整合。另一方面，当与现代化的工具链以及各种支持类库结合使用时，Vue 也完全能够为复杂的单页应用提供驱动。

### 引入方式
直接通过 CDN 引入
```html
<!-- 开发环境版本，包含了有帮助的命令行警告 -->
<script src="https://cdn.jsdelivr.net/npm/vue@2/dist/vue.js"></script>
```

### 声明式渲染
创建一个Vue 应用

#### 绑定数据

bind-data

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <!-- 开发环境版本，包含了有帮助的命令行警告 -->
    <script src="https://cdn.jsdelivr.net/npm/vue@2/dist/vue.js"></script>
</head>
<body>
<div id="app">
    {{ message }}
</div>

<script>
    const app = new Vue({
        el: '#app',
        data: {
            message: 'Hello Vue!'
        }
    });
</script>
</body>
</html>
```

我们已经成功创建了第一个 Vue 应用！看起来这跟渲染一个字符串模板非常类似，但是 Vue 在背后做了大量工作。现在数据和 DOM 已经被建立了关联，所有东西都是响应式的。

#### 绑定属性，循环以及条件判断

``` html

```







### 完成一个侧边菜单案例

#### 1、完成部分基础样式，左侧菜单元素位置、颜色以及图标库的引入（sidebar-init）

#### 2、引入 vue、初始化数据，计算属性以及方法，完成侧边栏切换（sidebar-vue）

#### 3、加入图标翻转以及标题（sidebar-title）

#### 4、完成路由切换等功能（sidebar-router）





