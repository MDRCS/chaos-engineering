# chaos_engineering

  Chaos engineering is the practice of deploying experiments into live production systems to discover weaknesses within those   systems. Chaos engineering allows you to learn about the behavior of your system by observing it during a controlled           experiment.

  + pip3 install -U chaostoolkit
  + pip3 install chaostoolkit-kubernetes
  //export FRONTEND_URL="http://$(kubectl get svc frontend -o jsonpath="{.status.loadBalancer.ingress[*].ip}"):8080/api/"

  + export FRONTEND_URL=http://journal.com/api
  + chaos run experiment.json
