
## Kali Control Validation

Tested with Kali 2022.1

## Description

With this tool written for endpoint security, attack vectors will be carried out from different networks for vulnerable web applications to be located at the endpoint. It is a control verification method made to check how many attack vectors are passed by security devices between two networks.

## Features

Information is collected in the following contents :-

_Vulnerable SOAP Service Command Injection Control_

_Vulnerable SOAP Service SQL Injection Control_

_Vulnerable SOAP Service Information Disclosure Control_

_Vulnerable SOAP Service LFI Control_

_Vulnerable Flask App. SQL Injection Control_

_Vulnerable Flask App. HTML Injection Control_

_Vulnerable Flask App. SSTI Control_

_Vulnerable Flask App. Command Injection Control_

## Configuration

The main file is called _Control.py_ in which the _vulnerable_ip_ & _soap_service_ needs to be configured.

The _vulnerable-flask-app.py_ and _vulnerable-soap-service_ are provided for testing along with the test database called _test.db_ made using sqlite3.

_You would require the following tools :-_

SOAPUI,
SQLMap,
Burpsuite,
DirBuster

## Installation

git clone https://github.com/HonestlyNotGarv-dev/Control-Validation-using-SOAP.git

cd Control-Validation-using-SOAP



## Usage

First, the servers are located and run on the internal network.

![server](https://github.com/HonestlyNotGarv-dev/Control-Validation-using-SOAP/assets/131512571/7aba7f61-4ce0-4de4-996a-f3a354f58148)


The control.py that will attack is placed on the desired network and run.

![control](https://github.com/HonestlyNotGarv-dev/Control-Validation-using-SOAP/assets/131512571/4362111e-927e-44fa-a8f3-c13ad4bbf113)



