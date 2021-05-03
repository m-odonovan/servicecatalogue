# Service Catalogue
Working concept assembled using Canvas and Model Driven Microsoft Power Apps. Allow employees to browse a service catalogue and order items from it.

## Background
I wanted to create a basic service catalogue application that would allow you to use as a concept starter or spark some ideas on how you could take this further. Could be use for IT and other scenarios where internally a department offers services to the rest of the organisation, and you would like to manage the service catalogue through a useful tool as well as allow employees to browser and "order" items from the catalogue

## Its a sample
Please do note, this is a sample application that is not intended to be used in production environments as is. It is intended to help a Power Apps developer to learn how they could assemble such an application. It is certainly not a perfect solution, it hasn't been well tested, and is missing some key features that I hope you would add over time.

## How it works
There are 2 main applications which makeup this solution. 
1 - Admin Model Driven App - manage the service catalogue items, categories etc.
2 - User Canvas App - employees use this to browse and order items (portal)

All data resides in the Microsoft Dataverse
The admin model driven app is where you create, edit and manage the service catalogue items, their attributes and more. A service catalogue item is associated to a service catalogue category, and so you can define these here also, along with service teams which support an item. The site map includes references to Dynamics 365 Customer Service items such as cases and knowledge articles.
The canvas app is a multi-screen sample app designed for tablet form factor. This could rather have been a Power App Portal, but seeing as the target audience is internal employees I felt it was easier to create as a canvas app. This allows employee to see service status, top incidents, and other important information for the employee, and then browse the service catalogue and request an item from it (Requests). It also shows active Dynamics 365 cases from the cases entity.

Solution file and overview PPT is in the solution folder.

Also, there are some wonderful more advanced solutions than this, do search for and explore "service catalog" and "ITSM" on appsource.microsoft.com.




