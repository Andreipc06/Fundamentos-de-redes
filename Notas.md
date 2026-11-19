DHCP
(protocolo de configuracion dinamica de host) es un servicio que asigna direciones IP automaticamente a los equipos. 
Evita configurar cada equipo a mano y os conflictos por direcciones duplicadas.

Tiempo de concesion 
la direccion se entrega en prestamo por un tiempo de concesion (lease), no de forma permanente.

El cliente renueva a la mitad del tiempo en windows 
ipconfig/release
ipconfig/renew


DHCP usa UDP: el servidor escucha en el puerto 67 y el cliente en el 68 