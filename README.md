## Api REST e RESTFul


A API REST, ou API RESTFul, é uma interface de programação de aplicações que segue as restrições da arquitetura REST. Ela facilita a interação com serviços web RESTful, transferindo representações do estado do recurso ao solicitante por meio de solicitações HTTP. A informação pode ser entregue em diversos formatos, como JSON, HTML, XML, Python, PHP ou texto sem formatação. O JSON é amplamente utilizado devido à sua independência de linguagem e capacidade de ser compreendido por máquinas e humanos. Cabeçalhos e parâmetros são cruciais nos métodos HTTP de uma solicitação de API RESTful, pois contêm informações relevantes, como identificadores, metadados, autorização, URI, cache, cookies e outros detalhes. Tanto os cabeçalhos da solicitação quanto os da resposta desempenham papéis importantes, fornecendo informações sobre as conexões HTTP e os códigos de status correspondentes.


## Diferenças entre REST e RESTFul


REST (Representational State Transfer) é um estilo arquitetônico que define princípios para projetar serviços web. Por outro lado, RESTful refere-se à implementação específica desses princípios em um sistema ou serviço web, garantindo conformidade estrita com as restrições do REST, como a utilização de métodos HTTP padrão, a arquitetura sem estado e a transferência de representações de recursos. Em resumo, REST é o conjunto de princípios, enquanto RESTful é a aplicação desses princípios em um sistema específico.

## HTTP verbs

O protocolo HTTP utiliza métodos de requisição, também conhecidos como HTTP Verbs, para indicar a ação a ser realizada em um recurso. Alguns desses métodos incluem:

```
1. GET: Obtém a representação de um recurso específico, retornando apenas dados.
2. HEAD: Solicita uma resposta idêntica ao GET, mas sem incluir o corpo da resposta.
3. POST: Submete uma entidade a um recurso, geralmente causando mudanças no estado ou efeitos colaterais.
4. PUT: Substitui todas as representações do recurso pelo conteúdo da requisição.
5. DELETE: Remove um recurso específico.
6. CONNECT: Estabelece um túnel para o servidor identificado pelo recurso.
7. OPTIONS: Descreve as opções de comunicação com o recurso.
8. TRACE: Executa um teste de chamada loop-back junto com o caminho para o recurso.
9. PATCH: Aplica modificações parciais em um recurso.
```

Cada método possui uma semântica diferente, mas alguns compartilham características como serem seguros, idempotentes ou cacheáveis. Esses métodos permitem uma comunicação eficaz entre clientes e servidores seguindo os princípios do protocolo HTTP.

## HTTP Status Code

Os códigos de status de resposta HTTP indicam o resultado de uma solicitação, divididos em cinco classes: informativas, bem-sucedidas, de redirecionamento, de erro do cliente e de erro do servidor.
```
Respostas informativas (100- 199)
Respostas bem-sucedidas (200- 299)
Mensagens de redirecionamento (300– 399)
Respostas de erro do cliente (400– 499)
Respostas de erro do servidor (500– 599)
```

Esses códigos são essenciais para a comunicação entre clientes e servidores na web. A seguir está alguns exemplos mais detalhados e seus significados:

```
Respostas Informativas
- 100 Continue: Resposta provisória indicando que o cliente deve continuar a solicitação ou ignorar se concluída.
- 101 Switching Protocols: Enviado em resposta a um cabeçalho Upgrade, indica a mudança de protocolo.
- 102 Processing (WebDAV): Indica que o servidor recebeu e está processando a solicitação.

Respostas Bem-Sucedidas
- 200 OK: Solicitação bem-sucedida, e o significado varia conforme o método HTTP.
- 201 Created: Solicitação bem-sucedida, resultando na criação de um novo recurso.
- 202 Accepted: Solicitação recebida, ainda não atendida, adequado para casos assíncronos.

Mensagens de Redirecionamento
- 300 Multiple Choices: Solicitação com várias respostas possíveis.
- 301 Moved Permanently: URL do recurso foi alterada permanentemente.
- 302 Found: URI temporariamente alterado, sujeito a futuras mudanças.

Respostas de Erro do Cliente
- 400 Bad Request: Servidor não pode processar devido a erro do cliente.
- 401 Unauthorized: Sem autenticação; o cliente deve se autenticar.
- 403 Forbidden: Cliente não autorizado; o servidor recusa o recurso solicitado.
- 404 Not Found:** Recurso solicitado não encontrado.

Respostas de Erro do Servidor
- 500 Internal Server Error: Situação que o servidor não sabe como lidar.
- 501 Not Implemented: Método de solicitação não suportado pelo servidor.
- 502 Bad Gateway: Servidor, como gateway, obteve uma resposta inválida.

```

---
Autor do resumo: [Pedro Ricardo Da Silva Rodrigues](www.linkedin.com/in/pedro-rs-rodrigues) - 01565486
