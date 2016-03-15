# autoiso

###About:
This is a script takes a iso file and a ks/preseed file
for a linux distrobution (Centos,Debian,Fedora,Ubunto)
and builds a new iso file. That can be used to install 
linux.

###Opts:
*  -d:	 Distrobution, se Current supported dist
*  -i:	 Isofile
*  -o:	 Name of isofile this script will create, if not set file will be called <dist>.iso
*  -p:	 Preseed/ks file to use
*  -v:	 Verbose output
*  -V:	 Verboser output
*  -h:   help

###Example usage:
autoiso -d debian -i debian.iso -p preseed.cfg -o newdeb.iso

###Current supported dists:
* Debian			  
* Debian(i386)   
* Centos      
* Fedora      
* Ubuntu        
