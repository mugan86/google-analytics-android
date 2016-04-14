# Google Analytics Android
Ejemplo para registrar eventos que ocurren en una aplicación en Google Analytics desde una app Android.

* Guía de referencia: https://developers.google.com/analytics/devguides/collection/android/v4/
* Ejemplos: https://developers.google.com/analytics/devguides/collection/android/v4/samples

Como obtener un track id:

1. Iniciar sesión en Google Analytics: https://www.google.com/analytics/web/#home/

2. Seleccionar pestaña "Admin" / "Administrador".

3. En el menú desplegable "ACCOUNT" / "CUENTA"In the ACCOUNT, click en "Crear nueva cuenta" / "Create new account". (O si lo prefieres selecciona una de las que ya tienes creadas)

4. Seleccionar el la pestaña central, en propiedad, "Nueva propiedad" (se pueden crear hasta 50 por cuenta)

5. Seleccionar "App Móvil" / "Mobile App" en la nueva propiedad del formulario.

6. Introducir "App Name" / "Nombre de la App".

7. Seleccionar la categoria a la que se adapta tu aplicación.

8. Seleccionar "Zona horaria".

9. Crear "ID de seguimiento".

10. Nos llevará a una nueva pantalla donde podremos ver un Tracking ID de este estilo (UA-XXXXXXXX-X), esto es lo que usaremos en res/values/xml/app_tracker.xml

Más referencias sobre esto: https://support.google.com/analytics/answer/2587087?hl=es&utm_id=ad


