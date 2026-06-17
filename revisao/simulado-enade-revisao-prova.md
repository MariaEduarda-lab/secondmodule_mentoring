# Simulado ENADE - Revisão de Prova

**Conteúdos:** Banco de Dados, SQL, MVC, Service/Repository, Testes, RF/RNF/RTM, UML e implantação.  
**Nível:** médio a um pouco mais difícil.  
**Total:** 30 questões.

## Orientações

Nas questões de **asserção-razão**, assinale:

A. As duas asserções são verdadeiras, e a segunda justifica corretamente a primeira.  
B. As duas asserções são verdadeiras, mas a segunda não justifica corretamente a primeira.  
C. A primeira asserção é verdadeira, e a segunda é falsa.  
D. A primeira asserção é falsa, e a segunda é verdadeira.  
E. As duas asserções são falsas.

Nas questões de **somatória**, some os valores das afirmativas corretas.

---

## Parte 1 - Asserção-Razão

### Questão 1

Em uma aplicação organizada em Controller, Service e Repository, um teste unitário de `PedidoService` deve substituir o `PedidoRepository` por um mock.

**PORQUE**

O objetivo do teste unitário do Service é verificar a regra de negócio de forma isolada, sem depender de consultas SQL reais ou do estado do banco de dados.

Assinale a alternativa correta.

A. As duas asserções são verdadeiras, e a segunda justifica corretamente a primeira.  
B. As duas asserções são verdadeiras, mas a segunda não justifica corretamente a primeira.  
C. A primeira asserção é verdadeira, e a segunda é falsa.  
D. A primeira asserção é falsa, e a segunda é verdadeira.  
E. As duas asserções são falsas.

### Questão 2

Em um teste de Repository, o banco de dados deve ser mockado para evitar que o teste dependa de infraestrutura.

**PORQUE**

O objetivo principal de um teste de Repository é validar se o SQL real, os mapeamentos e as constraints funcionam contra um banco real ou efêmero.

Assinale a alternativa correta.

A. As duas asserções são verdadeiras, e a segunda justifica corretamente a primeira.  
B. As duas asserções são verdadeiras, mas a segunda não justifica corretamente a primeira.  
C. A primeira asserção é verdadeira, e a segunda é falsa.  
D. A primeira asserção é falsa, e a segunda é verdadeira.  
E. As duas asserções são falsas.

### Questão 3

O método HTTP `GET` deve ser usado para recuperar dados e não deve alterar o estado do servidor.

**PORQUE**

Uma operação idempotente produz, em termos de resultado final no servidor, o mesmo efeito quando executada uma ou várias vezes.

Assinale a alternativa correta.

A. As duas asserções são verdadeiras, e a segunda justifica corretamente a primeira.  
B. As duas asserções são verdadeiras, mas a segunda não justifica corretamente a primeira.  
C. A primeira asserção é verdadeira, e a segunda é falsa.  
D. A primeira asserção é falsa, e a segunda é verdadeira.  
E. As duas asserções são falsas.

### Questão 4

Uma API deve retornar `403 Forbidden` quando o usuário não enviou token de autenticação.

**PORQUE**

O status `403 Forbidden` indica que o usuário não está autenticado no sistema.

Assinale a alternativa correta.

A. As duas asserções são verdadeiras, e a segunda justifica corretamente a primeira.  
B. As duas asserções são verdadeiras, mas a segunda não justifica corretamente a primeira.  
C. A primeira asserção é verdadeira, e a segunda é falsa.  
D. A primeira asserção é falsa, e a segunda é verdadeira.  
E. As duas asserções são falsas.

### Questão 5

Um relacionamento N:M no MER deve ser transformado em uma tabela associativa no modelo físico.

**PORQUE**

Em bancos relacionais, uma tabela associativa permite representar a combinação entre as chaves das duas entidades e ainda armazenar atributos próprios da relação.

Assinale a alternativa correta.

A. As duas asserções são verdadeiras, e a segunda justifica corretamente a primeira.  
B. As duas asserções são verdadeiras, mas a segunda não justifica corretamente a primeira.  
C. A primeira asserção é verdadeira, e a segunda é falsa.  
D. A primeira asserção é falsa, e a segunda é verdadeira.  
E. As duas asserções são falsas.

### Questão 6

O requisito "o sistema deve ser rápido" é um RNF adequado para documentação de projeto.

**PORQUE**

Requisitos não funcionais devem, sempre que possível, ser mensuráveis para permitir validação objetiva.

Assinale a alternativa correta.

A. As duas asserções são verdadeiras, e a segunda justifica corretamente a primeira.  
B. As duas asserções são verdadeiras, mas a segunda não justifica corretamente a primeira.  
C. A primeira asserção é verdadeira, e a segunda é falsa.  
D. A primeira asserção é falsa, e a segunda é verdadeira.  
E. As duas asserções são falsas.

### Questão 7

Em uma arquitetura com Controller, Service e Repository, o Controller não deve conter comandos SQL diretamente.

**PORQUE**

O Controller deve receber a requisição, realizar validações simples, delegar o fluxo ao Service e montar a resposta.

Assinale a alternativa correta.

A. As duas asserções são verdadeiras, e a segunda justifica corretamente a primeira.  
B. As duas asserções são verdadeiras, mas a segunda não justifica corretamente a primeira.  
C. A primeira asserção é verdadeira, e a segunda é falsa.  
D. A primeira asserção é falsa, e a segunda é verdadeira.  
E. As duas asserções são falsas.

### Questão 8

Um diagrama de classes de domínio deve conter, prioritariamente, classes como `PedidoController`, `PedidoService` e `PedidoRepository`.

**PORQUE**

Diagramas de classes de domínio representam conceitos do negócio, atributos e associações, evitando detalhes de framework e de camadas técnicas.

Assinale a alternativa correta.

A. As duas asserções são verdadeiras, e a segunda justifica corretamente a primeira.  
B. As duas asserções são verdadeiras, mas a segunda não justifica corretamente a primeira.  
C. A primeira asserção é verdadeira, e a segunda é falsa.  
D. A primeira asserção é falsa, e a segunda é verdadeira.  
E. As duas asserções são falsas.

### Questão 9

Em um diagrama de sequência, o fragmento `alt` é adequado para representar caminhos alternativos, como pagamento aprovado e pagamento recusado.

**PORQUE**

O diagrama de sequência representa interações ao longo do tempo, com participantes, mensagens, retornos e possíveis condições de fluxo.

Assinale a alternativa correta.

A. As duas asserções são verdadeiras, e a segunda justifica corretamente a primeira.  
B. As duas asserções são verdadeiras, mas a segunda não justifica corretamente a primeira.  
C. A primeira asserção é verdadeira, e a segunda é falsa.  
D. A primeira asserção é falsa, e a segunda é verdadeira.  
E. As duas asserções são falsas.

### Questão 10

Um diagrama de implantação deve mostrar onde os artefatos do sistema rodam e como os nós se comunicam.

**PORQUE**

Diagramas de implantação representam exclusivamente classes do domínio, como `Cliente`, `Pedido` e `Produto`.

Assinale a alternativa correta.

A. As duas asserções são verdadeiras, e a segunda justifica corretamente a primeira.  
B. As duas asserções são verdadeiras, mas a segunda não justifica corretamente a primeira.  
C. A primeira asserção é verdadeira, e a segunda é falsa.  
D. A primeira asserção é falsa, e a segunda é verdadeira.  
E. As duas asserções são falsas.

### Questão 11

Um `LEFT JOIN` retorna todos os registros da tabela à esquerda, mesmo quando não há correspondência na tabela à direita.

**PORQUE**

Quando não há correspondência à direita, as colunas da tabela direita aparecem com valor `NULL`.

Assinale a alternativa correta.

A. As duas asserções são verdadeiras, e a segunda justifica corretamente a primeira.  
B. As duas asserções são verdadeiras, mas a segunda não justifica corretamente a primeira.  
C. A primeira asserção é verdadeira, e a segunda é falsa.  
D. A primeira asserção é falsa, e a segunda é verdadeira.  
E. As duas asserções são falsas.

### Questão 12

Migrations são arquivos versionados que descrevem alterações no schema do banco de dados.

**PORQUE**

Elas permitem que ambientes diferentes apliquem as alterações de estrutura em uma ordem controlada e reprodutível.

Assinale a alternativa correta.

A. As duas asserções são verdadeiras, e a segunda justifica corretamente a primeira.  
B. As duas asserções são verdadeiras, mas a segunda não justifica corretamente a primeira.  
C. A primeira asserção é verdadeira, e a segunda é falsa.  
D. A primeira asserção é falsa, e a segunda é verdadeira.  
E. As duas asserções são falsas.

### Questão 13

A RTM ajuda a verificar se cada requisito possui origem, implementação e evidência de validação.

**PORQUE**

Uma matriz de rastreabilidade conecta necessidades, requisitos, regras, artefatos implementados e evidências, reduzindo o risco de requisitos esquecidos.

Assinale a alternativa correta.

A. As duas asserções são verdadeiras, e a segunda justifica corretamente a primeira.  
B. As duas asserções são verdadeiras, mas a segunda não justifica corretamente a primeira.  
C. A primeira asserção é verdadeira, e a segunda é falsa.  
D. A primeira asserção é falsa, e a segunda é verdadeira.  
E. As duas asserções são falsas.

### Questão 14

O Model de uma aplicação Express deve importar `req` e `res` para conseguir representar corretamente os dados do domínio.

**PORQUE**

O Model representa dados e conceitos principais do domínio, enquanto detalhes de HTTP devem permanecer no Controller.

Assinale a alternativa correta.

A. As duas asserções são verdadeiras, e a segunda justifica corretamente a primeira.  
B. As duas asserções são verdadeiras, mas a segunda não justifica corretamente a primeira.  
C. A primeira asserção é verdadeira, e a segunda é falsa.  
D. A primeira asserção é falsa, e a segunda é verdadeira.  
E. As duas asserções são falsas.

---

## Parte 2 - Somatória de Asserções

### Questão 15

Sobre banco de dados, MER, DER e modelo físico, analise as afirmativas:

I. O MER descreve entidades, atributos, relacionamentos e cardinalidades sem depender de um SGBD específico. **(1)**  
II. A FK garante que um valor referenciado exista na tabela relacionada, contribuindo para a integridade referencial. **(2)**  
III. Em um DER físico, uma relação N:M pode ser implementada diretamente por uma coluna multivalorada em uma das tabelas. **(4)**  
IV. Uma entidade fraca depende de uma entidade forte para existir ou ser identificada adequadamente. **(8)**  
V. `CHECK`, `UNIQUE` e `NOT NULL` são exemplos de constraints que restringem valores aceitos no banco. **(16)**

Qual é a soma das afirmativas corretas?

### Questão 16

Sobre testes automatizados com Jest e arquitetura em camadas, analise as afirmativas:

I. A etapa Arrange prepara dados, mocks e estado inicial do teste. **(1)**  
II. Em teste unitário de Service, é adequado mockar o Repository. **(2)**  
III. Em teste de Repository, o ideal é mockar o banco, pois o SQL já foi validado pelo Service. **(4)**  
IV. `beforeEach` pode ser usado para limpar o banco ou reiniciar mocks antes de cada teste. **(8)**  
V. Testes E2E costumam ser a base da pirâmide por serem mais rápidos e baratos que os unitários. **(16)**

Qual é a soma das afirmativas corretas?

### Questão 17

Sobre APIs REST, MVC e UML, analise as afirmativas:

I. `POST` é normalmente usado para criar recursos e não é considerado idempotente. **(1)**  
II. `401 Unauthorized` é mais adequado que `403 Forbidden` quando não há autenticação válida. **(2)**  
III. O Controller deve executar SQL diretamente para reduzir a quantidade de camadas. **(4)**  
IV. Diagrama de sequência é adequado para representar chamadas entre Cliente, Controller, Service, Repository e serviços externos ao longo do tempo. **(8)**  
V. Diagrama de implantação mostra nós, artefatos implantados e canais de comunicação. **(16)**

Qual é a soma das afirmativas corretas?

---

## Parte 3 - Múltipla Escolha

### Questão 18

Uma equipe está modelando um sistema em que alunos podem cursar várias disciplinas, e cada disciplina pode ter vários alunos. Além disso, é necessário guardar a data da matrícula e a nota final de cada aluno em cada disciplina.

Qual alternativa representa a melhor solução no modelo físico?

A. Adicionar uma coluna `disciplinas` na tabela `aluno` contendo uma lista separada por vírgulas.  
B. Adicionar uma coluna `alunos` na tabela `disciplina` contendo JSON com os alunos matriculados.  
C. Criar uma tabela `matricula` com FKs para `aluno` e `disciplina`, além de `data_matricula` e `nota_final`.  
D. Criar apenas uma FK `disciplina_id` em `aluno`, pois todo relacionamento N:M pode virar 1:N.  
E. Unificar `aluno` e `disciplina` em uma única tabela para evitar relacionamento.

### Questão 19

Considere o seguinte requisito: "Listar todos os clientes, inclusive aqueles que ainda não fizeram pedidos, mostrando a quantidade de pedidos de cada um".

Qual consulta SQL é mais adequada?

A.

```sql
SELECT c.nome, COUNT(p.id)
FROM cliente c
INNER JOIN pedido p ON p.cliente_id = c.id
GROUP BY c.id;
```

B.

```sql
SELECT c.nome, COUNT(p.id)
FROM cliente c
LEFT JOIN pedido p ON p.cliente_id = c.id
GROUP BY c.id;
```

C.

```sql
SELECT c.nome, COUNT(p.id)
FROM pedido p
LEFT JOIN cliente c ON c.id = p.cliente_id
GROUP BY c.id;
```

D.

```sql
SELECT c.nome, p.id
FROM cliente c
RIGHT JOIN pedido p ON p.cliente_id = c.id
WHERE p.id IS NULL;
```

E.

```sql
SELECT c.nome, COUNT(*)
FROM cliente c
WHERE c.id = pedido.cliente_id;
```

### Questão 20

Em uma API REST, um usuário autenticado tenta excluir um pedido que pertence a outro usuário. A autenticação é válida, mas a regra de autorização impede a ação.

Qual status HTTP é mais adequado?

A. 200 OK  
B. 201 Created  
C. 400 Bad Request  
D. 401 Unauthorized  
E. 403 Forbidden

### Questão 21

Em uma aplicação com camadas `Controller`, `Service`, `Repository`, `Model` e `View`, qual alternativa descreve corretamente a responsabilidade do `Service`?

A. Receber diretamente `req` e `res`, escrever SQL e devolver HTML.  
B. Representar apenas a estrutura visual que será renderizada para o usuário.  
C. Concentrar regras de negócio e orquestrar chamadas para outras camadas.  
D. Armazenar fisicamente os dados em tabelas do banco.  
E. Ser a única camada autorizada a conhecer rotas HTTP.

### Questão 22

Um requisito foi escrito da seguinte forma: "O sistema deve processar 95% das requisições em até 500 ms sob carga de 200 usuários simultâneos".

Esse requisito é melhor classificado como:

A. Requisito funcional, pois descreve uma tela do sistema.  
B. Requisito funcional, pois define uma regra de autorização.  
C. Requisito não funcional, pois define desempenho de forma mensurável.  
D. Regra de negócio, pois determina o estoque mínimo de um produto.  
E. Caso de uso, pois descreve todos os passos de interação do usuário.

### Questão 23

Uma equipe deseja documentar o fluxo "criar pedido", incluindo os participantes Cliente, Controller, Service, Repository e Gateway de Pagamento, bem como os caminhos "pagamento aprovado" e "pagamento recusado".

Qual diagrama UML é mais adequado?

A. Diagrama de implantação, pois mostra servidores e containers.  
B. Diagrama de sequência, pois mostra interações ao longo do tempo e pode usar fragmento `alt`.  
C. Diagrama de classes de domínio, pois mostra apenas atributos das entidades.  
D. DER, pois mostra tabelas, PKs e FKs.  
E. RTM, pois substitui qualquer diagrama UML.

### Questão 24

Em um diagrama de classes de domínio para um sistema de pedidos, qual conjunto de classes é mais coerente?

A. `PedidoController`, `PedidoService`, `PedidoRepository`, `Database`.  
B. `Router`, `MiddlewareAuth`, `Logger`, `HttpResponse`.  
C. `Cliente`, `Pedido`, `ItemPedido`, `Produto`.  
D. `Nginx`, `API Container`, `PostgreSQL`, `Redis`.  
E. `GET /pedidos`, `POST /pedidos`, `PATCH /pedidos/:id`.

### Questão 25

Uma migration cria a tabela abaixo:

```sql
CREATE TABLE usuario (
  id INTEGER PRIMARY KEY,
  email TEXT NOT NULL UNIQUE,
  perfil TEXT NOT NULL CHECK (perfil IN ('admin', 'user'))
);
```

Qual alternativa está correta?

A. `email` pode ser nulo, desde que não se repita.  
B. `perfil` aceita qualquer texto, pois `CHECK` é apenas documentação.  
C. `id` identifica unicamente cada linha da tabela.  
D. `UNIQUE` em `email` obriga que todos os usuários tenham o mesmo e-mail.  
E. `PRIMARY KEY` permite valores duplicados quando a tabela é pequena.

### Questão 26

Considere a pirâmide de testes apresentada em aula. Qual alternativa representa melhor sua ideia?

A. Muitos testes E2E, poucos testes unitários e nenhum teste de integração.  
B. Muitos testes unitários, alguns testes de integração e poucos testes E2E.  
C. Apenas testes manuais, pois testes automatizados são frágeis.  
D. Testes unitários devem acessar banco real e serviços externos para serem confiáveis.  
E. Testes E2E são sempre mais baratos e rápidos que testes unitários.

### Questão 27

Uma RTM bem construída deve relacionar:

A. Apenas os nomes das tabelas e seus tipos de dados.  
B. Apenas os endpoints REST, sem necessidade de requisitos.  
C. Necessidades, requisitos, regras, implementação, evidências e status.  
D. Somente os casos de teste automatizados aprovados.  
E. Apenas diagramas UML, pois eles substituem requisitos textuais.

---

## Parte 4 - Questões Abertas

### Questão 28 - Testes

Você recebeu a seguinte regra de negócio:

"Um pedido só pode ser criado se todos os itens solicitados possuírem estoque suficiente. Caso algum produto não tenha estoque, o sistema deve rejeitar a criação do pedido."

Considerando uma arquitetura com `PedidoController`, `PedidoService` e `PedidoRepository`, elabore uma estratégia de testes para essa funcionalidade.

Sua resposta deve conter:

1. Pelo menos **dois testes unitários** do `PedidoService`, indicando o que deve ser mockado.
2. Pelo menos **um teste de integração**, indicando se o banco deve ou não ser mockado.
3. Uso adequado da estrutura AAA: Arrange, Act e Assert.
4. Indicação de hooks do Jest que poderiam ser usados, como `beforeEach` ou `afterAll`.
5. Justificativa sobre por que nem tudo deve ser testado apenas por E2E.

### Questão 29 - Modelagem do Zero

Uma escola deseja construir um sistema web para gerenciar turmas, alunos, professores, disciplinas e avaliações.

Regras iniciais:

- Um aluno pode se matricular em várias turmas.
- Uma turma possui uma disciplina e um professor responsável.
- Uma turma pode ter várias avaliações.
- Cada aluno recebe uma nota em cada avaliação da turma em que está matriculado.
- A escola precisa consultar boletins por aluno e por turma.
- Apenas coordenadores podem cadastrar professores e disciplinas.
- Professores podem lançar notas apenas das turmas pelas quais são responsáveis.

Modele a solução **do zero**. Sua resposta deve conter:

1. Pelo menos **5 requisitos funcionais**.
2. Pelo menos **3 requisitos não funcionais mensuráveis**.
3. Pelo menos **3 regras de negócio**.
4. Um **MER ou DER textual**, indicando entidades, atributos principais, PKs, FKs e cardinalidades.
5. A resolução de pelo menos um relacionamento N:M com tabela associativa.
6. Um **diagrama de classes de domínio textual** com classes, atributos e relações.
7. Um **diagrama de sequência textual** para o fluxo "professor lança nota".
8. Uma proposta resumida de **RTM** com pelo menos 3 linhas.

### Questão 30 - API, SQL e Camadas

Considere que você deve implementar o endpoint `POST /pedidos` em uma API REST.

O endpoint recebe:

```json
{
  "clienteId": 10,
  "itens": [
    { "produtoId": 3, "quantidade": 2 },
    { "produtoId": 8, "quantidade": 1 }
  ]
}
```

Elabore uma solução conceitual para esse endpoint.

Sua resposta deve conter:

1. Responsabilidade de cada camada: View/cliente HTTP, Controller, Service, Repository e Model.
2. Pelo menos **4 validações** ou regras que devem ocorrer antes de salvar o pedido.
3. Um esboço de tabelas necessárias com PKs, FKs e constraints.
4. Um exemplo de consulta SQL com `JOIN` para listar pedidos com nome do cliente e total.
5. Status HTTP adequados para sucesso, erro de payload, falta de autenticação, falta de permissão e regra de negócio violada.

---

# Gabarito

## Asserção-Razão

1. A  
2. D  
3. B  
4. E  
5. A  
6. D  
7. A  
8. D  
9. A  
10. C  
11. A  
12. A  
13. A  
14. D

## Somatória

15. **27**  
Corretas: I, II, IV e V = 1 + 2 + 8 + 16.

16. **11**  
Corretas: I, II e IV = 1 + 2 + 8.

17. **27**  
Corretas: I, II, IV e V = 1 + 2 + 8 + 16.

## Múltipla Escolha

18. C  
19. B  
20. E  
21. C  
22. C  
23. B  
24. C  
25. C  
26. B  
27. C

## Critérios Esperados nas Abertas

### Critérios da Aberta 28

Uma boa resposta deve diferenciar teste unitário, integração e E2E; mockar o Repository em testes de Service; não mockar o banco no teste de Repository/integração; usar AAA; prever cenários de sucesso e de estoque insuficiente; e justificar por que E2E deve ser usado em menor quantidade.

### Critérios da Aberta 29

Uma boa resposta deve propor RFs, RNFs mensuráveis e regras de negócio coerentes; identificar entidades como Aluno, Professor, Disciplina, Turma, Matricula, Avaliacao e Nota; resolver N:M com tabela associativa; indicar PKs/FKs/cardinalidades; e apresentar diagramas textuais consistentes com o domínio, não com classes técnicas.

### Critérios da Aberta 30

Uma boa resposta deve separar responsabilidades entre Controller, Service e Repository; validar cliente, produtos, quantidades, estoque e permissão; propor tabelas como cliente, produto, pedido e item_pedido; usar JOIN corretamente; e associar status como 201, 400, 401, 403 e 422 às situações adequadas.
