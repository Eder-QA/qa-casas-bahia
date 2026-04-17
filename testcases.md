# 📋 Casos de Teste – Funcionalidade de Busca

## CT-01 – Busca com termo válido
**Pré-condição:** Usuário na página inicial  

**Passos:**
1. Inserir "geladeira" no campo de busca  
2. Pressionar Enter  

**Resultado esperado:**  
Sistema deve exibir produtos relacionados ao termo pesquisado  

---

## CT-02 – Busca com termo inexistente
**Pré-condição:** Usuário na página inicial

**Passos:**
1. Inserir termo inexistente
2. Pressionar Enter

**Resultado esperado:**
Sistema deve exibir uma resposta para busca sem resultados, sem apresentar erro na aplicação.

---

## CT-03 – Busca com campo vazio
**Pré-condição:** Usuário na página inicial  

**Passos:**
1. Deixar campo vazio  
2. Clicar em buscar  

**Resultado esperado:**  
Sistema não deve executar a busca com o campo vazio e não deve apresentar erro na aplicação.

---

## CT-04 – Busca com caracteres especiais
**Pré-condição:** Usuário na página inicial  

**Passos:**
1. Inserir "!@#$%"  
2. Pressionar Enter  

**Resultado esperado:**  
Sistema deve processar a busca com caracteres especiais sem apresentar erro ou quebra de funcionalidade.

---

## CT-05 – Busca com texto longo
**Pré-condição:** Usuário na página inicial  

**Passos:**
1. Inserir texto muito longo  
2. Pressionar Enter  

**Resultado esperado:**  
Sistema deve processar a busca com texto longo sem apresentar erro e sem quebrar o layout da página.
