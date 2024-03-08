
mandatory concepts in Linux/AWS:

how to create aws account
ec2 instance creation
linux os management:
   types of distributions
   types of users
   file management
      touch/cat/vi/cp/mv/ls/cd/pwd
   options:
      man pages
   user management: 
       useradd/groupadd/passwd/usermod/w/whoami/
               /etc/passwd, /etc/shadow
   ssh management:  
       /etc/ssh/sshd_config ,   /etc/sudoers
   ownerships/permissions:
      chown/chgrp/chmod
   package management: 
       yum/rpm
          /etc/yum.repos.d
   process management:
      ps/top
   service management: 
     ssytemctl 
   performance:
      free/top/lscpu/lsblk/df
   port management: 
     ports
     security grouops/firewalls

aws management:  only devops/cloud/system  admins have access to aws account.
   
    ec2 instance creation steps:
       ami backup and its automation/userdata/metadata/how to upgrade/terminationpolicy
       name/ami/instancetype/keypair/vpc/sg/storage
    regions/az:
    different types of storages:
       ebs/efs/s3
          volumesnapshot/how to increase ebs/how to atatch ebs,efs,s3
               s3properties:
                  versioning/tags/eventnotification/objectlock/requesterpays/serverlogging/staticwebsitehosting
                  lifecyclepolicy rule
    awscli:
       version/configure
    iam:
       rootuser/users/roles/policies/sso
    vpc:  security/privatenetwork/costcutting
       public,private subnets/igw/ngw/routetable/sg/nacl/vpcpeering/elasticip/sitetositevpn/jump/bastion
       ifconfig/ping/telnet/netstat/nmap/nslookup/traceroute/tcpdump
    high availibility: perofrmance
      autoscalinggroup/loadbalancer/route53
    
    
   

   


  


      
