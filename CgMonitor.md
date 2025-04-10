# Manual

---

## NOTAS
no atender los que digan ASA ...

en caso de no poder abrir servicios iniciarlos desde el administrador de tareas (click derecho en barra de tareas)
1. SGCVSVC: Monitor de controles volumetricos
<img src="imagenes/MonitorVolumetricos.png"/>
3. SGERSVC: Monitor de envio y recepcion de informacion
   <img src="imagenes/MonitorInformacion.png"/>
5. SGPMSVC: Monitor de bombas
   <img src="imagenes/MonitorBombas.png"/>
7. SGPSSVC: Servidor de imprecion
   <img src="imagenes/MonitorImpresion.png"/>
9. SGTMSVC: Monitor de tanque
    <img src="imagenes/MonitorTanques.png"/>

11. ruta donde se gaurdon los accesos SGCVSVC,SGERSVC,SGPMSVC,SGPSSVC,SGTMSVC
disco local/program files(86)/atio/controlgas

12. ruta donde se gaurdon los archivos SGCVSVC,SGERSVC,SGPMSVC,SGPSSVC,SGTMSVC
disco local/program files/atio/controlgas/carpeta de monitor

---

## CgMonitor

pasos para levantar  **Atio update,envol supervisor,FG ip sender,whatch dog atio loader**:

1. Ingresar a servicios.
2. los buscamosr.
3. clic derecho a en el servicio.
4. Nos dirigimos a la pestaña de recuperacion.
5. seleccionamos reiniciar servicios en los 3 apartados y ponemos 0 en dias y 1 en minutos.
6. revisamos que atio loader se este ejecutando
7. por ultimo reiniciamos cgmonitor en el apartado de servicios

---

## Cloud

1. Ingresar a proces o commvault.
2. verificar que el host y el servidor sean correctos.
   <img src="imagenes/cloud.png"/>
4. Diriguirse a servicios
5. Detener los 3 servicios.
6. Iniciar los 3 servicios.
7. si no deja iniciarlos, nos vamos a servicios y buscamos commvault
8. los habilitamos poniendolos en automatico

---

## CPU,FREESPACEHD,MEM

pasos para levantar  **CPU FREESPACEHD MEM**:

1. 
2. 

---

## SGCVSVC,SGERSVC,SGPMSVC,SGPSSVC,SGTMSVC

pasos para levantar  **SGCVSVC,SGERSVC,SGPMSVC,SGPSSVC,SGTMSVC**:

1. Revisamos que esten abiertos.
2. los iniciamos los servicios desde el escritorio.

---


---

sql
checar sql server browser y mssqlserver

cuando el num cliente y el host estan mal hacemos lo siguiente
1. se desisntala la aplicacion de commvault
2. presionamos que desistale todos los paquetes de la instancia
3. luego procedemos a instalar commvaul desde donde estan todos los instaladores
4. colocamos el num cliente y host correctos e instalamos


para instalar los programas
c/archivos del programa/atio/controlgas/herramientas   -> aquie estan los instaladores





---
## Instalaciones
INSTALAR CGMONITOR
WINSCP
PERFIL4
SELECIONAMOS LOS QUE APARECCA EN EL PORTAL
