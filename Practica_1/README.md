# Practica 1
**Por** *Juan Camilo Gonzalez Mulato*
## 1. Configuración del entorno: El estudiante deberá configurar su dispositivo de elección para ejecutar una imagen virtualizada de Linux, este será un suministro importante para el resto de prácticas.
### Se instaló la imagen de Linux Ubuntu y posteriormente se realizo las diferentes configuraciones del entorno.
![imagen](https://github.com/jgozalez/Informes_Practicas_IOT/blob/main/1.png?raw=true)

## 2. Instalar docker
- Verifico si alguna version anterior de docker no este instalada
![Docker](Imagenes_1/1.png)
- Actualizo el apt índice del paquete:
![Docker](Imagenes_1/2.png)

- Se hace la instalación Docker Engine, containerd y Docker Compose.
![Docker](Imagenes_1/3.png)

- Verifico que la instalación de Docker Engine sea exitosa ejecutando la hello-worldimagen:
![Docker](Imagenes_1/4.png)
![Docker](Imagenes_1/5.png)

## 3. Reconocimiento de herramientas de red: Identificar configuración de red por medio del comando ip e ifconfig. Identificar servicios y puertos ocupados en el sistema con los comandos ss, netstat y lsof.
- Comando ip 
Aqui nos muestra todas las direciones ip que esta utilizando el sistema. 
![Docker](Imagenes_1/7.png)

- Comando ifconfig
Aqui nos muestra  varias interfaces que ha creado el sistemas con sus respetivas direciones ip conectadas
![Docker](Imagenes_1/8.png)

Ahora utilizando los comandos ss, netstat y lsof para mirar que puertos y servicios está utilizando el sistema. 
![Docker](Imagenes_1/9.png)

## 4. Identificar servicios desplegados: El estudiante deberá identificar 5 servicios diferentes listados por las herramientas de red y determinar a qué aplicaciones posiblemente están relacionados.
 con el comando lsof | lees se se puede visualizar los servicios

![Docker](Imagenes_1/10.png)


