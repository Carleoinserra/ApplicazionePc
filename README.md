![gradle](https://github.com/Carleoinserra/ApplicazionePc/assets/28870796/5f4e9773-032d-47f4-8980-6a701784ce52)                              ![sb](https://github.com/Carleoinserra/ApplicazionePc/assets/28870796/1744dbfb-0f2c-4845-a591-32e91fb0eaaf)
<h3> AppPc is an application created with Spring Boot and Gradle for dependency management.</h3>
<h6>It was created for the Talentform Web Programming course.</h6>
<hr>
<h3>Dipendencies</h3>
```groovy
implementation 'org.springframework.boot:spring-boot-starter-mail'
implementation 'org.springframework.boot:spring-boot-starter-data-jdbc'
implementation 'org.springframework.boot:spring-boot-starter-thymeleaf'
implementation 'org.springframework.boot:spring-boot-starter-web'
implementation 'com.fasterxml.jackson.core:jackson-databind:2.17.1' 
developmentOnly 'org.springframework.boot:spring-boot-devtools'
runtimeOnly 'com.mysql:mysql-connector-j'
testImplementation 'org.springframework.boot:spring-boot-starter-test'
testRuntimeOnly 'org.junit.platform:junit-platform-launcher'


