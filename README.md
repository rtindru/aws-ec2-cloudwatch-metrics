AWS EC2 Cloudwatch Metrics
=========
Ansible role to setup additional metrics tracking for AWS EC2 instances via Cloudwatch
http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/mon-scripts.html#mon-scripts-systems

Requirements
------------
One of the following:
- Amazon Linux 2014.09.2
- Red Hat Enterprise Linux 6.6
- SUSE Linux Enterprise Server 12
- Ubuntu Server 16.04 and 14.04

Role Variables
--------------

TBD

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: rtindru.aws-ec2-cloudwatch-metrics, aws_access_key: XXXX, aws_secret: YYYY}

License
-------

MIT

Author Information
------------------

Rajtilak Indrajit

rt.indru@gmail.com