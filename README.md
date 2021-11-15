# Mi primer PWA

Las PWA se definen comúnmente como las Apps que reúnen lo mejor de las aplicaciones web y de las nativas, incluso llegando a ser entendidas como un punto medio o una forma evolucionada.

## Pantallas de Splash y Home
Pantalla Home de la parte web que muestra la PWA
![](https://alfaomegairon.000webhostapp.com/2021-11-14%20(1).png)

Pantalla Splash

![](https://alfaomegairon.000webhostapp.com/IMG-20211114-WA0039.jpg)
## Vistas generadas del lado del cliente y del servidor
![](https://miro.medium.com/max/2000/1*uGH8FWn-AlvAljniAo5uFw.png)
## Datos locales, remotos y offline
### Datos locales 

Esta función permite que las páginas con las cosas se apilen al instante, además de que los clientes pueden seguir comprando en el sitio web, incluso cuando vayan a otra zona sin Wi-Fi ni red local de datos. Esto brinda una experiencia activa y siempre accesible para los clientes, lo cual los motiva a que se comuniquen con la empresa de forma personal.

### Datos remotos

En este caso no participa la caché para nada. Simplemente se obtienen los datos del servidor remoto. Si no hay conexión a Internet no se podrán servir los archivos.

### OffLine

Las capacidades offline, es decir, dependen casi totalmente del servidor, y de que los clientes que se conecten tengan una adecuada conexión a Internet. 

## Notificaciones

Comencemos con las notificaciones: pueden funcionar sin push, pero son muy útiles cuando se combinan con ellas. Para empezar, veámoslo de forma aislada.

![](https://user-images.githubusercontent.com/62690531/141723602-2ad4b2d4-a8fe-48bc-9a72-edba01acfa38.png)

Pedir permiso

Para mostrar una notificación, primero debes solicitar permiso. Sin embargo, en lugar de mostrar la notificación de inmediato, la mejor práctica dicta que deberíamos mostrar la ventana emergente cuando el usuario la solicite haciendo clic en un botón:

## Uso de elementos físicos del dispositivo

 A esto contribuyen elementos como una pantalla de inicio, que se ejecute en una ventana de aplicación propia, totalmente responsive, que ocupe la pantalla por completo (sin la barra que muestra la URL), etc.
