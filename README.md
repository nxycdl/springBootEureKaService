# springBootEureKaService

三台主机的集群Eureka 服务<br>
需要注意的是配置文件里面 spring.boot.admin.client.url 地址和 eureka注册的集群地址,采用相互注册的方式<br>

java -jar springbooteurekaservice-0.0.1-SNAPSHOT.jar --spring.profiles.active = peer112

java -jar springbooteurekaservice-0.0.1-SNAPSHOT.jar --spring.profiles.active = peer136

java -jar springbooteurekaservice-0.0.1-SNAPSHOT.jar --spring.profiles.active = peer85

java -jar springbooteurekaservice-0.0.1-SNAPSHOT.jar --spring.profiles.active = peer135

mvn clean package -Dmaven.test.skip=true

