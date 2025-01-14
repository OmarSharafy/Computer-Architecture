# Computer-Architecture
This repository containes HWs for the course computer architecture in the technion 
# HW1 :
This simulator implements a two-level branch predictor similar to what is taught in class. The predictor configuration is flexible and defined through parameters at runtime. The simulator takes a program trace as input, predicting branch outcomes based on the instruction address. It then updates its state after the actual branch outcome is identified.
# HW2 :Cache Memory Simulator
In this exercise, we implement a cache memory simulator for your own design, similar to what is taught in class. The cache memory configuration will be flexible and defined at the start using parameters. Additionally, your simulator will read an input file detailing memory accesses. It should calculate the Miss/Hit rate and the average access time for the specified configuration and input trace.

# HW3 :Dependency Analysis Tool
The microarchitecture implementing the Execution-Order-Of-Out principles aims to exploit parallelism inherent in the command sequence for execution. Non-dependencies of operands between commands in the result of earlier commands allow running multiple commands in parallel in different functional units. Relationships between commands in a program are defined as data dependencies. In the analysis of data dependencies in a program, we specifically refer to True Data Dependencies (RAW), as false dependencies can be resolved using appropriate mechanisms like register renaming.

By analyzing data dependencies, it's possible to calculate the theoretical parallelism existing in a program. This information can be used for optimal microarchitecture planning and resource allocation in the processor, striking a balance between performance improvement through parallelization and hardware resource utilization.

# HW4 : Multithreading Simulator
In this homework assignment, you will implement a simulator that emulates the execution of a multi-threaded processor in two configurations: Fine-grained Multithreading (Fine-grained MT) and Multithreading Block (MT Block).
