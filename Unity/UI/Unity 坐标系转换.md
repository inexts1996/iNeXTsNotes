一直搞不明白Unity各种坐标系之间的转换，特别是不同相机之间坐标的转换。其本上都是靠各种试，通常都要耗费很多时间。主要原因还是自己不清楚这些坐标系之间转换的原理。
## 同一个相机下
1. World Space到Screen Space的转换方式是：Camera.WorldToScreenPoint
2. Screen Space到World Space的转换方式是：Camera.ScreenToWorldPoint
