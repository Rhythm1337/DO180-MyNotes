**Container Image**

```
FROM registry.ocp4.example.com:8443/ubi8/python-38:1-96
RUN echo "Hello from the container" > hello.html
```

**Login for registry**

podman login -u developer -p developer registry.ocp4.example.com:8443

**Copy Things**

podman cp cat.html container_name:/opt/app-root/src

**Open Shell in Container**

podman exec –it acme-demo-nginx bash 
