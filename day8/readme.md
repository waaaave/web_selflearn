# 媒体查询
- @media（orientation//查询媒体：portrait//垂直方向）{...}
- 媒体宽度小于480px
    @media(max-device-width:480px){...}
- 可视窗口宽高比
    （aspect-ratio：x/y）{}
- 设备的宽高比
    （device-aspect-ratio）{}
- 设备使用方向
    orientation：landscape水平方向/portrait竖直方向
- hight是窗口高度device-hight是设备高度，width同样
- resolution是像素密度
- 使用and可以连接多个查询方式相当于与条件，用逗号相当于或条件，not相当于非条件
# 响应式导航
- 