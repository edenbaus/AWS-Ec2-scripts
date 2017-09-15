# AWS-Ec2-scripts
Python &amp; Bash scripts to assist updating an 'aws' hostname entry in /etc/hosts

Note: to avoid needing the '-i /path/to/cert.pem' parameter, run ssh-add /path/to/cert.pem

you may need to change the permissions to /etc/hosts with: sudo chmod 755 /etc/hosts

# operating scripts
- ## aws-hostadd asks for an ec2 instance id (running instances only!) then the desired hostname
- ## ec2ssh is an alias for ssh: ec2ssh <awshostname>
