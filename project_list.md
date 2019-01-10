# Capstone Project List

## Industry Capstone Projects

### NetApp - Develop a Virtual Machine Provisioning Tool for Hyper-V

Project Background: Did you know you can create and manage virtual machines with a Windows OS? Microsoft’s Hyper-V is a Type-1, or “bare-metal”, hypervisor which comes bundled with various installations of Windows—including certain flavors of Windows 10. Hyper-V functionality can be controlled through an interface known as WMI (“Windows Management Instrumentation”), which allows for programs written in various scripting languages to manage Windows machines locally or remotely.

Project Summary: Students will develop a Python library capable of remotely managing the functionality of a Hyper-V host. Leveraging this Hyper-V management library, students will concurrently develop a CLI (“command-line interface”) tool designed to allow a user to create, configure, and manage guest virtual machines on a given Hyper-V host.

Project Details: Over the course of this Capstone project, students will accomplish the following high-level goals:
  * Plan and manage their own Agile-style development project
  * Research and engage with various computer virtualization concepts
  * Gain programming experience developing code which interfaces with the Windows OS
  * Write a Python library capable of remotely controlling the virtualization functionality of Hyper-V-capable Windows host
  * Create a CLI tool which assists a user in creating and managing virtual machines on a remote Hyper-V host

Stretch Goals: Afforded the time and opportunity, the students may also:

  * Enhance the CLI tool to provision a virtual machine from a given configuration file
  * Enhance the CLI tool to add and remove various types of virtual hardware devices to existing virtual machines
  * Enhance the Hyper-V management library to accept and convert OVF (“Open Virtualization Format”) packages into a format compatible and deployable with Hyper-V

POC: Tim Banyas

### NetApp - Develop A Kernel Extension For An Open Source File System

Project Background: Embedded and distributed systems focused projects are not commonly provided at a bachelor’s level Capstone project. Our goal is to provide an opportunity for aspiring embedded systems engineers to gain experience in this area utilizing an open source embedded file system as a base for developing a specific kernel extension. Developers at NetApp have been optimizing and enhancing our embedded proprietary file system (WAFL – write anywhere file layout) for over 20 years. Because of the proprietary nature of the file system we will be using an open source equivalent for this project. Working in the C language, students will gain real-life experience developing for embedded, distributed systems.

Project Summary: In this project, students will work with the FUSE open source file system installed on Ubuntu Linux platform. The project team will work through the detailed steps below to implement a kernel extension that reports the file system space usage.

Project Details: Over the course of this Capstone project, students will accomplish the following high-level goals:

  * Download and install FUSE on Linux.
  * Work through the open source “hello” example and a NetApp provided custom example.
  * Create a read/write file system as an underlying test bed and explore the properties of this system.
  * Write the kernel extension (using the C programming language) to implement a user space reporting function.
  * Execute automated tests during the writing of the kernel extension. Enhance the automated tests as necessary.
  
Stretch Goals:

  * Enhance the file system to store user space consumed data in an in-memory database.
  * Update the in-memory database based on incoming fileops.
  * Implement a space enforcement feature which prevents write fileops that exceed a defined usage limit.

POC: Kurt Johanknecht

### Viz - Lightweight Open Web Analysis

Most web analysis systems are proprietary and heavyweight, meaning that most of their algorithms is hidden and unable to be validated. It leads to a misunderstanding of the answers.

This project proposes to develop a lightweight open system that does web analysis in the most straightforward and modular way. It will not hide the implementation and make it available for understanding. It will be able to be selected as needed and not the heavy-weight requirements. This will be used not only for proper validation, but also as a platform to make web analytics more inclusive. It should allow for the processing of data without an integration of required hooks that forces users to be locked in simply because of the effort needed to change.

The application should be developed to provide reusable components that can be used in many types of web analysis as well as other forms of analytics.

POC: Mike Bigrigg

## Faculty Projects

### Labrinidis Project

TBD

### PittCoin

The goal of this project is to develop a Pitt-specific token.  We will first determine a method of claiming and distributing PittCoins as well as possible use cases for such a token.  After this, we will develop a token using the ERC-20 standard, an interface for displaying balances, and additional features.  Part of this project will be determining which features would be useful.  We will also conduct a security audit of the produced code to ensure the contract(s) operate(s) in the correct way and is secure.

Previous experience in the crytocurrency and blockchain space is nice, but not required.  This project will be written in Solidity with a web3.js front end.  

POC: Bill Laboon

### Luna project

TBD

### Pitt Civics Mobile App

Pitt Civics is a collaborative coalition of civic-minded Pitt students, staff, and faculty that strives to generate accessible pathways for civic growth for Pitt students. We seek creative student mobile developers to help us develop a gamified virtual civic learning platform—embracing civic competencies across academic disciplines - that is intended for and open to all Pitt students, and includes content modules dedicated to historic and modern understandings of democratic values, capacities to engage diverse perspectives and people, and commitment to collective civic problem solving. __NDA or IP agreement may be required.__

POC: Ron Idoko

### CampusGruv

CampusGruv is a campus community engagement app composed of a network of visually engaging 'campusfeeds' that allow for more dynamic interaction between the members - students, alumni, faculty, staff, local businesses, etc. - of respective campus communities. We are currently seeking creative student developers interested in assessing and redesigning elements our iOS platform. __NDA or IP agreement may be required.__

POC: Ron Idoko

### Studying Microgrids As A Feasible Solution For Reducing Power Generation

One way to reduce power generation by utilities is to harvest solar and wind power at each house.  However, sometimes energy is available when customers don't need it, and vice versa, creating the need to store Energy in expensive batteries.  Arranging customers into a small group of harvesters has been called a microgrid, collecting, sharing, and distributing the harvested energy (and sharing the batteries) among microgrid customers, who may have energy needs at different times.  

In this project, we will expand on the existing simulators to discover is the ideal size and distribution of batteries for a microgrid.  We will simulate different households with different energy needs, use profiles of different harvesters, and figure out the lowest cost minimum battery system that can be used to satisfy the energy needs of all customers in the microgrid.  For example, is one big  battery shared among all customers better than small batteries owned by different customers and shared among all customers?  What is the capacity of the battery system that would satisfy 95% (99%?) of the needs of the microgrid?

POC: Guy Gadola OR Daniel Mosse (TBD)

### Smartphone Gps Duty-Cycle For Saving Battery In Navigation

One of the main battery drainers in smartphones is the GPS and maps applications (map app or mapp).  While it is true that most mapps are used in a car, and that many times USB connectors can charge phones in the car, while using the mapp.  The goal of this project is to reduce the energy consumed by the mapp and other apps that use GPS, by recognizing what the needs of the application are (e.g., duty cycle requirements while walking are different than while driving in a city, which are different than while driving in a highway).

In this project, we'll learn how a GPS works in depth, how to control it, read related literature on how to do adaptive duty cycling of GPS, and propose new algorithms (perhaps based on machine learning?) for better duty cycling.  There will be a lot of self-discovery, therefore students should be good at finding information on their own.

Time permitting, we'll also propose algorithms for optimizing navigation by suggesting which lane to use, with the help of the GPS.

POC: Daniel Mosse

### User Impatience: How To Save Energy On Smartphones With User Inputs

Smartphones allow a user to perform a variety of tasks, such as playing music, watching video, making calls, locating attractions, and more. However, one of the main issues in smartphones is the battery.  Phones can and do adjust resource usage dynamically, for example, dimming screens or reducing CPU frequency.  However, it is not personalized, and it is only looking at 1-2 resources.  Are there ways to make it more general and more personal, maximizing battery life, while minimizing user frustration?  We have implemented a prototype of such a system, where the users give feedback to the system through different interfaces and the system learns how each user uses the device. 

This project will implement or enhance several parts: (a) acquiring data about the usage of resources (CPU, screen brightness, Wi-Fi, network, etc), (b)  feed the collected data to a machine learning model in the cloud, (c) install the model in the smartphone to install the correct resource configuration, (d) a resource discovery mechanism, which finds the user preferences (eg, for CPU, start all cores on and slow them down gradually; when the user think it is too slow, s/he will give a feedback to User Impatience), and (e) testing of the final product.  Students will participate in any and all of the 5 parts above.

Required Skills: 

* Java 
* Android knowledge (Activity, Threads, Services)
* Android internal files knowledge is desirable but not required
* MySQL

POC: Raphael Cardoso Fernandes

### Including Specialized Hardware into Artifact Evaluation
Many areas of computer science rely almost entirely on empirical evaluation that uses software, data sets, benchmarks, scripts, and a myriad of other artifacts to evaluate new ideas and compare with past innovation. These evaluations are typically carried out by running "our" software versus "their" software; we have build a system called Occam that facilitates and validates such comparisons, called Artifact Evaluation (AE), by keeping track of all experiments there are run in such comparisons.  Our current version of Occam only supports running experiments on Docker on Linux machines.
This project aims to expand our AE system to accommodate specialized hardware.  For example, if an experiment requires the use of a Raspberry Pi, Arduino, or supercomputer, how can we connect the images running on Docker to this specialized hardware?  A PhD student has already carried out one single proof of concept system, but it has been characterized as a hack: kludgy, one-of, hard to work with.  Our job this semester a good extension of AE for specialized hardware and integrate it into Occam.
Required Skills: knowledge of Linux, desire to learn how to connect different machines.
Desired (but not required) Skills: experience with containers such as Docker, experience with multithreaded programming.

POC: Henrique Potter

### CS Course Grading App

I have a web app that allows graders for my cs-007 / 401 / 445 courses to view student code that resides on AFS, and write feedback for that code back onto the same directories on AFS.  Currently this apps runs on a laptop but needs to be modified so that it reads/write directories on AFS instead of test directories on a laptop.

Looking for a team of 1 – 3 programmers skilled in PHP, Javacript, and server-side web development.

POC: Tim Hoffman

# Bioinformatics-Focused Projects

### Complementary DNA Sequence Analysis

I am designing a tool to identify sets of short DNA sequences that are complementary (base pair) with target DNA or RNA sequences, given physical and thermodynamic constraints. Ie., given a target sequence, the program returns a set of shorter DNA sequences that tile the length of the target (allowing gaps up to a maximum length), where each of the DNA sequences falls within a min/max length and a min/max melting temperature. Targeting sequences in this way has many uses in molecular biology; I would specifically be using this tool to design reagents to selectively recognize specific RNA sequences (ribosomal RNA) in a complex mixture, so that they can be depleted from a sample.

I have written a python script that produces a heuristic solution to the problem, so there are two main areas for improvement: 1) Creating a web interface that would take the input sequence and parameters, pass them to the script, then display the results in a graphically appealing way; and optionally, allow the user to "tweak" the solution through the GUI by shifting the boundaries of the DNA sequences, updating the melting temperatures in real-time; 2) Adding features to the core functionality, e.g. allowing the user to initially constrain what portions of the target sequence must be tiled.

POC: Miler Lee

### Aligning Brain Cell Location to a Common Coordinate System

Modern neuroscientists study the brain at all levels from gross anatomy of the organ to the single neuron. Understanding the function of neuronal circuits and characterizing unique cell populations within the brain requires contextualizing a single cell precisely within the larger organ. To deal with this challenge, the Center for Biologic Imaging at the University of Pittsburgh has developed very high-speed imaging that can capture the whole brain at sub-micron resolution. This enables us to identify a single solitary cell with a whole brain in less than 1 day.

Although we can find the cell, how do you know what specific region of the brain that that cell occupies? Generally, these data would be aligned to a common coordinate system, a brain atlas, that would allow us to identify a specific region of the brain. However, commonly available tools do not play well with the many terabytes of data that this is type of imaging generates.

We are looking to develop a work flow for aligning massive data volumes to a common coordinate system. This will involve the use of existing tools in the neuroscience community but could also lead to the development of novel solutions. The solutions will need to integrate with existing CBI data pipelines and infrastructure which includes a custom high-performance computing environment and over 1PB of storage. An understanding of Matlab, Python and Linux are helpful.

POC: Alan Watson

### O’Donnell Lab – Machine Learning To Map Cellular Localizations

In response to a changing environment, cells reshuffle the localization of key membrane proteins. Mapping these localization changes is crucial for human health; if proteins are not in the correct location they cannot execute their proper cellular function. For example, in diseases like cystic fibrosis, mislocalization of a key membrane channel results in impaired lung function. In the O’Donnell lab, we are interested in characterizing the localization changes for membrane proteins in a high-throughput fashion. Using cutting edge fluorescence microscopy, we can define the intracellular distribution for hundreds of membrane proteins. Quantitative analysis of these distributions requires labor intensive manual manipulations. We are interested in developing an automated pipeline, that likely involves machine learning approaches, to allow for high throughput quantification analyses of protein distribution between the plasma membrane and intracellular compartments. We currently have a large, manually quantified training dataset. Should this experience prove rewarding for the student and beneficial to our research program, we can offer paid summer internships to further aid us in achieving these goals.

POC: Ally O'Donnell

### Automated Acoustic Monitoring of Bird Populations

There is growing evidence that the planet is in the midst of its sixth great mass extinction event. Responding to this crisis will require ecologists and conservation biologists to gather data on species populations at unprecedented spatial scales. Our lab’s approach to very large-scale biodiversity data collection is autonomous acoustic recorders - devices that can be placed in the field, automatically turn on and off, and record all sounds in the surrounding area. These recordings are then processed using machine learning models to identify what species were present at each location. We are actively developing both hardware and software capable of generating and processing hundreds of thousands of hours of such recordings.

There are two possible student projects associated with this topic, and the student group could feel free to choose either one:

1. Assembling a simple real-time streaming recorder using a Raspberry Pi device, using designs already published in the literature. This device will be placed at the Pymatuning Lab of Ecology. The team will then build software to capture this real time stream, apply a simple model to classify or describe the sounds being recorded, and then serve both the streaming audio and the data analysis to either a web or phone app.

2. Adding new functionality to our open source analysis software, OpenSoundscape (written in Python). At present, we have one machine learning method built into this software to classify bird calls. The team would implement at least one additional machine learning approach (probably deep CNNs) as a feature in this software, and compare its performance to our existing classifier. The methods to implement are previously described in the literature and could be implemented as is, or the group could propose modified versions of these methods to test.

POC: Justin Kitzes

### Pharmit Interface

In this project we will use JavaScript/jQuery and HTML to improve the interface of the Pharmit (http://pharmit.csb.pitt.edu/) virtual screening web application.  We will identify problems in the current interface, the student will suggest different designs to address these problems, and then they will implement their design.  All code will be developed on GitHub under an open source license.

POC: David Koes
