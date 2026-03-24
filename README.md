# Watermark

## 功能总览

+ 支持文字水印和图片水印
+ 插件只是在输出时过滤了图片链接，不对实际上传的图片进行任何修改
+ 插件目录下的lh.ttf为字体文件，如果需要添加自己的字体文件，需上传放在插件目录下，然后在插件设置里设定。
+ VM.png 为水印图标文件，可自行上传自己的图标文件，然后在插件设置中设定。
+ 插件激活时会在 usr 目录下创建 img 目录，如果创建不成功则无法使用缓存功能，如需清除缓存可以在本插件设置页面底部缓存设置那里有个链接，点击即可清除缓存文件。
+ 



## 测试环境

+ 测试日期:202603
+ 软件环境:
  + apache2.4
  + php8.3
  + php-gd
  + php-fpm
+ 



## 安装方法

1. 首先下载插件

2. 然后把插件释放到` /usr/plugins/Watermark`

3. 最后的目录结构为

   ```
   # tree usr/plugins/Watermark/
   usr/plugins/Watermark/
   ├── Action.php
   ├── AnkeCalligraph.TTF
   ├── class.php
   ├── lh.ttf
   ├── Plugin.php
   ├── README.md
   └── WM.png
   ```

4. 



## 版本总览

### 1.3.0

针对typecho 1.3 修复了以下问题:

- [x] 修复缓存插件不生效的问题
- [x] 修复缓存删除功能失效的问题
- [x] 版本号对齐typecho主版本号



### 1.2.0

+ 这个插件来自于defe在2013年发布的[Watermark v1.2.0](http://defe.me/prg/431.html)

