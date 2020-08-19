# GuiaValidation
##Um guia de como fazer a validação de formulários utilizando algumas bibliotecas do nodejs.

![Formulario](https://user-images.githubusercontent.com/50187031/90700630-ad43ed00-e25c-11ea-9b1c-4c73902425f1.png)

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
# End Point

### GET /
Esse endpoint é responsável por carregar a página principal.
#### Parameters
Nenhum,

### POST /form
Esse endpoint é responsável por fazer o processo de validação do formulário.
#### Parameters
email: E-mail do usuário.

nome: Nome do usuário.

Pontos: Pontos tem uma condição não podendo ser menor que 5.
