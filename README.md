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
* 微服务
用户服务:   [user-service](https://github.com/Konoha-orz/user_service)
消息服务:   [message-service](https://github.com/Konoha-orz/message_service)
图片服务:   [picture-service](https://github.com/Konoha-orz/picture_service)
动态服务:   [moment-service](https://github.com/Konoha-orz/moment_service)
* Spring Cloud 组件
服务发现：[eureka_server](https://github.com/Konoha-orz/eureka_server)
服务网关：[gateway_zuul](https://github.com/Konoha-orz/gateway_zuul)
服务配置：[config_server](https://github.com/Konoha-orz/config_server)
* 统一管理配置
[Pulingle-Config-Repo](https://github.com/Konoha-orz/Pulingle-Config-Repo)
