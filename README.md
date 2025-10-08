rosty projekt pokazujący działanie Dockera z Pythonem.

## Pliki

- `app.py` – wyświetla losowy cytat przy każdym uruchomieniu
- `Dockerfile` – buduje obraz Dockera

## Budowa obrazu

```bash
docker build -t random-quote .

Uruchomienie kontenera
docker run random-quote


Każde uruchomienie kontenera wyświetli losowy cytat.

Cel projektu

Nauka podstaw Dockera

Zrozumienie Dockerfile i kontenerów


