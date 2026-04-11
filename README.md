# Odbiornik OGN w Aeroklubie Gdańskim

## Instalacja

Zainstaluj zależności:

Git:
`# apt install git`

Docker:
`# curl -fsSL https://get.docker.com | sh`

Sklonuj to repozytorium na swoje urządzenie:

`$ git clone https://github.com/Aeroklub-Gdanski/ogn-docker.git`

Wejdź do katalogu (`cd ogn-docker`) i wykonaj instrukcje poniżej.

### Konfiguracja
~~Skopiuj `.env.example` i zmień nazwę na `.env`, a następnie odpowiednio ustaw wartości.~~

Domyślna konfiguracja dla EPPR (Aeroklub Gdański) jest już uwzględniona. Zaktualizuj wszelkie wprowadzone zmiany w pliku `.env`!

## Obrazy Dockera
Wystarczy uruchomić plik makefile, aby utworzyć obrazy Dockera.

`$ make`

## Uruchom odbiornik

`$ docker compose up -d`

## Podgląd logów

`$ docker compose logs`
