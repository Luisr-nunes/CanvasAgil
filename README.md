<div align="center">

# 🗂️ Canvas Ágil

### Template de App Mobile — Exportado do Figma Make

<br>

![TypeScript](https://img.shields.io/badge/TypeScript-84.5%25-3178C6?style=flat-square&logo=typescript&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-15.4%25-1572B6?style=flat-square&logo=css3&logoColor=white)
![React](https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-build-646CFF?style=flat-square&logo=vite&logoColor=white)

<br>

![Tipo](https://img.shields.io/badge/Tipo-Template_/_Base_de_Projeto-4A4A4A?style=flat-square)
![Origem](https://img.shields.io/badge/Origem-Figma_Make-F24E1E?style=flat-square&logo=figma&logoColor=white)
![Status](https://img.shields.io/badge/Status-Base_para_reuso-FFB300?style=flat-square)

<br>

> *Front-end de app mobile exportado do Figma Make, salvo como base reutilizável*
> *para outros projetos. Estrutura completa com navegação e 6 telas funcionais.*

</div>

---

## Sobre o Repositório

Este repositório armazena o código front-end gerado a partir de um protótipo no **Figma Make**, exportado como aplicação **React + TypeScript** para servir de base e referência em projetos futuros.

O projeto simula um app mobile de planejamento ágil, com navegação por barra inferior e múltiplas telas já estruturadas e componentes prontos.

---

## Telas Disponíveis

| Tela | Componente | Descrição |
|---|---|---|
| Home | `HomeScreen` | Tela inicial com acesso a planos |
| Canvas | `CanvasEditor` | Editor de canvas ágil |
| Biblioteca | `LibraryScreen` | Repositório de modelos salvos |
| Comunidade | `CommunityFeed` | Feed de compartilhamento |
| Horários | `ScheduleManager` | Gerenciamento de agenda |
| Perfil | `ProfileScreen` | Dados e configurações do usuário |

---

## Tecnologias

| Tecnologia | Uso |
|---|---|
| **React 18** | Framework de interface |
| **TypeScript** | Tipagem estática |
| **Vite** | Bundler e servidor de desenvolvimento |
| **Radix UI** | Componentes acessíveis (accordion, dialog, tabs, etc.) |
| **Tailwind CSS** | Estilização utilitária |
| **shadcn/ui** | Design system sobre Radix UI |
| **Lucide React** | Ícones |
| **Recharts** | Gráficos |

---

## Estrutura

```
CanvasAgil/
├── src/
│   ├── App.tsx           # Roteamento entre telas
│   ├── main.tsx          # Entry point React
│   ├── index.css         # Estilos globais
│   └── components/       # Componentes de cada tela
├── index.html
├── vite.config.ts
└── package.json
```

---

## Como Rodar

```bash
# Clone o repositório
git clone https://github.com/Luisr-nunes/CanvasAgil.git
cd CanvasAgil

# Instale as dependências
npm install

# Inicie o servidor de desenvolvimento (abre na porta 3000)
npm run dev
```

---

## Atribuições

- Componentes de UI: **shadcn/ui** — licença MIT
- Imagens: **Unsplash** — licença Unsplash

---

## Autor

<div align="center">

**Luis Nunes**
Estudante de ADS — CESAR School

[![GitHub](https://img.shields.io/badge/GitHub-Luisr--nunes-181717?style=flat-square&logo=github)](https://github.com/Luisr-nunes)

</div>

---

<div align="center">

*⚡ Do Figma ao código — base pronta para o próximo projeto.*

</div>
