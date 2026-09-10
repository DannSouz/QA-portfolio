![QA](https://img.shields.io/badge/QA-FF69B4?style=for-the-badge)
![Manual Testing](https://img.shields.io/badge/Manual_Testing-FF8FAB?style=for-the-badge)
![Bug Bank](https://img.shields.io/badge/Bug_Bank-DDA0DD?style=for-the-badge)

# 🎀 Testes de Cadastro — Bug Bank ♡

<div align="center">

🌸 Projeto prático de testes manuais realizado na aplicação **Bug Bank**

✨ Explorando cenários reais, documentando evidências e acompanhando resultados

</div>

---

## 💗 Sobre o projeto

Este projeto foi desenvolvido como uma atividade prática de QA, com foco no formulário de cadastro da aplicação **Bug Bank**.

A proposta foi criar e executar casos de teste com diferentes tipos de cenário, comparar o comportamento esperado com o resultado obtido e registrar as evidências da execução.

Neste projeto, trabalhei com:

- 🌷 cenário positivo
- 🌷 cenário negativo
- 🌷 cenário exploratório
- 🌷 resultado esperado x resultado obtido
- 🌷 evidências de execução
- 🌷 classificação de status PASS e FAIL

O documento completo reúne três casos de teste de cadastro.

---

## 🎀 Casos de teste

### 🌸 CT01 — Cadastro com dados válidos

Objetivo: verificar se o usuário consegue criar uma conta preenchendo corretamente todos os campos obrigatórios.

**Resultado:** ✅ PASS

A conta foi criada com sucesso, o número da conta foi exibido e o saldo inicial de R$ 1.000,00 foi apresentado conforme esperado.

---

### 🌸 CT02 — E-mail obrigatório em branco

Objetivo: verificar se o sistema impede o cadastro quando o campo de e-mail não é preenchido.

**Resultado:** ❌ FAIL

O sistema bloqueou corretamente o cadastro, mas apresentou a mensagem:

> “É campo obrigatório”

enquanto o requisito previa:

> “Email não pode ser vazio”

Por isso, o caso foi marcado como FAIL devido à divergência entre o comportamento esperado e o resultado obtido.
---

### 🌸 CT03 — Cadastro com e-mail em formato inválido

Objetivo: avaliar se o campo de e-mail identifica um formato inválido antes de permitir a criação da conta.

**Resultado:** ✅ PASS

O sistema identificou o formato inválido, bloqueou o envio do formulário e nenhuma conta foi criada. 

---

## 🧪 O que pratiquei

Durante essa atividade, pratiquei:

- criação de casos de teste
- definição de pré-condições
- definição de dados de teste
- escrita de passos de execução
- comparação entre resultado esperado e resultado obtido
- registro de evidências
- análise de comportamento da aplicação
- identificação de divergências em relação ao requisito

---

## 📸 Evidências

As evidências foram registradas durante a execução dos testes e estão incluídas no documento.

Elas mostram:

- dados preenchidos nos campos
- criação de conta
- saldo inicial
- bloqueio de cadastro
- mensagens de validação
- comportamento do formulário

As evidências de execução estão registradas no documento completo, incluindo telas do sistema, resultados obtidos e mensagens de validação.

---

## 📄 Documento completo

🎀 [Clique aqui para visualizar os casos de teste](./casos-de-teste-cadastro-bug-bank.pdf)

---

<div align="center">

🌷 aprendendo na prática, documentando cada etapa e evoluindo um teste de cada vez ♡

</div>
