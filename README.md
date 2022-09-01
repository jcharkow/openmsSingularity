# Singularity Definition File for building OpenMS

This repository provides a definition file for building a custom build of OpenMS.
The official OpenMS repository can be found [here](https://github.com/OpenMS/OpenMS)


#### Requirements
1. [Singulairty](https://docs.sylabs.io/guides/3.8/user-guide/quick_start.html) 

#### Building OpenMS
1. Clone this repository using `git clone https://github.com/jcharkow/openmsSingularity`
2. Clone OpenMS using `git clone https://github.com/OpenMS/OpenMS.git`
3. (Optional) Make changes to OpenMS repository  
4. Edit line 31 of the `.def` with your location for OpenMS
3. Build your singulairty container using `singulairty build --fakeroot <containerName>.sig openms.def
