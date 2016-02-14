# BuzzApp
Buzz mobile application Enviroment SetUp (node.js, Mongo, express)  

Update linux AWS
  # sudo pip update
  
Install NPM and Node.js

    # sudo yum install gcc-c++ make
    # sudo yum install openssl-devel
  
  Install Git and Clone node repo
    
    # git clone git://github.com/joyent/node.git
  
Move to node directory 
  
    # cd node
  
git checkout with stable express version and install availbe git versions
    # git tag -l 
    # git checkout v0.12.0
    # ./configure
    # make
    # sudo make install
  
Add user path to sudoers

    # sudo su
    # vim /etc/sudoers
  
Edit path: 
  # Path = secure_path = /sbin:/bin:/usr/bin
Add to the end
    # :/usr/local/bin
  
Install express in desired directory

    # sudo npm install express-generator -g
  
express scaff setup

    #espress fileName
  
  
Install MongoDb
    # sudo su
    # vim /etc/yum.repos.d/mongodb-org-3.0.repo
    Add file content as follows: no (*)
    *
      [mongodb-org-3.2]
      name=MongoDB Repository
      baseurl=https://repo.mongodb.org/yum/amazon/2013.03/mongodb-org/3.2/x86_64/
      gpgcheck=0
      enabled=1
    *
      # write/quit with {!} 
  
  install command
  
    # sudo yum install -y mongodb-org
  
Make data directory

    # mkdir -p /data/db
  

  
  
