---
title: 'Home'
comments: false
---

<script async defer src="https://buttons.github.io/buttons.js"></script>

# Hello

这里是李幸娟博客的首页！！！:)
该博客仅用于日常学习的记录，如有错误或问题请联系我 (邮箱：18236129679@163.com)


<img src='/Blog/images/home-banner.svg' />


keep hungry, and eat 🥤🐂🍔🍗🍰☕️🍉🍒🍦🍭🌽🍓🍇🥬🥒🥕🥞🧇🥓🥩🍖🌭🍕🥙🌮🥗🥘🍝🍣🍱🍥🍧🍨🧁


# 小李的文章收藏

1.  [ ]  [面试资源汇总:很多面经和](https://github.com/abc-club/js-paradise/blob/master/INTERVIEW.md)
2.  [ ]  [Weekly-FE-Interview](https://github.com/airuikun/Weekly-FE-Interview)
3.  [ ]  [冴羽的博客:前端基础知识类](https://github.com/mqyqingfeng/Blog)
4.  [ ]  [fouber的博客:前端进阶知识类](https://github.com/fouber/blog)
5.  [ ]  [公众号「千古壹号」作者的博客](https://github.com/qianguyihao/Web?utm_source=gold_browser_extension)
6.  [ ]  [林鑫个人博客](https://github.com/lin-xin/blog)




## 杂七杂八的

<!-- 1.  [ ]  如果一个网络请求函数，在项目静态资源刚一加载的时候执行，然后将返回值赋值给了 -->
1.  [x]  vue响应式实现
2.  [ ]  前端导出word方案
    1.  [ ]  字体
    2.  [ ]  table
    3.  [ ]  highchart svg图片处理（转为base64 png方案）
3.  [ ] node端通过html导出word
    1.  [ ]  svg处理 - egg单独服务处理 - 在服务上使用puppeteer 绘制后，截图，转为base64返回
4.  [ ]  node导出word
5.  [ ]  react性能优化问题
    1.  [ ]  antd-table，onClick/onMouseMove都会引起antd整个table的重新渲染？？？
6.  [ ]  数据结构
7.  [ ]  lodash的对象merge实现
8.  [ ]  [hexo热编译+gitpage添加评论功能](https://segmentfault.com/a/1190000016267344)
9.  [ ]  去看下element UI 的必输校验怎么做的，此处有个bug, 具体代码见 /ccu-web/src/page/main_$tp/asset-tour/modal-wrap/tour-record.md.vue
    - TODO: 这里有个bug:
      这个说明form-item 字段位于form下面，
      使用:prop="`${recordData.actionType === 'INPUT' ? 'comment' : ''}`"必输校验不到
      如果使用 正常的 prop='comment' 的话，必输校验的时机看起来是blur,
      所以采用了 v-if v-else + key 的方法，
10. [x]  blur和change区别；
11. [x]  看下Hzero的权限控制怎么做的
12. [x]  vue-todo-list + 使用gitpage展示;
    1.  [x]  配置gitpage;
    2.  [ ]  添加删除全部按钮；
    3.  [ ]  列表项目杭高；
    4.  [ ]  飘雪花效果；
    5.  [ ]  添加todo添加时间；
13. [x]  vue-antd 实现 checkbox 放大和修改样式的效果；
14. [ ]  项目添加提交校验（console\dbugger\alert）
15. [x]  继承相关；
16. [x]  vuex 的store 是只有这一串父子组件可以访问还是整个应用都可以访问？整个应用
   1. [x]  经测试，刚进入页面的时候可以访问到，刷新页面就没了，所以这个vuex只能用于存储一串父子组件的状态，不能用于存储作用于整个应用的变量；
17. [x]  总结: 前端模块化规范，AMD，CMD等；
18. [x]  函数柯里化;
19. [x]  函数的方法扩展;
20. [x]  call和apply,bind,实现bind
21. [x]  node常用的方法总结;
22. [x]  总结，new创建函数过程；
23. [ ]  require.ensure()
24. [x]  给项目添加yarn lint
25. [x]  有哪些机制下，页面会渲染？比如，state变了？
26. [ ]  ❤️ 常用的vue业务场景总结并写成项目---my-vue
    1. [x]  项目结构规范
    2. [ ]  图片压缩
    3. [x]  文件上传
    4. [ ]  文件预览
    5. [ ]  一个页面的结构
    6. [x]  上拉更多，下拉刷新
27. [x]  从掘金看的深拷贝，怎么处理循环引用问题的;
28. [ ]  Object和Map的转换
29. [ ]  总结: 执行上下文;
30. [x]  lodash深拷贝;
31. [x]  递归，迭代（递归已经明白了）
32. [x]  原型和原型链问题
33. [ ]  闭包及其场景还没总结完
34. [ ]  对象有很多方法;
35. [ ]  Redux源码看一看，之前真的把Redux想的太难了，现在发现也没啥东西，就是把state放在一个大家都能访问和修改的文件里面嘛
36. [x]  vue:如果传给子组件的数据变了，子组件会重新渲染么？ 因为是 props, 没有在data里面 => 会的
37. [ ]  手写react webpack脚手架
38. [ ]  在react 的DOM中调用函数时候传递的bind的this,是不是就是整个class的实例？？？<img src='/Blog/images/react调用函数传递的this.png'>
39. [x]  Redux学习
40. [ ]  看react redux的源码reducer函数，阮一峰的[Redux 入门教程（一）：基本用法](http://www.ruanyifeng.com/blog/2016/09/redux_tutorial_part_one_basic_usages.html)中说叫readucer的原因是他可以作为数组的reduce方法的参数1？？？？为什么？
41. [x]  React源码视频里面讲的 `component` 和 `pureComponent` 区别是啥来着？我怎么忘了？好像pure多个啥东西
42. [ ]  我有一个疑问，如果一个组件的子组件触发修改了某条数组，那页面不会重新渲染么？即，深度监听；
43. [ ]  我一直都对这个静态类型检测不熟悉;

```javascript
  static propTypes = {
    comments: PropTypes.array,
    onSubmit: PropTypes.func
  };
```




## 持续pending的TODO

1. [ ]  vue源码学习;
2. [ ]  看react源码视频;
3. [ ]  整理代码简介之道的一些实用技巧；

