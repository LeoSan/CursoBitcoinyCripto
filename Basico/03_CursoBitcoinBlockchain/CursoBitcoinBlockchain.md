# 💡 BitcoinBlockchain 💡

> Bitcoin es una innovadora red de pagos de código abierto y una nueva clase de dinero. 

## El inicio del universo blockchain 💡

- Nacio en el 2009 con su white-paper 
- (Organización ORG Bit)[https://bitcoin.org/en/]
- (WhitePaper)[https://bitcoin.org/files/bitcoin-paper/bitcoin_es_latam.pdf]

## Bitcoin es... 📊 

- Seguro: transacciones a cualquier parte del mundo 
- Inmutable: transacciones no pueden ser modificadas
- Transparente: todas las transacciones son trazables
- Anónimo: en lugar de mostrar tu nombre, una transacción mostrará un número o código encriptado que corresponde a tu billetera
- Descentralizado: no está validado por una institución gubernamental, sino que la validan todas las personas que fungen como nodos

## Tecnologia que Forman el Bitcoin 📊 

> Blockchain: Es una base de datos distribuida en varios nodos de una red. Cadena de bloques de información.
Prueba de Trabajo: Búsqueda de un número variable que permite que se puedan insertar bloques en blockchain.

> Prueba de Trabajo: Búsqueda de un número variable que permite que se puedan insertar bloques en blockchain.
	- (Adam Back) HashCash el ancestro de PoW: Nació para evitar spam.
	- Funciona para no poder utilizar un bitcoin dos veces.

> P2P: Ordenadores conectados entre sí y permiten el intercambio directo de información de igual a igual. Servidores descentralizados.

> Criptografía: Tecnologia para resguardar la integridad de los datos y así evitar que personas no autorizadas accedan a la información.

## El whitepaper de Satoshi Nakamoto

> Por qué no se sabe nada del creador del Bitcoin, Satoshi Nakamoto, El 26 de abril de 2011, el creador de Bitcoin, abandonó la comunidad cripto para trabajar en otros proyectos. Nadie sabe de él.

- Satoshi Nakamoto es como se conoce al creador de Bitcoin. 
- Y aunque no sepamos quién es o era Satoshi Nakamoto, sí conocemos lo que hizo. 
- Inventó el protocolo bitcoin y lo publicó en un artículo científico a través de la Cryptography Mailing List en octubre de 2008.
- El 9 de enero de 2009, Nakamoto liberó la versión 0.1 del cliente de Bitcoin (hoy conocido como Bitcoin Core)
- Ese mismo día, a las 00:54, se minó el primer bloque de bitcoin y con él se crearon las primeras unidades. Tres días más tarde, el 12 de enero de 2009, Hal Finney, uno de los miembros más destacados de la lista de correo «Cryptography», recibió la primera transacción de bitcoin de la historia.  Y el 26 de abril de 2011, Nakamoto desapareció y nunca más se supo nada de él
- Satoshi Nakamoto es como se conoce al creador de Bitcoin. Y aunque no sepamos quién es o era Satoshi Nakamoto, sí conocemos lo que hizo: inventó el protocolo bitcoin y lo publicó en un artículo científico a través de la Cryptography Mailing List en octubre de 2008.


## Resumen del WhitePaper (Igual te dejo la responsabilidad de validar y de comprobar, jamas te quedes con la información de alguien mas busca tu verdad,  busca tu camino ninja)

- Funcionamiento de Bitcoin -> (WhitePaper)[https://bitcoin.org/files/bitcoin-paper/bitcoin_es_latam.pdf]

- Proof of Work (PoW) lo utilizan Bitcoin, Ethereum, Litecoin

- Proof of Stake (PoS) lo utilizan NXT, Tezos, soon Ethereum. Se puede decir que es mucho mas eficiente que PoW.

- Delegated Proof of Stake (DPoS) lo utilizan EOS, BitShares. Consiste en delegar a un pequeño grupo de validadores la labor de producir nuevos bloques.
- La produccion de nuevos bloques sucede cada 1 o 2 segundos.

- Proof of Activity (PoA): lo utiliza Decred. Este combina PoW y PoS para tener lo mejor de los dos mundos. Deja que sea escogido por los mineros.

- Proof-of-Location (PoL): lo utilizan FOAM, Platin. Introduce la localizacoin por GPS para sus nodos y correpondiende validación.


## Funcionamiento de blockchain

> El funcionamiento es complejo pero solo entendiendo los conceptos básicos se logra entender lo explicare de manera de fases. 
> Cada bloque de bitcoin se genera cada 10 minutos
> En total puede contener 2048 Transacciones 

## Diagrama
!(Como funciona)[./info/ComoFunciona.png]

## Mucho Texto Para Ejemplificar  🤐

- Fase Inicial  🔦
"El hash de un bloque efectivamente debe comenzar con una x cantidad de ceros. 
Pero en ese caso usted puede simplemente construirlo rellenando esa x cantidad de dígitos con cero 
y luego simplemente generar un número aleatorio cualquiera"

- Fase Media  🔦
"Luego el algoritmo de sha256 son una función que recibe como entrada un conjunto de datos y devuelve como salida un hash. 
En este caso los datos de entrada son la información del bloque que estamos construyendo el cual recordemos que contiene el 
hash del bloque anterior, la lista de transacciones y un campo de tiempo que indica el momento en que se construyó el bloque. 
"
- Fase Media  🔦
" Esa información se le envía como entrada a sha256 y se comprueba si el hash resultante cumple con las condiciones previstas 
(la x cantidad de ceros al inicio), si cumple con estas condiciones entonces se acepta el bloque en la cadena, pero si no cumple 
con las condiciones lo que se hace es re-ordenar las transacciones ponerlas en un orden diferente de manera aleatoria y colocar 
una nueva marca de tiempo" 

- Fase Alta  🔦
"Una vez hecho esto se repite el proceso hasta que finalmente se encuentra el hash que cumpla con las condiciones. 
Por eso es que es tan complejo encontrar el hash pero resulta realmente sencillo validar si un hash se ha construido 
de manera correcta o no. Esto permite la alta seguridad a la blockchain y a todo el ecosistema en general."

- Fase Final  🔦
"Ya que si alguien desea alterar un bloque tal vez para retractar una transacción o para acreditarse dinero que no le 
pertenece tendría que primero generar “hashes” válidos para cada bloque que desee modificar o crear y para cuando logre 
realizar esta labor, el resto de los nodos (que deben ser mayoría) ya han validado nuevas transacciones e incorporado nuevos 
bloques, recordemos que la cadena que se acepta es la más larga, por lo que el impostor siempre estaría detrás tratando de alcanzar 
al resto de los nodos para que acepten sus bloques, lo cual le resulta imposible."



## Como minar 🛑

> Lamentablente aun no lo enseñan en esta clase pero dejo un video Tutorial 
- (Como minar)[https://www.youtube.com/watch?v=XZzkZDri3Mk&ab_channel=Karlitros]

	