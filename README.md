# microservices-links
good resources about microservices, cloud, distributed systems archetictures and tools

#archeticture
  - https://microservices.io/patterns/microservices.html
  - https://docs.microsoft.com/en-us/dotnet/standard/microservices-architecture/ 
  - https://docs.microsoft.com/en-us/azure/architecture/patterns/
  
#spring-boot
  - https://www.javainuse.com/spring/springcloud
  - https://spring.io/blog/2018/06/20/the-road-to-reactive-spring-cloud
  - https://medium.com/@lhartikk/development-environment-in-spring-boot-with-docker-734ad6c50b34
  - https://www.baeldung.com/spring-cloud-bus #externa-config
  - https://github.com/joshlong/bootiful-reactive-microservices
  - https://cloud.spring.io/spring-cloud-gateway/single/spring-cloud-gateway.html #gateway
  
#Circuit breakers
- https://github.com/RobWin/resilience4j-spring-boot2-demo
- http://resilience4j.github.io/resilience4j/

#rate-limiting
- https://windmt.com/2018/05/09/spring-cloud-15-spring-cloud-gateway-ratelimiter/

#reactivity
- https://spring.io/blog/2016/06/07/notes-on-reactive-programming-part-i-the-reactive-landscape
- https://spring.io/blog/2016/06/13/notes-on-reactive-programming-part-ii-writing-some-code
- https://spring.io/blog/2016/07/20/notes-on-reactive-programming-part-iii-a-simple-http-server-application
- https://dzone.com/articles/reactive-spring-5-and-application-design-impact
- https://medium.com/@cheron.antoine/tuto-building-a-reactive-restful-api-with-spring-webflux-java-258fd4dbae41 [configuring more threads for reactor]
- https://dzone.com/articles/the-road-to-reactive-spring-cloud
- https://www.codingame.com/playgrounds/929/reactive-programming-with-reactor-3
  
#service-discovery
- https://piotrminkowski.wordpress.com/2018/05/04/reactive-microservices-with-spring-webflux-and-spring-cloud/
- https://thehecklers.com/register-instances-eureka/
- https://stackoverflow.com/questions/33921557/understanding-spring-cloud-eureka-server-self-preservation-and-renew-threshold
- https://itnext.io/how-to-use-netflixs-eureka-and-spring-cloud-for-service-registry-8b43c8acdf4e (mixes node & boot services)
- http://pscode.rs/spring-cloud-with-spring-config-and-eureka-in-high-availability-using-docker-swarm/

#scaling #performace-testing
  - https://dzone.com/articles/go-microservices-part-5-deploying-on-docker-swarm
  - https://workwiththebest.intraway.com/white-paper/Testing-Reactive-Microservices-With-Spring-Webflux/


#full-examples:
  - https://github.com/sivaprasadreddy/spring-boot-microservices-series/blob/master/docker-compose.yml
  - https://github.com/noorulhaq/reactive.loanbroker.system (full reactive, article: https://dzone.com/articles/functional-amp-reactive-spring-along-with-netflix)
  - https://piotrminkowski.wordpress.com/2018/05/04/reactive-microservices-with-spring-webflux-and-spring-cloud/
  - https://github.com/zhaoyibo/spring-cloud-study
  
#Security
  - https://medium.com/@ard333/authentication-and-authorization-using-jwt-on-spring-webflux-29b81f813e78
  - https://github.com/rwinch/spring-security51-by-example-reactive / https://www.youtube.com/watch?v=YcAufUtfm44
  - https://spring.io/blog/2018/01/30/next-generation-oauth-2-0-support-with-spring-security #important
  - https://docs.spring.io/spring-security-oauth2-boot/docs/current-SNAPSHOT/reference/htmlsingle/#oauth2-boot-authorization-server-spring-security-oauth2-resource-server-jwk-set-uri #jwt #oauth2-server
  - http://www.tinmegali.com/en/2017/06/25/oauth2-using-spring/
  - https://github.com/spring-tips/spring-security-5-oauth-client (local oauth2 server, jwt + oauth 2 client)
  
  
#kafka
- https://github.com/wurstmeister/kafka-docker
- https://www.kaaproject.org/kafka-docker/


#Monitoring & Tracing
 - https://medium.com/oracledevs/using-prometheus-to-monitor-apps-on-oracle-cloud-7b75dea9f2f3
 - #zpkin #slueth:
    - https://github.com/openzipkin/zipkin
    - https://cloud.spring.io/spring-cloud-static/spring-cloud-sleuth/2.1.0.RC3/single/spring-cloud-sleuth.html
    
#boot_actuator & boot_admin
 - https://dzone.com/articles/spring-boot-actuator-in-spring-boot-20 
 - https://www.vojtechruzicka.com/spring-boot-admin/
 - https://codecentric.github.io/spring-boot-admin/current/ (offical docs)
 - https://zoltanaltfatter.com/2018/05/15/spring-cloud-discovery-with-spring-boot-admin/ (eurka instead of admin-client)
 - https://github.com/joshiste/spring-boot-admin-samples
