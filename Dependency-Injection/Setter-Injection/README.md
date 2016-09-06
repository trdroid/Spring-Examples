# Setter Injection

The setter injection method performs dependency injection through the setter methods of a bean/component. The setter methods follow the JavaBean specification. The setters are mutators that allow the outside world to modify the properties of a component. This allows a component to externalize their properties allowing them to be assigned or modified from the outside world and any externalized properties can be injected. These properties could range from primitives like *int*, *char*, *boolean*, to collaborator instances.

### Features

* Dependency injection occurs during the component **creation** or **initialization** phase.

### Advantages

### Disadvantages

The disadvantages of the setter injection method are

* **Partially configured component state**: The component could be in a partially configured state as all the necessary dependencies may not be injected before use.
* **Lack of configuring the order of setter method invocation**: The component's contract does not allow the specification of the order in which the setter methods should be invoked. This is a drawback in situations where the order in which the setter methods are invoked is important.
