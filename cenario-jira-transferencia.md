
# 🧪 Teste em formato Jira

## 🆔 ID
QA-001

## 📝 Título
Validação de transferência sem saldo disponível

## 👤 Tipo
Bug

## ⚠️ Severidade
Crítica

## 🚨 Prioridade
Alta

## 📍 Ambiente
Sistema Bancário (Simulado)

## 📋 Descrição
O sistema permite realizar transferência mesmo quando a conta de origem não possui saldo suficiente.

## 🔁 Passos para reproduzir
1. Acessar o sistema bancário  
2. Selecionar conta com saldo insuficiente  
3. Tentar realizar transferência  
4. Confirmar operação  

## 🎯 Resultado esperado
O sistema deve bloquear a transferência e exibir mensagem de saldo insuficiente.

## ❌ Resultado obtido
A transferência é realizada com sucesso, mesmo sem saldo.

## 📎 Evidência
Simulação baseada em cenário de teste documentado no projeto.

## 📌 Status
Aberto
