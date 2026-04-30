
# Testes de Validação com SQL

## Cenário: Transferência sem saldo

### Objetivo
Validar se o sistema permite transferências sem saldo disponível.

### Contexto
Tabela: contas (id, saldo)  
Tabela: transferencias (conta_origem, valor)

# Teste SQL - Validação de saldo

## Query
```sql
SELECT id, saldo
FROM contas
WHERE saldo < 0;

## Resultado obtido
1 registro encontrado → BUG CRÍTICO (saldo negativo identificado)
