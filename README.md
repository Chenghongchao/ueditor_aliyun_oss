# ueditor_aliyun_oss
一、本项目里面的所有阿里云配置均已禁用，因此需要修改阿里云的配置信息
OSSKey.properties 配置文件参数描述
useStatus  true/false是否启用云存储，
autoCreateBucket   true/false是否添加新的存储仓库，默认false
key        仓库权限key
secret     仓库权限secret
bucketName  云存储仓库的名称
ossEndPoint  ueditor显示图片的访问域名
ossCliendEndPoint   阿里云文件存储的endpoint,在仓库概览里面可以看到
useCDN   true/false是否启用cdn加速
cdnEndPoint   cdn加速域名配置
useLocalStorager 是否启用本地存储
useAsynUploader  是否启用异步上传
二、启动运行项目
1、本项目编译环境，1.6及以上环境，idea 2016.2
2、测试http://localhost:8080/common/ueditor1_4_3-utf8-jsp/jsp/controller.jsp 如果不能正常访问那么上传文件就不能使用
3、可以直接运行，idea运行时的测试路径，因个人环境配置有直接关系，eclipse需要加上项目名称才能运行
http://localhost:8080/common/ueditor1_4_3-utf8-jsp/index.html
三、直接使用编译后的本项目到页面环境配置
1、直接将
