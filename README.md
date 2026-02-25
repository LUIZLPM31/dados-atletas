# Projeto de Certificação 2 - Dados dos Atletas

## 🚀 Sobre o Projeto
Uma aplicação em JavaScript que utiliza **Programação Orientada a Objetos** para gerenciar informações de atletas. A classe principal encapsula atributos como peso, altura e notas, automatizando cálculos de categorias esportivas, IMC e médias de desempenho.

## ⚙️ Funcionalidades
- **Cálculo de Categoria**: Define a categoria (Infantil a Adulto) com base na idade.
- **Cálculo de IMC**: Calcula o Índice de Massa Corporal.
- **Média Útil**: Calcula a média das notas descartando a maior e a menor pontuação.

## 🛠️ Como usar
Basta instanciar a classe `Atleta` passando os parâmetros necessários:
```javascript
const atleta = new Atleta("Nome", idade, peso, altura, [notas]);
