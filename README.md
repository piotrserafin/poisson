# Wizualizacja poissonowskiego strumienia zgłoszeń

## Wymagania wstępne

* Środowisko Python w wersji 3.6+ (https://www.python.org/downloads/)
* Manager pakietów pip3

```bash
Linux (Ubuntu/Debian):~/$ sudo apt-get install python python3-pip
```

W przypadku środowiska windows pakiet pip jest instalowany domyślnie wraz z instalacją pythona

## Konfiguracja

W celu skonfigurowania wirtualnego środowiska oraz instalacji zależnośći należy wykonać przejść do folderu projektu i wykonać skrypt:

```bash
Win> .\configure.bat
Linux:~/$ source configure
```

Zostanie utworzony nowy katalog ```.env_possion``` następnie terminal przełączy się do środowiska wirtualnego.

## Uruchomienie 

W celu wystartowania środowiska Jupyter należy wykonać komendę:

```bash
jupyter notebook
```

Uruchomiona zostanie przeglądarka internetowa z listą plików. Należy kliknąć na plik ```piossion.ipynb```

## Aktywacja/Deaktywacja środowiska wirtualnego

W celu aktywowania środowiska wykonujemy komendę

```bash
Win> .env_poisson\Scripts\activate.bat
Linux:~/$ source .env_poisson/bin/activate
```

Aby opuścić środowiska należy wykonać komendę

```bash
Win> .env_poisson\Scripts\deactivate.bat
Linux:~/$ deactivate
```
