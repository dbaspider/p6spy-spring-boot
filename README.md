# p6spy-it-spring-boot
p6spy integration with spring boot, for necessary spring-boot related config changes, see files:
* `application.yml` - modified: `spring.datasource.url` holding `p6spy`
* `spy.properties` - holding the p6spy specific options

To give it a test try, run:

    rm -rf spy.log; mvn clean test; tail spy.log
