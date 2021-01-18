# css选择器
- 类型选择器
    使用标签的名字进行选择
- 选择器的群组
    用逗号将各个群组分隔开
- 通用选择器
    用一个*选择所有元素
- 类选择器
    用.名称选择某个类的元素
- ID选择器
    用#名称选择某个ID的元素，ID不能重复
- 属性选择器
    用[]括起来的元素进行统一编辑，也可以选择多个属性，或者某个属性的某些值 ~因为选择多个值的时候通常用空格隔开，如果要选择属性中含有空格的元素，要在等号前加上~ ^以等号内容开头的值 $以等号内容结尾的值 *属性的值里面含有等号后内容
- 伪类
    在没有访问过的链接上会有一个：link的伪类
    访问过后的有：visited的伪类
    鼠标指针移动到上面会有一个：hover的伪类
    某个属性被按住或者被激活的时候会有一个：active的伪类 松开后消除
    被选中时会有一个：focus的伪类
    在文档内部在使用了一个ID作为连接，如果用户点击了这个链接被连接的元素会有个：target的伪类
    当前禁用的属性hi有一个：disable的伪类
    子元素基于他的副元素位置会创建一个：nth-child()的伪类括号内是参数可以是整数或关键字还有an+b，odd表示奇数 even表示偶数
    ：nth-last-child()和nth-child用法类似只不过是倒过来数
    在子元素的副元素中可以使用：nth-of-type()选择类型和位置
    nth-last-of-type()类似
    选择副元素中第一个元素可以用：first-child相当于:nth-child(1)
    last-child相反
    某个类型的第一个元素可以用：first-of-type，最后一个用last-of-type
    副类元素中只有一个子元素的用：only-child或者是：first-child：last-child
    ：only-of-type类似
    空白元素用：empty
    除了某些元素的选择可以使用：not()
    选择段落中第一行用：：first-line 第一个文字用：：first-letter
    选择某个元素之前用：：before，之后用：：after
- 组合类型选择器用空格分开称之后裔
- 想选择元素直接的子元素，而不包括其他的加上一个>
- 选择兄弟元素可以用+ 连续的用~
# 动画
- 编辑动画用transition-property:这里写变化的属性
    transition-duration：表示动画的时间
    transition-delay：表示动画的延迟效果
    transition-timing-function：cubic-bezier（0,0,0,0）括号中件表示过程的进度