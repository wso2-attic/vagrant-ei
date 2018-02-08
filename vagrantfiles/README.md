# Vagrantfile for WSO2 Enterprise Integrator

This section defines the procedure to run Vagrant resources for a specific profile of the WSO2 Enterprise Integrator

Please note that in order to run these Vagrant resources use, you need to install
[Oracle VM VirtualBox](http://www.oracle.com/technetwork/server-storage/virtualbox/downloads/index.html),
as Vagrant uses Oracle VM VirtualBox as the default provider.

Virtualization should be enabled in BIOS settings before building the boxes.

Requires minimum of 16GB ram.

## How to run the Vagrantfile

1. Checkout this repository into your local machine using the following Git command.

```
    git clone https://github.com/wso2/vagrant-ei.git
```

2. Build and add the Vagrant boxes for external MySQL database and WSO2 Enterprise Integrator using the Vagrantboxes resources.

3. Move to `vagrantfiles` folder.

```
    cd vagrantfiles
```

**The WSO2 EI considers 3 deployment profiles. Following are the 3 profiles.**

  1. Integrator, Analytics, and MySQL
  2. Integrator, Broker, Analytics, and MySQL
  3. Integrator, Broker, Business-process, Analytics, and MySQL

## To select a profile,

### First profile
 
Move to `integrator-analytics` folder.

```
    cd integrator-analytics
```

### Second profile

Move to `integrator-broker-analytics` folder.

```
    cd integrator-broker-analytics
```

### Third profile

Move to `integrator-broker-bps-analytics` folder.

```
    cd integrator-broker-bps-analytics
```

### Run the selected profile using the following command.

```
    vagrant up
```
