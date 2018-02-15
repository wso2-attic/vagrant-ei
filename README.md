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

2. Move to `vagrant-ei` folder.

```
    cd vagrant-ei
```

**The WSO2 EI considers 3 deployment profile combinations.**

  1. Integrator, Analytics, and MySQL
  2. Integrator, Broker, Analytics, and MySQL
  3. Integrator, Broker, Business-process, Analytics, and MySQL

## Select a profile combination

### Integrator with Analytics
 
Move to `integrator-analytics` folder.

```
    cd integrator-analytics
```

### Integrator and Broker with Analytics

Move to `integrator-broker-analytics` folder.

```
    cd integrator-broker-analytics
```

### Integrator, Broker and Business-process with analytics

Move to `integrator-broker-bps-analytics` folder.

```
    cd integrator-broker-bps-analytics
```

### Run the selected profile combination using the following command.

```
    vagrant up
```
