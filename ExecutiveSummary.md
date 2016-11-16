#Executive Summary
##Main Concepts
Open Source software is the future of Software development. It is becoming more and more self-evident that the Software industry is moving away from licensing models and moving towards a service based model for income(ie. MS Office365, AWS, BackBlaze, and Redhat contracts). This new development has reduced the importance of closed source software and highlighted the benefits of community developed software. This community driven software has allowed companies to quickly grow and develop products by working together and change profit models to be more stable and lucrative. For this reason it is important to be able to fully utilize the OSS packages available to developers. Many packages have license files imbedded within them as well as public records of bugs and vulnerabilitie.
##Project Purpose
This Project focuses on parsing packages of software and identifying the relevant OSS licenses for each component. In addition to this it is important to identify known vulnerabilities in the system. Vulnerabilities are often caught quickly and noted in the Issues section of a repository but these vulnerabilities are officially recorded in the NIST package vulnerabilities database. This program will use the license files included with each component as well as the NIST reported information to identify relevant OSS licenses and security vulnerabilities in the packages submitted to the system. 
This information will then be stored in a database so it can be freely queried by developers and managers within the company. The intention is that this will improve the development and project management process by allowing developers to identify and address vulnerabilities in valuable packages. This information will also allow managers to manage the projects based on license information in order to avoid breaking copyright(left) and in order to maximize the value in in-house code that is developed to work with OSS systems.
##Project Components
This Project is composed of several components which each have their own associated process. The results of the processes will ultimately result in output that the devewlopers and managers will utilize

**Package parser** - takes package input from the Developer and seperates the package(s) into individual components of software

**NIST database system** - National Institute of Standards and Technology database of known security vulnerabilities in software

**OSS license scanner** - process the scans compenents it receives and identifies the OSS license associated with the component as well as vital details

**Manager Report builder** - takes queries from the Manager, forms them into requests and receives the output from the Database befor forming it into a report for the manager

**Developer Query tool** - allows the Developer to query the Database for relevant information on licenses and known NIST vulnerabilities in previously submitted packages 

