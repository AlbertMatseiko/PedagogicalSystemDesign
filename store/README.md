See docker-compose for 

```
export STORE_debug=True
```


```bash
sudo usermod -aG docker $USER && newgrp docker
```

Kubectl
https://kubernetes.io/ru/docs/tasks/tools/install-kubectl/

```bash
curl -LO https://dl.k8s.io/release/v1.29.2/bin/linux/amd64/kubectl
chmod +x ./kubectl
sudo mv ./kubectl /usr/local/bin/kubectl
```

Minikube for local kubernetes check:
https://kubernetes.io/ru/docs/tasks/tools/install-minikube/


Amazon guide for fastapi deploy

https://developers.eksworkshop.com/docs/kubernetes/python/about-multiservice



https://gist.github.com/wholroyd/748e09ca0b78897750791172b2abb051