# TNS | Install Milvus and RMM

### Required Packages

###
##### APT LIKE
```bash
apt-get update
apt-get install python3-pip git sshpass -y
pip3 install pip --upgrade
pip3 install ansible pywinrm
```

##### YUM LIKE
```bash
yum install python3-pip git sshpass -y
pip3 install pip --upgrade
pip3 install ansible pywinrm
```
## Quick Start

- Clone the repository
```bash
git clone https://github.com/ybucci/tns_milvus_rmm.git
```

- Configure **inventory/cliente1/hosts.ini** with your servers and credentials
####
- Run the playbook in your Ansible Machine

```bash
ansible-playbook -i inventory/cliente1/hosts.ini install.yml
```