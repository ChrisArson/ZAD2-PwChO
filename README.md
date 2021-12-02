### a. Polecenie uruchamiające stack:
``` docker-compose up -d ```
### b. Polecenie uruchamiające phpMyAdmin:
``` ```
### c. Polecenie tworzące testową bazę
``` docker container run --rm -it --name mgraph -v $(pwd):/input pmsipilot/docker-compose-viz render -m image docker-compose.yml ```
