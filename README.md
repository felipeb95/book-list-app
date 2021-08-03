Project for the unit test course

# BookListApp

Proyecto de ejemplo para la utilización de pruebas unitarias con Jasmine y Karma. Sacado de curso en Udemy por Efisio Pitzalis Morillas.

## Development server

Para correr este proyecto se usará la librería de json-server. Se debe instalar de manera global con `npm i -g json-server` y luego para correrla utilizamos `json-server --watch db.json`. Finalmente ejecutamos `ng serve`.

## Testing

Para realizar las pruebas unitarias podemos usar `ng test` o `npm run test-coverage` (la segunda crea la carpeta `coverage` en la que encontraremos la cobertura de nuestro código).