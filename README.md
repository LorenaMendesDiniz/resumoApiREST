# Api REST e RESTFul

A arquitetura de API REST (Representational State Transfer) é um estilo utilizado para projetar redes e serviços na web. Ela utiliza recursos identificáveis e a manipulação desses recursos por meio de representações. As APIs RESTful utilizam os princípios REST, porém com adendos. Ambos são abordagens para projetar e desenvolver interfaces de programação web que seguem os princípios do estilo arquitetural REST.

## Diferenças entre REST e RESTFul

As principais diferenças entre APIs REST e RESTful estão no nível de aderência aos princípios REST. Enquanto as APIs REST seguem os princípios básicos do REST, as APIs RESTful são uma implementação mais completa e estrita desses princípios. APIs RESTful usam critérios adicionais, como a interface uniforme, clientes sem estado e operações baseadas em recursos.

## HTTP verbs

Os verbos HTTP indicam a ação desejada para ser executada em um recurso identificado. Os principais verbos utilizados em uma API REST/RESTFul são:

- **GET:** Solicita a representação de um recurso.
- **POST:** Envia dados para serem processados para um recurso específico.
- **PUT:** Atualiza um recurso ou cria um recurso se ele não existir.
- **DELETE:** Remove um recurso.

## HTTP Status Code

Os códigos de status HTTP são indicadores numéricos retornados pelo servidor para informar o resultado da solicitação feita pelo cliente. São números que indicam se uma solicitação HTTP foi concluída com êxito ou não. Eles são divididos em 5 classes:

- **1xx:** Respostas informativas
- **2xx:** Respostas bem-sucedidas
- **3xx:** Redirecionamentos
- **4xx:** Erros do cliente
- **5xx:** Erros do servidor

Dentre essas classes, alguns dos exemplos mais comuns são:

- **200 OK:** Indica que a solicitação foi bem-sucedida.
- **201 Created:** Indica que a solicitação resultou na criação de um novo recurso.
- **301 Moved Permanently:** Indica que o recurso foi permanentemente movido para uma nova localização. O cliente deve atualizar o URL para acessar o recurso no novo local.
- **400 Bad Request:** Indica que a solicitação do cliente foi inválida.
- **404 Not Found:** Indica que o recurso solicitado não foi encontrado no servidor.
- **500 Internal Server Error:** Indica que ocorreu um erro no servidor.

---

**Autor do resumo:** Lorena Mendes Diniz - 01528548
