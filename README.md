# my-exp-of-android
Write down the problem &amp; solution in my work . Hoping it's not too late.

mkdirs()可以建立多级文件夹， mkdir()只会建立一级的文件夹， 如下：
new File("/tmp/one/two/three").mkdirs();
执行后， 会建立tmp/one/two/three四级目录
new File("/tmp/one/two/three").mkdir();
则不会建立任何目录， 因为找不到/tmp/one/two目录， 结果返回false


应用启动会有黑屏1秒左右现象。
改变开屏页theme，添加window:background为开屏页图片。
