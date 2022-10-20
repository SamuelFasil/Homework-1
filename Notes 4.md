# Notes 4
## 1, What is virtualization?
Virtualization uses software to create an abstraction layer over computer hardware that allows the hardware elements of a single computer—processors, memory, storage and more—to be divided into multiple virtual computers, commonly called virtual machines (VMs). Each VM runs its own operating system (OS) and behaves like an independent computer, even though it is running on just a portion of the actual underlying computer hardware.

It follows that virtualization enables more efficient utilization of physical computer hardware and allows a greater return on an organization’s hardware investment.

Today, virtualization is a standard practice in enterprise IT architecture. It is also the technology that drives cloud computing economics. Virtualization enables cloud providers to serve users with their existing physical computer hardware; it enables cloud users to purchase only the computing resources they need when they need it, and to scale those resources cost-effectively as their workloads grow.
### Benefits of virtualization
Virtualization brings several benefits to data center operators and service providers:

#### Resource efficiency: 
Before virtualization, each application server required its own dedicated physical CPU—IT staff would purchase and configure a separate server for each application they wanted to run. (IT preferred one application and one operating system (OS) per computer for reliability reasons.) Invariably, each physical server would be underused. In contrast, server virtualization lets you run several applications—each on its own VM with its own OS—on a single physical computer (typically an x86 server) without sacrificing reliability. This enables maximum utilization of the physical hardware’s computing capacity.
#### Easier management: 
Replacing physical computers with software-defined VMs makes it easier to use and manage policies written in software. This allows you to create automated IT service management workflows. For example, automated deployment and configuration tools enable administrators to define collections of virtual machines and applications as services, in software templates. This means that they can install those services repeatedly and consistently without cumbersome, time-consuming. and error-prone manual setup. Admins can use virtualization security policies to mandate certain security configurations based on the role of the virtual machine. Policies can even increase resource efficiency by retiring unused virtual machines to save on space and computing power.
#### Minimal downtime: 
OS and application crashes can cause downtime and disrupt user productivity. Admins can run multiple redundant virtual machines alongside each other and failover between them when problems arise. Running multiple redundant physical servers is more expensive.
#### Faster provisioning: 
Buying, installing, and configuring hardware for each application is time-consuming. Provided that the hardware is already in place, provisioning virtual machines to run all your applications is significantly faster. You can even automate it using management software and build it into existing workflows.

## 2, What is Java?
Java is a general-purpose, class-based, object-oriented programming language designed for having lesser implementation dependencies. It is a computing platform for application development. Java is fast, secure, and reliable, therefore. It is widely used for developing Java applications in laptops, data centers, game consoles, scientific supercomputers, cell phones, etc.

### What is Java Platform?
Java Platform is a collection of programs that help programmers to develop and run Java programming applications efficiently. It includes an execution engine, a compiler, and a set of libraries in it. It is a set of computer software and specifications. James Gosling developed the Java platform at Sun Microsystems, and the Oracle Corporation later acquired it.

### Components Of Java Programming Language
A Java Programmer writes a program in a human-readable language called Source Code. Therefore, the CPU or Chips never understand the source code written in any programming language.

These computers or chips understand only one thing, which is called machine language or code. These machine codes run at the CPU level. Therefore, it would be different machine codes for other models of CPU.

However, you need to worry about the machine code, as programming is all about the source code. The machine understands this source code and translates them into machine understandable code, which is an executable code.

### All these functionalities happen inside the following 3 Java platform components:

#### Java Development kit (JDK)
JDK is a software development environment used for making applets and Java applications. The full form of JDK is Java Development Kit. Java developers can use it on Windows, macOS, Solaris, and Linux. JDK helps them to code and run Java programs. It is possible to install more than one JDK version on the same computer.

#### Why use JDK?
Here are the main reasons for using JDK:

JDK contains tools required to write Java programs and JRE to execute them.
It includes a compiler, Java application launcher, Appletviewer, etc.
Compiler converts code written in Java into byte code.
Java application launcher opens a JRE, loads the necessary class, and executes its main method.
#### Java Virtual Machine (JVM):
Java Virtual Machine (JVM) is an engine that provides a runtime environment to drive the Java Code or applications. It converts Java bytecode into machine language. JVM is a part of the Java Run Environment (JRE). In other programming languages, the compiler produces machine code for a particular system. However, the Java compiler produces code for a Virtual Machine known as Java Virtual Machine.

#### Why JVM?
Here are the important reasons of using JVM:

JVM provides a platform-independent way of executing Java source code.
It has numerous libraries, tools, and frameworks.
Once you run a Java program, you can run on any platform and save lots of time.
JVM comes with JIT (Just-in-Time) compiler that converts Java source code into low-level machine language. Hence, it runs faster than a regular application.
#### Java Runtime Environment (JRE)
JRE is a piece of software that is designed to run other software. It contains the class libraries, loader class, and JVM. In simple terms, if you want to run a Java program, you need JRE. If you are not a programmer, you don’t need to install JDK, but just JRE to run Java programs.

#### Why use JRE?
Here are the main reasons of using JRE:

JRE contains class libraries, JVM, and other supporting files. It does not include any tool for Java development like a debugger, compiler, etc.
It uses important package classes like math, swing, util, lang, awt, and runtime libraries.
If you have to run Java applets, then JRE must be installed in your system.
Different Types of Java Platforms

### There are four different types of Java programing language platforms:

#### 1. Java Platform, Standard Edition (Java SE): 
Java SE’s API offers the Java programming language’s core functionality. It defines all the basis of type and object to high-level classes. It is used for networking, security, database access, graphical user interface (GUI) development, and XML parsing.

#### 2. Java Platform, Enterprise Edition (Java EE): 
The Java EE platform offers an API and runtime environment for developing and running highly scalable, large-scale, multi-tiered, reliable, and secure network applications.

#### 3. Java Programming Language Platform, Micro Edition (Java ME): 
The Java ME platform offers an API and a small-footprint virtual machine running Java programming language applications on small devices, like mobile phones.

#### 4. Java FX: 
JavaFX is a platform for developing rich internet applications using a lightweight user-interface API. It user hardware-accelerated graphics and media engines that help Java take advantage of higher-performance clients and a modern look-and-feel and high-level APIs for connecting to networked data sources.

To understand Java programming language, we need to understand some basic concept of how a computer program can run a command and execute the action.

## 3, What is a native app?

A native app is any app that can be downloaded and live on your mobile device, functioning as an independent program and often accessing different features of your device to work. Even where products or programs run online as web apps (e.g. a social media platform), proper mobile apps aren’t the same as the website. They must be developed as independent programs. Even different operating systems require different apps, meaning that developers have to customize native apps to work well with whatever phone or device the users have. This means that native apps perform better on the operating system they’re built for than a website would, running faster than web apps since web apps have to download all of their data from a web server.

The benefit of a native app is that it lives on your phone, is easy to access, and most apps don’t always require an internet connection. The user experience is often better on a native app too, since it can be customized in ways websites can’t.

The other benefit is convenience, since users can have the product or service in their pocket, and apps have higher engagement because of notifications that keep prompting the user to come back to the app.

### Native app vs. web app

A native app is developed for your mobile device, while a web app usually exists in code and is accessed via a web browser. While your social media site might look sort of the same whether you access it on your computer or through an app on your device, you are functionally accessing two different things. That’s why they often have different features; for example, some social media platforms have live streaming in their apps but not on their website.

Native apps can often be accessed offline because they store relevant data on your phone. Web apps require the internet and they don’t store files on your computer.

A hybrid app mixes these two things on your mobile device, requiring some access to your hard drive and device features, but also using the HTML of a website to display within the app and therefore requiring internet access.

## 4, What is an Operating System?
An Operating System (OS) is a software that acts as an interface between computer hardware components and the user. Every computer system must have at least one operating system to run other programs. Applications like Browsers, MS Office, Notepad Games, etc., need some environment to run and perform its tasks.

The OS helps you to communicate with the computer without knowing how to speak the computer’s language. It is not possible for the user to use any computer or mobile device without having an operating system.

### Types of Operating System (OS)
Following are the popular types of OS (Operating System):

#### Batch Operating System
#### Multitasking/Time Sharing OS
#### Multiprocessing OS
#### Real Time OS
#### Distributed OS
#### Network OS
#### Mobile OS

