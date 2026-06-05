# 📍 Buscador de CEP com Java

Aplicação desenvolvida em Java para consulta de endereços a partir de CEPs utilizando a API ViaCEP.

O projeto consome dados de uma API REST, converte o JSON recebido para objetos Java utilizando Gson e gera arquivos JSON contendo os dados consultados.

## 🚀 Tecnologias Utilizadas

* Java 17
* Maven
* Gson
* HttpClient (Java API)
* ViaCEP API
* Git e GitHub

## 📋 Funcionalidades

* Consultar CEP informado pelo usuário
* Consumir dados da API ViaCEP
* Converter JSON para objetos Java
* Exibir informações do endereço no terminal
* Gerar arquivo JSON com os dados retornados

## 📂 Estrutura do Projeto

```text
src
└── main
    └── java
        └── org.example
            ├── Main.java
            ├── ConsultaCep.java
            ├── Endereco.java
            └── GeradorDeArquivo.java
```

## 🔧 Como Executar

### Clonar o repositório

```bash
git clone https://github.com/Wendersonjose/buscador-de-cep-java.git
```

### Entrar na pasta do projeto

```bash
cd buscador-de-cep-java
```

### Executar

Pelo IntelliJ IDEA:

1. Abrir o projeto.
2. Aguardar o Maven baixar as dependências.
3. Executar a classe `Main`.

## 📝 Exemplo de Uso

Entrada:

```text
Digite um número de CEP para consulta:
01001000
```

Saída:

```text
Endereco[
cep=01001-000,
logradouro=Praça da Sé,
localidade=São Paulo,
complemento=lado ímpar,
uf=SP
]
```

Também será criado um arquivo:

```text
01001-000.json
```

contendo os dados retornados pela API.

## 🌐 API Utilizada

ViaCEP

https://viacep.com.br

## 🎯 Objetivos de Aprendizado

Este projeto foi desenvolvido com o objetivo de praticar:

* Consumo de APIs REST
* Programação Orientada a Objetos
* Records em Java
* Tratamento de exceções
* Manipulação de JSON
* Escrita de arquivos
* Gerenciamento de dependências com Maven
* Versionamento com Git e GitHub

## 👨‍💻 Autor

Wenderson José da Silva

* GitHub: https://github.com/Wendersonjose
* LinkedIn: https://www.linkedin.com/in/wenderson-jose
