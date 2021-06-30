## Run playbook.yml

`ansible-playbook --private-key=~/aws_keys/aws_pair.pem -i inventory playbook.yml -u ubuntu`

**NOTE:** This playbook is tested on AWS Ubuntu Server 18.04 LTS. Ubuntu Server 18.04 LTS comes pre-configured with ubuntu user . This playbook uses that user. If you are using another cloud provider then you may have to create new sudo user and use that user.
