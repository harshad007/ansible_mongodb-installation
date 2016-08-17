# ansible_mongodb-installation
install mongodb server using configuration management tool ansible

Pre-Setup
	Change IP_ADDRESS in hosts file under group [prim]
	- enter IP on which you want to install mongodb-server

RUN
	run following command 
	ansible-playbook site.yml
