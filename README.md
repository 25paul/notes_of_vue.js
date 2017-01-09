#一、介绍<br/>
##1.1、vue.js是什么
一套构建用户界面的 渐进式框架、Vue 采用自底向上增量开发的设计。<br/>
Vue 的核心库只关注视图层。非常容易与其它库或已有项目整合。另一方面，Vue 完全有能力驱动采用[单文件组件](https://cn.vuejs.org/v2/guide/single-file-components.html)和 [Vue 生态系统支持的库](https://github.com/vuejs/awesome-vue#libraries--plugins)开发的复杂单页应用。
响应的数据绑定和组合的视图组件。
##1.2、起步
##1.3、声明式渲染
Vue.js 的核心是一个允许你采用简洁的模板语法来声明式的将数据渲染进 DOM 的系统。源码查看示例1-3.html。<br/>
这样数据和 DOM 已经被绑定在一起，所有的元素都是响应式的。打开你的浏览器的控制台，并修改 app.message，你将看到上例相应地更新。<br/>
除了绑定插入的文本内容，我们还可以采用这样的方式绑定 DOM 元素属性：源码查看示例1-3(2).html。<br/>
##1.4、条件与循环
控制切换一个元素的显示也相当简单：示例查看1-4(1).html<br/>
这个例子演示了我们不仅可以绑定 DOM 文本到数据，也可以绑定 DOM 结构到数据。<br/>
Vue强大的[过度效果](https://cn.vuejs.org/v2/guide/transitions.html)<br/>
v-for 指令可以绑定数据到数组来渲染一个列表：示例1-4(2).html<br/>
在控制台里，输入 app.messages.push({text:'ember.js'})。你会发现列表中多了一栏新内容。
