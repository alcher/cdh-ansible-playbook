# cdh-ansible-playbook
playbook for cdh cluster setup

# About this playbook
This playbook builds environment Cloudera's CDH 5.7 cluster.

## System requirement
- OS
```
CentOS 7.2(x86_64)
```
- ansible-playbook
```
ansible-playbook 1.9.4
```

### Sample target hosts
```
[cdh]
node0.x.y
node1.x.y
node2.x.y
```

## Install modules
- Cloudera Manager
- Oracle Java 

## Dependency yum modules
- Development tools
- ntp, ntpdate

## About proxy
If mesos environment is under proxy/nat, please use proxy vars and rewrite proxy rpm's options.

Also, please set the host's proxy environment:  http_proxy, https_proxy, ftp_proxy.

Example. "~/.bash_profile"
```
export HTTP_PROXY='http://yourproxy:proxyport/'
export HTTPS_PROXY='http://yourproxy:proxyport/'
export FTP_PROXY='http://yourproxy:proxyport/'
```
