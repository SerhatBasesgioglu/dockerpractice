- Kurulum

1 - Proje klonlandıktan sonra /app dizininde "./mvnw clean install" komutları kullanarak appserver için jar dosyası oluştur.

2 - Docker engine/ Docker desktop aktifken root dizininde "docker-compose up" komutu ile image'ları indirip containerları aktif hale getir. 

3 - http://localhost:80 adresine get request yollayarak "Hello World" mesajına eriş ("curl http://localhost:80")



- Setup

1 - After cloning the project run the "./mvnw clean install" command at /app directory.

2 - Run "docker-compose up" command at root directory while Docker Engine/ Docker Desktop is active.

3 - Receive "Hello World" message by sending get request to http://localhost:80 address ("curl http://localhost:80")
