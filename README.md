# Instalação do InfluxDB 2.6.1 via Docker

1- Iniciar o Ubuntu 20.04.  
No terminal do Linux, executar o comando **`sudo dockerd`** para inicializar o Docker.

![image](https://user-images.githubusercontent.com/126198206/221853555-e5ba9c47-3bfd-47ec-a869-ffe5b61179fa.png)

2- Abra um novo terminal do Linux para executar os comandos abaixo.

![image](https://user-images.githubusercontent.com/126198206/221853641-3a76b0fb-2fab-4f72-8ad8-f39c36a373e7.png)

3- Baixa, criar container e executar o Influxdb.  
**`sudo docker run -d -p 8086:8086 -v influxdb:/var/lib/influxdb --name influxdb influxdb:2.6.1`**

4- Iniciar o container do Influxdb.  
**`sudo docker start influxdb`**

Obs.: Sempre ao inicializar o Docker, precisa iniciar o container do Influxdb.  
**`sudo docker start influxdb`**
