# Desafio Controle de Fluxo

Este projeto foi desenvolvido como parte do desafio do módulo de Controle de Fluxo no curso da [DIO](https://www.dio.me/). O objetivo é exercitar os conceitos de controle de fluxo em Java, implementando um programa que realiza contagens baseadas em dois números fornecidos pelo usuário.

## Descrição do Desafio

O programa recebe dois números inteiros como entrada e realiza as seguintes operações:

1. **Validação dos números**:
   - Se o primeiro número for maior que o segundo, o programa lança uma exceção customizada chamada `ParametrosInvalidosException` com a mensagem: `"O segundo parâmetro deve ser maior que o primeiro"`.

2. **Contagem e impressão**:
   - Caso os números sejam válidos, o programa calcula a diferença entre eles e imprime no console os números incrementados, um por linha.

### Exemplo de Execução

#### Entrada:
Digite o primeiro número: 12 Digite o segundo número: 15

#### Saída:
Imprimindo o número 13 Imprimindo o número 14 Imprimindo o número 15

#### Entrada Inválida:
Digite o primeiro número: 20 Digite o segundo número: 10

#### Saída:
O segundo parâmetro deve ser maior que o primeiro

---

## Estrutura do Projeto
DesafioControleFluxo/ ├── src/ │ ├── Contador.java # Classe principal que contém a lógica do programa │ ├── ParametrosInvalidosException.java # Classe que define a exceção customizada └── README.md # Documentação do projet

---

## Classes

### 1. `Contador`
Classe principal que contém o método `main` e a lógica para:
- Receber os números do usuário.
- Validar os números.
- Realizar a contagem e imprimir os números incrementados.

### 2. `ParametrosInvalidosException`
Classe que representa uma exceção customizada. É lançada quando o primeiro número é maior que o segundo.

---

## Como Executar o Projeto

### Pré-requisitos
- Java JDK 8 ou superior instalado.
- Um terminal ou IDE para compilar e executar o código.

### Passos para Execução

1. **Clone o repositório ou copie os arquivos para o seu ambiente local.**

2. **Compile os arquivos Java:**
   No terminal, navegue até o diretório `src` e execute:
   ```bash
   javac *.java


## Autor
Desenvolvido por Guilherme Marlon como parte do curso da [DIO](https://www.dio.me/).