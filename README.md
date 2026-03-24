# CUME App

Aplicação web para gerenciamento das atividades de um grupo de escalada, controle de filas, documentação de membros, registro de presenças e fluxo de autenticação.

> Protótipos de referência disponíveis no [Figma](https://www.figma.com/design/AwogeUtZLeimrjxvfSwcwB/CUME---Prot%C3%B3tipo?node-id=13-1268&t=V69toOxfZcPzCCoA-1).

<img width="402" height="874" alt="image" src="https://github.com/user-attachments/assets/6ffb0b7d-915c-4e20-a8c4-70a7c0b4b16b" />
<img width="402" height="874" alt="image" src="https://github.com/user-attachments/assets/acfda94e-bdfa-480b-b3ee-a16704e7a47b" />
<img width="402" height="874" alt="image" src="https://github.com/user-attachments/assets/743d1ac5-9335-400d-abab-b952c4a18d74" />
<img width="402" height="874" alt="image" src="https://github.com/user-attachments/assets/e64f1c7c-e1ff-4d9e-93ae-3505157307fe" />

---

## Funcionalidades

- **Fila de escalada**: gerenciamento e registro de presença nas sessões
- **Documentação de membros**: formulários, documentos fotográficos e disclaimers
- **Base de dados**: visualização e gerenciamento de dados do grupo
- **Configurações**: administração da conta e preferências
- **Navegação responsiva**: menu lateral adaptado para desktop e mobile

---

## Stack

| Camada | Tecnologia |
|---|---|
| Framework | React |
| Estilização | Tailwind CSS (tema customizado) |
| Roteamento | React Router DOM |
| Ícones | FontAwesome |
| Fonte | Poppins (Google Fonts) |
| Documentação | Docusaurus |
| Linting | ESLint |

### Design System

O tema foi configurado no Tailwind com paletas customizadas (**amber**, **brown**, **gray**, **white**, **danger**) e classes de tipografia próprias (`body-sm/md/lg`, `title-h1/h2/h3`), alinhadas ao Figma.

---

## Estrutura

```
src/
├── components/       # Componentes base (Button, Header, SidebarMenu, Icons…)
├── pages/            # Páginas principais (Home, Climb, Documents, Manage…)
│   └── subpage/      # Subpáginas (QueueClimb, MemberForms, PhotoDocuments…)
├── layouts/          # SidebarMenuLayout — layout principal
└── App.jsx           # Definição de rotas
```

---

## Como rodar

### Pré-requisitos
- Node.js instalado

### Frontend

```bash
npm install
npm run dev
```

### Documentação (Docusaurus)

```bash
# Rodar servidor local
npm run docs:dev        # http://localhost:3000

# Gerar/atualizar docs de componentes
npm run docs:generate

# Build de produção
npm run docs:build
npm run docs:serve
```

---

## Referências

- [Figma — CUME Protótipo](https://www.figma.com/design/AwogeUtZLeimrjxvfSwcwB/CUME---Prot%C3%B3tipo?node-id=13-1268&t=V69toOxfZcPzCCoA-1)
