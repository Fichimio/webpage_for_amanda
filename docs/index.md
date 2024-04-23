# Amanda: Unified Instrumentation Framework for Deep Neural Networks

## Abstract

The success of deep neural networks (DNNs) has sparked efforts to analyze (e.g., tracing) and optimize (e.g., pruning) them. These tasks have specific requirements and ad-hoc implementations in current execution backends like TensorFlow/PyTorch, which require developers to manage fragmented interfaces and adapt their codes to diverse models. In this study, we propose a new framework called Amanda to streamline the development of these tasks. We formalize the implementation of these tasks as neural network instrumentation, which involves introducing instrumentation into the operator level of DNNs. This allows us to abstract DNN analysis and optimization tasks as instrumentation tools on various DNN models. We build Amanda with two levels of APIs to achieve a unified, extensible, and efficient instrumentation design. The user-level API provides a unified operator-grained instrumentation API for different backends. Meanwhile, internally, we design a set of callback-centric APIs for managing and optimizing the execution of original and instrumentation codes in different backends. Through these design principles, the Amanda framework can accommodate a broad spectrum of use cases such as tracing, profiling, pruning, and quantization, across different backends (e.g., TensorFlow/PyTorch) and execution modes (graph/eager mode). Moreover, our efficient execution management ensures that the performance overhead is typically kept within 5%.

## This tutorial 

The tutorial aims to present a comprehensive overview of the proposed Amanda instrumentation framework and illustrate its application through detailed examples. Firstly, we delve into the design principles behind the instrumentation abstraction and highlight the advantages brought by its unified interface. Subsequently, we provide a detailed demonstration of how systematic support is offered for implementing the proposed DNN instrumentation interface. Finally, we showcase and demonstrate the instrumentation framework using real-world case examples. This tutorial offers valuable insights for audiences from both the ML algorithm and system development communities. The introduced Amanda instrumentation framework holds the potential to facilitate the development of innovative optimization algorithms and aid system developers in analyzing DNN models.

## Project: 
[Amanda DNN Instrumentation Framework](https://github.com/uchuhimo/amanda)

## Time: 
Sunday, April 28th, 2024, 08:30am-12:00am.

Location: This tutorial will be held at Scripps II of Hilton La Jolla Torrey Pines, ASPLOS 2024, San Diego.

Schedule:
Time
Topic
08:30-10:00
Introduction of Amanda framework
10:00-10:30
Tea Break
10:30-11:30
Short course on Model Compression
11:30-12:00
Practice and demo


Organizer: ReArch Lab, Shanghai Jiao Tong University.