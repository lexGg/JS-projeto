# ![DevSuperior logo](https://raw.githubusercontent.com/devsuperior/bds-assets/main/ds/devsuperior-logo-small.png) Curso Nivelamento JavaScript
>  Aprenda de forma rápida os principais fundamentos de JavaScript para se preparar para trabalhar com frameworks front end

## Realização
[DevSuperior - Escola de programação](https://devsuperior.com.br)

[![DevSuperior no Instagram](https://raw.githubusercontent.com/devsuperior/bds-assets/main/ds/ig-icon.png)](https://instagram.com/devsuperior.ig)
[![DevSuperior no Youtube](https://raw.githubusercontent.com/devsuperior/bds-assets/main/ds/yt-icon.png)](https://youtube.com/devsuperior)

## Projeto DSViaCEP

### Design Figma
https://www.figma.com/file/idfHqxib6cRdqPQIcCy8HA/DSViaCEP

### Trechos de código

#### Definindo uma exceção personalizada
```javascript
// https://rollbar.com/guides/javascript/how-to-throw-exceptions-in-javascript/

export default function RequestException(message) {
  const error = new Error(message);
  return error;
}

RequestException.prototype = Object.create(Error.prototype);
```
