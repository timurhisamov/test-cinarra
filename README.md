Role Name
=========

## Cinarra test repo

## DELIVERABLES
1. Link to the your public GitHub repo with the script and test page.
2. Install Jenkins and publish it main page
3. A script must complete:
    * Launch the EC2 server using  AMI, OS: Centos 7 64-bit, please use
default AWS AMI.
    * Begin the configuration management / bootstrapping of the server:
Disable SE Linux, add user Cinarra with SSH key.
    * Install Applications: Jenkins and NGINX
    * Publish Jenkins through NGINX, Jenkins Web UI must available
    * Check status of running app's
4. Please reply with the private key for cinarra user. 

Run
------------

~~~bash
ansible-playbook test1.yml --ask-become-pass
~~~

Requirements
------------

botocore
boto3

pip3 install --user boto3 botocore

Role Variables
--------------

| Variables       | Descriptions  |
| ------------- |:------------------:|
| ec2_access_key     | access key for EC2  |
| ec2_secret_key     | secret key for EC2 |
| cinarra_password  |  password for user cinarra |

Dependencies
------------

---

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
