# loligo


![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Python](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)

An app for **black collar** jobs <br>
More details will be added during the development

## Setting up docker

Build the docker image
```
docker build -t loligo_ubuntu:latest .
```

run docker container from the docker image
```
docker run --name loligo_ubuntu -d -p 8000:8000 loligo_ubuntu:latest
```
server will be up and running in
```
http://127.0.0.1:8000/
```


