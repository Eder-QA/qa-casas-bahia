# 🐞 BUG-01 – Sistema retorna erro 404 ao inserir caracteres especiais na busca

## 📌 Ambiente
- Sistema: Casas Bahia (Web)
- Navegador: Chrome

---

## 🔥 Severidade: Alta  
Interrompe o fluxo do usuário e redireciona para uma página de erro fora do contexto da aplicação.

---

## 🎯 Prioridade: Média/Alta  
Impacta a experiência do usuário e pode afetar a navegação.

---

## 📝 Passos para reproduzir

1. Acessar a página inicial  
2. Inserir caracteres especiais no campo de busca (ex: !@#$%)  
3. Pressionar Enter  
4. Observar comportamento da página  

---

## ❌ Resultado atual

O sistema redireciona para uma página de erro (404) com a mensagem:  
"Ops! Desculpe, não foi possível acessar a página"

---

## ✅ Resultado esperado

## ✅ Resultado esperado

O sistema deve tratar corretamente entradas com caracteres especiais, mantendo o usuário no fluxo da aplicação e exibindo resultados válidos ou uma mensagem informativa.

---

## 🔁 Frequência

Ocorre de forma consistente (reproduzido múltiplas vezes)

---

## 📸 Evidência

(Adicionar print futuramente)
