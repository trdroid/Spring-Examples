# IoC Container

IoC Container is the core component of the Spring Application Framework. 

**Core Responsibilities**

The core responsibilities of the IoC Container is to

* **instantiate** objects of an application
* **initialize** them
* **wire up** objects as specified in the metadata

**Inputs to the IoC Container**

The IoC container has to be provided with

* Application Classes
* Configuration Metadata

![](_misc/IoC%20Container%20inputs.png)

### Configuration Metadata

Configuration metadata can be 

* XML-based
* Annotation-based
* Java-based

The configuration metadata for an application can be provided in any one or any combination of the formats specified above.

### Using the Spring container

The Spring container is essentially a Java object which can be instantiated using 

* the programmatic approach (or)
* the declarative approach
 


