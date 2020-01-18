# To Start
- create an app.groovy scriping with a Controller that returns a string from one of the methods annotated with @RequestMapping("/endpoint") annotations
- `spring run app.groovy` will resolve all dependencies and publish the application on localhost
- curl localhost:8080/your_endpoint or just /, and you'll see the message
- Done!

# Example output
```
➜  spring-command-line-demo spring run app.groovy
WARNING: An illegal reflective access operation has occurred
WARNING: Illegal reflective access by org.codehaus.groovy.vmplugin.v7.Java7$1 (jar:file:/usr/local/Cellar/springboot/2.2.3.RELEASE/lib/spring-boot-cli-2.2.3.RELEASE.jar!/BOOT-INF/lib/groovy-2.5.9.jar!/) to constructor java.lang.invoke.MethodHandles$Lookup(java.lang.Class,int)
WARNING: Please consider reporting this to the maintainers of org.codehaus.groovy.vmplugin.v7.Java7$1
WARNING: Use --illegal-access=warn to enable warnings of further illegal reflective access operations
WARNING: All illegal access operations will be denied in a future release
Resolving dependencies...

  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/
 :: Spring Boot ::        (v2.2.3.RELEASE)

2020-01-18 02:03:34.162  INFO 56321 --- [       runner-0] o.s.boot.SpringApplication               : Starting application on C02XG1REJGH8 with PID 56321 (started by oblavat in /Users/oblavat/personal/spring-command-line-demo)
2020-01-18 02:03:34.184  INFO 56321 --- [       runner-0] o.s.boot.SpringApplication               : No active profile set, falling back to default profiles: default
2020-01-18 02:03:35.022  INFO 56321 --- [       runner-0] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port(s): 8080 (http)
2020-01-18 02:03:35.034  INFO 56321 --- [       runner-0] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2020-01-18 02:03:35.035  INFO 56321 --- [       runner-0] org.apache.catalina.core.StandardEngine  : Starting Servlet engine: [Apache Tomcat/9.0.30]
2020-01-18 02:03:35.064  INFO 56321 --- [       runner-0] org.apache.catalina.loader.WebappLoader  : Unknown class loader [org.springframework.boot.cli.compiler.ExtendedGroovyClassLoader$DefaultScopeParentClassLoader@71623278] of class [class org.springframework.boot.cli.compiler.ExtendedGroovyClassLoader$DefaultScopeParentClassLoader]
2020-01-18 02:03:35.105  INFO 56321 --- [       runner-0] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2020-01-18 02:03:35.105  INFO 56321 --- [       runner-0] o.s.web.context.ContextLoader            : Root WebApplicationContext: initialization completed in 763 ms
2020-01-18 02:03:35.327  INFO 56321 --- [       runner-0] o.s.s.concurrent.ThreadPoolTaskExecutor  : Initializing ExecutorService 'applicationTaskExecutor'
2020-01-18 02:03:35.676  INFO 56321 --- [       runner-0] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat started on port(s): 8080 (http) with context path ''
2020-01-18 02:03:35.680  INFO 56321 --- [       runner-0] o.s.boot.SpringApplication               : Started application in 2.054 seconds (JVM running for 7.816)
2020-01-18 02:03:48.082  INFO 56321 --- [nio-8080-exec-1] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring DispatcherServlet 'dispatcherServlet'
2020-01-18 02:03:48.083  INFO 56321 --- [nio-8080-exec-1] o.s.web.servlet.DispatcherServlet        : Initializing Servlet 'dispatcherServlet'
2020-01-18 02:03:48.096  INFO 56321 --- [nio-8080-exec-1] o.s.web.servlet.DispatcherServlet        : Completed initialization in 13 ms
^C2020-01-18 02:04:05.652  INFO 56321 --- [extShutdownHook] o.s.s.concurrent.ThreadPoolTaskExecutor  : Shutting down ExecutorService 'applicationTaskExecutor'
```
