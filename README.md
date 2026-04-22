# Caderno Temático: APIs com Python e FastAPI

## Contexto e Objetivos

Este projeto tem como objetivo criar um caderno temático utilizando o NotebookLM com foco no estudo de APIs utilizando Python e FastAPI.

**Objetivos de estudo:**

- Compreender o funcionamento de APIs  
- Construir APIs RESTful  
- Entender autenticação e autorização  
- Integrar banco de dados  
- Utilizar IA como ferramenta de aprendizado ativo  

---

## Curadoria de Fontes

### 1. FastAPI  
https://fastapi.tiangolo.com/  

**Motivo:** Fonte principal para criação de APIs modernas com Python  
**Aprendizado:** Estrutura de rotas, validação de dados e documentação automática  

---

### 2. PostgreSQL  
https://www.postgresql.org/docs/  

**Motivo:** Banco de dados robusto amplamente utilizado  
**Aprendizado:** Persistência de dados e modelagem relacional  

---

### 3. OAuth2  
https://oauth.net/2/  

**Motivo:** Padrão de mercado para autorização  
**Aprendizado:** Fluxos de autenticação e controle de acesso  

---

### 4. Redis  
https://redis.io/docs/  

**Motivo:** Utilizado para cache e performance  
**Aprendizado:** Armazenamento em memória e otimização de APIs  

---

## Engenharia de Prompts e "Cicatrizes"

### Prompt 1

**"O que é uma API?"**

**Resposta (resumo):**  
Uma API permite comunicação entre sistemas através de requisições HTTP.

**Problema:**  
Resposta genérica e pouco útil para aplicação prática.

---

### Prompt 2

**"Como criar uma API com FastAPI?"**

**Resposta (resumo):**  
Exemplo simples com endpoints GET e POST.

**Problema:**  
Não incluía banco de dados nem autenticação.

---

### Prompt 3

**"Crie uma API RESTful com FastAPI com CRUD, autenticação JWT e banco de dados"**

**Resposta (resumo):**

- CRUD completo  
- Autenticação com JWT  
- Integração com banco  

**Melhoria:**  
Resposta mais próxima de um cenário real.

---

### Prompt 4

**"Como construir uma API profissional com FastAPI incluindo autenticação, banco, cache e testes?"**

**Resposta (resumo):**

- JWT  
- Cache com Redis  
- Testes automatizados  

**Melhoria:**  
Abordagem mais completa e alinhada com boas práticas.

---

## Dificuldades encontradas

- Prompts iniciais muito vagos  
- Respostas simplificadas demais  
- Falta de contexto real de desenvolvimento  

**Aprendizado principal:**  
A qualidade da resposta depende diretamente da qualidade do prompt.

---

## Miniguia de Estudo

### API

Interface que permite comunicação entre sistemas via HTTP.

---

### REST

Padrão baseado em recursos com uso de métodos HTTP:

- GET → leitura  
- POST → criação  
- PUT → atualização  
- DELETE → remoção  

---

### FastAPI

Framework para criação de APIs com:

- Alta performance  
- Tipagem com Python  
- Documentação automática  

---

### Autenticação e Autorização

- JWT → autenticação de usuários  
- OAuth2 → controle de permissões  

---

### Banco de Dados

- Uso de PostgreSQL  
- Armazenamento persistente  

---

### Cache

- Uso de Redis  
- Redução de tempo de resposta  

---

## Glossário

- API → Interface de comunicação  
- REST → Arquitetura baseada em HTTP  
- JWT → Token de autenticação  
- OAuth2 → Protocolo de autorização  
- Cache → Armazenamento temporário  

---

## Prompts Reutilizáveis

- "Explique o que é uma API com exemplos práticos"  
- "Crie uma API RESTful com FastAPI"  
- "Implemente autenticação JWT em FastAPI"  
- "Como integrar PostgreSQL em uma API?"  
- "Como melhorar performance de APIs com cache?"  

---

## Entrega

Este repositório contém:

- README estruturado conforme o desafio  
- Curadoria de fontes com justificativa  
- Registro da evolução de prompts  
- Miniguia consolidado de estudo  

---

## Conclusão

O uso de IA como ferramenta de aprendizado se mostrou eficiente, desde que utilizado com prompts bem estruturados e objetivos claros.
