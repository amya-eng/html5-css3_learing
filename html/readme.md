html文件：
注释掉某一行代码：ctrl + / 
浏览器没有出现中英文转化的弹出窗口：刷新页面或shift + 刷新页面
快速删除某一行：ctrl+shift+K
查找网页内容：ctrl+F
长行换行：ctrl+回车
向下复制一行：alt+shift+向下
abbr:li(list item)  dt(definition title) dd(definition description)
整块移动tab：选中+shift+tab
table的border属性如果设置>1，则只能控制最外层边框
table的heigth="500"表示table高至少为500
tbody的高度设置：如果整个表的总高度不过定义，则不变化
多行连线删除：光标移动+alt
画跨行跨列表格：先画最小行最小列表格模板
无论写了多少个空格和回车，最终都会解析成一个空格
表单：提交与反馈==请求与响应
form侧重收集，a侧重跳转
input type=submit 不可以写name
button默认类型：submit
查看剪切板历史：win+v
iframe如果嵌入一个zip， 打开网页即下载
关于“行高”：字是写在行的中线上的；font-size定义的是字体的大小；line-height=1.5表示的是行高为字体大小的1.5倍；
关于“元素”的理解：每一个元素都是一个盒子。
display:none; 死得很绝，相当于没写。
设置的背景元素会自动填充padding， border区域。
margin到底影不影响box的大小，主要看box的width有没有设置。
行内元素的padding上下不占位置。
行内元素的上下margin设置无效。
margin塌陷问题：在最上子元素中设置的margin-top, 最下子元素中设置的margin-bottom均被父元素抢走。
element style: 行内样式
继承样式级别低于默认样式
重置默认样式，从自身该。
空格也就是父元素content里面的一个文字元素。
基线对齐原则
但是基线不是文字的最低端，由此产生幽灵空白问题。
display: 可以用来实现二级菜单。
布局：首先定好盒子的宽高，加border和padding时需要减掉。
CSS写类名链：比较有自解释的功能。


js学习笔记：
async 与 defer 的区别： 如果脚本无需等待页面解析，且无依赖独立运行，那么应使用 async。
如果脚本需要等待页面解析，且依赖于其他脚本，调用这些脚本时应使用 defer，将关联的脚本按所需顺序置于 HTML 的相应 <script> 元素中。

修改input文本用.value
修改p文本用.textContent

在想要查看值的代码中添加console.log(变量名)： 控制台查看打印的值，是debug的一种常用方法

var与let的区别：变量提升，多次声名相同名称的变量，建议使用let
