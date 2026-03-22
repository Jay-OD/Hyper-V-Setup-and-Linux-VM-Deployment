# Hyper-V-Setup-and-Linux-VM-Deployment
This document outlines my experience setting up Hyper-V on my home PC and deploying a Linux virtual machine. I originally did this while completing a basic Linux overview course with Cisco, and I used the VM to practise terminal commands and understand how Linux behaves in a virtualised environment. 

Although this was a small personal project, it helped me build foundational skills that translate directly into cloud computing and Azure VM administration.

## What I Set Up

### Hyper-V Installation

* Enabled Hyper-V through Windows optional features
* Verified the installtion using Powershell
* Configured basic Hyper-V settings

Setting Up Hyper-V
<img width="2091" height="1326" alt="image" src="https://github.com/user-attachments/assets/652b0ce0-b60d-4bbc-a209-0515796e190f" />

### Linux VM Deployment

* Downloaded an Ubuntu ISO
* Created a new VM with custom CPU/RAM allocation
* Attached the ISO and installed Ubuntu
* Configured the VM for the first time use

Installed Ubuntu VM
<img width="2076" height="1266" alt="image" src="https://github.com/user-attachments/assets/82a80a28-c09f-4edf-b2b6-f41698bcc3c1" />

Error Encounted
<img width="2925" height="1809" alt="image" src="https://github.com/user-attachments/assets/623cb499-1d44-40b6-adf8-2f80d01e85d1" />
This was due to Hyper-V trying to boot from a Windows template by default. I did some research and I needed to change the boot from Windows Template to Microsoft UEFI Certificate Authority

<img width="2034" height="1116" alt="image" src="https://github.com/user-attachments/assets/f0ed1082-742a-491d-a125-c90f348c5914" />

Ubuntu is Now Booting
<img width="2181" height="1380" alt="image" src="https://github.com/user-attachments/assets/d52e6ea5-b0ec-41c1-a697-8e36a3fcfcf0" />

Ubuntu Intsalled and Running Terminal
<img width="3060" height="1767" alt="image" src="https://github.com/user-attachments/assets/863e1ca6-e094-4ade-a5a5-00031a855e48" />


## What I Practised Inside the Linux VM

### Basic Terminal Commands

Using the Ubuntu terminal, I practised essential Linux commands such as:

* ls, cd, pwd - navigation
* mkdir, rm, cp, mv - file management
* sudo, apt update, apt upgrade - package management
* chmod, chown - permission basics

While it wasnt required, I was trying to follow the lessons with a hands on approach in a real Linux enviroment rather than their portal.

Basic Bash Commands I was Practising
<img width="2205" height="1536" alt="image" src="https://github.com/user-attachments/assets/0750a644-bea3-47b6-9877-7801019d8221" />


## How This Experience Helped

Even though this wasnt required for the course, this small home project gave me hands on experiance with setting up VMs, Hyper-V, OS Images, and more of an understanding of Linux and its Distros. I had to research which Distro would work best, with Ubuntu having good feedback for being user friendly and is highly customisable which was perfect to practice with.

This project required a lot of research and while setting it up delayed my course, it was worth it as it gave me more hands on experience than the course alone was providing. 
