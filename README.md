# SLP D-App Registry

This repository contains guidance for developers interested in building decentralized applications (d-app) using SLP.  The purpose of this registry is to improve the overall user experience of SLP through encouraging (1) quality, (2) interoperability, and (3) network effect.  Each of these goals are achieved in the following ways:  

* **<u>Quality</u>** is achieved by allowing d-app developers to submit their d-app specification for peer-review as a Pull Request to this repository. Submissions will be reviewed for both formatting and adherence to the general specification requirements provided below.  Each d-app specification will be adopted with a "provisional" status, for at least 90 days after a public announcement, and until at least one implementation of the specification is available for  beta testing by the peer-reviewers.  After an implemented beta application has been peer-reviewed the d-app specification may be adopted with "standard" status and assigned with standard d-app identifier.
* **<u>Interoperability</u>** is achieved when there are multiple implementations of the same d-app specification.  SLP tokens associated with one d-app implementation need to be able to work with any of the other implementations.  In other words, d-apps specifications listed in this registry would not allow anyone to create an application that is a "walled-garden" type of platform.
* <u>**Network effect**</u> typically results in additional value for applications as a result of more possible interactions between participants in the network.  Using d-app protocol standards we are able to focus on building a network effect around the actual tokens people hold in their wallets and <u>*not*</u> necessarily individual app implementations.  Directing the network effect towards d-app specifications empowers the user instead of individual app developers.



## Spec Requirements

Peer reviewers will use the following requirements during the initial review of the specification Pull Request before merging the PR with a "Provisional" status.  Only after at least 90 days, and once an implementation has been tested by the reviewers with at least 3 

### General

1. Proposed d-application provides a solution to a real-world problem
2. Pull request can be merged cleanly, there are no conflicts

### Process

1. A specification Pull Request must have at least 3 reviewers prior to being merged to the "master" branch with "Provisional" status.
2. After the specification has been accepted the author shall use social media to announce the proposed specification and request a public review.  This public review period should last at least 90 days.
3. A specification may not be provisional for more than 180 days without any forward progress demonstrated or spec updates, otherwise the specification's status will be changed to "Abandoned" until the author starts the process again at step 1.
4. After public review period has ended, a Standard specification PR must have at least 3 reviewers prior to merging to "master" branch, and the specification's author must have announced for public review on social media platform required by the reviewers

### Formatting

Refer to the "/examples/slp-foobar-spec.md" for formatting guidelines.  This file should be copied and modified for your specification.



## Governance

There will be an initial appointment of 3-5 individuals capable of performing peer-reviews for this repository.  If anyone disagrees with the approach they are free to fork this repo and start maintaining their own d-app protocol registry.