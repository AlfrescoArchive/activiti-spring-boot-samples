# activiti-spring-boot-samples

Examples of how to use spring boot with com.activiti 

Make sure you have alfresco-internal maven reposiotry configured in your .m2/settings.xml


```xml
 <servers>
        <server>
              <id>alfresco-internal</id>
              <username>YOUR-USERNAME</username>
              <password>YOUR-PASSWORD</password>
              <configuration></configuration>
        </server>
 </servers>   

<mirrors>
       <mirror>
             <id>alfresco-internal</id>
             <name>Nexus Public Mirror</name>
             <url>https://artifacts.alfresco.com/nexus/content/repositories/activiti-enterprise-releases/</url>
             <mirrorOf>*</mirrorOf>
       </mirror>
</mirrors>
```
