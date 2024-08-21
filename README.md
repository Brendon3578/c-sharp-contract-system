# Contract System

Este projeto em C# .NET foi criado para estudar a aplicação de **enumerações (enums)** e **composição de objetos** em um sistema de contratos de trabalho.

## 💻 Descrição

O sistema gerencia trabalhadores, seus contratos de trabalho por hora, e calcula a renda mensal baseada no salário base e nos contratos firmados. Ele utiliza enums para definir o nível do trabalhador e composição para associar contratos a um trabalhador.

## 🔮 Funcionalidades

- **Cadastro de Trabalhadores**: Inclui nome, nível (Junior, MidLevel, Senior) e salário base.
- **Gerenciamento de Contratos**: Permite adicionar ou remover contratos de trabalho por hora associados a um trabalhador.
- **Cálculo de Renda Mensal**: Com base nos contratos firmados e no salário base, o sistema calcula a renda do trabalhador para um mês e ano específicos.

## 📁 Estrutura do Código

- **Classe `Worker`**: Representa o trabalhador, incluindo seu nome, nível (definido pelo enum `WorkerLevel`), salário base, departamento e a lista de contratos.
- **Classe `HourContract`**: Representa um contrato de trabalho por hora, com data, valor por hora e duração em horas. Também fornece o método `TotalValue()` para calcular o valor total do contrato.
- **Classe `Department`**: Representa o departamento ao qual o trabalhador está associado.
- **Enum `WorkerLevel`**: Define os níveis possíveis de um trabalhador (Junior, MidLevel, Senior).

## 🎈 Exemplo de Uso

Ao rodar a aplicação, o usuário deve inserir o nome do departamento, os dados do trabalhador, e os contratos de trabalho. Em seguida, pode-se calcular a renda mensal do trabalhador para um mês e ano específicos, levando em consideração o salário base e os valores dos contratos.

## ✨ Exemplo de Uso

- **C#**
- **.NET 8.0**

---

<h3 align="center">
    Feito com ☕ por <a href="https://github.com/Brendon3578"> Brendon Gomes</a>
</h3>
