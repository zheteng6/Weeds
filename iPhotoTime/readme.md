iPhotoTime
====

用来批量修改从 iOS 设备导出的照片、视频的文件名，给其添加日期前缀。
如： `IMG_2242.JPG -> 20140812_IMG_2242.JPG`
默认以照片内含时间信息为准，如文件内无时间信息则以文件创建日期为准。


用法
====

1. 将照片导入到一个指定目录，如: `~/xxx`
2. 直接以目录为参数调用即可: `./iPhotoTime.py ~/xxx`