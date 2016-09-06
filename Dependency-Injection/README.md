# Dependency Injection

If the objects in an application depend on collaborators or resources, the goal is to externalize the responsibilities of creating the collabtorator objects and looking up for resources from the application code to an IoC container. The application code should delegate the responsibilities of collaborator-objects creation and resource lookups to an IoC container.

Dependency Injection involves moving the responsibility of creating the dependent components out of the code to allow an **IoC container** to manage this process. 

The IoC container is responsible for handling the collaborator-object creation and resource lookup process and offering dependency injection service to the application code.

**Methods for Dependency Injection**

Dependency injection in Spring container is performed using any of the following methods

* Setter Injection
* Constructor Injection

If an IoC container supports both these methods of Dependency Injection, then any combination of these methods can be used. 

**Benefits of Dependency Injection**

* **Externalization**: The lookup logic is externalized from the application code
* **Decoupling from dependencies**: The target components are decoupled from their dependencies and are not even aware of their locations or classes, which implies that the unit testing of such target components becomes easy, as 
    * the dependent components can be easily mocked and injected to the target component in its test cases
    * there is no environmental dependency like the JNDI context
* **Easy porting across environments**: 

