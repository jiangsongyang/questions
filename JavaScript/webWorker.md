Web worker，Service worker和worklet都是将脚本运行在浏览器主线程之外单独的线程中，它们之间的区别是它们所应用的场景和他们的特性。

Worklet 是浏览器渲染流中的钩子，可以让我们有浏览器渲染线程中底层的权限，比如样式和布局。

Service worker 是浏览器和网络间的代理。通过拦截文档中发出的请求，service worker 可以直接请求缓存中的数据，达到离线运行的目的。

Web worker 是通常目的是让我们减轻主线程中的密集处理工作的脚本。