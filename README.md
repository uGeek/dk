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
dk   dc                  -> Montar un docker-compose (docker-compose up -d)
dk   n                   -> Guarda un nuevo docker (new)
dk   i                   -> Imagenes listadas por creación (image)
dk   u, up, start        -> Lista dockers con su número para iniciar (up)
dk   d, down, stop       -> Lista dockers corriendo, con su número para detener (down)
dk   r, restart          -> Reiniciando docker  
dk   d -a, stop -a, ...  -> Detener todos los contenedores 
dk   e, exec             -> Entrar dentro del contenedor
dk   ip                  -> Conoce la ip de un docker
dk   ls ip, ip -a        -> Listar todas las ip's
dk   net, red            -> Listar todas las redes
dk   ls, ps              -> Dockers que están corriendo y sus puertos (list)
dk   ls -a, ps -a        -> Todos los Dockers disponibles (list all)
dk   st, store           -> Descarga Dockers de la store de dockerc
dk   rm                  -> Lista contenedores con su número para ser borrado (remove)
dk   drm                 -> Lista contenedores con su número para ser detenido y borrado (down and remove)
dk   rmi                 -> Lista imagenes con su número para ser borradas (remove image)
dk   save                -> Exportar imagen en el directorio actual
dk   load                -> Cargar Imagen del directorio actual
dk   sload               -> Buscar imagen del directorio actual, filtrando por palabra
dk   l, log              -> Lista contendores con su número, para ver los logs
dk   s, stats            -> Ver consumo de cpu, memoria,... de todos los contenedores
dk   s c, stats c        -> Lista contenedores con su número para ver el consumo de cpu, memoria,...
dk   ss, stats sort      -> Ordena contenedores por cpu, memoria, ...
dk   p, prune            -> Borrar todos los Contenedores, imágenes, redes, que esten detenidos
dk  -h, h, --help        -> Ayuda (help)


  Copyright (C) 2020 Angel. uGeek
  ugeekpodcast@gmail.com
```

## Contact

If you want to contact me you can reach me at https://ugeek.github.io.

## License

This project uses the following license: [MIT License](https://choosealicense.com/licenses/mit/).
