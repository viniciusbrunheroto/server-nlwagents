# 🚀 NLW AGENTS

Este projeto foi desenvolvido durante um evento da **Rocketseat**, com foco em construir uma **API robusta, eficiente e escalável**, utilizando tecnologias modernas e práticas recomendadas do ecossistema JavaScript/TypeScript.

## ✨ Tecnologias Utilizadas

- **Node.js** (com suporte a TypeScript nativo via `--experimental-strip-types`)
- **Fastify** - Framework web leve e altamente performático
- **PostgreSQL** - Banco de dados relacional robusto e confiável
- **Drizzle ORM** - ORM moderno e type-safe
- **Zod** - Validação de esquemas com tipagem segura
- **Docker** - Ambientes isolados e consistentes para desenvolvimento e produção
- **Biome** - Linter e formatador moderno para código JavaScript/TypeScript

## 📦 Como rodar o projeto

### Pré-requisitos

- [Node.js](https://nodejs.org/)
- [Docker](https://www.docker.com/)
- [PostgreSQL](https://www.postgresql.org/)
- [pnpm](https://pnpm.io/) (ou npm/yarn)

### Instalação

```bash
# Instale as dependências
pnpm install

# Crie o banco de dados com Docker
docker-compose up -d

# Execute as migrations (caso existam)
pnpm drizzle:migrate
