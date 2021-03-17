# angles-java-client


### Maven dependency
The angles java client has been published to the maven repository. 

Simply add the following dependency to your POM:
``` xml
<dependency>
  <groupId>com.github.angleshq</groupId>
  <artifactId>angles-java-client</artifactId>
  <version>1.0.0-BETA4</version>
</dependency>
```



### Testng Listener
Add the following to your base/test class:
```
@Listeners({AnglesTestngTestListener.class})
```