# The Living God Church Website Container

The Living God Church Docker container for The Living God Church Website

## Prerequisites
* Docker for Windows, Linux or Mac
* Code Editor: Checkout [Atom](https://atom.io/) or [SublimeText](https://www.sublimetext.com/)

## Installation
1. Clone this repo: ```git clone https://github.com/markvillar/tlgc-docker.git```

2. Create a new Environment file ```.env``` in the root folder.

## Optional
3. Edit ```settings.py``` and your domain/ip to ```ALLOWED_HOSTS = ['yourhostipordomain']``` - if you're going to production.

```
SECRET_KEY='iocnuienuw3e4rowe92ednljqs230ewe2wd1we1dsadasd'
DB_NAME=DatbasName
DB_USER=DatbaseUser
DB_PASS=DatabaseUserPassword
DB_SERVICE=postgres
DB_PORT=5432
```

Where ```SECRET_KEY``` is simply just a random string characters - it can be as random and as long as you wish.

4. Fire up ```docker-compose up```

### Done! Let's get to work!

### Pull requests will be highly appreciated.. 😉
