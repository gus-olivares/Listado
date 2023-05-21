#Grupo 3
#Integrantes = [Gustavo Olivares , Yedixa Yanez , Sebastian Torres]

#El Archivo cuenta con los servicios Frontend / Backend / DB / Network / Volume

1- Ejecutar DockerCompose mediante consola (bash/CMD/PS) => docker compose up
2- Validar en consola que contenedores se encuentren arriba => docker ps -a
3- En el navegador visualizar en frontend con url => http://localhost:4000
4 - Para intertar datos a la DB se puede utilizar la app POSTMAN eligiendo el metodo post en donde key = name y vale = nombre del listado
    se puede verificar en body -> pretty con el mensaje -> "message": "Topic created!""
    http://localhost:8080/api/topics

###
Ejemplo
{
   key:"name",
   value:"Lista1"

}
###

5- Actualizar en el navegador url => http://localhost:4000 , se se inserto el dato enviado.
6- Para parar ejecucion (ctrl + c) -> docker compose down