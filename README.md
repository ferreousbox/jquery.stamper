jquery.stamper
==============

一款在网页上模拟现实中的盖章效果的jQuery插件


1、说明
------------------

jquery.stamper是一款模拟现实中盖章效果的jquery插件，通过动画的形式展现盖章效果。[访问GitHub项目库](https://github.com/ferreousbox/jquery.stamper)


2、使用
-------------------

在页面上引入jquery和jquery.stamper两个JS文件：

    <script src="jquery-1.10.2.min.js"></script>
    <script src="jquery.stamper.js"></script>

然后在需要盖章的元素上调用jquery.stamper即可，如下：

    $("#elementId").stamper({
        image : "images/stamper.png"
    });


3、参数
-----------------

jquery.stamper可配置的参数如下：

1.id：img对象的id，指定不同的id则会生成不同的img对象，默认是jquery_stamper_img <br>
2.image：章的图片路径，必须指定 <br>
3.scale：章图片的放大倍数，默认5倍。如果设置过大可能会超出屏幕大小太多导致较长时间才会显示 <br>
4.speed：效果速度值，默认是600（单位毫秒）。通常与scale配合一起决定整个效果的时间 <br>

