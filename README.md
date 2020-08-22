# SLP D-App Registry

This repository contains guidance for developers interested in building decentralized application (d-app) protocols using SLP.  The purpose of this registry is to help improve the overall user experience of SLP through encouraging (1) quality, (2) interoperability, and (3) network effect of d-apps usage.  These goals are achieved in the following ways:  

* **<u>Quality</u>** is achieved by facilitating a peer-review process for new d-app protocol specifications using this repository. D-app spec submissions will be reviewed for adherence to the requirements provided below.  Each d-app spec will be accepted with a "Provisional" status during a public review period.  After an implemented beta application has been peer-reviewed the d-app specification may be adopted with "standard" status and assigned with standard d-app identifier.
* **<u>Interoperability</u>** is achieved when there are multiple implementations of the same d-app specification.  SLP tokens associated with one d-app implementation need to be able to work with any of the other implementations.  In other words, d-apps specifications listed in this registry would not allow anyone to create an application that is a "walled-garden" type of platform.
* **<u>Network effect</u>** typically results in additional value for applications as a result of more possible interactions between participants in the network.  Using d-app protocol standards we are able to focus on building a network effect around the specified protocols and <u>*not*</u> necessarily individual app implementations.  This repository will facilitate building a network effect around d-app protocols which should empower users instead of individual app developers.

Currently this guidance is only relevant to Token types 0x01, 0x41, and 0x81.  Additional considerations may be needed for future token types.

## Spec Requirements

Peer reviewers will use the following requirements during the initial review of d-app spec Pull Requests.

### General

1. Proposed d-app has merit as determined by the reviewers
2. Specification includes requirement for unique identifier in "Document Hash" field following Bitcoin Files Protocol
3. Pull request can be merged cleanly, there are no conflicts

### Process

1. A spec Pull Request must have at least 3 reviewers prior to being merged into the "master" branch with "Provisional" status.
2. After the spec has been accepted the author shall use social media to announce the proposed spec and request a public review.  This public review period should last at least 90 days.
3. A spec may not be provisional for more than 180 days without any forward progress demonstrated or spec updates, otherwise the spec's status will be changed to "Abandoned" until the author starts the process again at step 1.
4. After public review period has ended, a Standard spec PR must have at least 3 reviewers prior to merging to "master" branch, and the spec's author must have announced for public review on social media platform required by the reviewers

### Formatting

Refer to the "./specs/examples/slp-foobar-spec.md" for formatting guidelines.  This file should be copied and modified for your spec.



## D-App Identifiers

Each d-app specification is assigned a unique d-app identifier stored within the Genesis "Document Hash" field of any token wishing to participate in the application.   For provisional specifications, this value can be set to any unique value.   For Standard specifications this value must be set to the file hash of a Bitcoin Files Protocol that is not The document hash value must be equal to the txid

### Provisional

| D-App Name | Current Provisional Unique Identifier |
| ---------- | ------------------------------------- |
| FooBar     | <Some BFP Token Document Hash>        |
|            |                                       |
|            |                                       |



### Standard

| D-App Name | Final Unique Identifier   |
| ---------- | ------------------------- |
| NA         | <BFP Token Document Hash> |
|            |                           |
|            |                           |

