# Towards Aggregate Programming in pure Kotlin through compiler-level metaprogramming
This is my thesis, that I am producing for my master degree for __University of Bologna__ (__Unibo__).  
Collektive is the project that this thesis refers to, and it can be found [here](https://github.com/ElisaTronetti/collektive).

## Abstract
The last few decades have seen significant technological advancements in computing, the internet, and mobile technology, leading to the growth of the Internet of Things (IoT). This has resulted in a network of physical devices embedded with sensors, software, and connectivity, which can collect and share data. However, this growth has also brought new challenges, such as the need for complex software engineering to take advantage of the computational infrastructure available while considering unpredictability and communication heterogeneity.

This thesis explores the aggregate programming, which is a paradigm based on field calculus, and it allows for the easy manipulation of data across devices, making it possible to perform operation on the data of distributed systems, in a simple and efficient manner. The paradigm has been implemented in various programming languages and platforms, such as *Protelis*, *Scafi* and *FCPP*.

This thesis proposes a new implementation of the aggregate programming paradigm, called *Collektive*.  
The aggregate programming requires the communication of the devices to be coordinated through the alignment, which keeps track of the computational state of each device. The work done in this thesis explores different Kotlin metaprogramming techniques in order to solve this problem, illustrating the final solution achieved through the implementation of a Kotlin compiler plugin, which is totally transparent and portable.

The project provides the user a minimal DSL, which is compatible with multiple platforms, such as JVM, JavaScript and Kotlin Native. This is possible because of the features offered by Kotlin Multiplatform, which is used for the implementation of the DSL. Moreover, this thesis addresses the validation process carried out to test the correct behavior of the system, which guarantees that Collektive can be considered at the same level of the existing aggregate programming implementations.

## Acknowledgement
A special thanks to [Alessandro Talmi](https://github.com/Tale152) for providing the LaTeX [template](https://github.com/TemplatesHub/unibo-thesis-template-english) that helped me to redact this document.
