# SpringBootActuatorMicrometer
_Explore Actuator And Micrometer concepts_

>Spring actuator provides some out of the box endpoints which we can use to monitor the health of the application:-

ID	             |          Description 
-----------------|-------------------------
auditevents	    | Exposes audit events information for the current application.
beans	        |Displays a complete list of all the Spring beans in your application.
caches	        |Exposes available caches.
conditions	|Shows the conditions that were evaluated on configuration and auto-configuration classes and the reasons why they did or did not match.
configprops	|Displays a collated list of all @ConfigurationProperties.
env	Exposes |properties from Spring’s ConfigurableEnvironment.
flyway	|Shows any Flyway database migrations that have been applied.
health	|Shows application health information.
httptrace	|Displays HTTP trace information (by default, the last 100 HTTP request-response exchanges).
info	|Displays arbitrary application info.
integrationgraph	|Shows the Spring Integration graph.
loggers	|Shows and modifies the configuration of loggers in the application.
liquibase	|Shows any Liquibase database migrations that have been applied.
metrics	|Shows ‘metrics’ information for the current application.
mappings	|Displays a collated list of all @RequestMapping paths.
scheduledtasks	|Displays the scheduled tasks in your application.
sessions	|Allows retrieval and deletion of user sessions from a Spring Session-backed session store. Not available when using Spring Session’s support for reactive web applications.
shutdown	|Lets the application be gracefully shutdown.
threaddump	|Performs a thread dump.
