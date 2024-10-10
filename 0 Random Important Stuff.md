cd ~/DO188/labs/images-managing

**Login for registry**

podman login -u developer -p developer registry.ocp4.example.com:8443

**Copy Things**

podman cp cat.html container_name:/opt/app-root/src

**Open Shell in Container**

podman exec –it acme-demo-nginx bash 
