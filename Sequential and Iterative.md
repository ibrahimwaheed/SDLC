# Sequential and Iterative SDLC




The following are Examples of Sequential and Iterative Lifecycle Models.

# Sequential
The Sequential model usually progresses through a number of defined phases until they have a product that the client will be happy with.
# Waterfall
The Waterfall method is the most well known sequential Method,it is also referenced as the Linear-Sequential life cycle model. The basic principle in the Waterfall method is that each phase has to be completed before the following phase may start and these phases cannot overlap.
![](https://www.tutorialspoint.com/sdlc/images/sdlc_waterfall_model.jpg)
The sequential phases of the waterfall method are as follows:
* Requirement Gathering and Analysis:
This phase is used to determine what the client would like the software to do, so all the possible ways this can be achieved are documented for use when actually developing the software.
* System Design:
The requirements that are obatained in the first phase are then studied in this phase in order to create a system design, this phase allows the company to specify what hardware and system requirements will be required in order to function properly as well as defining the overall system architecture.
* Implementation:
With the system design now confirmed, the program is developed into smaller programs also known as units, these are then integrated during the next phase. The reason for doing this is so that each unit can be tested seperate from the whole program to determine any flaws that need to be fixed.
* Intergration and Testing:
Once all the units have been developed during the implementation phase they are then combined together into one whole system after each unit has been tested, however once these units have been combined the program is once again tested for any faults that have occured and they are then fixed.
* Deployment:
After all the testing has been completed, the product is then released into the market or it us enabled for use in the environment that was specified.
* Maintenance:
After the program has been released, there are bound to be issues that arise after use which is why patches are released in order to fix vulnerabilities as soon as they arise. Moreover, companies constantly imporve their software which means newer versions are released that have more functionality.
# V-Model
This is an SDLC where execution of processes occur in a sequential manner in the shape of a V. This model is also known as the Verification and Validation Model. It is an extension of the Waterfall model and is built on the association of testing each corresponding phase which means each phase in the development cycle has a testing phase for it. Because of this the V-Model is highly disciplined and the next phase only begins when the previous one has been completed. ![](https://www.tutorialspoint.com/sdlc/images/sdlc_v_model.jpg)
The Verification Phases are as follows:
* Requirement Analysis:
This is the first phase of the development cycle, its where the product requirements are communicated from the customer. This involves having detailed conversations with the customer in order to understand their needs, this is very crucial to the entire process as most customers don't know what they are looking for in the product which means its up to the team to decipher what the clients like and what it needs to do.
* System Design:
Once the product requirements are confirmed, the company must now set out to create a full system design. This Design will include the hardware and communciation setup that will be required for the project. The system test plan is then produced by basing it on the system design to ensure it meets all the requirements. By creating the system test plan earlier it allows more time for executing the actual tests.
* Architecture Design:
In this phase the architectural details are designed, most of the time more than one technical approach is proposed and then based on these technical and financial feasibilities the final decision is made on what approach is to be made. The system design is then broken down into modules which are composed of different functionalities also known as High Level Design. 
* Module Design:
This phase is used to specify the detailed internal designs for the system modules, this is known as Low Level Design. It is crucial that the design is compatible with the other modules that are located in the system architecure as well as the other external systems. These tests are a neccessary part of any process development process and help to eliminate most of the faults and errors at an early stage.

The Validation Phases are described below:
* Unit Testing:
These tests are designed in the module design phase and are executed on the code during the validation phase. Unit testing is the testing that occurs at code level which can help to eliminate bugs at an early stage, but this doesn't ensure that all of the problems are uncovered.
* Integration Testing:
This phase is interlinked with the architectural design phase. These tests are performed in order to test coexistence and communication of the systems internal modules.
* System Testing:
System testing is associated with the system design phase. This phase checks the whole systems functionality and the communications of the system under development with external systems. Usually in this phase a majority of the software and hardware compatibility issues are uncovered during this system test execution.
* Acceptance Testing:
This is linked with the business requirement analysis phase and it revolves around the product being tested in a user environment. These tests help uncover any problems that are compatability issues with other programs in the user environment. 
# Iterative
With the Iterative model, the process usually begins with the implementation of a small range of requirements and then enhances these iteratively as the development cycle progresses until the software is ready to be deployed. The key thing to remember with the iterative model is that it does not attempt to start with a full spec of requirements, alternatively it only develops certain parts of the software and they then review it in order to reveal any other requirements that can be added. The process is repeated at te end of each new iteration in order for a new version to be created.

![](https://www.tutorialspoint.com/sdlc/images/sdlc_iterative_model.jpg)
# Pros and Cons
The advantages of the iterative model is:
* Functionality can be developed early
* The results are able to be obtained quickly as well as frequently
* Progress can be measured to ensure the project is moving at a reasonable pace
* Costs less for changes to be implemented as they can be added in the next iteration.
* Better risk analysis
* Suited for large projects

The disadvantages of the iterative model are
* More resources may be required
* High levels of management required
* End date of project is not known which could lead to increased costs
* Highly skilled resources needed for the risk analysis

# Agile Model
The Agile Model is an amalgamation of both the iterative and incremental models. This model concentrates on providing customer satisfaction by providing the customer with rapid delivery of the product whilst also tailoring it to meet any new requirements that have been supplied. The Agile method works by separating the product into smaller incremental builds which then enables the builds to be produced in iterations. These iterations can range from one - three weeks of development time, this requires multiple teams to work simultaneoulsy on various areas.
The core principle of the Agile method is that all projects need to be approached differently and that the existing methods need to be tailored in order to ensure the project is achieving its potential.
![](https://www.tutorialspoint.com/sdlc/images/sdlc_agile_model.jpg)
# Pros and Cons
The Pros of the Agile method is that:
* It's a realistic way of approaching software develpoment.
* Encourages teamwork and collaboration.
* Rapid development.
* Minimal resources needed.
* Suitable for either fixed or evolving requirements.
* Ease of management.
* Minimal planning required.
* Flexible for developers.

The Cons of the Agile method are:
* It depends heavily on being iteractive with the customer, which leads to problems if they dont have a clear vision.
* Lack of documentation means there is high individual dependency.
# Risk manangement in Spiral model
The spiral model is a combination of sequential and iterative methods. The major difference of th spiral model is that it utilises a risk-driven approach to developing software, because of this it integrates many of the strengths that are found in the other models.
The first thing that needs to be done is to determine the requirements that the client would like, this includes important information such as the cost, the resources needed and the system requirements.
The next thing that happens is that the company then identifies any risks that may occur and then creates plans on how to avoid these or if needed how to overcome them. After this a prototype is created which is scaled down to show what kind of features and functions could be included in the final version. 
The company then sets out to make the first iteration of the product in order to meet the brief which is then sent off to the client to review to which they send it back with feedback on whether it is to their specification and if not they repeat the steps until the client is satisfied witht the product.
The final phase is the review of the product, this is when the client reviews the product in order to give feedback on what has been created, this phase is also when the client is able to see the kind of risks that have been identified and how these have been monitored. Once the client is happy with the product they are then able to release it to be used by consumers.
![](https://cdncontribute.geeksforgeeks.org/wp-content/uploads/spiral-1-1024x945.jpg)
