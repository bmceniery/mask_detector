# mask_detector

microk8s.kubectl config view --minify --raw

tar -xvf md_chart.tar
microk8s.kubectl create namespace md-service
microk8s.helm install --set service.externalIP=<external ip> --name=md-service --namespace=md-service ./md_chart

