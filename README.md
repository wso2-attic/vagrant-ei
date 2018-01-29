# WSO2 Enterprise Integrator Vagrant

Vagrant is an open-source software product for building and maintaining portable virtual software development environments, e.g. for VirtualBox, Hyper-V, Docker, VMware, and AWS. The core idea behind it lies in the fact that the environment maintenance of virtualizations becomes increasingly difficult in a large software development project. Vagrant simplifies the necessary software configuration management in order to increase development productivity. Vagrant is written in the Ruby language, but its ecosystem supports development in almost all major languages.

## Vagrantboxes

Five vagrant boxes are created for WSO2 Enterprise Integrator.

1. Analytics
2. Broker
3. Business-process
4. Integrator
5. MYSQL

## Vagrantfiles

There are three deployement profiles, according to the above five components.

1. Integrator, Analytics, MYSQL
2. Integrator, Analytics, Broker, MYSQL
3. Integrator, Analytics, Broker, Business-process, MYSQL
