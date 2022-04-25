> ¿Por qué tengo una carpeta llamada ".expo" en mi proyecto?

La carpeta ".expo" se crea cuando se inicia un proyecto Expo usando el comando "expo start".

> ¿Qué contienen los archivos?

- "devices.json": contiene información sobre los dispositivos que han abierto recientemente este proyecto. Esto se usa para completar la lista de "Sesiones de desarrollo" en sus compilaciones de desarrollo.
- "packager-info.json": contiene números de puerto y PID de proceso que se utilizan para entregar la aplicación al dispositivo móvil/simulador.
- "settings.json": contiene la configuración del servidor que se utiliza para servir el manifiesto de la aplicación.

> ¿Debo confirmar la carpeta ".expo"?

No, no debe compartir la carpeta ".expo". No contiene ninguna información que sea relevante para otros desarrolladores que trabajan en el proyecto, es específica para su máquina.

Tras la creación del proyecto, la carpeta ".expo" ya está agregada a su archivo ".gitignore".
