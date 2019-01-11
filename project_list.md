# Capstone Project List

Please file your top THREE choices as an issue with a title beginning with PROJECT (will go over in class) by Tuesday (15 Jan) morning at 11:59 AM (i.e., right before noon). Please list them in the order that you prefer them.  You will be informed as to your project BEFORE the next Capstone class on Friday (18 Jan). YOU MUST FILE AN ISSUE IN ORDER TO BE PLACED ON A PROJECT AND THUS GET CREDIT FOR THE COURSE!  YOU WILL NOT BE PLACED ON A PROJECT IF YOU DO NOT FILE AN ISSUE!

REMEMBER TO ADD "PROJECT" TO THE BEGINNING OF YOUR ISSUE TITLE!

Along with your selections, please include any qualifications or specific reasons for interest that you have for those specific projects. Remember that you are "interviewing" for the project against others, especially if you have selected popular projects. Students who respond early also show enthusiasm for the projects, which goes a long way to showing that they actually want to do them.

I will attempt to place you in one of your top three choices. Last semester, every student got into one of their top three (and a majority into their #1 choice), although I do not make any guarantees.

Note: Some of you may be working on private projects. Please file an issue on this repository (as above) but note that you have already been assigned to a project. List the project and the name of the POC (e.g. faculty member or supervisor). If we have not discussed you being placed on a private project, do not put yourself on one.

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

### Bombardier - Personnel Tracking

Project Executive Summary: Bombardier Transportation is moving offices from West Mifflin to the Strip District. Along with this office move, many changes are taking place to the office structure. The new office will be taking an “open office” concept meaning there will not be any more assigned desks as mobility and flexibility is encouraged among employees in order to allow for easier collaboration. There will also be many new areas including new conference rooms, quiet spaces, think tanks, and labs.  In order to allow employees to locate one another through easier means in this new open office, Bombardier would like the development of an app that can allow employees to register their location as they move throughout the office.

Rationale for Project: Although there are general areas for the teams, there is a concern among employees that having unassigned desks and many new areas within the office could potentially lead to time spent on trying to locate someone throughout the office. Having an app that allows employees to voluntarily register a desk to themselves for the day and register their location as they move throughout the office can potentially lead to less time finding employees and more time working together. There are other benefits as well such as allowing the space in the office to be used more efficiently. For example, if a desk is no longer being used for the day because an employee leaves the office early, they should be able to unregister from the desk so that the desk can potentially be used by someone else. Second, the app could potentially be used to analyze which spaces in the office are being utilized and which are not thus allowing us to repurpose certain areas to better suit the employee needs.

Products & Deliverables:

  * An app that is compatible with Android and iOS (a tool such as Unity that allows development on both simultaneously is encouraged)
  * The app should at least have the basic functionality of registering/unregistering a user’s desk for the day
  * The app should also have a graphical proof of concept interface that allows users to see open desks, allows users to see who is sitting at a specific desk, and allows users to see where another user is sitting

POC: Muneeb Alvi

## Faculty Projects

### Dynamic and Searchable Campus Digital Signage

Project Director: Prof. Alex Labrinidis (http://labrinidis.cs.pitt.edu)

Short Description:
This project will revisit digital signage for the University of Pittsburgh campus (and beyond). Currently, many digital signage screens exist on Pitt's campus, but they display mostly static information (i.e., jpeg images that are shown on a schedule). Two notable exceptions are: (a) the screen at the lobby of SENSQ and (b) the screen across Panther Central; both of these are part of the PittSmartLiving project (led by Prof. Labrinidis) and show dynamic information. This capstone project will essentially create the infrastructure for web-based "screens" with dynamic content that can be included in the current digital signage displays or added to new installations. Examples of such dynamic content include listings of events and individual news stories. The content can come through integration with existing sources and/or development of new databases. Finally, a mobile-friendly "companion" web-page will allow users to interact with the screen in pre-determined ways (e.g., pick a specific day/time and see the matching events on the big screen). The plan will be to deploy this project by the end of the semester as an upgrade to the PittSmartLiving display at the lobby of SENSQ, to show such dynamic information in addition to the transit information it currently shows.

Number of students: 2-4

Technology:
The project will require a good database background (e.g., MySQL/Oracle), good web design/UI/UX background (esp. CSS, to make things look good in 4K screens), experience with mobile-friendly web sites, and experience with a web programming framework (e.g., python+flask/django). Not all students need to be experts in all areas, but the group should collectively be.

NOTE: If you are interested in this position, please include a CV/resume.  Dr. Labrinidis will review before placing students on the project.

POC: Alex Labrinidis

### PittCoin

The goal of this project is to develop a Pitt-specific token.  We will first determine a method of claiming and distributing PittCoins as well as possible use cases for such a token.  After this, we will develop a token using the ERC-20 standard, an interface for displaying balances, and additional features.  Part of this project will be determining which features would be useful - ideas include creating non-fungible tokens ("collectibles"), a leaderboard of who owns the most PittCoins, and Pitt-related games that can be played with them.  We will also conduct a security audit of the produced code to ensure the contract(s) operate(s) in the correct way and is secure.

Previous experience in the crytocurrency and blockchain space is nice, but not essential.  However, students who do have some background (via CS1699 Cryptocurrency and Blockchain technology, personal experience, or otherwise) are preferred.  This project will be written in Solidity with a web3.js front end.  

POC: Bill Laboon

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

This project aims to expand our AE system to accommodate specialized hardware.  For example, if an experiment requires the use of a Raspberry Pi, Arduino, or supercomputer, how can we connect the images running on Docker to this specialized hardware?  A PhD student has already carried out one single proof of concept system, but it has been characterized as a hack: kludgy, one-of, hard to work with.  Our job this semester  is to extend OCCAM adding an easy to use interface for specialized hardware. This interface will allow OCCAM to seamlessly execute AE in any hardware (when that hardware is available, obviously!).

Required Skills: knowledge of Linux, python programming, desire to learn how to connect different machines.

Desired (but not required) Skills: experience with containers such as Docker, multithreaded programming, and prototyping platforms (e.g., Arduino, raspberry pi)

POC: Henrique Potter

### CS Course Grading App

I have a web app that allows graders for my cs-007 / 401 / 445 courses to view student code that resides on AFS, and write feedback for that code back onto the same directories on AFS.  Currently this apps runs on a laptop but needs to be modified so that it reads/write directories on AFS instead of test directories on a laptop.

Looking for a team of 1 – 3 programmers skilled in PHP, Javacript, and server-side web development.

POC: Tim Hoffman

### Synthetic Student Generation

Personalized education is an exciting new field that has spawned from the (limited) success of Massively Open Online Courses and other online course offerings from different educational institutions.  These courses have generated a plethora of student data, where machine learning models have been created to assist students in a multitude of ways, such as reading/lecture material recommendation, problem solving suggestions, and peer-interaction encouragement.  However, not as much research effort has been directed at cross-course interactions, and similarly, not as much data has been published or analyzed.


This project will ask students to develop a tool that generates large synthetic student datasets that span across several courses in a university setting.  Real datasets are difficult to obtain in full, due to privacy and confidentiality policies, as well as exclusive research accessibility.  A generated synthetic dataset should allow any researcher to simulate a set of students with certain structural and student characteristics that can be specified as part of their parameters, such as course prerequisites, and grade distributions.  The resulting datapoint for each student will essentially read like a student's transcript, complete with a student's schedule of courses and the course grade received for each, along with more specific details regarding the student (e.g. demographics) and courses (e.g. which instructor taught the course).


Requirements: Students must have taken at least one of CS 1571 (AI), CS 1656 (Data Science), CS 1675 (Machine Learning), or an equivalent course that may be offered in other departments, or have previous experiences in research in machine learning or data mining.

POC: Nathan Ong

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

NOTE: Only one student will be selected for this project.

POC: David Koes

### Neurocognitive Assessment Toy

The aim on this project is to develop a toy and or app that allows us to quickly and effectively track cognitive development from childhood through adolescence to construct a pediatric neurocognitive growth chart to use during pediatric well visits. Developmental cognitive neuroscience has reached a level of understanding where we can begin to apply our understanding of what develops with regards to cognition and information processing informed by our understanding of the links with brain maturation, which my lab has investigated for the last 20 years. This is of importance because cognitive control, the ability to engage control over action for planned voluntary responses, is primary in our ability to engage with our environment and it is impaired in mental illness, which typically emerges in a developmental fashion particularly in adolescence. The idea is to use a fun toy that stores information regarding responses (reaction time, accuracy) and tabulates cognitive scores. Specifically, we are interested in measuring the following: reaction time (time between visual stimulus and button press), for tests of reactivity (how long to push a button when prompted by a visual stimulus), how long to press the button opposite the lit one when prompted and how many times did they fail and pressed the wrong button (inhibitory control), and how long and how many times where they able to follow a sequence after a 1-10 sec delay period. This can enable us to assess the level of the child for their given age and be able to see when they may be falling off the normative range and be able to determine assistance to correct their trajectory. This idea was inspired by the bop it toy (https://www.youtube.com/watch?v=p1rJ2uBWbw4; https://www.youtube.com/watch?v=Y_B795aUq20) but more recently we think a probe similar to the simon toy (https://en.wikipedia.org/wiki/Simon_(game)), would be a good first step.

NOTE: The Capstone project will involve creating a proof of concept of this assignment using a smartphone.  Some mobile development experience would be optimal.

POC: Beatriz Luna
