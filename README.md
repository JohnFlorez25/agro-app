# Manipular Cliente Web Agro App

## Pruebas con Api Fake
- npm i json-server
- ubicarse en la carpeta **services** y ejecutar el siguiente comando **json-server dataGeneral.json**

## Manipulación del entorno

Una vez que se ha levantado la Api Fake se tiene acceso a 5 endpoints:

- http://localhost:3000/modulos : Servicio para mostrar por pantalla la información general del módulo, variables de ambiente activas y variables de cuidado
- http://localhost:3000/simulador : servicio que realiza peticiones cada 3 segundos para simular la información que se obtiene desde el hardware ARDUINO o el cliente de simulación en ANDROID
- http://localhost:3000/Luz : muestra el histórico de como ha variado la Luz en el tiempo de cada módulo
- http://localhost:3000/Temperatura : muestra el histórico de como ha variado la Temperatura en el tiempo de cada módulo
- http://localhost:3000/Humedad : muestra el histórico de como ha variado la Humedad en el tiempo de cada módulo



