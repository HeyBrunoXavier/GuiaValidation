# GuiaValidation
##Um guia de como fazer a validação de formulários utilizando algumas bibliotecas do nodejs.

aqui entra uma imagem...

### Bibliotecas utilizadas

### express
```
const express = require("express");
```
#### expree-session

```
const session = require("express-session");
```

#### express-flash

```
const flash = require("express-flash");
```

#### body-parser

```
const bodyParser = require("body-parser");
```

#### cookie-parser
```
const cookie = require("cookie-parser");
```
### POST /form
Esse endpoint é responsável por fazer o processo de validação do formulário.
#### Parameters
email: E-mail do usuário.

nome: Nome do usuário.

Pontos: Pontos tem uma condição não podendo ser menor que 5.
