##   **Ejemplos Spring Cloud - Neosuniversity**

El proyecto spring-config-demo carga la configuracion usando Spring Cloud Config 

------------


El proyecto limitservice-microservice es un ejemplo que obtiene la configuracion del servicio spring-config-demo, tiene los siguientes end points:


- http://localhost:8080/api/v1/limits es un microservicio al cual le es inyectada la configuracion.
- http://localhost:8080/swagger-ui.html Interfaz web de swagger con los end points que exploro en automatico.
- http://localhost:8080/v2/api-docs End Points detectados por swagger


La configuracion de swagger consiste en lo siguiente:

```<dependency>
            <groupId>com.jayway.jsonpath</groupId>
            <artifactId>json-path</artifactId>
            <scope>test</scope>
        </dependency>
        <dependency>
            <groupId>io.springfox</groupId>
            <artifactId>springfox-swagger-ui</artifactId>
            <version>2.6.1</version>
            <scope>compile</scope>
        </dependency>
        <dependency>
            <groupId>io.springfox</groupId>
            <artifactId>springfox-swagger2</artifactId>
            <version>2.6.1</version>
            <scope>compile</scope>
        </dependency>
```
