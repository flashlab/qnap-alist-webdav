# 多云盘挂载集成工具 for QNAP
### Alist webdav for QNAP
A file list program that supports multiple storage, powered by Gin and Solidjs.

## 介绍
一款支持多种存储，支持网页浏览和 WebDAV 的文件列表程序，支持挂载本地存储、阿里云盘、百度网盘、OneDrive、Google Drive 等。

* Alist 版开源：https://github.com/alist-org/alist


## 如何使用
在QNAP系统，通过App Center手动安装 ***.qpkg*** 后辍程序。

* 支持 x86_64 构架的QNAP存储设备
* 支持 ARM 构架的QNAP存储设备
* 支持 aach64 构架的QNAP存储设备

## WebDAV 存储支持
| 存储类型| 	列出文件/文件夹	| 下载文件| 	创建目录| 	重命名| 	移动| 	复制| 	上传文件/文件夹| 
| :--------:   | :--------:  | :--------:  |:--------:  |:--------:  |:--------:  |:--------: |:--------: |
| 本地存储|	✅|	✅|	✅|	✅|	✅|	✅|	✅|
| 阿里云盘|	✅|	✅|	✅|	✅|	✅|	✅|	✅|
| Onedrive|	✅|	✅|	✅|	✅|	✅|	✅|	✅|
| 天翼云盘|	✅|	✅|	✅|	✅|	✅|	✅|	✅|
| GoogleDrive|	✅|	✅|	✅|	✅|	✅|	❌|	✅|
| 123pan|	✅|	✅|	✅|	✅|	✅|	❌|	✅|
| FTP|	✅|	✅|	✅|	✅|	✅|	❌|	✅|
| SFTP|	✅|	✅|	✅|	✅|	✅|	❌|	✅|
| PikPak|	✅|	✅|	✅|	✅|	✅|	✅|	✅|
| S3|	✅|	✅|	✅|	✅|	✅|	✅|	✅|
| USS|	✅|	✅|	✅|	✅|	✅|	✅|	✅|
| WebDAV|	✅|	✅|	✅|	✅|	✅|	✅|	✅|
| Teambition|	✅|	✅|	✅|	✅|	✅|	✅|	✅|
| 分秒帧|	✅|	✅|	✅|	✅|	✅|	✅|	✅|
| 和彩云|	✅|	✅|	✅|	✅|	✅|	✅|	✅|
| YandexDisk|	✅|	✅|	✅|	✅|	✅|	✅|	✅|
| 百度网盘|	✅|	✅|	✅|	✅|	✅|	✅|	✅|
| 夸克网盘|	✅|	✅|	✅|	✅|	✅|	✅|	✅|

## 注意
* 由于阿里云盘 referer 的限制，必须使用移动端 token。 使用桌面 Web 令牌将导致无法下载和预览。
* 点击这里获取移动版阿里云盘token ：https://alist.nn.ci/zh/guide/drivers/aliyundrive.html

## 如何获取Token


## 配置示意图 

 

## 本软件为免费开源项目，无任何形式的盈利行为。
 1. 本软件为免费开源项目，无任何形式的盈利行为。
 2. 本软件服务于阿里云盘，旨在让阿里云盘功能更强大。如有侵权，请与我联系，会及时处理。
 3. 本软件皆调用官方接口实现，无任何“Hack”行为，无破坏官方接口行为。
 4. 本软件仅做流量转发，不拦截、存储、篡改任何用户数据。
 5. 严禁使用本软件进行盈利、损坏官方、散落任何违法信息等行为。
 6. 本软件不作任何稳定性的承诺，如因使用本软件导致的文件丢失、文件破坏等意外情况，均与本软件无关。
