# Malware Classification with Cuckoo Sandbox

# Table of Contents

- [Project Overview](#project-overview)
- [Setup](#setup)
- [Obtaining Malware Samples](#obtaining-malware-samples)
- [Tasks](#tasks)
  - [Common Tasks](#common-tasks)
  - [Independent Tasks](#independent-tasks)
- [Disclaimer](#disclaimer)
- [Group Components](#members)

## Project Overview

<a name="project-overview"></a>

This repository showcases the implementation of a malware classification project utilizing the Cuckoo sandbox. We collected diverse malware samples from various GitHub repositories, subjected them to analysis using the Cuckoo Sandbox, and explored a method for classifying them based on a defined set of features. This project served as the Final Project for the MLCS (Machine Learning in Cyber Security) course at [Reykjavik University](https://en.ru.is/).

## Setup

<a name="setup"></a>

If you would like to replicate our results, you will need to either generate the dataset yourself or request us to share ours with you.
Before starting, make sure you have the necessary prerequisites:

- Cuckoo Sandbox (Version 2.0.7)
- Python 2.7 (required for Cuckoo 2.0.7)
- Python 3.9.0 (required for executing the Jupiter Notebook)
- Windows 7 VM (for Cuckoo 2.7)
- Access to a bare-metal Linux system or nested virtualization for Windows VM within a Linux VM

Refer to the official [Cuckoo documentation](https://cuckoo.readthedocs.io/en/latest/) for detailed setup instructions.

## Obtaining Malware Samples

<a name="obtaining-malware-samples"></a>

The malware samples were obtained from different public GitHub repositories:

- [The-MALWARE-Repo](https://github.com/Da2dalus/The-MALWARE-Repo/tree/master) by [Da2dalus](https://github.com/Da2dalus)
- [Malware-Database](https://github.com/cryptwareapps/Malware-Database/tree/main) by [cryptwareapps](https://github.com/cryptwareapps)
- [MalwareDatabase](https://github.com/Pyran1/MalwareDatabase) by [Pyran1](https://github.com/Pyran1)
- [DikeDataset](https://github.com/iosifache/DikeDataset/) by [iosifache](https://github.com/iosifache)

## Tasks

<a name="tasks"></a>

### Common Tasks

<a name="common-tasks"></a>

We have worked together with another group to perform the following common tasks:

- Obtaining malware samples
- Setup and execute analysis on Cuckoo Sandbox
- Utilize the VirusTotal API to obtain popular threat classification labels using the hash of the executable malware.

### Independent Task

<a name="independent-tasks"></a>

Our group has independently done the following tasks:

- Evaluated possible features other than API calls for classifying the model.
- Trained and evaluated different Machine Learning models.
- Fine-tuned parameters to obtain the best evaluation metrics.

## Disclaimer

<a name="disclaimer"></a>

To create the dataset, you have to download and analyze real malware, be careful and be sure to follow to maintain security and ethical standards throughout the project when trying to replicate the results.

## Group Members

<a name="members"></a>

- [Marco Serenelli](https://github.com/marcoserenelli)
- [Damiano Pasquini](https://github.com/damiano00)
