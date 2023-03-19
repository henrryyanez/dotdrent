# Dotdrent
## _API base de dotdrent_

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://github.com/henrryyanez/dotdrent)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://https://github.com/henrryyanez/dotdrent)

Para iniciar el proyecto puedes ejecutar el docker-copose:

```sh
docker-compose up -d
```
Para ejecutar comandos dentro del contenedor base puedes utilizar:
```sh
docker-compose run dotdrent sh -c "python dotdrent/manage.py makemigrations"
docker-compose run dotdrent sh -c "python dotdrent/manage.py migrate"
```
Verifica que el servicio está ejecutándose en el puerto: 8000
```sh
http://127.0.0.1:8000
```
Crea una app base
```sh
python3 manage.py startapp dot_app
```

 _Henrry Yánez_
[*Cybersecurity Engineer*]
## License

MIT

**Free Software, Yeah!**
