Installing siege
================

1. Open the Terminal app
2. Download the latest version of siege (currently 3.0.6)
   
   ``curl -C - -O http://www.joedog.org/pub/siege/siege-latest.tar.gz``
   
3. Extract the tarball
   
   ``tar -xvf siege-latest.tar.gz``
   
4. Change directories to the extracted directory (again, currently siege-3.0.6)
   
   ``cd siege-3.0.6/``
   
5. Run the following commands (one at a time) to build and install siege. If you have an older version of siege 
   read the INSTALL file for more instructions.
   
   ``./configure``
   ``make`` 
   ``make install``
