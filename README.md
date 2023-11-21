# Openmv
#
# sensor(感光元件)
import sensor#引入感光元件的模块

# 设置摄像头
sensor.reset()#初始化感光元件
sensor.set_pixformat(sensor.RGB565)#设置为彩色
sensor.set_framesize(sensor.QVGA)#设置图像的大小
sensor.skip_frames()#跳过n张照片，在更改设置后，跳过一些帧，等待感光元件变稳定。

# 一直拍照
while(True):
    img = sensor.snapshot()#拍摄一张照片，img为一个image对象

sensor.set_pixformat() 设置像素模式。\n
sensor.GRAYSCALE: 灰度，每个像素8bit。\n\r
sensor.RGB565: 彩色，每个像素16bit。
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
