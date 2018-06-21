# Spring Cloud  Eureka Zuul and Hystrix Example

## Components
- `techprimers-service` - The Eureka service which is the Service Registry
- `techprimers-server` - The Service which is going to give data to the Client.
- `techprimers-client` - The Service which is going to get data from Server via the Discovery Service from the Service Registry (`techprimers-service`).
- `techprimers-zuul` - The Service which is going to get data from Eureka Service  Discovery (`techprimers-client`).  


-MicroServcie working princple 
<img src="https://github.com/DaqingFeng/spring-colud-zuul-eureka-sample/blob/master/picture/Java-microservices.jpg">


- Project Strucure
<img  src="https://github.com/DaqingFeng/spring-colud-zuul-eureka-sample/blob/master/picture/projectStructure.png" >


- Project Strucure
<img  src="https://github.com/DaqingFeng/spring-colud-zuul-eureka-sample/blob/master/picture/projectStructure.png" />


- eureka service 
<img  src="https://raw.githubusercontent.com/DaqingFeng/spring-colud-zuul-eureka-sample/master/picture/eureka.png" />


- eureka client 
<img  src="https://raw.githubusercontent.com/DaqingFeng/spring-colud-zuul-eureka-sample/master/picture/eurekaclient.png" />


- zuul proxy
<img  src="https://raw.githubusercontent.com/DaqingFeng/spring-colud-zuul-eureka-sample/master/picture/zuulproxy.png" />