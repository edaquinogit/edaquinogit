# Ednaldo Aquino

**Software Engineer | Full-Stack Product Engineering | Process Management**

Desenvolvedor de software focado em construir produtos web com base técnica sólida, regras de negócio bem protegidas e documentação que acompanha o código real. Minha experiência em gestão de processos orienta a forma como projeto sistemas: primeiro entendo o fluxo, depois traduzo isso em arquitetura, API, interface e qualidade verificável.

Atualmente desenvolvo o **BipFlow Manage**, uma plataforma full-stack para gestão de catálogo, frete, carrinho, checkout via WhatsApp e histórico de vendas. O objetivo do projeto é demonstrar código de produto, não apenas CRUD isolado.

---

## Projeto Em Destaque

### [BipFlow Manage](https://github.com/edaquinogit/BipFlow-Manage)

Plataforma de gestão para pequenos negócios, com backend Django REST, frontend Vue 3 + TypeScript e checkout público integrado ao WhatsApp.

| Área | Implementação |
| --- | --- |
| Backend | Django 6, Django REST Framework, Simple JWT, RBAC, throttling e persistência de pedidos |
| Frontend | Vue 3, TypeScript, Vite, Vue Router, Axios, Zod, composables e services dedicados |
| Produto | Dashboard administrativo, catálogo público, carrinho, frete por região e histórico de vendas |
| Segurança | Backend como autoridade para preço, estoque, disponibilidade, frete, totais e permissões |
| Qualidade | Pytest, Ruff, Vitest, Cypress, ESLint, typecheck e build validado |
| Documentação | README, visão de arquitetura, guia de desenvolvimento e referência funcional da API |

**Decisões técnicas relevantes**

- Separação clara entre backend Django REST, frontend Vue e motor Node isolado.
- Escrita administrativa protegida por papéis como `staff`, `admin` e `manager`.
- Cadastro público sem concessão automática de acesso ao dashboard.
- Checkout recalculado no servidor e persistido como pedido de venda.
- Chamadas HTTP concentradas em `src/services/` e tokens centralizados em `token-store.ts`.
- Documentação curta, versionada e mantida como fonte operacional do estado atual.

---

## Como Trabalho Engenharia

- **Produto antes do framework:** tecnologia entra para resolver o fluxo real, não para inflar a arquitetura.
- **Contratos explícitos:** APIs, schemas, permissões e regras de domínio documentados e testáveis.
- **Segurança no servidor:** o backend é a fonte de verdade para dados sensíveis, totais, estoque e autorização.
- **Manutenção como requisito:** organização de camadas, comandos de qualidade e documentação acompanham o ciclo de mudança.
- **IA com critério:** uso assistentes de desenvolvimento para acelerar análise, refatoração e validação, mantendo responsabilidade técnica sobre as decisões.

---

## Stack Principal

<div align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/Django_REST-ff1709?style=for-the-badge&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" />
  <br />
  <img src="https://img.shields.io/badge/Vue_3-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge&logo=zod&logoColor=white" />
  <br />
  <img src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" />
  <img src="https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white" />
  <img src="https://img.shields.io/badge/Cypress-69D3A7?style=for-the-badge&logo=cypress&logoColor=black" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
</div>

---

## Foco Atual

- Evoluir o BipFlow como produto full-stack operável e bem documentado.
- Fortalecer testes, contratos de API e qualidade de entrega.
- Aplicar gestão de processos para transformar requisitos de negócio em software simples de manter.
- Buscar oportunidades em engenharia de software onde produto, arquitetura e execução caminhem juntos.

---

## Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ednaldo-aquino-area)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/edaquinogit)
