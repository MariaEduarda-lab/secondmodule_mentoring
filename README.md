# Monitoria: Desenvolvimento Web - 2o Modulo

Repositorio central da monitoria do segundo modulo, com materiais de apoio para arquitetura em camadas, requisitos, modelagem, banco de dados, WAD e revisao de prova.

O foco e ajudar os estudantes a organizar o raciocinio antes de codar: entender o problema, documentar requisitos, desenhar os fluxos, modelar os dados e implementar respeitando as camadas do projeto.

---

## Como o repositorio esta organizado

```text
.
|-- README.md
|-- assets/
|   `-- mer.png
|-- conteudos/
|   |-- README.md
|   |-- arquitetura-camadas.md
|   |-- fluxo-requisicao-endpoints.md
|   |-- modelagem-software.md
|   |-- requisitos-rnf-uml-rtm.md
|   `-- rtm.md
`-- revisao/
    |-- README.md
    |-- revisao-prova-slides.pdf
    `-- simulado-enade-revisao-prova.md
```

---

## Sumario

1. [Arquitetura MVC](conteudos/arquitetura-camadas.md)
2. [Requisitos Funcionais e Nao Funcionais](conteudos/requisitos-rnf-uml-rtm.md)
3. [Modelagem de Dados e Banco de Dados](conteudos/modelagem-software.md)
4. [Fluxo de Requisicao e Endpoints](conteudos/fluxo-requisicao-endpoints.md)
5. [RTM - Requirements Traceability Matrix](conteudos/rtm.md)

---

## Conteudos principais

### 1. Arquitetura em camadas

Material sobre MVC estendido no contexto de Node.js, Express, TypeScript, PostgreSQL e EJS.

Inclui:

- responsabilidade de cada camada;
- fluxo completo de uma requisicao;
- exemplos de `Route`, `Controller`, `Service`, `Repository`, `Model` e `config/db`;
- boas praticas para evitar SQL no Controller e regra de negocio no Repository.

Arquivo: [conteudos/arquitetura-camadas.md](conteudos/arquitetura-camadas.md)

### 2. Requisitos, RNFs, UML e RTM

Guia para escrever requisitos funcionais e nao funcionais de forma verificavel.

Inclui:

- exemplos de RFs e RNFs;
- criterio SMART para RNFs;
- diagramas de sequencia UML;
- tabela de rastreabilidade RF -> RNF -> Diagrama;
- checklist para entrega de documentacao.

Arquivo: [conteudos/requisitos-rnf-uml-rtm.md](conteudos/requisitos-rnf-uml-rtm.md)

### 3. Modelagem de software e banco de dados

Material comparando diferentes artefatos de modelagem.

Inclui:

- diagrama de classes;
- diagrama de sequencia;
- MER;
- DER;
- modelo relacional;
- leitura integrada de um fluxo completo.

Arquivo: [conteudos/modelagem-software.md](conteudos/modelagem-software.md)

### 4. Fluxo de requisicao e endpoints

Material para entender como a informacao passa do cliente ate o banco de dados e volta como resposta.

Inclui:

- fluxo HTTP completo;
- conceito de endpoint;
- metodos `GET`, `POST`, `PUT`, `PATCH` e `DELETE`;
- exemplos de documentacao de endpoint;
- status HTTP comuns;
- checklist para documentar rotas.

Arquivo: [conteudos/fluxo-requisicao-endpoints.md](conteudos/fluxo-requisicao-endpoints.md)

### 5. RTM - Requirements Traceability Matrix

Material para montar a matriz de rastreabilidade de requisitos.

Inclui:

- objetivo da RTM;
- campos recomendados;
- exemplo preenchido;
- relacao entre RF, RNF, implementacao e testes;
- template para copiar;
- checklist de validacao.

Arquivo: [conteudos/rtm.md](conteudos/rtm.md)

---

## Revisao de prova

Esta pasta concentra os materiais para estudar perto da avaliacao.

- [revisao-prova-slides.pdf](revisao/revisao-prova-slides.pdf): PDF com os slides de revisao da prova.
- [simulado-enade-revisao-prova.md](revisao/simulado-enade-revisao-prova.md): simulado com 30 questoes, gabarito e criterios esperados nas questoes abertas.

Sugestao de uso:

1. Leia o PDF de revisao para relembrar os temas.
2. Resolva o simulado sem consultar o gabarito.
3. Corrija pelas respostas ao final do arquivo.
4. Volte aos conteudos principais nos temas em que errou.

---

## Checklist do que nao pode faltar no WAD

- Objetivo do projeto e problema que ele resolve.
- Requisitos funcionais numerados.
- Requisitos nao funcionais mensuraveis e verificaveis.
- Regras de negocio separadas dos requisitos.
- MER ou DER com entidades, relacionamentos e cardinalidades.
- Modelo relacional com PKs, FKs e constraints.
- Diagramas de sequencia dos principais fluxos.
- Lista de endpoints com metodo HTTP, rota, entrada, saida e status esperado.
- RTM conectando requisito, implementacao, teste/evidencia e status.
- Evidencias de teste ou validacao.

---

## Dicas para o modulo

- Antes de codar, entenda o fluxo do usuario e escreva os requisitos.
- Use nomes claros para rotas, variaveis, tabelas e arquivos.
- Separe responsabilidade: Controller responde HTTP, Service decide regra, Repository acessa banco.
- Escreva RNFs com criterio de verificacao, nao apenas como frases genericas.
- Sempre confira se o diagrama combina com o codigo que sera implementado.

---

## Videos do Afonso que podem ajudar

- [Setup de Maquina com Node + VSCode e Supabase](https://youtu.be/KFaPPwKmNhQ?si=qMvrIrOub7a76GiP)
- [Como conectar nossa arquitetura com banco de dados](https://youtu.be/_iUuW_JTzcc?si=Ehz79EJy0bhHOHi8)
- [Conectar um Banco de Dados na Nuvem com DBeaver](https://youtu.be/6NlYK5UU99c?si=pv7joCtEyy-vS_x4)
- [Aula de Rotas e Controllers](https://www.youtube.com/live/uhrL3Lm0Et4?si=5sBwUC3sLrclZ21s)
- [GitFlow Modulo 2](https://www.youtube.com/live/-nbwtsIwbpg?si=RfqgS63pe8CEQgCS)
- [Tutorial Completo - Node + EJS](https://www.youtube.com/live/JLS8XDgJzNY?si=XCRyGHhXQwJIzryT)
- [Modelando um Banco de Dados com MermaidJS](https://www.youtube.com/live/W6Ik2ZnBkDg?si=LNVM277W2pqUZTHg)
- [Criando um Projeto NodeJS](https://www.youtube.com/live/1X_3RN26viY?si=BSNZtSOdrHUp1zp7)

---

## Duvidas

Procure a monitoria durante os horarios de atendimento ou abra uma Issue no repositorio.
