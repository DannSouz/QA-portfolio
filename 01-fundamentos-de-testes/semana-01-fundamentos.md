# Semana 01 — Fundamentos de Testes

## Erro, defeito e falha

### Erro
Uma ação humana incorreta que pode resultar na introdução de um defeito.

### Defeito
Uma imperfeição existente em um componente, sistema ou outro produto de trabalho.

### Falha
Comportamento incorreto observado quando um sistema ou componente é executado.

### Exemplo

**Requisito:**  
O sistema deve permitir o cadastro de usuários com 18 anos ou mais.

**Implementação:**

`idade > 18`

**Análise:**

- Erro: interpretação ou implementação incorreta do limite estabelecido no requisito.
- Defeito: utilização de `> 18` em vez de `>= 18`.
- Falha: usuário com exatamente 18 anos tem seu cadastro recusado.

---

## Teste e debugging

### Teste

Atividade utilizada para avaliar a qualidade e revelar falhas no software.

### Debugging

Atividade de investigação da causa de um problema, envolvendo a localização e correção do defeito.

Teste e debugging são atividades diferentes.

---

## Verificação e validação

### Verificação

Avalia se o produto está de acordo com os requisitos e especificações definidos.

Pergunta principal:

**Estamos construindo o produto corretamente?**

### Validação

Avalia se o produto atende às necessidades dos usuários.

Pergunta principal:

**Estamos construindo o produto certo?**

## 7 Princípios de Teste

### 1. Testes mostram a presença de defeitos
Os testes podem revelar defeitos, mas não conseguem provar que o sistema está completamente livre deles.

### 2. Testes exaustivos são impossíveis
Testar todas as combinações e possibilidades geralmente não é viável, sendo necessário priorizar os testes.

### 3. Testar cedo economiza tempo e dinheiro
Defeitos identificados nas etapas iniciais tendem a gerar menos retrabalho e custos.

### 4. Defeitos se agrupam
Uma quantidade relativamente pequena de componentes pode concentrar grande parte dos defeitos encontrados.

### 5. Paradoxo do pesticida
Executar repetidamente os mesmos testes pode diminuir sua capacidade de encontrar novos defeitos.

### 6. Testes dependem do contexto
A estratégia e os tipos de testes utilizados dependem do sistema, dos riscos e dos objetivos.

### 7. Ausência de defeitos é uma falácia
Mesmo um sistema com poucos ou nenhum defeito conhecido pode não atender às necessidades dos usuários.


XOXO
