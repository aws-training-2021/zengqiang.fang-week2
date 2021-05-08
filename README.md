# zengqiang.fang-week2

## kubernetes training

### 预装环境

* #### docker desk

* #### enable kubernetes

* #### brew install kubectl

### 启动 local k8s中部署的service

* #### kubectl apply -f deployment.yaml

* #### kubectl apply -f service.yaml

* #### kubectl apply -f ingress.yaml

* #### input http://zqmaster.org/swagger/index to play with k8s

### the architecture of this application

![the architecture of this application](images/architecture.png)

### 常用命令总结

* #### **kubectl logs**: Print the logs for a container in a pod or specified resource. If the pod has only one container, the container name is optional

* #### **kubectl describe**: Show details of a specific resource or group of resources Print a detailed description of the selected resources, including related resources such as events or controllers. You may select a single object by name, all objects of that type, provide a name prefix, or label selector

* #### **kubectl apply**: Apply a configuration to a resource by filename or stdin. The resource name must be specified. This resource will be created if it doesn't exist yet. To use 'apply', always create the resource initially with either 'apply' or 'create --save-config' (JSON and YAML formats are accepted)

* #### **kubectl delete**: Delete resources by filenames, stdin, resources and names, or by resources and label selector. JSON and YAML formats are accepted. Only one type of the arguments may be specified: filenames, resources and names, or resources and label selector

### aspnetapi kubectl get/describe

* #### kubectl get pod

![kubectl get pod](images/GETPODS.png)

* #### kubectl get deployment

![kubectl get deployment](images/getdeployment.png)

* #### kubectl get service

![kubectl get service](images/getservice.png)

* #### kubectl describe pod

![kubectl describe pod](images/getdescribepods.png)

* #### kubectl describe deployment

![kubectl describe deployment](images/getdescribedeployment.png)

* #### kubectl describe service

![kubectl describe service](images/getdescribeservice.png)

* #### kubectl logs [pods name]

![first-aspnetapi-deployment-6f8b6464b9-2v8kb](images/getlog.png)
