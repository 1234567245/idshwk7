1、将学号姓名（57117205HYZ）使用Base64转换成ASCII码：NTcxMTcyMDVIWVo=
2、将该ASCII码放入 信息.txt
3、将txt与需要隐藏的test1.jpg/test2.png放一起
4、在cmd中进入该文件夹目录，使用copy命令将二者合成成新的test3.jpg/test4.png
5、使用文本文档形式打开test.jpg/test.png即可发现 NTcxMTcyMDVIWVo=
6、注意！！！！！！因为在合成后打开合成的图片发现图片打不开。。。。所以就换了颜色隐藏那种方法：使用python LSBSteg.py encode –i test1.png -o test.png -f info.txt
生成的最终结果test.png
7、解密后可以得到57117205HYZ
