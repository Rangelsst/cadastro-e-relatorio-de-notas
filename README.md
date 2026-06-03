# 📚 Sistema de Notas Escolares

## 📖 Sobre o Projeto

O **Sistema de Notas Escolares** é uma aplicação desenvolvida em Python com o objetivo de realizar o cadastro de alunos, disciplinas, notas e faltas, gerando automaticamente um relatório acadêmico com o resultado final do estudante.

O projeto foi desenvolvido utilizando conceitos fundamentais da programação, como:

* Funções
* Listas
* Dicionários
* Estruturas de repetição (`for` e `while`)
* Estruturas condicionais (`if`, `elif` e `else`)
* Entrada e saída de dados
* Organização e reutilização de código

Além de atender a um cenário educacional simples, o sistema demonstra a capacidade de modelar dados, validar informações fornecidas pelo usuário e gerar resultados com base em regras de negócio.

---

## 🎯 Objetivo

Automatizar o processo de registro e análise do desempenho de estudantes, permitindo:

* Cadastro do aluno;
* Definição do nível de ensino;
* Registro de disciplinas;
* Armazenamento de notas e faltas;
* Cálculo da média geral;
* Cálculo do total de faltas;
* Geração de relatório final;
* Verificação de aprovação ou reprovação.

---

## ⚙️ Funcionalidades

### Cadastro de Dados

O sistema solicita:

* Nome do aluno;
* Nível de ensino (Fundamental II ou Médio);
* Quantidade de disciplinas;
* Nota final de cada disciplina;
* Quantidade de faltas por disciplina.

### Cálculo de Média

A média geral é calculada automaticamente a partir das notas cadastradas.

### Controle de Frequência

O sistema soma todas as faltas registradas para o aluno.

### Relatório Final

Ao final da execução, é exibido um relatório contendo:

* Dados do aluno;
* Disciplinas cadastradas;
* Notas;
* Faltas;
* Média final;
* Total de faltas;
* Situação do estudante.

---

## 📋 Regras de Aprovação

O aluno será considerado aprovado quando:

* Média final maior ou igual a 6,0;
* Frequência mínima de 75%.

Caso uma dessas condições não seja atendida, o sistema indicará a reprovação e o motivo.

---

## 🛠️ Tecnologias Utilizadas

* Python 3
* Terminal/Console

---

## 📂 Estrutura do Projeto

```text
Sistema de Notas
│
├── cadastrar_dados()
├── calcular_notas()
├── calcular_faltas()
├── gerar_relatorio_final()
└── execução principal
```

---

## 🚀 Exemplo de Utilização

### Entrada

```text
Digite o nome do aluno: João Silva

Qual nível de ensino? [Fundamental 2 / Medio]:
Medio

Quantas matérias deseja cadastrar?
3

Disciplina 1
Matemática
Nota: 8.5
Faltas: 2

Disciplina 2
Português
Nota: 7.0
Faltas: 4

Disciplina 3
História
Nota: 6.5
Faltas: 3
```

### Saída

```text
-----==== Relatório Final ====-----

Aluno: João Silva

Nível de escolaridade: Medio

Disciplinas Cadastradas:

Matemática | Nota: 8.5 | Faltas: 2
Português | Nota: 7.0 | Faltas: 4
História | Nota: 6.5 | Faltas: 3

Média Final: 7.33

Total de faltas: 9

Aprovado!

Nota final superior à nota mínima.
Frequência superior a 75%.
```

---

## 💡 Aprendizados Desenvolvidos

Durante o desenvolvimento deste projeto foram aplicados conhecimentos relacionados a:

* Modularização do código através de funções;
* Manipulação de listas e dicionários;
* Validação de entrada de dados;
* Estruturas de decisão;
* Estruturas de repetição;
* Organização lógica de programas em Python.

---

## 👨‍💻 Autor

**Rangel Tulio**

Projeto desenvolvido para fins acadêmicos e de aprendizado em programação Python.
