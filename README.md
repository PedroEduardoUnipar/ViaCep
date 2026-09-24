# ViaCEP

Projeto acadêmico em Java para consulta de endereços a partir de um CEP utilizando a API pública ViaCEP.

## Objetivo

Praticar consumo de API HTTP, leitura de resposta, modelagem de classes e organização de um projeto Maven.

## Tecnologias

- Java
- Maven
- API ViaCEP
- Lombok
- HTTP

## Estrutura

- `src/main/java/br/unipar/backend/Main.java` — realiza a consulta do CEP informado pelo usuário
- `src/main/java/br/unipar/backend/model/Endereco.java` — representa os dados de endereço
- `pom.xml` — configuração e dependências Maven
- `.gitignore` — evita versionamento de arquivos gerados e configurações locais

## Funcionamento

A aplicação solicita um CEP, realiza uma requisição para a API ViaCEP e utiliza os dados retornados para trabalhar com informações de endereço.

Endpoint utilizado:

```text
https://viacep.com.br/ws/{CEP}/json/
```

## Como executar

Com Java e Maven configurados:

```bash
mvn clean compile
mvn exec:java
```

Também é possível executar a classe `Main` diretamente pela IDE.

## Contexto acadêmico

O projeto foi desenvolvido durante os estudos de back-end e posteriormente separado em um repositório próprio para facilitar a visualização e organização no GitHub.
