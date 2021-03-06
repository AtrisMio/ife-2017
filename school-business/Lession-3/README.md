# [巨型画布](http://ife.baidu.com/course/detail/id/19)

[马海娜](http://ife.baidu.com/mentor/detail/id/5) | [商业平台学院](http://ife.baidu.com/college/detail/id/5)

时间  平均用时0.0天

### 课程概述

作业提交截止时间：04-24

## 任务描述

* 首先，我们需要一个巨型画布
>* 这个画布不是大，而是巨大。它所支持的图片分辨率应当达到19200 x 10800。
>* 我们不希望看到一个尺寸巨大的canvas容器，将整个图片显示出来。
>* 呈现给用户的画布尺寸，最大分辨率是1024 x 768，画布只显示图片的一部分（暂时不考虑图片缩放显示）。
* 其次，我们希望这个画布支持拖拽
>* 画布只能显示图片的一部分，我们希望通过鼠标在画布上的拖动，查看图片的其他部分。
>* 为了不影响运行效率，鼠标拖拽的过程中，可以不做效果处理，只在鼠标抬起后，给出交互结果。
* 第三，我们需要一个缩略图
>* 画布只能显示图片的一部分，我们希望在画布旁边，有一个小图，能显示整张图片。
>* 我们希望缩略图上有一个框，框出当前画布所显示的图片区域。当然，用户在画布上拖拽时，这个框要随之移动。

![http://i1.baidu.com/it/u=1153308557,2550933973&fm=202](http://i1.baidu.com/it/u=1153308557,2550933973&fm=202)

* 第四，这个画布应当是可编辑的
>* 你可以自行设计一些编辑项目，比如鼠标点击时，在鼠标点击位置绘制一个圆点。
* 第五，请在demo中给出一张图片
>* 这张图片可以以任何形式给出，动用你的想象力。

## 任务注意事项

* 请提交工程在github的托管地址
* **请尽量使用JS原生API开发**，允许使用jQuery等简单框架
* 请合理组织代码结构，添加必要的注释
* 工程以index.html启动，第三方库放在dep文件夹中，项目代码放在src文件夹中
* 如工程需要构建或特殊启动流程，请在readme.md中提供

## 参考文献

* [RGB颜色空间新的色差公式](http://wenku.baidu.com/link?url=ejQyrhRTaaiHVjanXnqHOnL1HmNorfq1icgud_85LqJ3w_t4wv1hTYzbF-Q74tCdwS8oYR_p76pKvhTKjJpmbFf9WpEhNNDkYNIyUkxv3Ti)