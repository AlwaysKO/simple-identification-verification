## PHP识别简单的图片验证码

思路：

解析出图片的像素以及每个像素的色素。

再算出数字对应色素的像素组合。

然后将图片的像素组合与数字的组合进行对比，得到对应的数字。

本文的情况只针对规则数字的验证码。无变形，无复杂多变的背景色，简单的验证码图片。