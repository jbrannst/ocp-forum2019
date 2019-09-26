# OpenShift Service Mesh demo instructions for Red Hat Forum 2019
1. Follow the 4.1 Service Mesh installation guide at https://docs.openshift.com/container-platform/4.1/service_mesh/service_mesh_install/installing-ossm.html
2. create myproject
3. enable service mesh for myproject as per https://docs.openshift.com/container-platform/4.1/service_mesh/service_mesh_install/installing-ossm.html#ossm-member-roll_installing-ossm

# Installing bookinfo
1. git clone this repo
2. make sure you are logged in to 'myproject'
3. install by running
``` 
cd bookinfo 
./bookinfo_install 
```
4. show the kiali GUI, it's in istio-system
5. apply the istio networking overlays in turn 
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
