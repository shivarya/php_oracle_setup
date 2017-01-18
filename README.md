# PHP Oracle setup in xampp
Following is the tutorial to install oracle on xampp with php  
**Step 1:**
download "Instant Client Package - Basic Lite" package from this [link](http://www.oracle.com/technetwork/topics/winsoft-085727.html)  
**Step 2:**
Unzip the package into a location such as: "C:\instantclient_11_2"  
**Step 3:**
add "C:\instantclient_11_2" to PATH of windows environment variable  
**Step 4:**
download these dll packages from [here](http://windows.php.net/downloads/pecl/releases/oci8/2.0.8/php_oci8-2.0.8-5.6-ts-vc11-x86.zip) and paste these dlls on php/ext directory  
**Step 5:**
add these lines to php.ini  
```
extension=php_oci8.dll
extension=php_oci8_11g.dll
```
**Step 6:(optional)**
if you dont have MDB2 already installed type these command on command  
```
pear install MDB2
pear install MDB2_Driver_oci8
```

Restart Apache and you are done  

