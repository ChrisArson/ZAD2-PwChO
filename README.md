### a. Polecenie uruchamiające stack:
``` docker-compose up -d ```
### b. Polecenie uruchamiające phpMyAdmin:
``` docker exec <nazwa_kontenera> mysql --execute="CREATE DATABASE <nazwa_bazy_danych>" --user=<nazwa_uzytkownika> --password=<haslo_uzytkownika> ```
### c. Polecenie tworzące testową bazę
``` docker container run --rm -it --name mgraph -v $(pwd):/input pmsipilot/docker-compose-viz render -m image docker-compose.yml ```

![image](https://user-images.githubusercontent.com/85616944/144505754-897f9e4c-39ab-4c99-b2f7-d913fef7ef74.png)
