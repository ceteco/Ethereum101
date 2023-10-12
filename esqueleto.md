*Para estudiar como y en que momentos integrar a la presentación: El blockchain además de **tecnología** es **filosofía aplicada**. Estudiar las filosofías que nos han llevado hasta web3. Una es el **software libre**, otra es la filosofía **UNIX** de desarrollo de apps (Que la app haga solo una cosa, pero que la hagan bien)  También estudiar donde incluír el **trilema del blockchain** (Descentralización, seguridad, escalabilidad)*

- **Blockchain:** Es una base de datos tal como una hoja de excel, pero sin permisos de edición y solamente permite agregar datos nuevos frente a la celda anterior, así que va tomando la forma de una cadena de bloques -Por eso el nombre *blockchain*.
Otra diferencia con una hoja de excel o base de datos tradicional, es que el blockchain solamente tiene habilitados permisos de lectura.

  - **Esqueumórficos de blockchain** 
  - *Libro contable, ledger:* <- No todos están familiarizados, término más amistoso para personas sin literacidad computacional.
  - *Excel:* Sí estamos esperando que sepan manejar celulares y sistemas operativos de PC, es bastante probable que tengan nivel de Office y haber visto o usado alguna vez una hoja de cálculo.
  - *Base de datos:* Como MySQL puede familiarizar bastante a una audiencia que trabaja en sistemas computacionales, tal como alumnos de Sistemas y afines

# ¿Que se puede guardar en un blockchain?

- **Token:** A alguien se le ocurrió que puede guardar tokens representativos de valor para realizar intercambios de valor. 
  - **Esqueumórficos de token** 
  - *Dinero:* <- Bastante posible que todos estén familiarizados.

- **Adress** Dichos tokens, están enlazados a un address que es una cadena de caracteres hexadecimales. El address viene a ser similar a tu número de cuenta bancaria.
  - **Esqueumórficos de address** 
  - *Número de cuenta de banco:* <- Muy posible que todos estén familiarizados.

## El primer conjunto de estas tres keywords: Blockchain, token y address se llamó Bitcoin. El nombre de su token es BTC

(Se puede preguntar a los participantes que cosas se les ocurre hacer con una base de datos así de limitada. Sí después de 7 segundos nadie contesta, se puede sugerir como un ejercicio para pensar ¿Que pasaría de implementarse en transacciones de un gobierno, obteniendo transparencia obligada por el sistema?

## ¿Que pasa sí a Bitcoin le agregamos la capacidad de guardar software?

- **Nace Ethereum:** Es como Bitcoin, pero además de tokens y transacciones, también puede guardar software al cuál también se refieren como *Contratos inteligentes* (En realidad son aplicaciones escritas en lenguajes de programación como Solidity)

  - **Esqueumórficos de Ethereum** 
  - Dinero Programable:* <- No todos }

## ¿Como ejecuta la red de Ethereum el Software?

- **EVM/Ethereum Virtual Machine:** Se puede pensar como un servidor de Amazon Web Services, donde el desarrollador sube su programa y Amazon le cobra una tarifa por los gastos que incurra el uso del servidor. La diferencia con la EVM, es que cada quien se encarga de sus gastos por el uso de el blockchain de Ethereum y la EVM. Por ejemplo, el programador paga una tarifa única de gas para subir su aplicación. El usuario que quiera ejecutar dicha aplicación, paga gas para hacerlo.

## Como el dinero está guardado en el mismo lugar donde se ejecuta el software, esto dá lugar a novedosas aplicaciones financieras.

- **Gas:** Pago de gastos por el uso de un blockchain. Este sube o baja dependiendo de cuán saturada se encuentre dicha red en ese momento. A mayor saturación, más caro el gas.

# Ethereum con el tiempo ha ido adquiriendo muchos usuarios, lo cuál encarece el costo del gas

- **L2 / Layer 2:** Soluciones para escalar Ethereum. Empaquetan muchas transacciones en un solo bloque y lo guardan en el blockchain de Ethereum, abaratando costos. Según la L2 que sea, puede tener diferentes desarrollos como ZK para aumentar seguridad, tecnología Optimism, transacciones más rápidas, etc... Puedes imaginarlo como otro blockchain encima de Ethereum.

# Ejemplos de L2: Optimism, Arbitrum, Scroll
