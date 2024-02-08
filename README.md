# Introdução

Domain Driven Design é uma forma de desenvolver software com o foco no coração da aplicação, o que chamamos de domínio, tendo como objetivo de entender suas regras, processos e complexidades.

DDD deve ser aplicado para casos de projetos de softwares complexos.

Grandes projetos possuem muitas áreas, muitas regras de negócio, muitas pessoas com diferentes visões em diferente contextos. (exemplo um contexto do serviço oferecido, exemplo um contexto de cobrança, um contexto de venda)


## Como o DDD pode ajudar
- Entender com profundidade o domínio e subdomínio da aplicação. 

	- Dominio é o principal daquilo que a gente vai desenvolver. Dominio é a visão geral. 
	- Subdominios é o parte de nosso sistemas, que em conjunto agrega valor a empresa. Subdominio como se fosse com uma lupa.


- Ajuda a ter uma linguagem universal(linguaguem ubíqua) entre todos os envolvidos

- Ajuda a criar design mais estratégico utilizando bounded contexts. (o que isso significa? que eu tenho um dominio e diversos subdominio, e baseado nesses subdominios eu vou criar uma estratégia de modelagem para criar contextos. e quando eu tiver esses contexto eu tenho uma visão geral de tudo que precisa ser desenvolvido.)

- Ajuda a criar um design tático para conseguir mapear e agregar as entidades e objetos de valor da aplicação.

- Voce consegue entender o problema do negocio e as complexidades.

________________________________________________
## Domínio e Subdomínios 

**Core Domain**  o coração do meu negócio.
**Support Subdomain** apoia o domínio, faz a operação do domínio possível.

**Generic Subdomain** auxilia o domínio, mas não tem um diferencial competitivo. pode ser facilmente substituido.
por exemplo 

___________________________________________________
## Espaço do problema vs espaço da solução

espaço do problema - é visão geral do dominio e suas complexidades, depois de entender e visualizar eu começo a separar esse domínio em subdominios.


como eu consigo entender esse problema e organizar esse problema de uma forma que eu consiga preparalo para conseguir solucionar tudo isso? por isso que eu tenho o espaço da solução

espaço da solução - analise e modelagem do dominio. 
contexto delimitados =
quando eu quero resolver cada subdominio, eu vou pegar cada subdominio e delimitar contexto e cada contexto que eu delimitar vai acabar virando subprodutos que eu vou acabar resolver e trabalhar.

veja o problema que voce tem, começa a modelar esse problema, separe esse problema em problemas menores, e delimite esses problemas menores em pontos que voce vai começar a se organizar para desenvolver.

______________________________________________________
## Contexto delimitado / bounded contexts 
É uma divisão de uma parte do dominio.


______________________________________________________
## O que é contexto?
o contexto ele sempre vai determinar qual area da empresa a gente está trabalhando, que tipo de problema a gente está tentando resolver.

exemplo de contextos
- contexto de venda
- contexto de cobrança
- contexto de brindes
_____________________________________________________
## Elemento transversal
vamos supor que exista dois ou mais contexto com o mesmo elemento.
- contexto de vendas tem o cliente.
- contexto de cobrança tem o cliente.
- contexto de brindes tem o cliente.

uma boa pratica para esses casos é criar um elemento cliente para cada contexto, pois um unico elemento para atender os tres contextos, esse elemento vai acabar virando um frankestein.
________________________________________________________________

