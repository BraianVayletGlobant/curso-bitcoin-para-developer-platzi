# 📝 Notas del Curso de Bitcoin para Developers

### Clases:

- Clase1: [Introducción](#Introducción)
- Clase2: [Qué es Blockchain](#Qué-es-Blockchain)
- Clase3: [Estructura de un bloque](#Estructura-de-un-bloque)
- Clase4: [Merkle trees](#Merkle-trees)
- Clase5: [La arquitectura de una red P2P](#La-arquitectura-de-una-red-P2P)
- Clase6: [La economía de Bitcoin](#La-economía-de-Bitcoin)
- Clase7: [Minando un bloque](#Minando-un-bloque)
- Clase8: [Cambiando las reglas de consenso (forks)](<#Cambiando-las-reglas-de-consenso-(forks)>)
- Clase9: [Transacciones: outputs e inputs](#Transacciones:-outputs-e-inputs)
- Clase10: [Script](#Script)
- Clase11: [Transaction fees](#Transaction-fees)
- Clase12: [Llaves públicas y privadas / Bitcoin addresses](#Llaves-públicas-y-privadas-/-Bitcoin-addresses)
- Clase13: [Formatos de llaves](#Formatos-de-llaves)
- Clase14: [Tipos de wallets: nondeterministic, deterministic](#Tipos-de-wallets:-nondeterministic,-deterministic)
- Clase15: [Seeds and mnemonic codes](#Seeds-and-mnemonic-codes)
- Clase16: Conclusión

## Introducción

> Links:
>
> - [https://bitcoin.org/files/bitcoin-paper/bitcoin_es_latam.pdf](https://bitcoin.org/files/bitcoin-paper/bitcoin_es_latam.pdf)
> - [https://github.com/bitcoinbook/bitcoinbook](https://github.com/bitcoinbook/bitcoinbook)
> - [http://napkinbooks.com/](http://napkinbooks.com/)

## Qué es Blockchain

- **Libro Mayor Descentralizado**
- Inmutabilidad, solo puedo añadir transacciones
- Herramienta que me indique el estado de mi libro mayor

> Links:
>
> - [https://www.reddit.com/r/explainlikeimfive/comments/12knie/eli5_bitcoins/](https://www.reddit.com/r/explainlikeimfive/comments/12knie/eli5_bitcoins/)
> - [https://queue.acm.org/detail.cfm?id=3136559](https://queue.acm.org/detail.cfm?id=3136559)

## Estructura de un bloque

> Links:
>
> - [block 0](https://www.blockchain.com/btc/block/000000000019d6689c085ae165831e934ff763ae46a2a6c172b3f1b60a8ce26f)
> - [https://www.blockchain.com/](https://www.blockchain.com/)
> - [https://www.npmjs.com/package/bitcoin-cli](https://www.npmjs.com/package/bitcoin-cli)

## Merkle trees

> Links:
>
> - [https://queue.acm.org/detail.cfm?id=3136559](https://queue.acm.org/detail.cfm?id=3136559)
> - [https://github.com/melekes/merkle-tree-rs](https://github.com/melekes/merkle-tree-rs)
> - [https://github.com/bitcoinbook/bitcoinbook/blob/develop/code/merkle.cpp](https://github.com/bitcoinbook/bitcoinbook/blob/develop/code/merkle.cpp)
> - [https://www.youtube.com/watch?v=PraPZFMj6h8](https://www.youtube.com/watch?v=PraPZFMj6h8)
> - [https://es.wikipedia.org/wiki/%C3%81rbol_de_Merkle](https://es.wikipedia.org/wiki/%C3%81rbol_de_Merkle)

## La arquitectura de una red P2P

> Links:
>
> - [https://github.com/bitcoinbook/bitcoinbook](https://github.com/bitcoinbook/bitcoinbook)
> - [https://platzi.com/blog/como-funciona-bitcoin-conceptos-basico-para-entender/](https://platzi.com/blog/como-funciona-bitcoin-conceptos-basico-para-entender/)
> - [https://docs.symbolplatform.com/concepts/data-validation.html](https://docs.symbolplatform.com/concepts/data-validation.html)

## La economía de Bitcoin

> Links:

## Minando un bloque

> Links:
>
> - [https://github.com/bitcoinbook/bitcoinbook/blob/develop/code/hash_example.py](https://github.com/bitcoinbook/bitcoinbook/blob/develop/code/hash_example.py)
> - [https://www.amazon.com/-/es/Andreas-M-Antonopoulos-ebook/dp/B071K7FCD4](https://www.amazon.com/-/es/Andreas-M-Antonopoulos-ebook/dp/B071K7FCD4)

## Cambiando las reglas de consenso (forks)

### Dato:

_Según esta herramienta: [Bitcoin Node Count History](https://luke.dashjr.org/programs/bitcoin/files/charts/historical.html), a día de hoy (Febrero - 2022) se contabilizan un total de 49555 nodos activos de Bitcoin. Por lo que un ataque del 51% supondría un control total, paralelo y síncrono de más de 24778 nodos de la red Bitcoin. Teóricamente es muy poco probable que sucede, y a nivel práctico es casi imposible._

> Links:
>
> - [https://bitcoinops.org/en/topics/taproot/](https://bitcoinops.org/en/topics/taproot/)
> - [https://en.bitcoin.it/wiki/Majority_attack](https://en.bitcoin.it/wiki/Majority_attack)
> - [https://luke.dashjr.org/programs/bitcoin/files/charts/historical.html](https://luke.dashjr.org/programs/bitcoin/files/charts/historical.html)

## Transacciones: outputs e inputs

...

## Script

...

## Transaction fees

...

## Llaves públicas y privadas / Bitcoin addresses

> Links:
>
> - [https://es.wikipedia.org/wiki/Criptograf%C3%ADa_de_curva_el%C3%ADptica](https://es.wikipedia.org/wiki/Criptograf%C3%ADa_de_curva_el%C3%ADptica)
> - [https://cryptography.io/en/latest/development/custom-vectors/secp256k1/](https://cryptography.io/en/latest/development/custom-vectors/secp256k1/)
> - [https://learn.bybit.com/es/blockchain-es/claves-publicas-claves-privadas/](https://learn.bybit.com/es/blockchain-es/claves-publicas-claves-privadas/)

## Formatos de llaves

> Links:
>
> - [https://github.com/bitcoinbook/bitcoinbook/blob/develop/code/key-to-address-ecc-example.py](https://github.com/bitcoinbook/bitcoinbook/blob/develop/code/key-to-address-ecc-example.py)

## Tipos de wallets: nondeterministic, deterministic

...

## Seeds and mnemonic codes

#### ¿Qué es un mnemónico?

Una representación de un número aleatorio a través de 12/24 palabras muy sencillas de escribir.

> Links:
>
> - [https://github.com/btcontract/wallet](https://github.com/btcontract/wallet)
> - [https://play.google.com/store/apps/details?id=com.btcontract.wallet&amp;hl=en_US&amp;gl=US](https://play.google.com/store/apps/details?id=com.btcontract.wallet&hl=en_US&gl=US)

## Conclusión

...
