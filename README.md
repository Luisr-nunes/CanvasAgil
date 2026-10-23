# Canvas Ágil

[Read in English](README.en.md)

Protótipo de app mobile para professores montarem o planejamento de uma aula em cerca de 10 minutos, com um canvas estruturado e sugestões de um copiloto de IA. Front-end exportado do Figma Make em React e TypeScript.

## Sobre

O Canvas Ágil organiza o plano de aula em blocos (faísca inicial, metodologia, verificação e plano B para quando a internet cair) e oferece sugestões prontas para cada bloco. Este repositório guarda o front-end gerado a partir do protótipo no Figma Make, mantido como referência visual e base para reaproveitar componentes em outros projetos. Não há back-end: os dados das telas são simulados.

## Telas

| Tela | Componente | Descrição |
| --- | --- | --- |
| Início | `HomeScreen` | Saudação, atalho para novo planejamento e planejamentos recentes |
| Canvas | `CanvasEditor` | Editor do plano de aula em blocos |
| Copiloto | `AIBottomSheet` | Painel inferior com sugestões para o bloco selecionado |
| Biblioteca | `LibraryScreen` | Planejamentos e modelos salvos |
| Comunidade | `CommunityFeed` | Compartilhamento entre professores |
| Horários | `ScheduleManager` | Agenda de aulas |
| Perfil | `ProfileScreen` | Dados e preferências do usuário |

## Tecnologias

- React 18 e TypeScript
- Vite 6 com `@vitejs/plugin-react-swc`
- Componentes shadcn/ui sobre Radix UI
- CSS gerado pelo Tailwind CSS 4 (já compilado em `src/index.css`)
- Lucide (ícones), Recharts, React Hook Form, Sonner

## Estrutura

```
CanvasAgil/
└── Canvas Ágil/            # aplicação
    ├── index.html
    ├── package.json
    ├── vite.config.ts
    └── src/
        ├── App.tsx         # navegação entre telas
        ├── components/     # telas, ui/ (shadcn) e figma/
        ├── guidelines/
        └── Attributions.md
```

## Como executar

Pré-requisito: Node.js 18+.

```bash
git clone https://github.com/Luisr-nunes/CanvasAgil.git
cd "CanvasAgil/Canvas Ágil"
npm install
npm run dev      # http://localhost:3000
```

Para gerar a versão de produção: `npm run build` (saída em `build/`).

## Créditos

- Componentes de [shadcn/ui](https://ui.shadcn.com/), licença MIT.
- Fotos do [Unsplash](https://unsplash.com), [licença Unsplash](https://unsplash.com/license).

## Autor

Luís Nunes — [GitHub](https://github.com/Luisr-nunes) · [LinkedIn](https://www.linkedin.com/in/luis-nunes-dev/)

Projeto acadêmico do curso de Análise e Desenvolvimento de Sistemas da Cesar School.
