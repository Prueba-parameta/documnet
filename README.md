# documnet
Para ejecutar este proyecto, ejecutar en el siguiente orden


mkdir test-dario-garzon

cd test-dario-garzon

git clone https://github.com/Prueba-parameta/soap-db.git

git clone https://github.com/Prueba-parameta/prueba-tecnica-ws.git







ubicarse en la carpeta soap-db y ejecutar

gradlew clean build bootRun

esto para levantar el SOAP y ver el wsdl


una vez el WS esté arriba, ejecutar el otro.

ubicarse en la carpeta de la prueba tecnica

cd test-dario-garzon/prueba-tecnica-ws

y ejecutar

gradlew clean build bootRun


el json de envio está en la ruta

POST: http://localhost:8085/agregarEmpleado

{
    "nombres": "Dario",
    "apellidos": "Garzon",
    "tipoDoc": "CC",
    "numeroDoc": "123465",
    "birthDate": "2002-05-30",
    "vinculadoDate": "2002-05-30",
    "cargo": "dev",
    "salario": 1994.5
}
