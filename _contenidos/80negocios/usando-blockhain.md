INTRODUCCION: Cuando se inicia una transacción, los datos de la transacción se ajustan a un bloque y luego se duplican en múltiples computadoras o nodos en la red. Los nodos son el cuerpo administrativo de blockchain y verifican la legitimidad de las transacciones en cada bloque. Para llevar a cabo el paso de verificación, los nodos o mineros necesitarían resolver un rompecabezas computacional, conocido como prueba del problema de trabajo. El primer minero para descifrar cada problema de transacción de bloque recibe una moneda. Una vez que se ha verificado un bloque de transacciones, se agrega a blockchain

- PoW vs PoS 

Prueba de trabajo vs prueba de participacion. En que se diferencian?? 
Vamos por parte, cualquiera de las dos son pruebas, esto quiere decir que un sistema requiere que el cliente:
 a) Realice una prueba de trabajo mostrando el trabajo y su costo invertido.
 b) demuestre una prueba de participacion, mostrando posesion del activo en cuestión.
El tema da para rato, pero busco no complicarla. La diferencia fundamental radica en la estructura necesaria para generar las pruebas. No es lo mismo tener monedas alojadas en cualquier servidor, que tener servidores para responder una pow en calquier lugar de la tierra. 
Finalmente, en PoW, la energia y el tiempo invertido se traducen en la robustez de la blockchain resultante, superando ampliamente en cuanto al valor generable en una blockchain PoS.
Tambien existen sistemas hibridos con ambos tipos de mineria. Sera explicado en otro post.

- Solucion al problema de los generales bizantinos
 Esta cuestion plantea de forma metafórica el problema que se da entre un conjunto de sistemas informáticos que tienen un objetivo común. Deben encontrar un plan de acción común a partir de una estructura jerárquica, donde uno de los sistemas que tiene mayor rango proporciona una orden a partir de la cual el resto de sistemas tiene que operar (fijar su decisión). Además es posible que alguno de ellos no sea fiable y provea información falsa de forma intencionada.1​
Entonces: "Bitcoin permite crear un registro unico comun de manera descentralizada"
 Esto parece complicado pero es muy simple. Supongamos que tenemos un ejercito con 3 generales o tenientes y debemos identificar si uno es el traidor. Como lo identificamos? Por medio del CONSENSO. Por ej: si dos generales deciden atacar y uno no, el mensaje va a ser el de atacar, eliminando la validez del mensaje del traidor que es retirarse.
 Una explicacion mas detallada y con mayores variables se encuentra aqui: 
https://web.ua.es/en/recsi2014/documentos/papers/bitcoins-y-el-problema-de-los-generales-bizantinos.pdf

- SegWit

Este es un detalle importante en lo que respecta al movimiento de nuestro dinero y no tanto a la parte tecnica. Segregated Witness es un cambio en el formato de las transacciones para minimizar el uso de datos en las mismas. Eliminando la firma de desbloqueo (datos del "testigo") de su lugar original y añadiéndola como una estructura separada al final.

- Trusted third party

En pocas palabras, la eliminacion de de una tercera parte (como los bancos) en las transacciones reduce al maximo sus costos operativos. Los libros distribuidos abarcan este problema brindando una solucion contable y confiable ajena a las partes.

- Side-chain y Cross-chain

La batalla por la escalabilidad de los sistemas tiene multiples caras. Las cadenas laterales brindan una solucion por encima de la cadena original, haciendo las transacciones mas rapidas y brindando usos mayores. Esto se hace de la siguiente manera. La cadena lateral "toma" una pequeño valor de la cadena principal, utilizandolo como energia para hacer uso y cumplimiento de un contrato inteligente. Cuando la fue transaccion finaliza, el valor vuelve a su cadena de origen. 
Las cross-chain permiten la interoperabilidad entre blockchains a travez de los intercambios atomicos.
Aunque suenen parecidas tienen objetivos diferentes. Las crosschains apuntan a funcionar como intercambios masivos de valor. Las sidechains son algo mas complejas, solucionan problemas como los del doble gasto y pueden crecer en cuanto a su valor por la capacidad de ser minadas en conjunto con la blockchain principal. Un dato no menos importante.
Mayor info: https://docs.rsk.co/Drivechains_Sidechains_and_Hybrid_2-way_peg_Designs_R9.pdf

- Mineria

La mineria es el trabajo o energia invertidos para generar y crear un activo. Su poder se basa en la capacidad de computo. 
Mayor informacion sobre ambos tipos de mineria y respondiendo al item 1 aqui:
https://blockgeeks.com/guides/proof-of-work-vs-proof-of-stake/
