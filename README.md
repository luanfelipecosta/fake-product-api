# API Fake de produtos

# Utilização

1. Copie o arquivo `api.js` para a sua aplicação

2. Importe e utilize.

```
import { fetchProducts, queryProducts } from './api';
```

# Utilizando as promises

```
async function() {
  const produtos = await fetchProducts();
  ...
}
```

ou de forma sincrona

```
fetchProducts().then((response) => {
  setState(response);
})
```
