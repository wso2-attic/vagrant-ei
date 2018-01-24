# Vagrantfile for WSO2 Enterprise integrator

This section defines the procedure to execute run Vagrant resources for a specific profile of the WSO2 Enterprise Integrator

Please note that in order to run these Vagrant resources use, you need to install
[Oracle VM VirtualBox](http://www.oracle.com/technetwork/server-storage/virtualbox/downloads/index.html),
as Vagrant uses Oracle VM VirtualBox as the default provider.

Virtualization should be enabled in BIOS settings before building the boxes.

Requires minimum of 16GB ram.

## How to run the Vagrantfile

##### 1. Checkout this repository into your local machine using the following Git command.
```
git clone https://github.com/wso2-incubator/vagrant-is.git
```
##### 2. Build and add the Vagrant boxes for external MySQL database, WSO2 Identity Server and WSO2 Identity Server Analytics using the Vagrant box automation resources.

##### 3. Move to `machines` folder.

    cd machines

##### 4. Spawn up the Vagrant setup.

The WSO2 EI considers 3 deployment profiles.

Following are the 3 profiles.

  1. Integrator, Analytics, and MySQL
  2. Integrator, Broker, Analytics, and MySQL
  3. Integrator, Broker, Business-process, Analytics, and MySQL

Using the following command, a specific profile will be spawned

    profile=# vagrant up

Eg - For profile 3 the command is as follows

    profile=3 vagrant up
