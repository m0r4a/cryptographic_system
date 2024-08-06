# Sistema criptográfico

## Resumen

Se desarrollará un programa que permita guardar información encriptada y firmada, de manera que se pueda
identificar que usuario la almaceno por medio de certificados digitales

## Funcionalidad

La aplicación deberá:

1. Iniciar preguntando si quiere registrarse (crear un nuevo certificado), o iniciar sesión (leer un certificado
ya creado)

2. El certificado debe guardarse como dos archivos (llave publica / llave privada) con la llave privada
cifrada por contraseña

3. Se deberá poder guardar información cifrada con los certificados del usuario

4. Se utilizará un sistema blockchain o de curvas elípticas para la generación de llaves

5. Debe contar por lo menos con tres sistemas criptográficos siendo uno simétrico, uno asimétrico, y uno
a libre elección (según lo requiera el alumno)

6. De manera opcional se puede crear una DApp sencilla que permita el guardado de información (aun así,
deberá cumplir con el punto numero 2)

## Detalles

| Descripción                                                | Puntos |
|------------------------------------------------------------|:------:|
| Método de encriptado simétrico                             |   10   |
| Método de encriptado asimétrico                            |   10   |
| Método de encriptado libre (distinto a los dos anteriores) |   10   |
| Uso de clave publica/clave privada                         |   10   |
| Guardado de certificados en archivo                        |   10   |
| Uso de llaves de blockchain o curvas elípticas             |   15   |
| Firmado de la información                                  |   15   |
| Identificación del usuario por certificado                 |   20   |
| Creación de DApp (Opcional)                                |   15   |
