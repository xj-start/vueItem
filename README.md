## vue stageOne
>1.MVC 和 MVVM 的区别 <br/><hr>
2.Vue最基本代码的结构 <br/><hr>
3.插值表达式 [v-clock v-text v-html v-bind(缩写是:) v-on(缩写是@)]   v-model(数据的双向绑定)  v-for(循环) v-if(判断) v-show(显示隐藏)<br/><hr>
4.事件修饰符 stop(阻止事件冒泡) prevent(清除默认行为,比如a标签的跳转) self(触发自己范围内的事件，不包含子元素) once(只执行一次) capture(与事件冒泡相反,不含子元素)<br/><hr>
5.el 指定要控制的区域 data 是个对象 指定了控制的区域内要用到的数据  methods 虽然带个s后缀 但是是个对象 这里可以自定义了方法<br/><hr>
6.在VM实例中 如果要访问 data 上的数据 或者要访问methods中的方法 必须要带this<br/><hr>
7.在 v-for 要会使用key属性 (只要是string/number)<br/><hr>
8.v-model 只能应用于表单元素<br/><hr>
9.在vue中绑定样式两种方法 v-bind:class v-bind:style<br/>
