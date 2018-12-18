# DemoForCamera2

## reference Link

[CV深度学习模型Android端落地方案之一：使用Android Camera2接口获得实时预览图像](https://blog.csdn.net/tonydandelion2014/article/details/85039451)  
[CV深度学习模型Android端落地方案之二：使用Face类进行实时人脸检测并将人脸框出](https://blog.csdn.net/tonydandelion2014/article/details/85058178)  


## usage
Using Function ```do_something()``` in **Camera2BasicFragment.java** add your own code which process a bitmap object and show the result nearby the rectangle coordinate.  


## do_something() API
```
@parameters:  
	bmp: Bitmap Object (the bitmap for process)  
	located: Integer Array (the rectangle coordinate{left, top, right, bottom})  
@return: void  
```
