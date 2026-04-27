# Bugs Reportados

## 🐞 BUG-001 - Login não autentica com credenciais válidas 

Descrição:
Sistema não autentica usuário com dados válidos.

Pré-condição:
Usuário cadastrado no sistema.

Ambiente:
Sistema Web - Ambiente de Testes

Passos para reproduzir:
1. Acessar página de login
2. Inserir login: usuario@teste.com
3. Inserir senha: 123456
4. Clicar em "Entrar"

Resultado esperado:
Usuário autenticado com sucesso

Resultado atual:
Sistema retorna erro de autenticação

Severidade:
Crítica

Prioridade:
Alta

Impacto:
Permite inconsistência financeira e risco ao usuário final

Evidência:
Falha reproduzida em ambiente de testes durante execução manual

---

## 🐞 Bug 002 - Transferência duplicada

Descrição:
Sistema realiza duas transferências ao clicar duas vezes no botão.

Passos para reproduzir:
1. Acessar área de transferência
2. Inserir valor
3. Clicar duas vezes rapidamente

Resultado esperado:
Apenas uma transação realizada

Resultado atual:
Duas transações são realizadas

Severidade:
Crítica

Prioridade:
Alta

Impacto:
Permite inconsistência financeira e risco ao usuário final

Evidência:
Falha reproduzida em ambiente de testes durante execução manual

---

## 🐞 BUG-003 - Transferência sem validação de saldo

Descrição:
Sistema permite transferência mesmo sem saldo suficiente.

Pré-condição:
Usuário logado com saldo inferior ao valor da transferência.

Ambiente:
Sistema Web - Ambiente de Testes

Passos para reproduzir:
1. Acessar área de transferência
2. Inserir valor maior que o saldo
3. Confirmar operação

Resultado esperado:
Sistema deve bloquear a operação e exibir mensagem de saldo insuficiente

Resultado atual:
Transferência realizada normalmente

Severidade:
Crítica

Prioridade:
Alta

Impacto:
Permite inconsistência financeira e risco ao usuário final

Evidência:
Falha reproduzida em ambiente de testes durante execução manual
