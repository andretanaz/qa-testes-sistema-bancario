# Casos de Teste

## [CT-001][AL] Login realizado com credenciais válidas

Pré-condição:
Usuário cadastrado no sistema e com acesso ativo.

Passos:
1. Acessar página de login
2. Inserir login: usuario@teste.com
3. Inserir senha: 123456
4. Clicar em "Entrar"

Resultado esperado:
Usuário autenticado com sucesso

Resultado atual:
Usuário autenticado com sucesso

Status: Aprovado

---

## [CT-002][MD] Tentativa de login com senha inválida

Pré-condição:
Usuário cadastrado no sistema.

Passos:
1. Acessar página de login
2. Inserir login: usuario@teste.com
3. Inserir senha inválida: 000000
4. Clicar em "Entrar"

Resultado esperado:
Sistema deve exibir mensagem de erro de autenticação

Resultado atual:
Sistema apresentou erro de autenticação

Status: Reprovado 

---

## [CT-003][AL] Transferência realizada com saldo disponível

Pré-condição:
Usuário logado no sistema com saldo disponível.

Passos:
1. Acessar área de transferência
2. Inserir valor: 100
3. Confirmar operação

Resultado esperado:
Transferência realizada com sucesso

Resultado atual:
Transferência realizada com sucesso

Status: Aprovado
