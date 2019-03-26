# Ansible Nodejs Deployment 
**this playbook will help deploy the following:**
* Nginx as reverse proxy
* Mongodb
* Nodejs server
* Angularjs

### prerequisite
_centos7_
### Installation
* setup your environment using vagrant file which contains:
  * master
  * nginx server
  * nodejs server
  * angular server 
  * mongodb server 
* install master ssh key on the remaining servers 
* install ansible 
* clone my playbook 

### Running the Playbook
`$ ansible-playbook -i inventory main-play.yml`
