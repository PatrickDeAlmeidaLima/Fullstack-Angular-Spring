### Fullstack-Angular-Spring
Fullstack Angular &amp; Spring

## Modulo - 1 Introdução ao Rest
* Aula 1
O que é SOFEA?
Ideia básica é remover toda a lógica de apresentação do servidor e levar para o cliente.
* SOFEA é a sigla para Service-Oriented Front-end Architecture. É uma arquitetura de software que se concentra em criar serviços orientados a front-end que possam ser reutilizados em várias aplicações.
* A idéia por trás da SOFEA é separar a interface do usuário e a lógica do negócio em serviços independentes que podem ser facilmente integrados em diferentes aplicações e plataformas. Isso permite a criação de aplicações mais rápidas, escaláveis e flexíveis.
* A SOFEA também incentiva a utilização de tecnologias modernas como JavaScript, HTML, CSS e REST APIs para criar serviços altamente interativos e adaptáveis aos dispositivos móveis.
Os benefícios podem ser:
* Desenvolvimento assíncrono do front-end e back-end.
* Escabilidade.
* Interoperabilidade.
* Melhor experiência do usuário do usuário e baixa latência.

Aula 2
O que é REST?
Ideia básica é integrar dois sistemas.
* REST é a sigla para Representational State Transfer, que é um estilo arquitetural de software para a World Wide Web. É uma forma de criar sistemas distribuídos, como serviços web, que permitem que aplicativos sejam integrados com outros aplicativos através da Internet.
* REST é baseado em conceitos simples e estabelecidos da web, como URLs para identificar recursos e HTTP para transmitir informações. O objetivo é tornar os sistemas distribuídos fáceis de serem implementados, escalados e mantidos.
* REST é amplamente utilizado em API's para a web, onde os desenvolvedores podem criar recursos e funcionalidades que podem ser acessados por outras aplicações através da Internet. Isso permite a integração de aplicativos e serviços, criando soluções mais robustas e escaláveis.

Aula 3
E o que é uma API REST?
* API REST (Application Programming Interface - RESTful) é um tipo de API que permite a integração de sistemas e aplicações através da web. É baseado no estilo arquitetural REST e utiliza o protocolo HTTP para trocar informações entre aplicativos.
* Uma API REST define uma série de endpoints (pontos finais), cada um representando um recurso que pode ser acessado, criado, atualizado ou excluído através de requisições HTTP. Essas requisições incluem métodos como GET, POST, PUT, DELETE, entre outros.
* O uso de uma API REST permite que aplicações e sistemas diferentes possam se comunicar entre si de forma simples e clara. Isso facilita a integração de aplicativos, aumenta a escalabilidade e permite que novas funcionalidades sejam adicionadas sem afetar as aplicações existentes.
* A API REST é amplamente utilizada em aplicações web, especialmente em aplicações de e-commerce, serviços de mídia social e em sistemas de gerenciamento de conteúdo.

Aula 4 
Como fazer teste de rotas de back-end?
* É possível com o programa postman ou insonia passando a rota com o verbo referente a aplicação.
* Pode ser testado através do seguinte link: https://designer.mocky.io/design
* Programas para serem instalados para pleno funcionamento do back-end:
* Postman, mysql, Spring Tool Suite 

Aula 5
O que é http e o que tem haver com rest?
* HTTP significa Protocolo de Transferência de Hipertexto (em inglês, Hypertext Transfer Protocol) e é o protocolo mais utilizado para a transferência de dados na internet. Ele foi criado para permitir a comunicação entre servidores e clientes (como navegadores web) na web.
* REST, por sua vez, é um estilo de arquitetura de software que utiliza o HTTP como um de seus principais protocolos de comunicação. Uma API RESTful (ou simplesmente API REST) é uma API que segue os princípios do estilo REST e utiliza o HTTP como meio de comunicação para a transferência de dados.
* Na prática, uma API REST é composta por endpoints (URLs) que representam recursos, e cada endpoint corresponde a uma operação específica (como, por exemplo, criar, ler, atualizar ou excluir um recurso). As operações são realizadas por meio dos métodos HTTP (como GET, POST, PUT e DELETE), que indicam a ação que deve ser executada sobre o recurso correspondente ao endpoint.
* Assim, o HTTP tem uma relação importante com o estilo de arquitetura REST, já que é o protocolo utilizado para a comunicação entre os clientes e os servidores que implementam uma API REST.
* HTTP retorna após a requisição os códigos por exemplo: 200, 400, 404, etc.

Aula 6
O que é recurso? (URI/URL)
* Em sistemas web e na arquitetura REST, um recurso é uma informação identificável e manipulável que é exposta através de uma URI (Uniform Resource Identifier) ou URL (Uniform Resource Locator). Os recursos são o cerne da arquitetura REST, e são acessados via HTTP utilizando verbos como GET, POST, PUT e DELETE para realizar operações de leitura, criação, atualização e exclusão, respectivamente.
* Por exemplo, em um sistema de gerenciamento de produtos, os produtos em si podem ser considerados recursos, e cada produto pode ter uma URI única para ser acessada.

Aula 7
O que é representação de um recurso?
* Em REST, a representação de um recurso é a forma em que o recurso é apresentado em um determinado formato, que pode ser uma imagem, um documento HTML, JSON, XML, entre outros.
* A representação é a forma como o recurso é "visto" e interage com outros sistemas, e pode ser manipulada através de requisições HTTP, como GET, POST, PUT, DELETE, PATCH, entre outras.
* É importante destacar que a representação não é o próprio recurso, mas sim uma forma de apresentá-lo e interagir com ele através de uma determinada aplicação ou sistema. A representação é usada para transmitir o estado do recurso entre diferentes sistemas, sendo fundamental para a comunicação e troca de dados em arquiteturas RESTful.

Aula 8
O que é modelo de maturidade Richardson?
* O Richardson Maturity Model é um modelo de maturidade para o design de APIs RESTful, criado por Leonard Richardson. O modelo descreve quatro níveis de maturidade, que vão desde o nível 0 (serviços web) até o nível 3 (serviços RESTful avançados):
* Nível 0: Serviços Web
* Neste nível, os serviços são implementados como operações de método remoto, baseados em protocolos como SOAP ou XML-RPC. Eles não seguem as restrições e princípios do REST, como a utilização de URIs para identificar recursos e a utilização dos verbos HTTP para realizar operações em recursos. Em geral, os serviços neste nível são considerados menos flexíveis, menos escaláveis e menos adaptáveis às mudanças do que os serviços RESTful.
* Nível 1: Recursos
No nível 1, os serviços são implementados como recursos, identificados por URIs. Os recursos podem ser objetos físicos ou abstratos, como documentos, imagens, pessoas, transações ou quaisquer outros objetos que possam ser representados digitalmente. Cada recurso é representado por um único URI, que é utilizado para identificar e acessar o recurso.
* Nível 2: HTTP Verbs
No nível 2, os serviços utilizam os verbos HTTP (GET, POST, PUT, DELETE) para realizar operações em recursos. Isso significa que, em vez de implementar operações específicas de método remoto, como "addUser", "deleteUser", "updateUser", etc., os serviços utilizam os verbos HTTP para realizar operações comuns em recursos, como obter um recurso, criar um novo recurso, atualizar um recurso existente ou excluir um recurso.
* Nível 3: HATEOAS
No nível 3, os serviços utilizam hipermídia para informar o cliente sobre as ações possíveis em cada recurso. Isso significa que, em vez de o cliente depender de documentação externa ou conhecimento prévio sobre o serviço para saber como interagir com os recursos, o serviço informa ao cliente, por meio de links hipermídia, quais são as ações possíveis em cada recurso. Isso torna os serviços mais flexíveis, adaptáveis e escaláveis, permitindo que novas funcionalidades sejam adicionadas sem afetar os clientes existentes.
* Em resumo, o modelo Richardson Maturity Model descreve a evolução dos serviços web de uma abordagem baseada em operações de método remoto para uma abordagem baseada em recursos, identificados por URIs, e operações comuns, realizadas por meio dos verbos HTTP. Em seguida, ele evolui para uma abordagem baseada em hipermídia, que torna os serviços mais flexíveis, adaptáveis e escaláveis.