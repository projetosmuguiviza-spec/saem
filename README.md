#  SAEM - Sociedade Académica de Engenharia de Moçambique

> **A nova geração da engenharia em Moçambique começa aqui.**

Site oficial da SAEM

## 🛠️ Stack Tecnológica

### Frontend
| Tecnologia | Versão | Função |
|---|---|---|
| [Next.js](https://nextjs.org/) | 14+ | Framework principal |
| [React](https://react.dev/) | 18+ | Biblioteca de UI |
| [Tailwind CSS](https://tailwindcss.com/) | 3+ | Estilização |
| [Framer Motion](https://www.framer.com/motion/) | latest | Animações |

### Backend
| Tecnologia | Versão | Função |
|---|---|---|
| [Node.js](https://nodejs.org/) | 18+ | Ambiente de execução |
| [NestJS](https://nestjs.com/) | 10+ | Framework de API |
| [PostgreSQL](https://www.postgresql.org/) | 15+ | Base de dados |
| [Prisma](https://www.prisma.io/) | latest | ORM |

---

## 👥 Equipa de Desenvolvimento

### 🖥️ Frontend
| # | Nome | Função |
|---|---|---|
| 1 | **Kelven Bulha** | Líder Frontend - Arquitectura + componentes base |
| 2 | **Nico Microsse** | Tailwind CSS - estilização de páginas |
| 3 | **Renny** | Responsividade + animações Framer Motion |

### ⚙️ Backend
| # | Nome | Função |
|---|---|---|
| 1 | **Mauro Muguiviza** | Full-Stack + arquitectura geral |
| 2 | **Mauro + Chance** | Prisma + PostgreSQL + Base de Dados |
| 3 | **Adérito Jr.** | API Endpoints + integração Next.js |

---

## 📁 Estrutura do Projecto

```
saem/
├── frontend/                    # Next.js App
│   ├── app/
│   │   ├── page.tsx             # Página inicial
│   │   ├── sobre/
│   │   ├── projectos/
│   │   ├── eventos/
│   │   └── contactos/
│   ├── components/
│   │   ├── Navbar.tsx
│   │   ├── Hero.tsx
│   │   ├── Pilares.tsx
│   │   ├── Estatisticas.tsx
│   │   ├── Projectos.tsx
│   │   ├── Eventos.tsx
│   │   └── Footer.tsx
│   ├── public/
│   ├── tailwind.config.ts
│   └── package.json
│
├── backend/                     # NestJS API
│   ├── src/
│   │   ├── membros/
│   │   ├── eventos/
│   │   ├── projectos/
│   │   ├── auth/
│   │   └── main.ts
│   ├── prisma/
│   │   └── schema.prisma
│   └── package.json
│
└── README.md
```

---

## 🚀 Como Instalar e Correr

### Pré-requisitos
- Node.js 18+
- npm ou yarn
- PostgreSQL instalado

### 1. Clonar o repositório
```bash
git clone https://github.com/projetosmuguiviza-spec/saem.git
cd saem
```

### 2. Configurar o Frontend
```bash
cd frontend
npm install
npm run dev
```
> Acede em: `http://localhost:3000`

### 3. Configurar o Backend
```bash
cd backend
npm install
cp .env.example .env
# Edita o .env com as credenciais da tua base de dados
npx prisma migrate dev
npm run start:dev
```
> API em: `http://localhost:3001`

---

##  Fluxo de Trabalho Git

```bash
# Cada membro trabalha na sua branch
git checkout -b frontend/nome-da-funcionalidade
git checkout -b backend/nome-da-funcionalidade

# Fazer commit
git add .
git commit -m "feat: descrição do que fizeste"
git push origin nome-da-branch

# Abrir Pull Request para a branch develop
# Mauro faz review e merge
```

### Branches
| Branch | Uso |
|---|---|
| `main` | Código estável - só eu (Mauro) faço merge |
| `develop` | Integração geral da equipa |
| `frontend/*` | Funcionalidades do frontend |
| `backend/*` | Funcionalidades do backend |

---

## Páginas do Site

- `/` — Página inicial
- `/sobre` — Sobre a SAEM
- `/areas-de-actuacao` — Áreas de actuação
- `/projectos` — Projectos em destaque
- `/eventos` — Próximos eventos
- `/noticias` — Notícias
- `/recursos` — Recursos para membros
- `/contactos` — Contactos

---

## Missão

> A Ciência ao Serviço do Desenvolvimento

A SAEM é uma sociedade académica  criada por estudantes de engenharia para promover a excelência, a inovação e o desenvolvimento sustentável de Moçambique.

---

## Licença

Este projecto está licenciado sob a [MIT License](LICENSE).

---

<p align="center">
  Feito pela SAEM
</p>
