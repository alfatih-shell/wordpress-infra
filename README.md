# wordpress-infra

The purpose of this repo for provisioning ec2 instance and wordpress

## How To Use this pipeline in your local host
* To use the script you should clone this repository
* Make sure you already have python 3 installed on your local host
* Install python dependencies requirements to your local host
> pip install -r requirements.txt
* Make sure you have ansible galaxy colection from this list
> amazon.aws         5.0.0
> ansible.windows    1.11.1
> community.aws      4.2.0
> community.windows  1.11.0
* Make sure you have access_key and secret_key for aws and also password for database
* Make sure you have ansible installed in your local
* Run this command from your local
> ANSIBLE_CONFIG=ansible.cfg ansible-playbook playbook.yml --ask-vault-pass --tags create_ec2 -v


