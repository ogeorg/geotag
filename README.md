Idea:

Esta aplicacion sirve para asignar una geolocalizacion a cada evento

Me muestra para cada año una lista de eventos

Al seleccionar un evento, puedo ver la posición del evento. Posibilidades:
+ pinchar en el mapa, setea un nuevo sitio. Debo mandar para actualizar en la BD
+ si se ha modificado, puedo resetear

+--------------------------------------------------------------------+
| Titulo                                                             |
|                                                                    |
| +-----------------------------+     +----------------------------+ |
| |                             |     | Evento 1                 |^| |
| |         Mapa                |     | Evento 2                 | | |
| |                             |     | Evento 3                 | | |
| |                             |     | Evento 4                 | | |
| |                             |     | Evento 5                 |v| |
| |                             |     +----------------------------+ |
| |                             |     Evento 3                       |
| |                             |     Posición anterior: xx / yy     |
| |                             |     Nueva posición:    xx / yy     |
| |                             |     [Acceptar] [Resetear]          |
| +-----------------------------+                                    |
+--------------------------------------------------------------------+

Urls:
mapa                            enseña el mapa
eventos/{aaaa}                  lista de eventos para el año aaaa
posicion/{eventid}              devuelve la posicion en json
posicion/{eventid}/{xx}/{yy}    setea la nueva posicion del evento


Por hacer: 
1) Enseñar el mapa
2) view para devolver los eventos de un año
3) integrar los eventos en la página del mapa
4) 
