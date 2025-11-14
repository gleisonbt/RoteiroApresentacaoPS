# 🧭 Modelo de Apresentação de Projeto  
**Tempo total:** até **7 minutos**  
**Objetivo:** Demonstrar maturidade técnica, coerência arquitetural e responsabilidade ética.

---

# **1. Capa**

- **Nome do Projeto:**  
- **Turma:**  
- **Integrantes:**  
- **Resumo curto (1 frase):**  
  > Ex.: “O sistema *Lanches1000* ajuda usuários a registrar refeições e controlar calorias diárias.”

---

# **2. Resumo do Projeto (30 segundos)**

- O que o sistema resolve?  
- Quem é o público-alvo?  
- Como o sistema ajuda esse público?  
- Problema → Solução em 1 frase

---

# **3. Modelagem de Domínio (1 minuto)**

**Mostrar no slide:**
- Imagem do **Diagrama de Classes**

**Explicar rapidamente:**
- Principais entidades  
- Justificativa das relações  
- Como o modelo reflete o mundo real

> **Dica:** Não ler o diagrama. Explicar o porquê das entidades.

---

# **4. Arquitetura do Sistema (1 minuto)**

**Mostrar no slide:**
- Print da **estrutura de pastas** do projeto (GitHub ou IDE)

**Explicar:**
- Controller → recebe a requisição  
- Service → regra de negócio  
- Model → estrutura de dados  
- Repository → gravação/consulta  
- View → interação com o usuário  

> **Mostrar ao vivo no GitHub ou na IDE.**

---

# **5. Casos de Uso Selecionados**

**Escolher DOIS casos de uso principais:**
1. Caso de Uso 1: *(nome)*  
2. Caso de Uso 2: *(nome)*  

**Mostrar:**
- Imagem do **Diagrama de Casos de Uso**
- Destaque visual nos dois escolhidos

---

# **6. Demonstração do Caso de Uso 1 (30–40s)**

**Título:** Demonstração – Caso de Uso 1 *(nome)*

**Mostrar ao vivo:**
- Tela / formulário  
- Ação do usuário  
- Resultado sendo exibido  

---

# **7. Fluxo Interno do Caso de Uso 1 (Código ao Vivo)**

**Mostrar no slide apenas a lista:**

1. View  
2. Rota  
3. Controller  
4. Service  
5. Model  
6. Repository  
7. Banco / Retorno à View  

**Durante a apresentação:**  
Abrir AO VIVO:
- View  
- Rota  
- Controller  
- Service  
- Model  
- Repository  

> **Obrigatório:** mostrar o caminho real no código.

---

# **8. Demonstração do Caso de Uso 2 (30–40s)**

**Título:** Demonstração – Caso de Uso 2 *(nome)*

**Mostrar ao vivo:**
- Tela  
- Funcionalidade acontecendo  
- Dados carregando do banco  

---

# **9. Fluxo Interno do Caso de Uso 2 (Código ao Vivo)**

**Mostrar no slide apenas:**

1. View  
2. Rota  
3. Controller  
4. Service  
5. Model  
6. Repository  
7. View exibindo os dados  

**Durante a apresentação:**  
Navegar nos arquivos ao vivo, na ordem.

---

# **10. Requisitos Implementados (Checklist REAL no README)**

O grupo deve incluir **no README DO PROJETO** um checklist completo dos requisitos funcionais, assim:

### **Exemplo de checklist (copiar/adaptar):**

| Requisito | Implementado? |
|-----------|----------------|
| Cadastro de usuários | ✔️ |
| Login com validação | ✔️ |
| CRUD de funcionários | ✔️ |
| Listagem com filtros | ✔️ |
| Tela de perfil | ❌ |
| Logout | ✔️ |
| Termo de Uso na primeira execução | ✔️ |
| Responsividade | ❌ |
| Integração com API externa | ✔️ |

> **Na apresentação**, mostrar no slide o checklist do README e destacar:  
> ✔ O que foi totalmente entregue  
> ✦ O que foi diferencial  
> ❌ O que ficou pendente (se houver)

---

# **11. Ética e Termos (OBRIGATÓRIO NA APLICAÇÃO)**

A aplicação deve conter **telas reais** de:

- **Termo de Uso**  
- **Termo de Consentimento**  
*(pelo menos um deles deve existir; preferencialmente os dois)*

E na apresentação o grupo deve mostrar:

### ✔ **As telas dentro da aplicação:**  
- Tela de Termo de Uso  
- Tela de Consentimento (se houver)  
- Check “Li e aceito os termos”  

### ✔ **Demonstração obrigatória:**  
Ao se cadastrar ou acessar pela primeira vez, o usuário:

1. **Vê o termo automaticamente**  
2. **Precisa aceitar** (checkbox ou botão)  
3. **Só então entra no sistema**

> **Se o usuário não aceitar, o sistema deve bloquear o acesso.**

### O que explicar (em 1 frase cada):
- **Termo de Uso:** define as regras da plataforma.  
- **Consentimento:** garante que os dados do usuário serão protegidos e que ele concorda com o uso ético dos dados.

---

# **12. Encerramento (30 segundos)**

- Reforçar o problema que o sistema resolve  
- Principal aprendizado técnico  
- Maturidade arquitetural do grupo  
- Evolução individual e coletiva  

Finalizar com:  
**“Obrigado pela atenção!”**

---

# ✅ **Checklist Final para Ensaiar**

- [ ] Dois casos de uso funcionando ao vivo  
- [ ] Dois fluxos completos demonstrados no código  
- [ ] Modelagem coerente  
- [ ] Arquitetura MVC + Service + Repository implementada  
- [ ] Termos obrigatórios funcionando  
- [ ] Requisitos marcados no README  
- [ ] Repositório atualizado e organizado  
- [ ] Apresentação cronometrada: máx. 7 minutos  

---
