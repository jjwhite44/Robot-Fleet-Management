# (Our Awesome Product) Overview

## Goal

The goal of the present product is to provide a system in which users can interact with a live simulation of autonomous cleaning robots. These robots have various sizes and functions, and can be assigned to different types of tasks across virtual rooms in need of cleaning. Different users interact with the application in unique ways, as specified further in the [user guide](docs/user_guide/USER_GUIDE.md). There are four major components that make up the application, as specified in the following section.

## Features

There are explicit instructions on how to build and run the application in the aforementioned user guide. Once the user is running the application, they interact directly with the **graphical user interface (GUI)**. The resultant data from their interactions with this interface are taken by the **data manager**. The data manager then handles further communication with the **database** and **simulation** components of the software. The database is responsible for logging and maintaining information about robots (properties, error status, etc.), tasks (completion status, etc.), and rooms (cleanliness, availability, etc.). The simulation is responsible for providing a virtual representation of the work autonomous cleaning robots do, providing live updates on robots' battery levels and water levels, simulating the work and completion of cleaning tasks the robots have been assigned to, and more. For further information on how these four components interact with one another to result in a functioning application, check out our `docs` folder, as specified below.

## Navigation

+ `docs` - this [folder](docs) maintains our project's documentation, including [design documents](docs/design/DESIGN.md), [contribution statements](docs/contributions) from team members, and a [user guide](docs/user_guide/USER_GUIDE.md) for how to use our software. 
+ `include` - this [folder](include) contains the included libraries for our software, for example our [Robot class](include/robot.hpp).
+ `src` - this [folder](src) provides the source files for the project, and are implementations of the header files from the included libraries. 
+ `wxWidgets/Project_Implementation` - this [folder](wxWidgets/Project_Implementation) consists of the files making up the GUI that users interface with. For general wxWidgets information, [see here](wxWidgets/README.md). For further project GUI information, [see here](wxWidgets/Project_Implementation/README.md).
+ `tests` - this [folder](tests) consists of a testing suite used to ensure the efficacy of our libraries and application.