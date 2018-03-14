---
layout: home
title:  Platform for Situated Intelligence
---

# Platform for Situated Intelligence

**Platform for Situated Intelligence** is an open, extensible framework that enables the enables the development, fielding and study of situated, integrative-AI systems.

Over the last years, we have seen significant progress with machine learning techniques on various perceptual and control problems. At the same time, building end-to-end, multimodal, integrative-AI systems that leverage multiple technologies and act autonomously or interact with people in the open world remains a challenging, error-prone and time-consuming engineering task. Numerous challenges stem from the sheer complexity of these systems and are amplified by the lack of appropriate infrastructure and development tools.

The Platform for Situated Intelligence project aims to address these issues and provide a basis for developing, fielding and studying integrative-AI systems. The platform consists of three layers. The **Runtime** layer provides a parallel programming model centered around temporal streams of data, and enables easy development of components and applications using .NET, while retaining the performance properties of natively written, carefully tuned systems. A set of **Tools** enable multimodal data visualization, annotations, analytics, tuning and machine learning scenarios. Finally, an open ecosystem of **Components** encapsulate various AI technologies and allow for quick compositing of integrative-AI applications. For more information about the goals of the project and the types of systems that you can build using it, and the various layers see [Platform for Situated Intelligence Overview](/psi/PlatformOverview).

# Using and Building

Platform for Situated Intelligence is a .NET Framework. Large parts of it are build on .NET Core and thereforerun both on Windows and Linux, whereas some components are specific and available only to one operating system (for instance a Kinect sensor component is available only for Windows.)

You can build applications based on Platform for Situated Intelligence either by leveraging nuget packages, or by cloning and building the code. Below are instructions:

* [Using \\psi via Nuget packages](/psi/UsingWithNuget)
* [Building the \\psi codebase](/psi/BuildingPsi)

# Getting Started

To get started, the [Brief Introduction](/psi/tutorials) page provides a guided walk-through for some of the main concepts in \\psi. It shows how to create a simple program, describes the core concept of a stream, and explains how to transform, synchronize, visualize, persist to and replay data from disk. We recommend that you work through the examples in this tutorial to familiarize yourself with these core concepts.

After going through this first brief tutorial, it may be helpful to look through the set of [Samples](/psi/samples) provided. Some of the samples address specialized topics like how to leverage speech recognition components or how to bridge to ROS, but reading them will give you more insight into programming with \\psi.

Finally, additional information is provided in a set of [In-Depth Topics](/psi/topics) that dive into a bit more detailsin various aspects of the framework, like synchronization, persistence, remoting, visualization etc.

Like the rest of the codebase, the documentation is still under construction and in various phases of completion. If you need explanation about any of these areas, please open an issue, label it `documentation` and `user request`, as this will help us focus our documentation development efforts to the highest priority needs.

# Disclaimer

The codebase is currently in beta and various aspects of the platform are at different levels of completion and robustness. The are probably still bugs and we will likely be making breaking API changes. We plan to continuously improve the framework and we hope the community can help.

For some additional information, we recommend you read the [Known Issues](/psi/ReleaseNotes#KnownIssues) section from the [Release Notes](/psi/ReleaseNotes) document, which provides more information about important issues that are known and that we plan to address in the near future. Also, the [Roadmap](/psi/Roadmap) document provides more information about our future plans.

# Getting Help

TBD.

# Contributing

We hope the community can help improve and evolve Platform for Situated Intelligence. If you plan to contribute to the codebase, please read the [Contributing Guidelines](https://github.com/Microsoft/psi/blob/master/CONTRIBUTING.md) document. It describes how the source code is organized and things you need to know before making any source code changes.

# License

The Platform for Situated Intelligence is available under an [MIT License](https://github.com/Microsoft/psi/blob/master/LICENSE.txt).