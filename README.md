# spring-boot swagger2
1. Clone the project.
2. Hit following command `mvn clean install`
3. When you are done browse to `/v2/api-docs` for example in our case <br/>
`http://localhost:8086/v2/api-docs`

4. If you want to see the result in GUI form browse `/swagger-ui.html#/`
In our case, Browse to <br/>
`http://localhost:8086/swagger-ui.html#/`
5. If you have spring security in your apps, allow permission for given list of endpoints
 `- /swagger-resources/**`
 ` - /swagger-ui.html`
 ` - /v2/api-docs`
 ` - /webjars/**`
