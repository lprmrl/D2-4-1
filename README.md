# D2-4-1

Установка Docker/
sudo apt install docker.io/
sudo groupadd docker/
sudo usermod -aG docker $USER/
newgrp docker/

Установка minikube start:
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
sudo install minikube-linux-amd64 /usr/local/bin/minikube

 
Запуск кластера из 5 нод, одна из них Сontrol Plane-нода
minikube start --memory=max --cpus=max -p В2-4-1 -n=5
https://github.com/lprmrl/D2-4-1/blob/main/%D1%80%D0%B5%D0%B7%D1%83%D0%BB%D1%8C%D1%82%D0%B0%D1%82.png

https://github.com/lprmrl/D2-4-1/blob/main/%D0%BA%D0%BE%D0%BD%D1%82%D0%B5%D0%B9%D0%BD%D0%B5%D1%80.png

Для проверки установленных нод используем команду 
minikube status -p D2-4-1
https://github.com/lprmrl/D2-4-1/blob/main/%D1%81%D1%82%D0%B0%D1%82%D1%83%D1%81.png
