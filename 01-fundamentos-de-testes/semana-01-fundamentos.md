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
