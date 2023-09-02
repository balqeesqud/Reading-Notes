# Class 11

## **Spring App Basics**


   1. **What role do the @Controller classes play in a Spring MVC application?**
      is used to define classes that handle HTTP requests from clients, such as web browsers. These classes play the
      role of controllers and are responsible for processing incoming requests, interacting with the application's
      logic or services, and preparing data to be displayed in a view.

   2. **Explain to a non-technical friend what a GET request is.**
      When someone is using a web browser to visit a website. and start typing a web address (URL) in their browser's 
      address bar and press Enter, browser sends a request to the server hosting that website. This request is 
      like asking the server for a specific piece of information, like a webpage. A GET request is a specific type of 
      request where your browser asks the server to send back a resource, like a webpage, without making any changes or
      updates.

   3. **What annotation should be placed on your Spring Boot application class?**
      @SpringBootApplication. This annotation is essential because it combines several other annotations, such as 
      @Configuration, @EnableAutoConfiguration, and @ComponentScan, into a single annotation. It tells Spring Boot to
      consider this class as the entry point for your application, enabling auto-configuration, component scanning, and 
      other Spring Boot features. This annotation ensures that your Spring Boot application starts and configures 
      itself correctly.




## **Spring MVC and Thymeleaf**


   1.  **What method allows for a variable defined in Java (in your Spring Controller) to be displayed in HTML with the
       help of Thymeleaf?**
       by adding the variable as a model attribute. This can be achieved using the addAttribute method of the Model 
       object in the controller or by returning a ModelAndView object with attributes included.

   2.  **Explain the role of a @Controller class in a Spring MVC application.**
       class plays the role of handling HTTP requests and preparing a model map with data to be displayed in a view. 
       It essentially acts as the bridge between the client's request and the server's response.

   3.  **What is a model attribute referred to in Thymeleaf?**
       is referred to as a context variable. It represents data that is made available to Thymeleaf templates for 
       rendering. Model attributes are essentially variables or objects that are passed from the controller to the 
       view, allowing dynamic content generation in HTML templates using expressions like ${attributeName} where 
       attributeName is the name of the model attribute. 
