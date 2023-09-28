# JPEG高清压缩库

在保证高清质量的条件下大大压缩文件存储大小。

### [NativeImageUtils](jpegTurboLibrary/src/main/java/com/dds/ndkimage/NativeImageUtils.java)

#### 将Bitmap压缩后存到文件：**compressBitmap(Bitmap b, int q, String p)**

| 参数 | 描述 |
|:---|:---|
|b|位图|
|q|quality-压缩质量(0 ~ 100)|
|p|压缩后保存路径|

#### 获取文件的缩略图：**zoomCompress(String input, String output, int q)**

| 参数 | 描述 |
|:---|:---|
|input|源图|
|output|缩率图|
|q|quality-压缩质量(0 ~ 100)|
