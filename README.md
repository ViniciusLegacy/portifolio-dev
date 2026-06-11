# Portfólio — Vinícius Leandro

Site de portfólio pessoal apresentando minha trajetória como Desenvolvedor Full Stack, com seções de introdução, projetos em destaque, serviços oferecidos e contato.

## Tecnologias

- **HTML5** — estrutura semântica das páginas
- **CSS3** — estilização com variáveis customizadas, Grid Layout e responsividade
- **Google Fonts** — fontes Asap, Inconsolata e Maven Pro

Nenhuma biblioteca ou framework JavaScript foi utilizado; o projeto é 100% estático.

## Estrutura

```
portifolio-dev/
├── index.html              # Página principal
├── assets/
│   ├── profile.jpeg        # Foto de perfil
│   ├── icons/              # Ícones SVG (tecnologias e redes sociais)
│   └── images/             # Thumbnails dos projetos
└── styles/
    ├── index.css           # Ponto de entrada — importa todos os demais
    ├── global.css          # Reset, variáveis de cor e tipografia
    ├── utilities.css       # Classes utilitárias (grid, grid-flow-col, etc.)
    ├── header.css          # Estilos da seção de introdução (header)
    └── main.css            # Estilos das seções de projetos, serviços e contato
```

## Como rodar localmente

O projeto é estático e não precisa de nenhuma instalação. Basta servir os arquivos com qualquer servidor HTTP local.

### Opção 1 — Live Server (VS Code)

1. Instale a extensão [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) no VS Code.
2. Abra a pasta do projeto no VS Code.
3. Clique com o botão direito no `index.html` e selecione **"Open with Live Server"**, ou clique em **"Go Live"** na barra de status.
4. O navegador abrirá automaticamente em `http://127.0.0.1:5500`.

### Opção 2 — qualquer servidor HTTP simples

Com Python instalado, rode na raiz do projeto:

```bash
# Python 3
python -m http.server 5500
```

Depois acesse `http://localhost:5500` no navegador.
