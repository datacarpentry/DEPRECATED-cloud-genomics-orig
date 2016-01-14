---
layout: lesson
root: .
title: Introduction to Cloud Computing
minutes: 5
---

### Learning Objectives

- Understand why you would want to use cloud computing
- Understand what cloud computing and high-performance-computing resources are
- Be aware of what resources are available


### What are some of reasons to access a remote computer system?

 * Your computer does not have enough resources to run the desired analysis (memory, processors, disk space, network bandwidth).
 * You want to produce results faster than your computer can.
 * You cannot install software in your computer (application does not have support for your operating system, conflicts with other existing applications)

### Main Computational Resources

![Computer Node](https://raw.githubusercontent.com/datacarpentry/cloud-genomics/master/lessons/images/Computer.png)

The main limitations of a computer are:

- memory
- number of processors
- speed of processors

Different applications might require more of less of different resources, but in bioinformatics most programs require more than your laptop has available.

Cloud computing resources like Amazon EC2 or Microsoft Azure and high-performance-computers (HPCs) like you might have at your university have much more capacity however.

For instance where your computer might have 8 GB of memory, these resources can have Terabytes.

### What is a remote computer system?

These are computers that are in a room, or a lot of rooms, somewhere else.

To access these machines, you have to log in to them remotely. It's like you're calling them on the telephone to be able to use them.

--- Need better information here


### HPC vs. Cloud:

While both Cloud and HPC resources allow you to run larger and faster analyses, there are some distinctions. 


   * High Performance Computing (HPC): large assemble of physical machines and a homogeneous operating system (e.g., your institutions' HPC, XSEDE's HPC)
   * Cloud Computing: virtual machines, distributed platforms and/or applications offered as a service (e.g., Amazon Web Services, Microsoft Azure, Google Cloud Computing)


| HPC | Cloud |
|:----|:------|
| User account on the system | root account on the system |
| Limited control of the system | Full control of the system |
| Central shared file system | Local file system |
| Jobs submitted into a queue | Jobs executed on each resource |
| Account-based isolation | OS-based isolation |
| Batch-oriented execution of applications | support for batch or interactive applications |
| Request for resource and time allocation | Pay-per-use |
| etc. | etc.|

![HPC vs. Cloud](https://raw.githubusercontent.com/datacarpentry/cloud-genomics/master/lessons/images/HpcVsCloud.png)


### Resources:

 * Cloud computing offerings:
  * Amazon EC2: http://aws.amazon.com/ec2/
  * Microsoft Azure: https://azure.microsoft.com/en-us/
  * Google Cloud Platform: https://cloud.google.com/
  * iPlant's Atmosphere: http://www.iplantcollaborative.org/ci/atmosphere
  * iPlant's help page: https://pods.iplantcollaborative.org/wiki/display/atmman/Atmosphere+Manual+Table+of+Contents
 * HPC offerings:
  * XSEDE: https://www.xsede.org/high-performance-computing
