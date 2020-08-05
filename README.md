# spring-cloud-config
配置中心
配置了 application.yml 为总配置
里面指定 spring.profiles.active=dev 这个会生效找到 application-dev中的值

总结：pring-config真的不好用，修改了dev后不生效，要么就是pro生效

建议：如果是开关类的可以用spring-config,如果是控制生产环境还是测试环境，那还是要谨慎，总感觉要重启所有服务一样

springCloud-config 不爱你了
