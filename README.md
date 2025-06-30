# 🚀 Trilha Fullstack JavaScript com Segurança (versão 30/06/2025)

Esta trilha cobre do zero ao avançado em desenvolvimento fullstack com JavaScript moderno, com foco em **boas práticas e segurança** desde a base. Ideal para iniciantes ou desenvolvedores que querem se atualizar com as práticas reais do mercado.

---

## 📚 Conteúdo da Trilha

### 🔰 1. Fundamentos da Web (HTML, CSS, Git)
- HTML semântico, CSS Flexbox e Grid.
- Git: versionamento com commits significativos.
- Segurança:
  - Use `.gitignore` para ocultar `.env`, `node_modules`.
  - Nunca exponha chaves ou senhas no repositório.

### 🧠 2. JavaScript Essencial
- Variáveis, funções, estruturas, callbacks, promises, async/await.
- DOM, eventos e manipulação da interface.
- Segurança:
  - Evite `eval()`, `innerHTML` com dados externos (proteção contra XSS).
  - Validação de dados no frontend.

### 🌐 3. APIs e Web Avançada
- `fetch`, tratamento de erros, integração com APIs públicas.
- Segurança:
  - Sanitização de dados externos antes de exibição.
  - Uso de HTTPS e headers seguros.

### ⚛️ 4. React + TypeScript
- Componentização, hooks, props, JSX, roteamento.
- Introdução ao TypeScript com tipagem de props e estados.
- Segurança:
  - Escapar dados dinamicamente inseridos.
  - Tipar corretamente para evitar vulnerabilidades de tipo.

### 🔙 5. Node.js, Express, MongoDB
- Criação de APIs REST, MVC, rotas, middlewares.
- Mongoose: schemas, validação.
- Segurança:
  - Uso de `helmet`, `express-rate-limit`, `cors` configurado.
  - Validação com `joi`/`zod`, proteção contra NoSQL injection e XSS.

### 🛡️ 6. Autenticação e Autorização
- JWT + bcrypt + refresh tokens.
- Login, logout, proteção de rotas e RBAC (controle por papéis).
- Segurança:
  - Armazenar tokens em cookies HTTPOnly.
  - Implementar expiração e renovação de sessão.

### 🔗 7. Integração Frontend + Backend
- Comunicação entre React e API REST.
- Variáveis de ambiente, CORS, headers.
- Segurança:
  - Nunca expor tokens no frontend.
  - Sempre validar dados recebidos no backend.

### 🚢 8. Deploy e Publicação
- Vercel (frontend), Render (backend).
- Variáveis de ambiente e scripts de build.
- Segurança:
  - Configuração HTTPS obrigatória.
  - Remoção de ferramentas de debug em produção.

### ✅ 9. Testes e Clean Code
- Jest, Supertest para backend.
- ESLint, Prettier, Husky para qualidade de código.
- Segurança:
  - Testes automatizados detectam regressões e vulnerabilidades recorrentes.

### 💼 10. Projetos para Portfólio
- ToDo List (React), Blog (fullstack), API de Usuários, Mini Ecommerce.
- Cada projeto deve:
  - Ter autenticação segura.
  - Validar dados.
  - Evitar XSS, CSRF, Injections.

---

## 🧠 Estimativa de Tempo

Total estimado: **~205 horas**  
Sugestão para 10h semanais: **~5 a 6 meses**

---

## 🧩 Segurança por tecnologia (resumo)

| Tecnologia | Vulnerabilidades comuns | Proteções recomendadas |
|------------|--------------------------|-------------------------|
| HTML/JS    | XSS, clickjacking        | Content-Security-Policy, escaping |
| React      | DOM-based XSS            | JSX escape, evitar `dangerouslySetInnerHTML` |
| Node.js    | NoSQL Injection, DoS     | `helmet`, `rate-limit`, validação rigorosa |
| Express    | Routing override, XSS    | Middleware de validação, sanitização |
| MongoDB    | Query injection          | Use `mongoose` com schemas validados |
| JWT/Auth   | Token theft, session fix | HTTPOnly cookies, expiração, refresh |
| GitHub     | Exposição de segredos    | `.gitignore`, Secret Scanning |

---

## 📌 Dica Final
Estude com foco em segurança desde o início. Seu código será mais confiável, escalável e pronto para o mercado.

---
 
📅 30/06/2025
