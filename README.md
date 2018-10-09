# Vagrantfile for WSO2 Enterprise Integrator

In order to use Vagrant boxes, you will need an active subscription from WSO2 since the Vagrant boxes hosted at vagrant.wso2.com contains the latest updates and fixes to WSO2 Enterprise Integrator. You can sign up for a Free Trial Subscription [here](https://wso2.com/free-trial-subscription).

If you wish to use the Vagrant boxes without updates, please build them from [here](https://github.com/wso2/vagrant-boxes).

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
>If you are to try out an already released zip of this repo, please ignore this 1st step.
2. Move to `vagrant-ei` folder.

```
    cd vagrant-ei
```
>If you are to try out an already released zip of this repo, please ignore this 2nd step also. Instead, extract the zip file and directly browse to vagrant-ei-<released-version> folder.

>If you are to try out an already released tag, after executing 2nd step, checkout the relevant tag, i.e. for example:
 git checkout tags/v6.4.0.1 and continue below steps.

**The WSO2 EI considers 4 deployment profile combinations.**

  1. Integrator, Analytics, and MySQL
  2. Integrator, Broker, Analytics, and MySQL
  3. Integrator, Business-process, Analytics, and MySQL
  4. Integrator, Broker, Business-process, Analytics, and MySQL

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

### Integrator and Business Process with Analytics

Move to `integrator-bps-analytics` folder.

```
    cd integrator-bps-analytics
```

### Integrator, Broker and Business-process with analytics

Move to `integrator-broker-bps-analytics` folder.

```
    cd integrator-broker-bps-analytics
```

### Run the selected profile combination using the following command.

```
    vagrant --updates up
```
In order to run the setup without updates,run the selected profile combination using the following command.

```
    vagrant up
```
