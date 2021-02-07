# k8s-prometheus-stack
------------------------------------

use this to setup persistant volumes for grafana and prometheus on K8S promtheus-community/kube-prometheus-stack

------------------------------------

simply use kubectl create -f . -n <your_namespace>

then use the below command to install this chart with your custom values that defined in values.yml file:
  
          helm install  -f values.yml  monitoring   prometheus-community/kube-prometheus-stack   -n mon
          
-------------------------------------          
