- spring-boot-sample-ant >>> ant run
- spring-boot-sample-activemq >>> activeMQ, producer, Consumer
- spring-boot-sample-actuator >>> actuator, health, info, metrics with spring security, full test cases
- spring-boot-sample-actuator-log4j2 >>> ????
- spring-boot-sample-actuator-noweb >>> ????
- spring-boot-sample-actuator-ui >>> actuator, health, info, metrics with spring security, with UI
- spring-boot-sample-actuator-custom-security >>> actuator, health, info, metrics with spring security (user, admin), with UI http://localhost:8080/actuator/health
- spring-boot-sample-amqp >>> rabbit MQ >>> Docker Compose up >>> build amqp and connect to amqp to send msg
- spring-boot-sample-animated-banner >>> custom banner.gif when you are starting server
- spring-boot-sample-aop >>> AOP pointcut method checking, execution after called
- spring-boot-sample-atmosphere >>> web Chate websocket,
- spring-boot-sample-batch >>> batch process, job, step, task
- spring-boot-sample-cache >>> Cache config file.xml, CacheManager provide cache
- spring-boot-sample-custom-layout >>> ???
- spring-boot-sample-data-cassandra >>> spring data with cassandra database none-sql,
        docker run --name cassandra-node -p 9042:9042 -d cassandra,
        docker exec -it cassandra-node bash,
        cqlsh,
        ref: https://medium.com/@phayao/%E0%B8%AA%E0%B8%A3%E0%B9%89%E0%B8%B2%E0%B8%87-microservice-cassandra-%E0%B8%94%E0%B9%89%E0%B8%A7%E0%B8%A2-spring-boot-spring-data-a28ec9cec3ba
- spring-boot-sample-data-couchbase >>> spring-data for couchbase none-sql on mobile
- spring-boot-sample-data-elasticsearch >>>
    start elasticsearch with docker: curl https://gist.githubusercontent.com/markheath/f246ec3aa5a3e7493991904e241a416a/raw/c4fa64575bc854e34a2506291bd14033caf5e9b6/docker-compose-v1.yml > docker-compose-v1.yml
    ref: https://markheath.net/post/exploring-elasticsearch-with-docker,
    ref: https://mkyong.com/spring-boot/spring-boot-spring-data-elasticsearch-example/
- spring-boot-sample-data-jpa >>> h2 database with spring data
- spring-boot-sample-data-ldap >>> LDAP JPA simple
- spring-boot-sample-data-mongodb >>> Spring data with embedmongo-db,findAll, findById, save
- spring-boot-sample-data-neo4j >>> Spring data with embedneo4j-db,findAll, findById, save
- spring-boot-sample-data-redis >>>
    docker pull bitnami/redis,
    docker run --name redis_cont -e ALLOW_EMPTY_PASSWORD=yes bitnami/redis:latest
    ref: https://medium.com/@phayao/%E0%B8%AA%E0%B8%A3%E0%B9%89%E0%B8%B2%E0%B8%87-microservice-redis-%E0%B8%94%E0%B9%89%E0%B8%A7%E0%B8%A2-spring-boot-spring-data-f7a43e3f2522
    ref: https://github.com/anacondong/spring-boot-redis
- spring-boot-sample-data-rest >>> *** API with spring data, database h2, Restful api >>> http://localhost:8080/api/cities/search/findByNameContainingAndCountryContainingAllIgnoringCase?name=&country=UK
- spring-boot-sample-data-solr >>> spring data with solr
- spring-boot-sample-devtools >>> devtools access resources
- spring-boot-sample-flyway >>> controll excution script data base
- spring-boot-sample-hateoas >>> spring-data, API restful, hateoas inmemory
- spring-boot-sample-integration >>> ?????
- spring-boot-sample-jersey >>> spring-boot-jersey >> API
- spring-boot-sample-jersey1 >>> very Simple spring-boot-jersey >> API
- spring-boot-sample-jetty >>> API spring boot restful with server jetty
- spring-boot-sample-jetty-jsp >>> Spring web app MVC, JSP,  exception handler, server jetty
- spring-boot-sample-jetty-ssl >>> SSL web with jetty ssl >>> https://localhost:8443/
- spring-boot-sample-jooq >>> Tools Generate Model from Data base object
- spring-boot-sample-jpa >>> jpa, web , sql
- spring-boot-sample-jta-atomikos >>> JMS Message Q, Active MQ atomikos
- spring-boot-sample-jta-bitronix >>> JMS Message Q, Active MQ bitronix
- spring-boot-sample-jta-narayana >>> JMS Message Q, Active MQ narayana
- spring-boot-sample-jta-jndi >>> JMS Message Q, Jboss, Restfull
- spring-boot-sample-junit-jupiter >>> sample junit jupiter
- spring-boot-sample-kafka >>> spring boot sample kafka >> Consumer, Producer
- spring-boot-sample-liquibase >>> spring boot sample liquibase
- spring-boot-sample-logback >>> Config logback >> Debug, TRACE
- spring-boot-sample-oauth2-client >>> **** Spring boot sample connect Oauth2 client to Github to get data from resources server

    == Register Github OAuth2 application
   To run the sample, you need to link:https://github.com/settings/applications/new[register an OAuth application on Github].
   While registering your application, ensure the Authorization callback URL is set to http://localhost:8080/login/oauth2/code/github.
   After completing the registration, you will have a new OAuth Application with a Client ID and Client Secret.

- spring-boot-sample-parent-context >>> ????
- spring-boot-sample-profile >>> spring profile run by evn
- spring-boot-sample-property-validation >>> spring boot load properties >> @ConfigurationProperties
- spring-boot-sample-quartz >>> Quartz Job,Task, excuting
- spring-boot-sample-secure >>> secure >> role stick to use service method
- spring-boot-sample-secure-webflux >>> unitest with spring security
- spring-boot-sample-servlet >>> Servlet
- spring-boot-sample-session >>> Handle HttpSession
- spring-boot-sample-session-webflux >>> Handle WebSession
- spring-boot-sample-simple >>> Simple Template project
- spring-boot-sample-test >>> Simple Template Web project including Unittest
- spring-boot-sample-test-nomockito >>> ???
- spring-boot-sample-testng >>> ???
- spring-boot-sample-tomcat >>> embedded Tomcat server
- spring-boot-sample-tomcat-jsp >>> *** spring boot MVC , Tomcat server, Simple Template
- spring-boot-sample-tomcat-ssl >>> Tomcat SSL,cert >>> https:
- spring-boot-sample-tomcat-multi-connectors >>> multi connectors cat SSL,cert >>> https:
- spring-boot-sample-traditional >>> Spring MVC old school style
- spring-boot-sample-undertow >>> ???
- spring-boot-sample-undertow-ssl >>> ???
- spring-boot-sample-war >>> packaging war file
- spring-boot-sample-web-freemarker >>> spring web freemarker template
- spring-boot-sample-web-groovy-templates >>> Spring MVC, Groovy on Rail template
- spring-boot-sample-web-jsp >>> Sample web jsp
- spring-boot-sample-web-method-security >>> Sample MVC with method security
- spring-boot-sample-web-mustache >>> spring mvc Error handler, redirect to error page
- spring-boot-sample-web-secure >>> *** Init project spring MVC, Spring security, error handler
- spring-boot-sample-web-secure-custom >>> spring MVC, Spring security
- spring-boot-sample-web-secure-jdbc >>> *** Init project spring MVC, Spring security, error handler, JDBC
- spring-boot-sample-web-static >>> static html website
- spring-boot-sample-web-ui >>> Spring MVC with UI template
- spring-boot-sample-webflux >>> ???
- spring-boot-sample-websocket-jetty >>>  spring web socket wit jetty server
- spring-boot-sample-websocket-tomcat >>> spring web socket wit tomcat server
- spring-boot-sample-websocket-undertow >>> spring web socket wit undertow server
- spring-boot-sample-webservices >>> spring webservice ???
- spring-boot-sample-xml >>> spring start with xml