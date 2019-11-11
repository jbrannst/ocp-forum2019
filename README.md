# OpenShift Service Mesh demo instructions for Red Hat Forum 2019
1. Install OpenShift 4.1 by running the installer from https://cloud.redhat.com
2. Follow the 4.1 Service Mesh installation guide at https://docs.openshift.com/container-platform/4.1/service_mesh/service_mesh_install/installing-ossm.html
3. Create myproject
4. Enable service mesh for myproject as per https://docs.openshift.com/container-platform/4.1/service_mesh/service_mesh_install/installing-ossm.html#ossm-member-roll_installing-ossm

# Installing bookinfo
1. Git clone this repo
2. Make sure you are logged in to 'myproject'
3. Install by running
``` 
cd bookinfo 
./bookinfo_install 
```
# Running the demo
1. Offer the audience to look at the app in their phone, this drives traffic and engagement.
2. Ask if anyone knows how it works. Show the kiali GUI, it's in istio-system. Ask someone to explain how it works now
3. Apply the istio networking overlays in turn, each time asking the audience if they can see what happened 
``` 
./1
```
. and so on
``` 
./2
```
``` 
./3
```
. and optionally the abort scenario
``` 
./4
```
