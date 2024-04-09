DAY 1
+ 环境配置
+ 华为的开发工具安装包竟然是全英文！差评
DAY 2
+ artTS 基于 ts
	+ 声明式UI
	+ 状态管理
+ 方舟编译器来将字节码转为机器码 提高渲染效率
+ TS的基本语法
	+ 比较运算用=== 三等不用类型转换 所以不用==
	+  ts中 空字符串 数字0 null undefined 都被认定为 false 所以可以直接用变量来做条件
	+ for in  遍历得到数组角标  for of  直接得到元素  
	+ function 函数 支持可选参数，默认参数，箭头函数
	+ ts具有面向对象的基本语法，例如interface class enum  也具备封装，继承，多态等面向对象的基本特征（多态？构造函数？implements实现？接口和类？）
	+ ts的模块化
Day 3
+ 项目创建
+ entry 入口  ability
+ index.ets   ets就是artts文件
+ 装饰器  自定义组件：可复用的ui单元
+ @state  标记变量为状态变量，监控元素变化来实现动态页面
+ build（）｛｝  ui 描述：以声明式方式描述ui结构
+ 内置组件包括容器组件（row column）和基础组件（text）等
+ 组件里可以设置属性方法和事件方法
+ 一些组建的使用
+ 布局column竖row横
+ 主轴
![](1712663839772.png)
+ 交叉轴column  HorizontalAlign
![](1712664040748.png)
+ row verticalAlign
