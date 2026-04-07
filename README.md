Projeto de QA – Testes Funcionais em E-commerce

## 📌 Sistema testado
Casas Bahia (Aplicação Web – Ambiente de Produção)

## 🎯 Objetivo
Realizar testes na funcionalidade de busca e fluxo de login, identificando falhas que impactam a experiência do usuário e o funcionamento do sistema.

---

## 🔍 Escopo
- Busca de produtos  
- Tratamento de entradas  
- Página de resultados  
- Fluxo de login (CPF/CNPJ)  

---

## 🧠 Abordagem de Teste
- Testes funcionais  
- Testes exploratórios  
- Validação de fluxo do usuário  
- Análise de comportamento do sistema  

---

## 🐞 Bugs Encontrados

### 🔴 BUG-01 – Erro 404 ao buscar caracteres especiais
- Tipo: Funcional  
- Severidade: Alta  
- Descrição: Inserção de caracteres especiais na busca redireciona o usuário para uma página de erro 404, interrompendo o fluxo da aplicação  

---

### 🔴 BUG-02 – Bloqueio de digitação no campo CPF/CNPJ
- Severidade: Crítica  
- Descrição: O campo realiza validação antecipada e impede a digitação completa, bloqueando o login  

---

## 📁 Estrutura do Projeto
- test-cases  
- bug-reports  
- evidencias  

---

## 🚀 Aprendizados
- Validação de entrada é crítica  
- Bugs podem impactar diretamente o negócio  
- Testes exploratórios revelam falhas reais  
- Importância de testar fluxos completos  

---

## 📌 Próximos Passos
- Testar filtros e ordenação  
- Iniciar testes de API  
- Evoluir para automação  
