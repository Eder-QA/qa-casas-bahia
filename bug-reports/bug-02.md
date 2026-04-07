# 🐞 BUG-02 – Campo de CPF/CNPJ bloqueia digitação após validação antecipada

## 📌 Ambiente
- Sistema: Casas Bahia (Web)
- Navegador: Chrome

---

## 🔥 Severidade: Crítica  
Impede completamente o fluxo de login/cadastro, bloqueando o acesso do usuário.

---

## 🎯 Prioridade: Alta  
Afeta funcionalidade essencial do sistema e pode impactar diretamente a conversão.

---

## 📝 Passos para reproduzir

1. Acessar a página de login  
2. Clicar no campo "CPF ou CNPJ"  
3. Iniciar a digitação (ex: inserir 1 ou 2 dígitos)  
4. Observar o comportamento do campo  
5. Tentar continuar a digitação  

---

## ❌ Resultado atual

O sistema realiza validação imediata após poucos dígitos, exibe mensagem de erro e bloqueia a continuidade da digitação, impedindo o preenchimento completo do campo.

---

## ✅ Resultado esperado

O sistema deve permitir a digitação completa do CPF/CNPJ antes de realizar validação, garantindo que o usuário consiga concluir o preenchimento.

---

## 🔁 Frequência

Ocorre de forma consistente (reproduzido múltiplas vezes)

---

## 📸 Evidência

(Adicionar print futuramente)
