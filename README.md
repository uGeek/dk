# dk
Create dockers that you have saved in 2 steps. 
List your dockers and their ports. List your images by creation date

## Install

```
sudo curl -L https://raw.githubusercontent.com/uGeek/dockerc/master/dockerc \
          -o /usr/bin/dk && sudo chmod +x /usr/bin/dk
```


## Help
```
Modo de empleo: dockerc [OPCIONES]

dk                       -> Menú para crear un contendor guardado con docker o docker-compose
dk   vc                  -> Menú para ver un contendor guardado con docker o docker-compose (show, see) 
dk   a                   -> Automontaje de todos los dockers de un grupo (add)
dk   n                   -> Guarda un nuevo docker (new)
dk   i                   -> Imagenes listadas por creación (image)
dk   u, up, start        -> Lista dockers con su número para iniciar (up)
dk   d, down, stop       -> Lista dockers corriendo, con su número para detener (down)
dk   d -a, stop -a, ...  -> Detener todos los contenedores 
dk   rm                  -> Lista contenedores con su número para ser borrado (remove)
dk   rmi                 -> Lista imagenes con su número para ser borradas (remove image)
dk   l, log              -> Lista contendores con su número, para ver los logs
dk   s, stats            -> Ver consumo de cpu, memoria,... de todos los contenedores
dk   s c, stats c        -> Lista contenedores con su número para ver el consumo de cpu, memoria,...
dk   ss, stats sort      -> Ordena contenedores por cpu, memoria, ...
dk   p, prune            -> Borrar todos los Contenedores, imágenes, redes, que esten detenidos
dk   ps,    ls           -> Dockers que están corriendo y sus puertos (list)
dk   ps -a ,ls -a        -> Todos los Dockers disponibles (list all)
dk  -h, h, --help        -> Ayuda (help)

  Copyright (C) 2020 Angel. uGeek
  ugeekpodcast@gmail.com
```

## Contact

If you want to contact me you can reach me at https://ugeek.github.io.

## License

This project uses the following license: [MIT License](https://choosealicense.com/licenses/mit/).
