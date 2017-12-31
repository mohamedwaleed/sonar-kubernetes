# Sonar-kubernetes
It is a kubernetes project for deplying sonar qube in kubernetes

# How to run
Make sure that kubernetes is installed correctly and you able to connect to it by kubectl

Run these command to create the following objects:
```sh
kubectl create -f nfs-pv.yml
kubectl create -f nfs-pvc.yml
kubectl create -f mysql-secret.yml
kubectl create -f mysql.yml
kubectl create -f sonar.yml
kubectl create -f mysql-service.yml
kubectl create -f sonar-service.yml
```


License
----

[Mohamed Waleed](https://github.com/mohamedwaleed) & [Omar Ewedah](https://github.com/OmarEwedah)
