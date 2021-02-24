# REDES2_1S2021_P2_GRUPO6

## Topologia
Para la practica se brindo la red a utilizar 192.168.5X.0/24 pero se pedia modificar los valor X por el numero de grupo por lo tanto al ser el grupo numero 6 se usara X=6 para configurar las direcciones solicitadas.

|SubRed|VLAN|Direccion de Red|Primera Direccion asignable|Ultima Direccion asignable|Direccion de Broadcast|
|-|-|-|-|-|-|
|**1 Administracion**|**16**| 192.168.56.0/26 | 192.168.56.1 | 192.168.56.62 | 192.168.56.63
|**2 Profesores**|**26**| 192.168.56.64/26 | 192.168.56.65 | 192.168.56.126 | 192.168.56.127
|**3 Clase A**|**36**| 192.168.56.128/26 | 192.168.56.129 | 192.168.56.190 | 192.168.56.191
|**4 Clase B**|**46**| 192.168.56.192/26 | 192.168.56.193 | 192.168.56.254 | 192.168.56.255


### Hosts

|VLAN|Dispositivo|Direccion Ip|Mascara de Red | Gateway
|-|-|-|-|-|
|**16**|PC-ServidorAdmin|192.168.56.1|255.255.255.192|192.168.56.62
|**26**|PC-ServidorProfesor|192.168.56.65|255.255.255.192|192.168.56.126
|**16**|PC-Administracion1|192.168.56.2|255.255.255.192|192.168.56.62
|**26**|PC-Profesor1|192.168.56.66|255.255.255.192|192.168.56.126
|**16**|PC-Administracion2|192.168.56.3|255.255.255.192|192.168.56.62
|**26**|PC-Profesor2|192.168.56.67|255.255.255.192|192.168.56.126
|**36**|PC-ClaseA1|192.168.56.129|255.255.255.192|192.168.56.190
|**36**|PC-ClaseA2|192.168.56.130|255.255.255.192|192.168.56.190
|**46**|PC-ClaseB1|192.168.56.193|255.255.255.192|192.168.56.254
|**46**|PC-ClaseB2|192.168.56.194|255.255.255.192|192.168.56.254

## Diagrama final
Finalmente se puede observar como quedan las direcciones una vez se ha reemplazado la variable X.
![Alt text](imgs/Topologia.png?raw=true "Up time")
