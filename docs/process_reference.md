# Processes

Processes describe a series of steps to execute in an automated browser. These steps navigate to, set the scene for, and capture a screenshot of a page, region, or element of a page.

Process are also the basis for the primary execution model in UserDocs. They can be executed indiviually. When they are executed, a Process Instance is created, representing the individual execution of that process. Additionally, a step instance, representing the individual execution of a step is created for each step. 

Processes can be added to jobs, which will run ordered collections of steps and processes.  Processes should be kept small, short, and focused on doing one thing. Doing so will make it easier to create them in the application, compose them together in your jobs, and test before releasing to CICD.

## Additional Documentation

* [Process Menu](process_menu.md)
* [Process Form](process_form.md)