# Casos de Teste — E-commerce

## Objetivo

Este documento contém os cenários e casos de teste elaborados para validar as principais funcionalidades de uma aplicação de e-commerce.

Os testes serão executados de forma prática e os resultados serão registrados conforme a execução.

---

## CT-001 — Login com credenciais válidas

**Módulo:** Login  
**Tipo:** Teste funcional

**Pré-condição:** Usuário válido cadastrado.

**Passos:**
1. Acessar a tela de login.
2. Informar um usuário válido.
3. Informar uma senha válida.
4. Clicar em "Login".

**Resultado esperado:**  
O sistema deve autenticar o usuário e permitir o acesso 

**Resultado obtido:** O sistema autenticou o usuário com sucesso e direcionou para a página de produtos.

**Status:** PASSOU


---

## CT-002 — Login com senha incorreta

**Módulo:** Login  
**Tipo:** Teste negativo

**Pré-condição:** Usuário cadastrado.

**Passos:**
1. Acessar a tela de login.
2. Informar um usuário válido.
3. Informar uma senha incorreta.
4. Clicar em "Login".

**Resultado esperado:**  
O sistema deve impedir o acesso e apresentar uma mensagem informando que as credenciais são inválidas.

**Resultado obtido:** A executar.

**Status:** Pendente

---

## CT-003 — Login com usuário inexistente

**Módulo:** Login  
**Tipo:** Teste negativo

**Passos:**
1. Acessar a tela de login.
2. Informar um usuário inexistente.
3. Informar uma senha.
4. Clicar em "Login".

**Resultado esperado:**  
O sistema deve impedir o acesso e apresentar uma mensagem de erro.

**Resultado obtido:** A executar.

**Status:** Pendente

---

## CT-004 — Login sem informar usuário

**Módulo:** Login  
**Tipo:** Teste de validação

**Passos:**
1. Acessar a tela de login.
2. Deixar o campo de usuário vazio.
3. Informar uma senha.
4. Clicar em "Login".

**Resultado esperado:**  
O sistema deve informar que o campo de usuário é obrigatório.

**Resultado obtido:** A executar.

**Status:** Pendente

---

## CT-005 — Login sem informar senha

**Módulo:** Login  
**Tipo:** Teste de validação

**Passos:**
1. Acessar a tela de login.
2. Informar um usuário.
3. Deixar o campo de senha vazio.
4. Clicar em "Login".

**Resultado esperado:**  
O sistema deve informar que o campo de senha é obrigatório.

**Resultado obtido:** A executar.

**Status:** Pendente

---

## CT-006 — Visualização de produtos

**Módulo:** Produtos  
**Tipo:** Teste funcional

**Passos:**
1. Acessar a aplicação.
2. Acessar a página de produtos.

**Resultado esperado:**  
O sistema deve apresentar a lista de produtos disponíveis.

**Resultado obtido:** A executar.

**Status:** Pendente

---

## CT-007 — Visualização dos detalhes de um produto

**Módulo:** Produtos  
**Tipo:** Teste funcional

**Passos:**
1. Acessar a lista de produtos.
2. Selecionar um produto.

**Resultado esperado:**  
O sistema deve apresentar as informações do produto, incluindo nome, imagem, descrição e preço.

**Resultado obtido:** A executar.

**Status:** Pendente

---

## CT-008 — Adicionar produto ao carrinho

**Módulo:** Carrinho  
**Tipo:** Teste funcional

**Passos:**
1. Acessar a lista de produtos.
2. Selecionar um produto.
3. Adicionar o produto ao carrinho.
4. Acessar o carrinho.

**Resultado esperado:**  
O produto selecionado deve aparecer no carrinho.

**Resultado obtido:** A executar.

**Status:** Pendente

---

## CT-009 — Remover produto do carrinho

**Módulo:** Carrinho  
**Tipo:** Teste funcional

**Pré-condição:** Deve existir um produto adicionado ao carrinho.

**Passos:**
1. Acessar o carrinho.
2. Selecionar a opção de remover o produto.

**Resultado esperado:**  
O produto deve ser removido do carrinho.

**Resultado obtido:** A executar.

**Status:** Pendente

---

## CT-010 — Adicionar múltiplos produtos ao carrinho

**Módulo:** Carrinho  
**Tipo:** Teste funcional

**Passos:**
1. Selecionar um produto e adicioná-lo ao carrinho.
2. Selecionar outro produto.
3. Adicionar o segundo produto ao carrinho.
4. Acessar o carrinho.

**Resultado esperado:**  
Os dois produtos devem aparecer no carrinho e seus valores devem ser apresentados corretamente.

**Resultado obtido:** A executar.

**Status:** Pendente
