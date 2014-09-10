this is a error spring restful web service i only added gdata dependency to build.gradle file:

to see fail

```sh
$ ./gradlew tomcatRunWar
```
this is the output of the error:

:compileJava 
```
    C:\Users\Grubhart\Documents\proyectos\error_Rest_Gdata\complete\src\main\java\com\yummynoodlebar\config\WebAppInitializer.java:38: error: cannot find symbol
    servletContext.addListener(new ContextLoaderListener(rootContext));
                  ^      
    symbol:   method addListener(ContextLoaderListener)
    location: variable servletContext of type ServletContext
    C:\Users\Grubhart\Documents\proyectos\error_Rest_Gdata\complete\src\main\java\com\yummynoodlebar\config\WebAppInitializer.java:39: error: cannot find symbol
    servletContext.setInitParameter("defaultHtmlEscape", "true");
                  ^      
    symbol:   method setInitParameter(String,String)
    location: variable servletContext of type ServletContext
    C:\Users\Grubhart\Documents\proyectos\error_Rest_Gdata\complete\src\main\java\com\yummynoodlebar\config\WebAppInitializer.java:54: error: cannot find symbol
    ServletRegistration.Dynamic appServlet = servletContext.addServlet(
                                                           ^
    symbol:   method addServlet(String,DispatcherServlet)
    location: variable servletContext of type ServletContext
3 errors
```
:compileJava FAILED      
          
FAILURE: Build failed with an exception.
          
* What went wrong:
Execution failed for task ':compileJava'.
> Compilation failed; see the compiler error output for details.
