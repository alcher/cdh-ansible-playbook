# cdh-ansible-playbook
playbook for cdh cluster setup

# About this playbook
This playbook builds environment Cloudera's CDH 5.7 cluster.

## System requirement
- OS
```
CentOS 7.2(x86_64)
```

### Sample target hosts
```
[cdh]
node0.x.y
node1.x.y
node2.x.y

## Install modules
- Cloudera Manager
- Oracle Java 

## Dependency yum modules
- Development tools
- ntp, ntpdate
