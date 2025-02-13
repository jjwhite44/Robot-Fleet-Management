# Sprint5_Contribution_Yili_Zhang

For this sprint I contributed to enhancing the DataManager by integrating real-time task execution with the robot task system, enabling dynamic task progress simulation and periodic updates to MongoDB. I implemented robust thread safety measures using mutex locks to ensure safe concurrent data access. Additionally, I linked robots dynamically to room assignments during tasks and incorporated room data management for simulation. For testing, I extended the test cases to validate thread-driven updates, ensuring that task execution, resource usage, and error handling function correctly in a simulated environment, while maintaining synchronization with MongoDB.