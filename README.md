# Práctica 14 - Creación de una alerta para Azure Service Health

## Innovaccion Virtual (VII Edición) #IAWizards

### Semana 3 - Sesión 7

En esta práctica se llevó a cabo la implementación de una alerta para el estado de los recursos de Azure de manera global con Azure Service Health.

-------------------------------------------------------

#### Requerimientos
- Cuenta de Azure con suscripción.

-------------------------------------------------------

#### Pasos a seguir

1. En portal.azure.com buscamos ‘Service Health’. Veremos 3 apartados donde podremos elegir la suscripción, la región, y el servicio a buscar por fallas.

![P14I1](https://github.com/AlbertoSF99/Practica-14/blob/main/Images/Sesi%C3%B3n%207%20-%20P14%2001.PNG)

2. Se puede agregar una alerta que informe sobre algún servicio que esté fallando de manera global, o específicamente en una región. Para esto le damos en ‘Añadir alerta de Service Health’.

![P14I2](https://github.com/AlbertoSF99/Practica-14/blob/main/Images/Sesi%C3%B3n%207%20-%20P14%2002.PNG)

3. Como datos principales, tendremos que seleccionar la suscripción, la región que se quiere analizar y el servicio que se quiere investigar, así como también el tipo de evento a buscar (puede ser desde errores en servicios hasta mantenimientos planeados).

![P14I3](https://github.com/AlbertoSF99/Practica-14/blob/main/Images/Sesi%C3%B3n%207%20-%20P14%2003.PNG)

4. Después, le damos en ‘Seleccionar grupos de acciones’ y le damos en ‘Crear grupo de acciones’. Rellenamos los datos solicitados.

![P14I4](https://github.com/AlbertoSF99/Practica-14/blob/main/Images/Sesi%C3%B3n%207%20-%20P14%2004.PNG)

![P14I5](https://github.com/AlbertoSF99/Practica-14/blob/main/Images/Sesi%C3%B3n%207%20-%20P14%2005.PNG)

5. En el apartado de notificaciones elegimos un tipo de notificación. Si es por correo electrónico, tendremos que escribir dicho correo. Finalmente, le damos en ‘Aceptar’ y ‘Crear’.

![P14I6](https://github.com/AlbertoSF99/Practica-14/blob/main/Images/Sesi%C3%B3n%207%20-%20P14%2006.PNG)

6. Podemos probar su funcionamiento al darle en ‘Grupo de acciones de prueba’ y nos vamos a la función previamente creada. Podemos escoger el tipo de ejemplo que se quiera realizar, como, alerta de estado del servicio, y al darle en ‘Test’ este enviará al correo la notificación.

![P14I7](https://github.com/AlbertoSF99/Practica-14/blob/main/Images/Sesi%C3%B3n%207%20-%20P14%2007.PNG)

![P14I8](https://github.com/AlbertoSF99/Practica-14/blob/main/Images/Sesi%C3%B3n%207%20-%20P14%2008.PNG)

![P14I9](https://github.com/AlbertoSF99/Practica-14/blob/main/Images/Sesi%C3%B3n%207%20-%20P14%2009.PNG)

7. De igual manera, puede crearse una regla, en ‘Crear una regla de alertas’ y en los apartados de ‘Nombre de la regla de alertas’ y ‘Grupo de recursos’ deberán ser llenados.

![P14I10](https://github.com/AlbertoSF99/Practica-14/blob/main/Images/Sesi%C3%B3n%207%20-%20P14%2010.PNG)
