# 背景

最近`vue2.7`的提交非常频繁，小伙伴们想让我说说这个版本。

![image-20220706101600628](https://raw.githubusercontent.com/57code/imgbed/master/image-20220706101600628.png)

# 内容

我们主要从`版本状态`、`使用体验`、`使用总结`、`深度学习`几方面谈一下感受。

![image-20220706103100706](https://raw.githubusercontent.com/57code/imgbed/master/image-20220706103100706.png)

# 版本状态

目前2.7.2已经是正式版本了，代号Naruto（火影忍者），作为末代版本维护最后18个月至2023年底。



# 使用体验

## CDN方式

快速体验vue2.7的方式是cdn方式

```html
<script src="http://unpkg.com/vue@2.7"></script>
```



## Vue2.7 Demo

我写了一个小的时钟应用供大家参考：https://github.com/57code/vue2.7-test

![image-20220706111912824](https://raw.githubusercontent.com/57code/imgbed/master/image-20220706111912824.png)

![image-20220706110418210](https://raw.githubusercontent.com/57code/imgbed/master/image-20220706110418210.png)



## vite

工程中体验`vue2.7`，vite中提供了一个vue2的插件：`@vitejs/pulgin-vue2`

大家感兴趣的话多给我点点赞，专门做一个系列把vue2.7新特性带大家都体验一遍！

# 使用总结

vue2.7是一个兼具兼容性和vue3开发体验的版本，是一个真香版本。



## 项目代码变化

`vue2.7`用ts重写了一遍，这样便于vue3新特性的引入。

![image-20220706111713417](https://raw.githubusercontent.com/57code/imgbed/master/image-20220706111713417.png)

同时包管理工具改为了pnpm，但是包结构基本和之前一样没有变化。

![image-20220706111800541](https://raw.githubusercontent.com/57code/imgbed/master/image-20220706111800541.png)



## 新特性

如下图，除了最重要的`Composition API`，还有vue3中SFC setup，css bind等。另外esm方式可以使用defineComponent()/h()/useSlot()等等函数。稍后大家点赞安排到位，我写一个更完整的工程，试用一遍。

![image-20220706110850345](https://raw.githubusercontent.com/57code/imgbed/master/image-20220706110850345.png)



# 深度学习

vue2.7这个版本是如何丝滑的引入vue3中的那些特性的哪，我们使用时应该注意那些和vue3有差异的地方，这些内容需要我们好好看文档（暂时还未更新），读一读源码：http://github1s.com/vuejs/vue。

不少同学不太会读源码学习，恰好村长的私教课《Vue源码全家桶》中重新讲了一遍`vue2.7`的源码剖析，并手写实现了这个版本的`mini-vue`，大家可以扫码了解课程。

![源码二维码](https://raw.githubusercontent.com/57code/imgbed/master/%E6%BA%90%E7%A0%81%E4%BA%8C%E7%BB%B4%E7%A0%81.png)

