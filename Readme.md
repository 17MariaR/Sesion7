# Sesion 7

## Practica 1

**Azure service health** es un servicio que nos informa de los problemas actuales y futuros que puedan afectar al servicio

Para crear una alerta en service health tenemos que dirigirnos a [Azure](https://portal.azure.com)

![image text](Azure.PNG)

Nos vamos al buscador de azure y escribimos Service health

![image text](Service-health.PNG)

Para crear una alerta en service health le damos click en crear alerta 

![image text](Servicehealth.png)

Ahora configuraremos la alerta para que nos notifique algun problema

![image text](servicehealth2.png)

Seleccionamos grupos de acciones y llenamos lo que nos pide

![image-text](Servicehealth3unnamed.png)

Ahora nos seleccionaremos el apartado notificaciones donde seleccionaremos el medio por el cual seremos notificados

![image text](Servicehealth4.png)

Una vez creada la alerta, podemos probarla con la opcion grupo de acciones de prueba y seleccionamos alerta de estado del servicio como ejemplo 

![image text](Servicehealth5.png)

Y como resultado obtendriamos este correo de la alerta
![image text](Servicehealth6.png)

## Practica 2

Creamos una maquina virtual y la conectamos
![image text](alerta1.png)

Ahora creamos una alerta para la maquina virtual y seleccionamos el porcentaje de cpu
![image text](alerta2.png)

Y creamos la alerta

![image text](Alerta3.png)

![image text](Alerta4.png)

![image text](Alerta5.png)

Notifica cuando advisor detecta un cambio, mejora el entorno de nube (reduce costos, mayor seguridad)

![image text](Alerta6.png)

## Practica 3

ARM (Azure Resource Manager) es el que crea los recursos, nosotros podemos hacer nuestra plantilla en vscode y para eso creamos un archivo al que llamaremos azuredeploy.js

![image text](ARM1.png)

Esto es lo mínimo que debemos tener para crear una plantilla de ARM

![image text](ARM2.png)

Para subir la plantilla a azure debemos abrir un cmd en la ubicación del archivo y ponemos lo siguiente

![image text](ARM3.png)

Cuando aparece running significa que pasó la primera validación de azure 

![image text](ARM4.png)

Asi aparece nuestra plantilla cuando ya ha sido creada, ahora implementaremos un storage account en nuestra plantilla

![image text](ARM5.png)

Esta sería la serie de comandos para implementar un storage account

![image text](ARM6.png)

Volvemos a ingresar la línea de comandos
![image text](ARM7.png)

Aquí podemos ver la cuenta de almacenamiento ya hecha

![image text](ARM8.png)

# Sesion7
# Sesion7
# Sesion7
