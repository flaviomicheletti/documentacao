---
title  : Documentação
layout : home
---

Este é nosso primeiro pequeno exemplo!

Aqui entramos com a descrião da API.

Podemos descrever em detalhes comom funcionará cada serviço.

+ [Servico ABC](abc/)
+ [Servico DEF](abc/)
+ [Servico XYZ](abc/)


## Consultar Serviço XYZ

Este serviço disponibilizará ao cliente acesso aos dados principais denominado XYZ.


### Request

A requisição poderá ser feita com o nome completo.

    PUT https://www.mocky.io/v2/5185415ba171ea3a00704eed

O corpo da requisição deve como mostrado abaixo:

```javascript
{
  "id": 123,
  "nome": "um nome qualquer"
}
```

### Response

A responta é semelhante a...

    < HTTP/1.1 200 OK
    < Content-Type: application/json; charset=UTF-8
    { "hello": "world" }
