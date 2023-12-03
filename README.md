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

Os códigos de status de resposta HTTP indicam o resultado de uma solicitação, divididos em cinco classes: informativas, bem-sucedidas, de redirecionamento, de erro do cliente e de erro do servidor. As respostas informativas (100-199) incluem códigos como "100 Continue", indicando que o cliente deve continuar a solicitação. As respostas bem-sucedidas (200-299) incluem "200 OK", indicando que a solicitação foi concluída com sucesso. As mensagens de redirecionamento (300–399) incluem códigos como "301 Moved Permanently", indicando uma mudança permanente na URL solicitada. As respostas de erro do cliente (400–499) incluem códigos como "404 Not Found", indicando que o servidor não pode encontrar o recurso solicitado. As respostas de erro do servidor (500–599) incluem códigos como "500 Internal Server Error", indicando que o servidor encontrou uma situação que não sabe como lidar. Esses códigos são essenciais para a comunicação entre clientes e servidores na web.

---
Autor do resumo: [Pedro Ricardo Da Silva Rodrigues](www.linkedin.com/in/pedro-rs-rodrigues) - 01565486
