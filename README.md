# Docker Kurulumu

Bu dökümantasyon üzerinde docker kurulumu sağlıyacağız. İşletim sistemimizi güncelleyip, Docker'ı bash script yöntemiyle kuracağız.

Docker, "konteynerleştirme" olarak da bilinen işletim sistemi seviyesinde sanallaştırma sağlayan bir bilgisayar programıdır.
 
## Gereksinimler
-   Ubuntu Server 20.04 LTS

## Docker Kurulumu
Sistemimizi güncelleyelim
>sudo apt-get update && apt-get upgrade -y

Docker'i kuralım
>curl -fsSL https://get.docker.com -o get-docker.sh
>sudo sh get-docker.sh

Docker'in durumunu kontrol edelim
>systemctl status docker

Aşağıdaki gibi bir çıktı ile karşılaşıyorsanız docker kurulumu tamalanmıştır.

![enter image description here](https://raw.githubusercontent.com/ReptilianusBileciktus/ubuntu-20.04-zerine-docker-kurulumu/main/ddd.png)

