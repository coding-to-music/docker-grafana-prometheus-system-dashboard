## Starting the containers
kubectl -n prometheus-operator port-forward svc/prometheus-operator-prometheus 9090
kubectl -n prometheus-operator port-forward svc/prometheus-operator-alertmanager 9093
 
cp k8s-1-18-6-do-0-nyc1-1596172591964-kubeconfig.yaml config
 
kubectl get pods -A
kubectl -n prometheus-operator get pods | grep prometheus-operator-grafana<br>
kubectl -n prometheus-operator get pods | grep prometheus-operator-grafana
kubectl port-forward prometheus-operator-grafana-cf6954699-dd9jq  -n prometheus-operator 8080:3000

