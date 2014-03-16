[Siege](http://www.joedog.org/siege-home/) is an http load testing and benchmarking utility. It was designed to let web developers measure their code under duress, to see how it will stand up to load on the internet. Siege supports basic authentication, cookies, HTTP and HTTPS protocols. It lets its user hit a web server with a configurable number of simulated web browsers.

Installing siege on Mac OS X
============================

1.  Open the Terminal app
2.  Download the latest version of siege (currently 3.0.6)
    
    ``curl -C - -O http://www.joedog.org/pub/siege/siege-latest.tar.gz``
    
3.  Extract the tarball
    
    ``tar -xvf siege-latest.tar.gz``
    
4.  Change directories to the extracted directory (again, currently siege-3.0.6)
    
    ``cd siege-3.0.6/``
    
5.  Run the following commands (one at a time) to build and install siege. If you have an older version of siege 
    read the INSTALL file for more instructions.
    
    ```bash
    ./configure
    make
    make install

This installed ``siege`` to ``/usr/local/bin/``. This should already be in your ``PATH``, so type:

``siege``

will print its usage to your screen.
