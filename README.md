# SpringCloudEurekaServer
SpringCloud可运行工程

记录
配置 [peer-eureka-nodes-update-interval-ms: 0] 会导致启动异常 

Exception encountered during context initialization - cancelling refresh attempt: org.springframework.beans.factory.UnsatisfiedDependencyException: Error creating bean with name 'org.springframework.cloud.netflix.eureka.server.EurekaServerInitializerConfiguration': Unsatisfied dependency expressed through field 'eurekaServerBootstrap'; nested exception is org.springframework.beans.factory.UnsatisfiedDependencyException: Error creating bean with name 'eurekaServerBootstrap' defined in class path resource [org/springframework/cloud/netflix/eureka/server/EurekaServerAutoConfiguration.class]: Unsatisfied dependency expressed through method 'eurekaServerBootstrap' parameter 1; nested exception is org.springframework.beans.factory.BeanCreationException: Error creating bean with name 'eurekaServerContext': Invocation of init method failed; nested exception is java.lang.IllegalStateException: java.lang.IllegalArgumentException
