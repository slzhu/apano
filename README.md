# apano
Additional patch for Nginx based on Openresty

## Install
1. Download the wanted openresty tarball from the [Download](http://openresty.org/en/download.html) page
2. Unpack it like this:  
    `tar -xzvf openresty-VERSION.tar.gz`
3. Fetch this [repository](https://github.com/slzhu/apano.git)
4. Copy the 'prepatch' and 'patches' into the openresty folder
5. Run the './prepatch' to apply the patches in "patches" folder
6. Next follow the official guide of Openresty to install, maybe like  
```
    ./configure
    make
    make install
```
