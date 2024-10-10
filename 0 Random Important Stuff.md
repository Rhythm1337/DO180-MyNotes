cd ~/DO188/labs/images-managing

podman login -u developer -p developer registry.ocp4.example.com:8443

podman cp cat.html container_name:/opt/app-root/src
