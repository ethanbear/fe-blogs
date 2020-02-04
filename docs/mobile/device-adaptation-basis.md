# 基础概念

## 设备独立像素 DeviceIndepentPixels 

- 由于不同的设备具备不同的分辨率。实际开发过程中我们需要一个统一的单位来告诉设备界面上某个元素需要显示的大小。

- 这个单位就是设备独立像素(DeviceIndepentPixels)，也称密度无关像素。

> DIP可以理解为计算机系统中的一点，这个点是逻辑上理解的像素，并非屏幕渲染时实际的像素。

- 打开Chrome开发者工具后模拟各个手机型号的时候，其对应的尺寸是指设备独立像素，而非物理像素。

- W3C社区制定的css像素指编写css过程中所使用的px单位即为设备独立像素一种。也可以理解为逻辑像素。其他如图片的分辨率所提到的如1920*1080也是逻辑像素。

## 设备物理像素 

设备像素设是物理概念，指的是设备中使用的物理像素。
比如iPhone 5的分辨率640 x 1136px。

## 设备像素比(device pixel ratio)

DPR = DIP / 物理像素

在某些浏览器中，可以通过window.devicePixelRatio来获取该值；

##  