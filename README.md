# Instrukcja

# Zadanie 2
![alt text](https://github.com/DenisFromUkraine/Pwcho1Kolomoiets/blob/main/pics/Dockerfile.PNG "Dockerfile")
Dockerfile
# Zadanie 3
## a. docker build -f Dockerfile -t local .
![alt text](https://github.com/DenisFromUkraine/Pwcho1Kolomoiets/blob/main/pics/docker%20build.PNG "docker build")
## b. docker run -p 2300:1600 -d --rm --name Projekt local
![alt text](https://github.com/DenisFromUkraine/Pwcho1Kolomoiets/blob/main/pics/docker%20run.PNG "docker run")
## c. docker logs Projekt
![alt text](https://github.com/DenisFromUkraine/Pwcho1Kolomoiets/blob/main/pics/docker%20logs.PNG "docker logs")
## d. docker image inspect local | jq ".[] .RootFS"
![alt text](https://github.com/DenisFromUkraine/Pwcho1Kolomoiets/blob/main/pics/image%20inspect.PNG "docker logs")

# Zadanie 4
1. Aby zbudować obraz wykorzystując bezpośrednio link do Dockerfile umieszczonego na GitHub należy użyć polecenia: docker build adresURLDoRepozytoriumGitHub.
2. Aby przenieść stworzony obraz na swoje konto na DockerHub należy użyć poleceń: docker tag nazwaObrazu:nazwaTagu nazwaRepozytorium:nazwaTagu i docker push nazwaRepozytorium:nazwaTagu.
