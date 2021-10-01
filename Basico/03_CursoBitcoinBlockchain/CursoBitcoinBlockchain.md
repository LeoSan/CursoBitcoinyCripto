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
> Cada bloque de bitcoin se genera cada 10 minutos. 
> En total puede contener 2048 Transacciones durante este rango de tiempo. 
> En este periodo los mineros pueden minar 6.25
> En el 2024 Baja a 3.25


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


## El rol de quienes minan Bitcoin

> Minería
- Ejecución de PoW. 
- Resolución de algoritmos complejos para el funcionamiento descentralizado y seguro de Bitcoin a partir de poder de cómputo.
- Cada 210.000 Baja la recomenpesa 
- El Halving es el aumento de la dificultad de minado 
- Se hacen piscinas de minerias para unir el poder de computo y asi apoyarse 
- La mayoria de los Mineros se encuentran en China pero esto era antes actualmente el gobierno de china esta expulsando a los mineros 

## El rol de quienes minan
- Comprueban que las transacciones sean realizadas.
- Certificar que nadie pueda usar dos veces la misma moneda o introducir monedas falsas.
- Crean nuevos bitcoins a partir de la creación de nuevos bloques.
- Reciben una recompensa por el trabajo realizado.
- Incentivos

## Por su labor, las personas que minan reciben dos tipos de recompensas:

- Al resolver un bloque y emitir nuevos bitcoins.
- Al validar rápidamente transacciones que se incluyen en los bloques.

> Resolviendo bloques
- 6.25 BTC (hoy día).
- Comisiones de transacciones.
- Esta recompensa se reduce a la mitad cada vez que se minan 210.000 bloques y se conoce como Halving o aumento de la dificultad de minado.
- Para tener más probabilidades de resolver bloques existen pools de minería.

> Validando transacciones
- Comisiones de transacciones.
- Debido al crecimiento de la red, los mineros priorizan y validan transacciones.
- Evita la posibilidad de ataques a la red.
- En cuanto se minen los 21 millones de bitcoins, será probablemente el proceso que sustente el funcionamiento de la red.

>Tasa de Hash
- Poder de cómputo total que se utiliza para minar y poder procesar transacciones de Bitcoin (PoW).
- Mientras más alto en hashrate mayor la seguridad del ataque y también la complejidad para minar.

## Enlaces 
- https://www.buybitcoinworldwide.com/es/bitcoin-clock/
- https://www.blockchain.com/charts/hash-rate
- https://www.blockchain.com/charts/miners-revenue
- https://www.blockchain.com/charts/pools


## Lightning network
 
- Transacciones instantáneas
- Comisiones realmente bajas
- Software independiente, que requiere de comunicación con la blockchain de Bitcoin
- LN puede integrarse en otras redes
- Las dos principales wallets que usan Lightning network son BlueWallet y Muun Wallet.
- Muun Wallet es un proyecto argentino con mucho potencial 


## ¿Por qué usar LN?
- Escalabilidad
- Micropagos
- Privacidad
- Pagos instantáneos

## Enlaces 
- https://lightning.network/
- https://www.blockchain.com/charts/fees-usd-per-transaction
- https://lightning.network/lightning-network-paper.pdf
- https://opensourcelibs.com/libs/lightning-network Proyectos  Lightning network
- https://ycharts.com/indicators/bitcoin_supply

## Pilares de Bitcoin

- Abierto
- Escaso
- Publico
- Sin fronteras
- Resistente a la censura
- Descentralizado
- Confianza

> Usos de Bitcoin:
- Dinero como primera aplicación.
- Pago de bienes y servicios.
- Envío de remesas.
- Intereses.
- Préstamos utiliza


## Blockchain más allá de Bitcoin

> Blockchain públicas
- Accesible a cualquier persona del mundo. Ejemplo: Bitcoin y Ethereum.

> Blockchain privada
- Válidas para solventar problemas de eficiencia, seguridad y fraude dentro de instituciones financieras tradicionales. Ejemplo: Hyperledger, etc.

> Híbridas
- Intento de aprovechar lo mejor de ambos mundos. La participación en la red es privada, pero la contabilidad es accesible de forma pública. Ejemplo: R3, Energy Web, etc.

> Evolución de blockchain
- Blockchain 1.0: Digital Currency
- Blockchain 2.0: Smart Contracts
- Blockchain 3.0: DApps
- Blockchain 4.0: Industry

## Hyperledger.

Hyperledger es una comunidad de código abierto enfocada al desarrollo de un conjunto de frameworks, herramientas y librerías, con el fin de ser usadas en soluciones blockchain en el sector empresarial.
Sirve como un hogar neutral para varios frameworks relacionados con tecnologías descentralizadas, incluyendo Hyperledger Fabric, Sawtooth, Indy, así como herramientas como Hyperledger Caliper y bibliotecas como Hyperledger Ursa.

!(OtrosPosiblesUsos)[./info/OtrosPosiblesUsos.png]

## Blockchain 1.0: Digital Currency

> Blockchain 1.0: Digital Currency
- Es la primera fase de evolución en el desarrollo de esta tecnología.
- Se derivó de la estructura original de Bitcoin, que a su vez tomó conceptos e ideas de proyectos que iniciaron en la era cypherpunk.

> Tecnologías
- Blockchain mostró el potencial de interrumpir innumerables industrias; sin embargo el desarrollo blockchain se centró en la creación de criptomonedas.
- DLT (Tecnología de registro distribuido)
- Blockchain
- PoW

> Objetivos
- Crear una nueva forma revolucionaria de abordar las finanzas.
- Brindar transparencia a través de un sistema de registro de transacciones distribuido e inmutable.
- Acceso público al sistema financiero global.


## Blockchain 2.0: Smart Contracts
> Blockchain 2.0
- Facilita el intercambio de valor más allá de bitcoin y las criptomonedas, mediante los contratos inteligentes.
- El registro de información no está directamente relacionado con dinero, sino que se almacena cualquier otro tipo de archivo o activo digital.

> Tecnologías
- Está pensado para la gestión y transferencia de activos y cualquier otro tipo de bien que pueda estar en un registro público.
- Smart Contracts
- Archivos Digitales (IPF)
- Ethereum Virtual Machine (EVM)

> Objetivos
- Ejecuta de forma automática acciones programadas en blockchain.
- Registro y transferencia de valor más allá del dinero.
- Autonomía, nuevos modelos de negocio, anonimato.

## Blockchain 3.0: DApps

- Se crean las Dapps 
- Nuevos protocolos de consenso DApps (IPFS) Sistema de archivos interplanetario https://ipfs.io/ 
- Nuevos protocolos Proof of Stake 
- Nuevos protocolos Proof of History 

> Tecnologías
- Arquitectura Daaps
	- Frontend: Similar a las aplicaciones tradicionales. Html5 + css por ejemplo.
	- Backend: A diferencia de las aplicaciones mas tradicionales, las Dapps tiene el backend descentraalizado usando smart contracts.
	- Almacenamiento de datos: Datos descentralizados usando la blockchain.

> Objetivos	
- Se introdujo para solucionar problemas de: Escalabilidad, sostenibilidad, costo, Seguridad, Dilemas de interperabilidad
- Redes de Blockchain programables 

## Blockchain 4.0: Industry
- Es una solución idonea para los ambientes industriales
- Se presenta para una apuesta para las industrias
- Todo esto es gracias por la trazabilidad 

> Tecnologías

- Logistica : Vechain
- DEX: Uniswap
- Smart contracts: Ethereum y cardano
- Interoperabilidad: Polkadot, clover, cosmos
- Reserva de valor : Bitcoin
- Nfts: Ejin coin, Chilliz, Axies infinity, Decentraland, flow
- Interner de las cosas: Iota
- Apis en las blockchain : the Graph
- Manejo de Identidad: Litentry
- Oraculos: Chainlink
- Stablecoins: Theter (USDT). USD coin (USDC), DAI
- Intercambio de datos dencentralizado: Ocean Protocol
- Blockchain como servicio BaaS: Stratis
- Blockchain enfocado en Bancos: Ripple, Stellar
- Video descentralizado: Livepeer, theta
- Provacidad: Monero, Zcash
- Navegadores y publicidad : Brave (BAT)

> Objetivos	
- Mejorar cadenas de producción indistrial 
- Mejorar procesos existentes en la producción de bienes. 
- Relaciones entre empresas en mecanismos transparentes. 
 
## Protocolos de consenso

- Es el mecanismo que regula la forma en que los nodos crean los bloques llegando a un acuerdo entre si para poder hacerlo e incorporar ese bloque a la cadena

>Principales protocolos de consenso:

- PoW: Poder computacional para resolver el acertijo y crear los nuevos bloques. Ejm: Bitcoin, Litecoin. En este caso el riesgo es el del 51%. Un pool con la mayoria de poder computacional bajo sucontrol.
- PoS: Para creear el nuevo bloque se debe bloquear una cantidad especifica de la moneda de la blockchain. Es hacia donde va Ethereum

## Limitaciones de blockchain 💸

- inmutabilidad de la información ->  No permite ser flexibles con los errores humanos una ves generado el bloque este no se puede alterar.   
- Velocidad de procesamiento de información -> La velocidad no sea tan amplia puede ser lento o muy rapida generando esto algunas veces usarse en nuestra contra.  
- Ataque de 51% -> Muchos ataques en el tiempo 
- Escalabilidad -> 
- Privacidad    -> Anomiamatun si lo usan las personas con fines malevolos. 

## El futuro de blockchain



## Como minar 🛑

> Lamentablente aun no lo enseñan en esta clase pero dejo un video Tutorial 
- (Como minar)[https://www.youtube.com/watch?v=XZzkZDri3Mk&ab_channel=Karlitros]

	