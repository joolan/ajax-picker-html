html仿京东移动端地址选择器，支持动态获取层级数据，理论支持N个层级，支持层级中途无下一层级时确定选择结构；

本项目改编自https://github.com/huangjieqiu/ajax-picker ，主要优化为支持无下级时提前结束选择（比如四级地址选择，存在有的地区可能只能选到第三级就结束了没有第4级的选项）

该层级选择器不仅仅可用于地址选择，它就相当于是个多层级选择器，你想做成分类筛选也是一样的道理，比如选“电子产品--家电/办公--- 洗衣机/打印机”这种有层级关系的。

# 使用说明
1、直接运行demo下的index.html文件查看效果

2、本身只是对demo下的ajax-picker.min.js进行了二次修改优化，没有修改原项目src下的ajax-picker.js等项目文件

3、如果想要编译或修改ajax-picker.js项目文件，可以参考demo下的ajax-picker.min.js进行修改，反正我是直接用demo文件夹就可以了



博文地址：https://ranjuan.cn/address-picker-html/
