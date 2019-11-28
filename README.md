项目原因
把element-ui组件的tree树形控件迁移了一下，适配了iview组件

element-ui 的tree树形控件
修改为适配iview组件

element-ui tree树形控件源码抽离，适配iview，修改了源码，方便在iview里面使用强大的element-ui组件

##使用方法

```
npm i chu-tree-iview

import chuView from 'chu-tree-iview'
import iview from 'iview'

Vue.use(iview)
Vue.use(chuView)

<chu-tree></chu-tree>
```

使用文档跟element-ui一模一样
http://element-cn.eleme.io/#/zh-CN/component/tree

## 必须按照iview
样式风格全部替换成了ivew
功能全部按照element-ui原先一样

有问题联系作者
873056154@qq.com

1.1.1 修复了vue-cli载入失败
