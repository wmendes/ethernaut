Este gatekeeper presenta algunos desafíos nuevos. Regístrate como entrant para pasar este nivel.

##### Cosas que pueden ayudar:
* Recuerda lo que has aprendido al pasar el primer gatekeeper: el primer gate es el mismo.
* La palabra clave `assembly` en el segundo gatekeeper permite que un contrato acceda a una funcionalidad que no es nativa de Solidity. Consulta [aquí](http://solidity.readthedocs.io/en/v0.4.23/assembly.html) para obtener más información. La llamada `extcodesize` en este gate obtendrá el tamaño del código de un contrato en una dirección determinada; puedes obtener más información sobre cómo y cuándo se setea en la sección 7 del [yellow paper](https://ethereum.github.io/yellowpaper/paper.pdf).
* El carácter `^` en el tercer gate es una operación bit a bit (XOR), y se usa aquí para aplicar otra operación bit a bit común (ver [aquí](http://solidity.readthedocs.io/en/v0.4.23/miscellaneous.html#cheatsheet)). El nivel CoinFlip también es un buen lugar para comenzar al tratar este desafío.