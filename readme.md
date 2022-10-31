Crear LLave Publica y LLave Privada:
npx nodemon generar-claves.js --name Rob
npx nodemon generar-claves.js --name Cat

Encriptar
npx nodemon encriptar-fichero-stream.js --private Rob --public Cat --data fichero.txt

Desencriptar:
npx nodemon desencriptar-fichero-stream.js --private Cat --public Rob --data fichero.txt

