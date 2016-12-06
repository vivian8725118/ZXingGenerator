# ZXingGenerator
二维码生成
#Usage
QRCode.java文件中提供了6种生成二维码的样式，可直接按照如下方式使用。
```
qrcode1.setImageBitmap(QRCode.createQRCode("http://www.tmtpost.com/2536837.html"));
qrcode2.setImageBitmap(QRCode.createQRCodeWithLogo2("http://www.jianshu.com/users/4a4eb4feee62/latest_articles", 500, drawableToBitmap(getResources().getDrawable(R.drawable.head))));
qrcode3.setImageBitmap(QRCode.createQRCodeWithLogo3("http://www.jianshu.com/users/4a4eb4feee62/latest_articles", 500, drawableToBitmap(getResources().getDrawable(R.drawable.head))));
qrcode4.setImageBitmap(QRCode.createQRCodeWithLogo4("http://www.jianshu.com/users/4a4eb4feee62/latest_articles", 500, drawableToBitmap(getResources().getDrawable(R.drawable.head))));
qrcode5.setImageBitmap(QRCode.createQRCodeWithLogo5("http://www.jianshu.com/users/4a4eb4feee62/latest_articles", 500, drawableToBitmap(getResources().getDrawable(R.drawable.head))));
qrcode6.setImageBitmap(QRCode.createQRCodeWithLogo6("http://www.jianshu.com/users/4a4eb4feee62/latest_articles", 500, drawableToBitmap(getResources().getDrawable(R.drawable.head))));
   
```


##效果图
<img src="https://github.com/vivian8725118/ZXingDemo/blob/master/art/S61128-17080029.jpg" width="50%" height="50%"/>
