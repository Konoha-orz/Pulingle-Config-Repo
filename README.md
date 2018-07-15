# Pulingle-Config-Repo
## Pulingle配置中心
托管在GitHub上的，Pulingle项目的统一管理微服务配置。配置信息通过config_server进行加解密,配置信息以密文存储。

###  为什么要统一管理配置?
* 集中管理配置:
Pulingle项目采用微服务架构，其应用系统包含多个微服务(message-service、user-service、moment-service、
picture-service)。集中管理配置可以更加高效方便。
* 不同环境不同配置：
数据源配置在不同的环境（开发、生成、不同服务器）中是不同的。例如在多台服务器（我们当时用的是阿里云的学生服务器）上部署同一个服务，其配置信息不同。
* 运行期间可动态调整：
可以根据各个微服务情况，动态调整不同的配置参数，并且在调整配置时不停止微服务。
## Pulingle项目
* 微服务</br>
用户服务:   [user-service](https://github.com/Konoha-orz/user_service)</br>
消息服务:   [message-service](https://github.com/Konoha-orz/message_service)</br>
图片服务:   [picture-service](https://github.com/Konoha-orz/picture_service)</br>
动态服务:   [moment-service](https://github.com/Konoha-orz/moment_service)</br>
* Spring Cloud 组件</br>
服务发现：[eureka_server](https://github.com/Konoha-orz/eureka_server)</br>
服务网关：[gateway_zuul](https://github.com/Konoha-orz/gateway_zuul)</br>
服务配置：[config_server](https://github.com/Konoha-orz/config_server)</br>
* 统一管理配置</br>
[Pulingle-Config-Repo](https://github.com/Konoha-orz/Pulingle-Config-Repo)</br>

### 项目演示</br>
* [视频演示地址](https://pulingle.oss-cn-shenzhen.aliyuncs.com/Pulingle%E6%BC%94%E7%A4%BA%E5%BD%95%E5%B1%8F.mp4)</br>
