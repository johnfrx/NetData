Bootstrap: docker
From: centos:latest

%runscript
    exec echo "Centos7 image for use with globus"


%post
    #echo "The post section is where you can install, and configure your container."
    #
        yum -y install autoconf automake curl gcc git libmnl-devel libuuid-devel openssl-devel libuv-devel lz4-devel Judy-devel make nc pkgconfig python zlib-devel
        git clone https://github.com/netdata/netdata.git --depth=100
        cd netdata
        echo | ./netdata-installer.sh

