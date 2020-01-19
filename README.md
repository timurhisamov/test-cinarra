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

Requirements
------------

botocore
boto3

pip3 install --user boto3 botocore

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
