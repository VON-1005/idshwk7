使用盲水印的方式实现，采用课上讲的blind-watermark工具

原图为orig.jpg，加了水印后的图为test.png

添加水印：python encode.py --image orig.jpg --watermark watermark.png --result test.png

解密方法：python decode.py --image test.png --orig orig.jpg --result watermarkRes.png
