# 🚀 Monitoria: Desenvolvimento Web - 2º Módulo

Bem-vindo ao repositório central da monitoria de **Desenvolvimento Web**! Este espaço foi criado para consolidar os materiais, explicações e guias essenciais para o segundo módulo do primeiro ano.

O foco deste módulo é entender como as aplicações web se estruturam por baixo do "capô", indo além do visual e focando na lógica, organização e documentação.

---

## 📌 Sumário
1. [💡 Dicas para o Módulo](#-dicas-para-o-módulo)
2. [📋 Requisitos Funcionais e Não Funcionais](requisitos.md)
3. [🔄 Fluxo de Requisição e Endpoints](#-fluxo-de-requisição-e-endpoints)
4. [📑 RTM (Requirements Traceability Matrix)](#-rtm-requirements-traceability-matrix)
5. [🏗️ Arquitetura MVC](arquitetura_camadas.md)
6. [📄 Dicas de WAD (Web App Documentation)](#-dicas-de-wad-web-app-documentation)
---

## 💡 Dicas para o Módulo

* **Não pule etapas:** Antes de codar, entenda o problema. A documentação (WAD) salva horas de refatoração.
* **Pratique a lógica:** O back-end exige um pensamento sequencial claro. Use fluxogramas se necessário.
* **Atenção aos nomes:** Use nomes de variáveis e rotas que façam sentido (semântica é tudo!).
* **Consulte a documentação:** Aprender a ler a documentação oficial das linguagens/frameworks é a maior habilidade de um dev.

---

## 📋 Requisitos Funcionais e Não Funcionais

A base de qualquer software de sucesso é saber o que ele deve fazer.

* **Requisitos Funcionais (RF):** Descrevem as funcionalidades e o comportamento do sistema. O que o usuário consegue fazer?
    * *Exemplo:* "O sistema deve permitir que o usuário recupere a senha via e-mail."
* **Requisitos Não Funcionais (RNF):** Descrevem as qualidades e restrições do sistema. Como o sistema deve performar?
    * *Exemplo:* "O sistema deve carregar qualquer página em menos de 2 segundos" ou "As senhas devem ser criptografadas".

---

## 🔄 Fluxo de Requisição e Endpoints

Entender o caminho que a informação percorre é crucial:

1.  **Client (Front-end):** Faz uma requisição (Request) através de uma URL (Endpoint).
2.  **Server (Back-end):** Recebe a requisição, processa a lógica, consulta o banco de dados se necessário.
3.  **Response:** O servidor devolve uma resposta (geralmente um JSON e um Status Code como 200 OK ou 404 Not Found).

**O que é um Endpoint?** É o endereço (ponto de extremidade) onde a API recebe as requisições. Ex: `GET /usuarios/123`.

---

## 📑 RTM (Requirements Traceability Matrix)

A **Matriz de Rastreabilidade de Requisitos** é uma tabela que liga os requisitos do início ao fim do projeto.
Ela serve para garantir que:
* Cada requisito foi de fato desenvolvido.
* Cada funcionalidade no código tem uma razão de existir baseada num requisito.
* Facilitar testes e auditorias.

---

## 🏗️ Arquitetura MVC

O padrão **Model-View-Controller** organiza o código em três camadas:

* **Model (Modelo):** Gerencia os dados e a lógica de negócio (comunicação com o banco de dados).
* **View (Visão):** A interface que o usuário vê (HTML/CSS/JS).
* **Controller (Controlador):** O intermediário. Ele recebe a entrada da View, processa via Model e devolve a resposta para a View.

---

## 📄 Dicas de WAD (Web App Documentation)

Uma boa **Web App Documentation** é o mapa do seu projeto. O que não pode faltar:

1.  **Objetivo do Projeto:** O que ele resolve?
2.  **Diagramas:** Use diagramas de caso de uso ou de classe.
3.  **Dicionário de Dados:** Explique o que cada campo do seu banco de dados faz.
4.  **Wireframes:** Esboços das telas antes de estarem prontas.
5.  **Lista de Endpoints:** Liste as rotas da sua API e o que cada uma espera receber.

---

✉️ **Dúvidas?** Procure o monitor durante os horários de atendimento ou abra uma *Issue* aqui no repositório!