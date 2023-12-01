Proyecto 5 Aplicación de Comercio Electrónico

## Demo

Puedes ver el demo [dando click en este enlace.](https://sebamellam.github.io/client/)

## Instalación

Para realizar la instalación de este proyecto, es necesario realizar `clone` o `fork` de este repositorio.

`Terminal 1 Client`
Puedes ver el repo [dando click en este enlace.](https://github.com/Sebamellam/client)

```shell
$ cd client
$ npm install
$ npm run start
```

`Terminal 2 Server-ok`

```shell
$ cd server
$ npm install
$ npm run dev
```
Una vez hecho esto en cada uno, deberás crear las variables de entorno en cada carpeta.

`./client/.env`

```
REACT_APP_BACKEND_URL="https://server-ok.onrender.com"
REACT_APP_MERCADO_PAGO_PUBLIC_KEY='TU-NÚMERO-DE-MERCADOPAGO-PARA-ACTIVAR-PAGOS'
```


`./server/.env`

```
PORT=3005
MONGODB_URI='mongodb+srv://mongo:mongo@cluster0.ftm9cmq.mongodb.net/?retryWrites=true&w=majority'
SECRET_JWT='PALABRASECRETADEBESCAMBIARLA'
PROD_ACCESS_TOKEN='TEST-8283691311611373-111111-6e0891837d7ee10afe79266843d56e31-1545626684'
```

`Pago MERCADOPAGO`
Para poder realizar el pago utilizando MERCADOPAGO 

```
Prueba de comprador
usuario TESTUSER349596683
contraseña M1VnA5bU4w
tarjeta mastercard 
numeroº 5416 7526 0258 2580
codigo de seguridad 123
fecha de caducidad 11/25

APRO= nombre del titular
documento de identidad 123456789
```
