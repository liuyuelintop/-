

![屏幕快照 2018-07-19 下午12.45.53.png](https://upload-images.jianshu.io/upload_images/13089440-b28c40573a25d100.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

when I click the button "加入购物车“
I get an error:
![屏幕快照 2018-07-19 下午12.50.59.png](https://upload-images.jianshu.io/upload_images/13089440-2acbd0396aca1ec7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

Check app/models/cart.rb, I found that method add_product_to_cart(product) wasn't defined:
![屏幕快照 2018-07-19 下午10.14.38.png](https://upload-images.jianshu.io/upload_images/13089440-3860a72e3a0c9718.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



After adding code to  /app/models/cart.rb:
![屏幕快照 2018-07-19 下午1.15.08.png](https://upload-images.jianshu.io/upload_images/13089440-a68b3e696f9ec83f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
I got it:

![屏幕快照 2018-07-19 下午1.16.20.png](https://upload-images.jianshu.io/upload_images/13089440-09b70b7fed49dc17.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

刘月林
写于湖北沙洋
2018/07/19
