#

姓名：徐佳春
学校：同济大学
专业：计算机科学与技术专业，本科
年级：2023级毕业

因为目录下包含大量配置文件，上传比较耗时，所以将其压缩后上传了

## 第一周：双线程

- index.js和subThread.js

    1. index.js对应主线程，其中有一个getSum函数，计算两个参数的和
    2. subThread.js对应子线程，其中有一个getDifference函数，计算两个参数的差

- index.js中声明了两个get方法

    1. /main：主线程计算100+200的值
    2. /sub：主线程启动一个子线程，子线程计算100-200的值

- 启动

    ![这里是图片](/image/week1.1.png "week1的demo启动")

- 结果

    ![这里是图片](/image/week1.2.png "week1的/main请求")
    ![这里是图片](/image/week1.3.png "week1的/sub请求")

## 第二周：vdom渲染

- 代码

    主要参考了资料中的代码
    <https://juejin.cn/post/7055364698136379423>

- 启动

    ![这里是图片](/image/week2.1.png "week2的demo启动")

- 结果

    ![这里是图片](/image/week2.2.png "week2的主页")
    ![这里是图片](/image/week2.3.png "week2的点击事件")

## 第三周：react编译

- 代码

    主要参考了react的官方文档<https://react.docschina.org/tutorial/tutorial.html#setup-for-the-tutorial>
    配置了一个用babel编译react代码的环境
    可以直接在.js文件中使用react的语法

    ![这里是图片](/image/week3.1.png "week3的demo部分代码")

- 启动

    ![这里是图片](/image/week3.2.png "week3的demo启动")

- 结果

    ![这里是图片](/image/week3.3.png "week3的主页")

## 第四周：小程序运行时

因为精力和水平有限，所以没能实现最终的任务

对于js代码，我以前从来没有写过，所以在代码的局部细节和整体框架上都不是很熟练，开展项目时困难较大，不知道从何做起，遂放弃
