# sample-config
Spring Cloud External Configuration Repository


git clone https://github.com/rohitghatol/spring-boot-microservices

1. Config Server              配置服务，其他的服务都从该服务器上获取配置
2. Webservice Registry        启动Eureka提供微服务注册功能
3. Web Portal                 提供UI前端静态文件的微服务
4. User Webservice            基于用户实体的微服务
5. Auth Server                Oauth 认证微服务
6. Api Gateway                使用Zuul Proxy 集成前后端，包括4,5的Api与3的Ui

http://jhipster.github.io/microservices-architecture/
![microservices-architecture](http://jhipster.github.io/images/microservices_architecture_1.png "microservices-architecture")
