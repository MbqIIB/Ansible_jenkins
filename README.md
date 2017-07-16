# Ansible_jenkins
Successfully commit code for jenkins installtion on centos7
steps to run this code
# Ansible_setup
# yum install git
# git clone https://github.com/pavantech/Ansible_setup.git
# cd Ansible_setup
# sh setup.sh
# ansible --version
# git clone https://github.com/pavantech/Ansible_jenkins.git
# cd Ansible_jenkin
# cd centos7
# vi hosts
# [jenkins] 
# xx.xx.xx ansible_ssh_user=username ansible_ssh_pass=password
# vi main.yml
# uncomment host jenkins
# comment host # host localhost
# save
# ansible-playbook main.yml

