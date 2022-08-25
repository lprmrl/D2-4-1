# D2-4-1

Установка Docker:
sudo apt install docker.io 
sudo groupadd docker 
sudo usermod -aG docker $USER 
newgrp docker 

Установка minikube start:
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64


sudo install minikube-linux-amd64 /usr/local/bin/minikube

 
Запуск кластера из 5 нод, одна из них Сontrol Plane-нода: 
minikube start --memory=max --cpus=max -p d2-4-1 -n=5


Посмотреть профиль:
minikube profile list


Для проверки установленных нод используем команду:  
minikube status -p d2-4-1


Удалить все 
minikube delete --all

