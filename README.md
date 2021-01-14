# Fundamentos de Arquitetura de Software

## Plataforma

[desenvolvedor.io](https://desenvolvedor.io/)

## Link para o curso

[Fundamentos de Arquitetura de Software](https://desenvolvedor.io/curso/633d37f3-f03f-40d4-a3b6-afd558ccf364)

## Instrutor

### Eduardo Pires

Eduardo Pires é fundador da plataforma desenvolvedor.io, arquiteto e desenvolvedor de software, palestrante e instrutor de treinamentos.

Foi reconhecido como Most Valuable Professional (MVP) pela Microsoft na competência de desenvolvimento de software de 2014 até 2020.

Este reconhecimento é um prêmio internacional conferido pela Microsoft aos profissionais de maior destaque no mercado, existem cerca de 3.500 MVPs no mundo e 110 MVPs no Brasil, sendo 40 deles na competência de desenvolvimento de software.

## Progresso do Curso

### Introdução

- [x] Apresentação (1:00)
- [x] O que é arquitetura? (15:00)

### Perfis de Arquitetos

- [x] Perfis de arquitetos (6:00)
- [x] Arquiteto Corporativo (7:00)
- [x] Arquiteto de Negócios (6:00)
- [x] Arquiteto de Soluções (6:00)
- [x] Arquiteto de Software (11:00)
- [x] Outros perfis de arquitetos (3:00)

### Perfil do Arquiteto de Software

- [x] Responsabilidades (7:00)
- [x] Requisitos Técnicos (8:00)
- [x] Requisitos Pessoais (14:00)
- [x] Mitos sobre o Arquiteto de Software (11:00)

### OOP

- [x] Pilares da Programação Orientada a Objetos (4:00)
- [x] Estado e Comportamento (7:00)
- [x] Herança (6:00)
- [x] Abstração (4:00)
- [x] Polimorfismo (9:00)
- [x] Encapsulamento (20:00)
- [x] Interface x Implementação (10:00)
- [x] Herança x Composição (17:00)
- [x] Teste seus conhecimentos - Herança (3:00)
- [x] Teste seus conhecimentos - Abstração (5:00)
- [x] Teste seus conhecimentos - Polimorfismo (4:00)
- [x] Teste seus conhecimentos - Encapsulamento (5:00)
- [x] Teste seus conhecimentos - OOP (4:00)

### SOLID

- [x] Princípios SOLID (10:00)
- [x] SRP - Single Responsability Principle (13:00)
- [x] OCP – Open Closed Principle (15:00)
- [x] LSP- Liskov Substitution Principle (20:00)
- [x] ISP - Interface Segregation Principle (8:00)
- [x] DIP - Dependency Inversion Principle (18:00)
- [x] Teste seus conhecimentos - SRP (3:00)
- [x] Teste seus conhecimentos - OCP (4:00)
- [x] Teste seus conhecimentos - LSP (4:00)
- [x] Teste seus conhecimentos - ISP (3:00)
- [x] Teste seus conhecimentos - DIP (4:00)

### Dependency Injection

- [x] Exemplo do "mundo real" (16:00)
- [x] Tipos de ciclo de vida (17:00)
- [x] Registro de generics (7:00)
- [x] Property Injection (8:00)
- [x] Service Locator "Pattern" (11:00)
- [x] N Classes : 1 Interface (10:00)
- [x] Teste seus conhecimentos (3:00)

### Clean Code

- [x] Apresentação (4:00)
- [x] O que é um código limpo? (4:00)
- [x] Desculpas e responsabilidades (25:00)
- [x] Como medir um bom código? (13:00)
- [x] Boas práticas (13:00)
- [x] Devo comentar meu código? (7:00)
- [x] Tratamento de erros (10:00)

### Design Patterns

- [x] Apresentação (8:00)
- [x] Creational Patterns (6:00)
- [x] Abstract Factory (21:00)
- [x] Factory Method (12:00)
- [x] Singleton (14:00)
- [x] Structural Patterns (6:00)
- [x] Adapter (10:00)
- [x] Facade (15:00) <!-- * Tem a ideia de domain no exemplo   -->
- [x] Composite (14:00)
- [x] Behavorial Patterns (7:00)
- [x] Command (15:00)
- [x] Strategy (12:00) <!-- * Strategy funciona muito bem com o façade!   -->
- [x] Observer (11:00)
- [x] Evite o Patternite (4:00)

### Arquitetura de Software

- [x] Estilos Arquiteturais (13:00)
- [x] Padrões Arquiteturais (6:00)
- [x] 3-Tier Architecture (4:00)
- [x] Onion Architecture (9:00) <!-- Arquitetura bem interessante, pode ser inclusive monolítica e ser uma arquitetura boa   -->
- [x] Hexagonal Architecture "Ports & Adapters" (22:00)
- [x] CQRS - Command Query Responsibility Segregation (16:00)
- [x] Event Sourcing (10:00)
- [x] DDD - Domain-Driven Design (30:00)
- [x] Arquiteturas Evolutivas (10:00)
- [x] Sempre considere a complexidade! (7:00)
- [x] Conway's Law (9:00)
- [x] Agilidade e o Manifesto Ágil (15:00)
- [x] DevOps (12:00)
- [x] Principios DRY, KISS e YAGNI (10:00)
- [x] Leituras recomendadas (7:00)

### Encerramento

- [x] Palavras finais (6:00)

---

---

---

## **Anotações:**

---

## **Domain Driven Design**

Indicado para aplicações complexas, com muitas entidades e regras de negócio.

Razoavelmente fácil de enetender, difícil de aplicar.

É um guia de como entender um negócio, organizá-lo em conjunto de princípios, cirar uma modelagem com base no negócio e implementar utilizando diversas boas práticas.

---

### **Entender o Negócio**

O primeiro passo é entender o negócio juntamente com um "Domain Expert" (pessoa responsável pelo negócio), as vezes essa pessoa também assume o papel de "Product Owner", ou algum outro papel desde que ele se denomine o responsável pelo negócio.

Essa pessoa vai te guiar, vai estar 100% disponível para tirar dúvidas, até mesmo para definir novos modelos de negócio, novas regras, nomear coisas.

### **Extrair a Linguagem Ubíqua**

É um vocabulário de todos os termos específicos do domínio

- nomes, verbos, adjetivos, jargões, apelidos, expressões idiomáticas e advérbios

Compartilhado por todas as partes envolvidas no projeto

- Primeiro passo para evitar desentendimento

Usada em todas as formas faladas e escritas de comunicação

- A linguagem universal de um negócio é feita dentro da empresa

### **Modelagem Estratégica**

Extrair a linguagem Ubíqua vai colaborar na visão e entendimento do negócio e como segregar seu domínio em partes menores e reponsáveis.

Para documentar estas segregações responsáveis utilizando o Mapa de Contextos (Context Map) que pode ser representado através de imagens e uma simples documentação do tipo de relacionamento entre os contextos.

Cada contexto delimitado possui sua própria Linguagem Ubíqua, pois em contextos diferentes, os termos podem ter significados diferentes.

"No modelo de domínio o contexto muda a forma de como o produto é visto / de como o produto é trabalhado. (exemplo do produto no modelo de negócios 'produto representa a mesma coisa em todos os contextos' e no exemplo o produto é diferente em cada contexto 'produto em marketing context é diferente de sales context, que é diferente de pricing context, etc.')"

Context Map: a ideia de como vai funcionar o domínio

### **Definir a Arquitetura**

Falar de tecnologia, divisões em camadas e modelagem na forma técnica.

Definir como vão funcionar os subdomínios / contextos.

### **Modelagem Tática**

#### **Aggregate Object**

Uma entidade que é a raiz agregadora de um processo de domínio que envolve mais de uma entidade.

#### **Domain Model**

Uma entidade do domínio, possui estados e comportamentos, lógica de negócio, getters e setters AdHoc, etc.

#### **Value Object**

Um objeto que agrega valor às entidades, não possui identidade e é imutável.

#### **Factory**

Classe responsável por construir adequadamente um objeto / entidade.

#### **Domain Service**

Serviço do domínio que atende partes do negócio que não se encaixam em entidades específicas, trabalha com diversas entidades, realiza persistência através de repositórios e etc.

#### **Application Service**

Serviço de aplicação que orquestra ações disparadas pela camada de apresentação e fornece DTOs para comunicação entre as demais camadas e para o consumo da camada de apresentação.

#### **Repository**

Uma classe que realiza a persistência das entidades se comunicando diretamente com o meio de acesso aos dados, é utilizado apenas um repositório por agragação.

#### **External Service**

Serviço externo que realiza a consulta/persistência de informações por meios diversos.

---

"Processo do Domain Driven Design é para que você possa ter essa entrega (aplicação funcionando), não é apenas para *'simplesmente criar camadas de aplicação, domínio e pronto'*. O DDD é você pensar no negócio do começo ao fim. Fazer as perguntas certas, extrair a linguagem ubíqua, depois fazer a modelagem estratégica, para depois pensar na arquitetura, para depois pensar na modelagem tática, se você não seguir esses passos você provavelmente vai errar!"

---

## DRY

Don't Repeat Yourself

## KISS

Keep It Simple, Stupid

## YAGNI

You Ain't Gonna Need It

---

## Leituras Recomendadas

- Clean Code - *Robert C. Martin*
- Clean Coder - *Robert C. Martin*
- Clean Architecture - *Robert C. Martin*
- Patterns of Enterprise Application Architecture - *Martin Fowler*
- Computer Science - *Robert Sedgewick Kevin Wayne*
- Domain-Driven Design - *Eric Evans*
- Implementing Domain Driven Design - *Vaugh Vernon*
- Domain-Driven Design Distilled - *Vaughn Vernon*

---

## Links

[01 - TOGAF - Framework de Arquitetura](https://www.opengroup.org/togaf)

[02 - ISO 42010:2011](https://www.iso.org/standard/50508.html)

[03 - MS Architect Journal](https://docs.microsoft.com/en-us/previous-versions/cc505968(v=msdn.10))

[04 - IASA - Architects Association](https://iasaglobal.org/)

[05 - Zachman - Enterprise Architecture](https://www.zachman.com/)

[06 - BPMN - Business Process Model and Notation](http://www.bpmn.org/)

[07 - Catalogo Web de Design Patterns](https://www.dofactory.com/net/design-patterns)

---

---

---
