# proxy-and-reactive

最近 Vue3.0 发布，其中一个比较大的更新是将 Reactive 这个双向绑定的基础库抽离出来了。之前它的底层是基于对象的 get、set 方法，现在基于 Proxy 进行了重写。

我们基于 Proxy 来实现一个 toyed 版的 Reactive。

详细的步骤介绍见 [Proxy 与 Reactive](https://www.yuque.com/wendraw/fe/proxy-and-reactive)
