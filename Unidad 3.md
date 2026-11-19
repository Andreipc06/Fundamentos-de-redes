### Comandos

| **ping**     | **Comprueba si hay comunicación con otro dispositivo o sitio web en la red y mide el tiempo de respuesta.** |
| ------------ | ----------------------------------------------------------------------------------------------------------- |
| **ipconfig** | Muestra la configuración de red del equipo, como la dirección IP, máscara de subred y puerta de enlace.     |
| **tracert**  | Muestra la ruta que siguen los paquetes de datos hasta llegar a un destino.                                 |
| **cd**       | Cambia de directorio (carpeta).                                                                             |
| **cd ..**    | Retrocede al directorio padre, es decir, una carpeta hacia atrás.                                           |
| **dir**      | Lista los archivos y carpetas que contiene el directorio actual.                                            |

### Actividad 3.1

### Actividad 3.2
Capas del modelo osi: la capa fisica se compone de los medios fisicos cables, dispositivos, conectores y los datos y señalisaciones que pasan por estos.

Parametros: los parametros se miden en ancho de banda, el rendimiento y la latencia.

¿Por que los puntos de intercambio reducen la latencia?
por que estos permiten recibir los datos y redirigirlos por una ruta segura sin que estos recorran una distancia larga a riesgo de perder intencidad 

UTP: los 8 hilos del UTP forman 4 pares trenzados 

Fibra optica: transmite pulsos de luz llega a mayores y es inmune a interferencias electromagnéticas.

Medios inalambricos
Transmiten por hondas de radio 

### Actividad 3.3 HTML

Nombre: Peña Cardona Andrei

Campo 1
Dato de ejemplo: 10101010 10101010 10101010 10101010 10101010 10101010 10101010 10101011 (8 bytes)
Nombre del campo: Preambulo
Para qué sirve: Para sincronizar la hora de los servidores

Campo 2
Dato de ejemplo: FFFF.FFFF.FFFF (6 bytes)
Nombre del campo: Dirección MAC
Para qué sirve: Sirve para que un dispositivo sepa la ubicacion de otro mediante su direccion mac

Campo 3
Dato de ejemplo: 0001.4321.ABCD (6 bytes)
Nombre del campo: Origen MAC
Para qué sirve: Para saber de donde viene o de donde es el dispositivo que manda la señal desde su  ubicaccion MAC

Campo 4
Dato de ejemplo: 0x0806 (2 bytes)
Nombre del campo: Tipo de ethernet
Para qué sirve: Sirve para saber que protocolo de ethernet es el que se recive

Campo 5
Dato de ejemplo: ¿Quién tiene la IP 192.168.1.2? Responde a 192.168.1.1 (entre 46 y 1500 bytes)
Nombre del campo: Payload
Para qué sirve: Para enviar datos o informacion mediante una solicitud o respuesta ARP

Campo 6
Dato de ejemplo: 0x3A7F91C2 (4 bytes)
Nombre del campo: Frame Check Sequence
Para qué sirve: Para detectar errores que pueden ocurrio o ya ocurrieron durante el transporte de datos ARP

### Actividad 3.4

		|Switch2	         |Switch 3 
¿que son?  |Trabaja en la **Capa de Enlace de Datos**  del modelo OSI.
Diferencias |

|             | Switch 2                                               | Switch 3                                       |
| ----------- | ------------------------------------------------------ | ---------------------------------------------- |
| ¿que son?   | Trabaja en la Capa de Enlace de Datos  del modelo OSI. | Trabaja en la Capa de Red además de la Capa 2. |
| Diferencias | Sirve para direcciones MAC                             | Sirve para direcciones MAC e IP                |

### fibra monomodo
Tiene un nucleo muy delgado por donde viaja un solo haz de luz, generado con laser, alcanza decenas de kilometros

### Fibra multimodo
Tiene un nucleo mas grueso por donde viajan varios haces a la vez, generados con led; sirve para distancias cortas, como dentro de un edificio o un campus.

### Donde se usa la fibra optica

En el backbone de internet en los cables submarinos, en los enlaces entre edificios de un campus y en los centros de datos.

### Direcciones MAC
La direccion MAC es el identificador de 48 bits que tiene cada tarjeta de red y que sirve para indentificar el origen y el destino de una trama dentro de LAN (capa 2).

Como se se escribe la MAC, con 12 digitos hexadecimales y el formato cambia segun el sisytema.
Los primeros 24 bits identifican al fabricante y los ultimos 24 los asigna el fabricante a cada tarjeta.
para que sirve la mac: los switches usan la MAC par decidir por que puerto reenviar cada trama y contruyen su tabla de direcciones aprendiendo la MAC de origen.


### Unicast 

De uno a uno
La trama va a un solo destinatario, identificado por su MAC especialmente es el tipo de trafico mas comun.

En el switch
El switch busca la MAC de destino en su tabla de direcciones y envia la trama solo por el puerto.

### Multicast

de uno a un grupo
La trama va a un grupo de equipos que se unieron a el, los demas lo ignoran. 

### Brodcast

de uno a todos 
la trama llega a todos los equipos de la red, con MAC de destino FF:FF:FF:FF:FF:FF; Todos la reciven y la procesan.

