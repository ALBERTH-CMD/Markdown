<center><img align=”middle” src="ic_logo.png"></center>
_______________________________________________________________________________________________

# Pasos para Instalar Y Clonar Proyectos Laravel en ubuntu 20.04+ en su versiones mas Actuales:

# Instrucciones:
antes que nada, nos dirigimos a la pagina de github en la cual se aloja el repositorio a clonar, posteriormente, ejecutamos
los comandos siguientes en terminal.

- Git clone https://github.com/ALBERTH-CMD/Proessa.git.
para clonar dicho repositorio, deben de tener acceso a dicho repo, ya que es un repo privado, require el acceso con credenciales y autorizacion del propietario.

- cd Proessa.

- cp .env.example .env.

## instalar los componentes y paquetes nesesarios para poder ejecutar el proyecto sin errores:

- composer install or composer update.

## generar llave de seguridad y de ejecucion:

- php artisan key:generate.

## permisos a la carpeta donde se encuetra la raiz del proyecto y poder ejecutarlo en el navegor de sus preferencia:

- sudo chmod -R 777 ./storage.

## migraciones ya existentes, al igual estan las migraciones con seeders, los cuales nos permite realizar pruebas:

- php artisan migrate and seeds php artisan migrate --seed.
