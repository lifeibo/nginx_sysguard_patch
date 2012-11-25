==DESCRIPTION==

Path of sysguard for nginx 1.2.5.

==INSTALLATION==

    wget http://www.nginx.org/download/nginx-1.2.5.tar.gz
    tar xzvf nginx-1.2.5.tar.gz
    cd nginx-1.2.5
    patch -p1 < nginx_sysguard_1.2.5.patch
    ./configure --with-http_sysguard_module
    make && make install
