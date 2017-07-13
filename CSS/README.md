# God-talk-Human CSS语录
干货是什么，干货就是GH，God-talk-Human，记录下来的大神与提问者的对话
## 语言记录
* [CSS - 学习思路 - 2017.7.13](https://github.com/setcamp/God-talk-Human/tree/master/CSS#2017-7-13)
## 2017-7-13
### CSS - 学习思路
#### **Human问：想要掌握CSS基础知识，需要看哪些书**
#### **God  答：**
1. 两本书，一本《CSS权威指南》为基础知识，主要讲解了CSS2.0与CSS2.1。另一本为帮助提高技巧的《CSS揭秘》
#### **Human问：那less和sass怎么样学习比较好**
#### **God  答：**
1. less要配合模块化进行实操
2. 可以去读一下bootstrap.less的源码
3. less的编程思路
    * `common.less`定义全局共用样式
    * `page`里面的每一个`less`，就代表一个页面的布局。记住，只写布局
    * `mixin.less`定义需要的函数和变量
    * 最后有`main.less`引入
    * 按钮，分页，导航什么的，如果是共用的放在common文件下，如果是组件特有的就放在组件下
    * 路径清晰，有利于后期维护，迭代，修改。
#### **Human问：CSS如何优化性能，书写注意哪些**
#### **God  答：**
1. 单位统一，少使用float和position
2. CSS性能，方面注意少用嵌套，少用id，少用标签来写
