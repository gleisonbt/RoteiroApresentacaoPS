# 🧭 Roteiro de Apresentação de Projeto

> **Tempo total:** até **7 minutos**  
> **Objetivo:** Demonstrar maturidade técnica, coerência arquitetural e responsabilidade ética.

---

## 1. Introdução (30 segundos)

- **Nome do projeto:**  
- **Turma:**  
- **Integrantes:**  
- **Resumo curto:** Explique em uma frase o que o sistema faz e qual problema resolve.  
  > Exemplo: “O sistema *Lanches1000* ajuda usuários a registrar refeições e controlar calorias diárias.”

---

## 2. Modelagem de Domínio (1 minuto)

- Mostrem rapidamente o **diagrama de classes**.  
- Expliquem **como as entidades refletem o problema real**.  
- Destaquem **as principais classes e relações** (ex.: Usuário, Pedido, Produto).  
- Mostrem que **o modelo faz sentido dentro do tema** do projeto.

> **Dica:** Sejam objetivos: o foco é mostrar entendimento do domínio, não ler o diagrama.

---

## 3. Casos de Uso e Demonstração Funcional (2 minutos)

- Mostrem o **diagrama de casos de uso**.  
- Escolham **dois casos de uso principais** e **demonstrem funcionando**:
  - Se o sistema for **mobile**, mostrem **ao vivo no celular**.  
  - Se for **web**, demonstrem **rodando em um servidor** (Render, Vercel, ou localhost via navegador).  
- A demonstração deve exibir o **fluxo completo da funcionalidade**, da ação do usuário ao resultado na tela.  

> **Dica:** Evitem apenas mostrar código. O avaliador precisa ver **a funcionalidade em execução**, seja ao vivo ou em vídeo curto sem audio.

---

## 4. Arquitetura (MVC + Repository) (2 minutos)

- Mostrem a **estrutura de pastas** do projeto (Models, Views, Controllers, Repositories).  
- Demonstrem um **fluxo real**: por exemplo, “Cadastro de Usuário”:
  1. Controller recebe a requisição.  
  2. Controller chama o Repository.  
  3. Repository grava ou consulta o Model.  
  4. Resultado é exibido na View.  
- Mostrem que **as camadas estão separadas** (sem lógica misturada).

> **Dica:** Explique a responsabilida das camadas do sistema:  
> “Controller coordena, Repository acessa o banco, Model representa a regra de negócio.”

---

## 5. Funcionalidades e Ética (1 minuto)

- Mostrem a **lista dos 20 requisitos funcionais implementados**.  
- Destaquem **uma ou duas funcionalidades diferenciais**.  
- Mostrem no aplicativo as telas de temo de uso e termo de consentimento.
- Expliquem em **uma frase** o que cada termo garante (privacidade, direitos do usuário, ética no uso).

---

## 6. Encerramento (30 segundos)

- Reforcem brevemente:
  - O que o sistema resolve.  
  - O principal aprendizado técnico do grupo.  
  - A maturidade da entrega (arquitetura, código limpo, ética).  
- Agradeçam de forma breve e segura.

---

## ✅ Checklist de Preparação

- [ ] Repositório atualizado e rodando  
- [ ] Vídeo ou demonstração funcional (mobile ou web)  
- [ ] Diagramas revisados e coerentes com o código  
- [ ] Termos éticos adicionados ao repositório  
- [ ] Falas ensaiadas e cronometradas (máx. 7 min)

---
