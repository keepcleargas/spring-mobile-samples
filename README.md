# Spring Mobile Samples

[Spring Mobile] is an extension to the popular [Spring Web MVC] web framework , that aims to simplify the development of mobile web applications. This repository contains sample projects illustrating usage of Spring Mobile. See [Spring Mobile on GitHub] for more information about building from source.


## Sample Applications

The following sample applications demonstrate the capabilities of [Spring Mobile] for server-side device detection and handling. See the README within each sample project for more information and additional instructions.

 - [lite-device-delegating-view-resolver] - example showing view names adjusted based on device
 - [lite-device-delegating-view-resolver-xml] - example using XML based configuration, showing view names adjusted based on device 
 - [lite-device-delegating-view-resolver-thymeleaf] - example showing view names adjusted based on device, integrated with Thymeleaf for view resolution
 - [lite-device-resolver] - illustrates DeviceResolver functionality and usage 
 - [lite-device-resolver-xml] - example using XML based configuration, illustrates DeviceResolver functionality and usage
 - [lite-site-preference-handler] - illustrates SitePreferenceHandler functionality
 - [lite-site-switcher-handler-mdot] - illustrates SiteSwitcherHandler functionality using the 'mDot' strategy
 - [lite-site-switcher-handler-urlpath] - combines all features of Spring Mobile to showcase the use of the 'urlPath' site switching strategy
 - [thorax-lumbar-client] - showcases the use of Spring Mobile with JavaScript libraries

## Build and Deploy with Gradle

Most of the sample apps can be built and run using the following Gradle commands from within the sample's folder.

1. Build the app:

    ```sh
    $ ./gradlew build
    ```

2. Deploy the .war to a Servlet 3 ServletContainer using Gradle:

    ```sh
    $ ./gradlew tomcatRun
    ```


## Build and Deploy with Maven

Maven configurations are also available for most of the sample apps.

1. Build the app:

    ```sh
    $ mvn clean package
    ```

2. Deploy the .war to a Servlet 3 ServletContainer using Maven:

    ```sh
    $ mvn tomcat7:run
    ```


## Contribute

[Pull requests] are welcome. See the [contributor guidelines] for details.


## License

[Spring Mobile] is released under version 2.0 of the [Apache License].


[Spring Mobile]: http://projects.spring.io/spring-mobile
[Spring Web MVC]: http://docs.spring.io/spring/docs/current/spring-framework-reference/html/mvc.html
[Spring Mobile on GitHub]: https://github.com/spring-projects/spring-mobile
[lite-device-delegating-view-resolver]: ./lite-device-delegating-view-resolver
[lite-device-delegating-view-resolver-thymeleaf]: ./lite-device-delegating-view-resolver-thymeleaf
[lite-device-delegating-view-resolver-xml]: ./lite-device-delegating-view-resolver-xml
[lite-device-resolver]: ./lite-device-resolver
[lite-device-resolver-xml]: ./lite-device-resolver-xml
[lite-site-preference-handler]: ./lite-site-preference-handler
[lite-site-switcher-handler-mdot]: ./lite-site-switcher-handler-mdot
[lite-site-switcher-handler-urlpath]: ./lite-site-switcher-handler-urlpath
[thorax-lumbar-client]: ./thorax-lumbar-client
[Pull requests]: http://help.github.com/send-pull-requests
[contributor guidelines]: https://github.com/spring-projects/spring-mobile/wiki/Contributor-Guidelines
[Apache license]: http://www.apache.org/licenses/LICENSE-2.0
