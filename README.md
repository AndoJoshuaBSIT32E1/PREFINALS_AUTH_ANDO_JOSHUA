# PREFINALS_AUTH_ANDO_JOSHUA_BSIT32E1

Self-Assessment: Onion Architecture, MVC, and Web API (.NET Core) with Bottlenecks (Encountered)
Conceptual Understanding:
 
Onion Architecture: (Yes/No)
 
Have you heard of the Onion Architecture principle in software design?
 - YES
 
 
MVC Pattern: (Yes/No) 
 
Are you familiar with the Model-View-Controller (MVC) pattern for building web applications?
 - YES
 
 
Web API: (Yes/No) 
 
Do you understand the concept of building RESTful APIs using ASP.NET Core Web API?
 
 - YES
 

Application & Bottlenecks:
Onion Architecture:
 
 
Benefits: (1-3 keywords)
 
 
Briefly list some key benefits of using Onion Architecture in .NET Core projects. (e.g., separation of concerns, testability)

Answer:
Adaptability to Change: 
Better Code ORganization
Flexibility and Maintability
 
 
Bottlenecks (Encountered): (Yes/No and Briefly Explain)
 
 
Have you encountered any challenges with Onion Architecture in your projects? If so, briefly describe the bottleneck(s). (e.g., Increased complexity for simple projects, difficulty finding developers familiar with the pattern)
 - Performance Overhead: Even though the architecture tries to provide testability and maintainability, there may be performance overhead, particularly if the layers are not created and executed well. The overall performance of the system may be affected, necessitating cautious adjustment.


 
 

MVC:
 
 
Components: (1-3 keywords each)
 
 
Briefly describe the roles of the Model, View, and Controller in the MVC pattern.
Model: This stands for the application's primary data and logic. It manages tasks including storing, retrieving, and doing any necessary computations on the data. Think of it as the application's brain.
View: This refers to the user's visual and interactive experience with the application. It lets the user to add input and shows the data that was pulled from the model. Consider it to be the user interface.
Controller: Serves as a bridge between the view and the model. It takes user input from the view, makes any necessary adjustments to the model, and then tells the view to update itself with any new information. It's the traffic cop, making sure that everything goes as planned.

 
 
 
Bottlenecks (Encountered): (Yes/No and Briefly Explain)
 
 
Have you encountered any challenges with tight coupling between Model and Controller in MVC projects? If so, briefly describe the issue(s). (e.g., Difficulty in unit testing controllers, logic changes rippling through the application)
Diffuculty in Reuse: Often, tightly connected components have lower reusability. Reusing the Model and Controller in different scenarios or contexts becomes more difficult when they are tightly connected. This may restrict the application architecture's scalability and adaptability.
 
 
 

Web API:
 
 
Differences from MVC: (Yes/No and Briefly Explain)
 
 
Can you differentiate between traditional MVC applications and Web APIs? Briefly explain the main difference.
- Conventional MVC applications concentrate on providing user interfaces in session-based settings by utilizing a Model-View-Controller architecture to create HTML pages for user interaction. Conversely, web APIs emphasize data interchange between systems by using standardized formats like JSON or XML for communication and using endpoints for activities. They don't maintain session state, which improves scalability and dependability. Instead, they function statelessly.

 
 
 
 
Bottlenecks (Encountered): (Yes/No and Briefly Explain)
 
 
Have you encountered any performance challenges with traditional MVC applications compared to Web APIs? If so, briefly describe the scenario(s). (e.g., Frequent page refreshes causing performance overhead, complex data exchange requiring a more lightweight approach)
-Server-side Processing-In order to create and deliver HTML content, MVC applications often rely on server-side processing. This can cause latency, particularly during times of high demand or when performing resource-intensive tasks.

 
 
 
