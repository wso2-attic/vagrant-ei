# WSO2 Enterprise Integrator Vagrant

This repository contains the following Vagrantfiles for the 4 profiles of the WSO2 Enterprise Integrator.

- Analytics
- Broker
- Business-process
- Integrator


## Boxes
This contains the source code of obtaining 3 ubuntu/trusty64 vboxes as the base boxes and adding the WSO2 Enterprise Integrator and MYSQL to each box with the relevant JDK version. The WSO2 Server files are extracted inside each vbox. These boxes are automatically added to to the local Vagrant box cache.

## Vagrantfile
The vboxes added previously to the local Vagrant box cache are configured with the necessary IPs and Ports. Also the WSO2 Enterprise Integrator's profiles are deployed inside the vbox and could be evaluated by logging into the management console through the web browser.


