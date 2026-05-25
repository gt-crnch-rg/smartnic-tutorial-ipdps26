# In-network Computing with SmartNICs for Parallel Applications

Tutorial at IPDPS 2026

**Held on**: Monday, May 25, 8:30 AM - 12:00 PM and 1:30 PM - 5:00 PM CDT; Room J (4th floor of the Marriott hotel)

[Event website and Program](https://www.ipdps.org/ipdps2026/2026-tutorials.html)

![BlueField 3 SmartNIC](https://github.com/gt-crnch-rg/smartnic-tutorial-sc25/blob/2b33a3f47e94bf85083d54571c9a110bd97f93bc/fig/smartnic_bf3.jpg)

## Audience Tutorial Survey

Please take our brief survey on how we can improve the tutorial at [this form](https://forms.office.com/r/Bt1t3eN53T).

## Presenters

* Jeffrey Young [(Georgia Institute of Technology)](https://crnch-rg.cc.gatech.edu/)
* Elie Kfoury [(University of South Carolina)](https://sc.edu/study/colleges_schools/engineering_and_computing/faculty-staff/elie_kfoury.php)
* Richard Graham [(NVIDIA)](https://www.nvidia.com/)
* Aaron Jezghani [(Georgia Institute of Technology)](https://research.gatech.edu/people/aaron-jezghani)
* Antonio Peña [(Barcelona Supercomputing Center)](https://www.bsc.es/)
* Paul Ruth [(UNC Chapel Hill)](https://www.unc.edu/)

**Abstract:** The past few years have witnessed an increased level of support for and deployment of programmable network adapters, known as "SmartNICs". These enhanced network devices offer standard packet processing capabilities as well as advanced "in-network" computing features built around programmable lightweight processing cores, FPGAs, and even CPU- and GPU-based platforms capable of running separate operating systems. SmartNICs have gained rapid adoption for data center tasks, including infrastructure management, packet filtering, and I/O acceleration. Increasingly these devices are also being explored for high-performance computing (HPC) and AI application acceleration.

This tutorial offers an in-depth exploration of the state-of-the-art for SmartNICs and the emerging software ecosystems supporting them. Attendees will engage in hands-on exercises to better understand how to take advantage of SmartNICs for accelerating HPC and AI applications. Specific topics include MPI and OpenMP offloading, algorithmic modifications to utilize SmartNIC processors, in-line packet processing frameworks like P4, security and containerization efforts, and I/O acceleration techniques. Participants will have the opportunity to execute these exercises using cutting-edge SmartNICs like NVIDIA's BlueField-3 Data Processing Unit (DPU) and a cloud-based Netlab environment. The tutorial presenters will discuss additional techniques for optimizing applications to harness SmartNICs as communication accelerators in HPC systems.

Please note that tutorials are open to IPDPS 2026 attendees.

[Register here](https://www.ipdps.org/ipdps2026/)

## Agenda (Tentative, Subject to Updates)

| Time | Topic | Details |
|------|-------|---------|
| 8:30-8:40 | Introduction | Attendee Survey |
| 8:40-9:20 | Communication Offloading | SmartNIC overview, DPU examples, DPU programming models |
| 9:20-10:00 | SmartNIC Use Cases | Packet processing, cyber-security, AI/HPC |
| 10:00-10:30 | **BREAK** | |
| 10:30-11:15 | Infrastructure SW | DOCA and P4 frameworks |
| 11:15-12:00 | Hands-on | DOCA and P4 demo |
| 12:00-1:30 | **LUNCH** | |
| 1:30-2:15 | HPC Programming | MPI collective offload, OpenMP offload |
| 2:15-2:30 | Hands-on HPC | OpenMP offload and MPI demo |
| 2:30-3:00 | Storage Acceleration | Discussion of use case for SmartNICs with storage systems for AI |
| 3:00-3:30 | **BREAK** | |
| 3:30-3:35 | Tutorial Survey | |
| 3:35-4:00 | Additional Application Demos and Discussions | Machine Learning, Cybersecurity, Future Use Cases |
| 4:00-5:00 | Continued Hands-on Activities | Added demos and hands-on time |

Conference schedule reference: [IPDPS 2026 At-a-Glance Program](https://ssl.linklings.net/conferences/ipdps/ipdps2026_program/views/at_a_glance.html)

## Hands-on Examples

See the hands-on login information at this [Google Doc](https://docs.google.com/document/d/1VWvWfcDN3IV7K_ObqXnFvV-aCfes6OoldXtpO5862Jw/edit?usp=sharing)

The following topics will be covered via selected hands-on modules using the [FABRIC testbed](https://fabric-testbed.net/) and [Netlab testbed](https://research.cec.sc.edu/cyberinfra/cybertraining).

- MPI and OpenMP offloading patterns for SmartNIC-enabled applications
- In-line packet processing frameworks such as P4
- BlueField-3 DPU and Netlab-based practical exercises
- Security, containerization, and I/O acceleration techniques

## Slides

Handouts/slides for IPDPS 2026 tutorials will be posted here near the conclusion of the tutorial.
