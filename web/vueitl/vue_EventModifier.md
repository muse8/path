```
v-on 提供了很多事件修饰符来辅助实现一些功能。事件修饰符有如下：

.stop 阻止冒泡。本质是调用 event.stopPropagation()。

.prevent 阻止默认事件（默认行为）。本质是调用 event.preventDefault()。

.capture 添加事件监听器时，使用捕获的方式（也就是说，事件采用捕获的方式，而不是采用冒泡的方式）。

.self 只有当事件在该元素本身（比如不是子元素）触发时，才会触发回调。

.once 事件只触发一次。

.{keyCode | keyAlias} 只当事件是从侦听器绑定的元素本身触发时，才触发回调。

.native 监听组件根元素的原生事件。

PS：一个事件，允许同时使用多个事件修饰符。
```