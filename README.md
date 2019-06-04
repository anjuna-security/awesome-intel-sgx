# Awesome Intel® SGX
> [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
> A curated list of awesome resources related to Intel® Software Guard Extensions (SGX).

## Contents
* [Introduction](#introduction)
* [Official Intel® Documentation](#official-intel-documentation)
* [Tutorials](#tutorials)
* [Related Security Research](#related-security-research)
* [Applications](#applications)

## Introduction

Intel® Software Guard Extensions (SGX) is Intel's take on enabling creating secure enclaves for applications on Intel's processors, starting with Skylake and on. Some of the objectives of Intel® SGX are:

* Allow applications to protect sensitive data from unauthorized access or modification by rogue software running at higher privilege levels.
* Enable applications to preserve the confidentiality and integrity of sensitive code and data without disrupting the ability of legitimate system software to schedule and manage the use of platform resources.
* Enable the platform to measure an application’s trusted code and produce a signed attestation, rooted in the processor, that includes this measurement and other certification that the code has been correctly initialized in a trustable environment.
* Enable the development of trusted applications using familiar tools and processes.
* Allow the performance of trusted applications to scale with the capabilities of the underlying application processor.
* Enable applications to define secure regions of code and data that maintain confidentiality even when an attacker has physical control of the platform and can conduct direct attacks on memory.

## Official Intel® Documentation
* [Intel® Software Guard Extensions](https://software.intel.com/en-us/sgx-sdk/documentation)
* [Overview of Intel® Software Guard Extensions Instructions and Data Structures](https://software.intel.com/en-us/blogs/2016/06/10/overview-of-intel-software-guard-extensions-instructions-and-data-structures)

## Tutorials
* [Intel® SGX Explained](https://eprint.iacr.org/2016/086.pdf)

## Related Research
* [CoSMIX: A Compiler-based System for Secure Memory Instrumentation and Execution in Enclaves](https://www.usenix.org/conference/atc19/presentation/orenbach)
