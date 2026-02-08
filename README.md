# Entorno de desarrollo Laravel con Sails
 - Docker desktop iniciado
 - Terminal o consola
 - WSL 2 
## Crear proyecto laravel
- Buscamos ruta donde vamos a quereer iniciar proyecto nosotros va a ser en Documentos, para esto abrimos la terminal y accedemos a ella
![ruta](assets/img/ruta.png)
- Usamos el comando wsl para acceder a terminar linux.
- Ejecutamos " curl -s "https://laravel.build/mi-proyecto" | bash " donde mi proyecto puede ser el nombre que queramos
![Proyecto](assets/img/proyecto.png)
- accedemos al proyecto 
![Ruta acceso proyecto](assets/img/rutaacceso.png)
- Iniciamos el entorno de contenerdores por primera vez " ./vendor/bin/sail up -d "
![Iniciamos contenedores por primera vez](assets/img/entornocontenedores.png)

- comprobamos con docker ps 
![comprobamos](assets/img/dockerps.png)

## Ejecutamos migraciones 
- Ejecutamos migraciones  "./vendor/bin/sail artisan migrate"

![migraciones](assets/img/migraciones.png)
- Y nos dirigiomos a  http://localhost
![funciona](assets/img/funciona.png)

