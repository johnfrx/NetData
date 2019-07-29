Bootstrap: docker
From: centos:latest

%runscript
    exec echo "Centos7 image for use with globus"


%post
    #echo "The post section is where you can install, and configure your container."
    #
    yum install -y wget
    wget https://my-netdata.io/kickstart.sh
    printf "\ny\n" | bash kickstart.sh
    #trigger commit
    
