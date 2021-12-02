### a. Polecenie uruchamiające stack:
``` docker-compose up -d ```
### b. Polecenie uruchamiające phpMyAdmin:
``` docker exec <nazwa_kontenera> mysql --execute="CREATE DATABASE <nazwa_bazy_danych>" --user=<nazwa_uzytkownika> --password=<haslo_uzytkownika> ```
### c. Polecenie tworzące testową bazę
``` docker container run --rm -it --name mgraph -v $(pwd):/input pmsipilot/docker-compose-viz render -m image docker-compose.yml ```
