# Tech Journey

Página institucional do programa de desenvolvimento **Tech Journey** da Yandeh.

## Sobre

Landing page única que apresenta o programa interno de capacitação técnica e comportamental para colaboradores: modalidades aceitas, critérios de elegibilidade, processo de candidatura e compromissos entre empresa e participante.

## Estrutura

Arquivo único, autocontido — sem dependências de build:

```
TechJourney/
├── index.html          # Página completa (HTML + CSS inline)
├── README.md
└── assets/
    ├── logo.png        # Logo horizontal (marca + wordmark) — usado no cabeçalho
    └── logo_square.png # Marca quadrada — usada no hero ao lado do wordmark
```

A única dependência externa é a fonte **Roboto** (pesos 300, 400, 500, 700) via Google Fonts.

## Seções da página

1. **Hero** — cabeçalho com logo + apresentação do programa e CTAs
2. **Modalidades** — cinco formatos elegíveis (plataformas, cursos curtos, eventos, certificações, outros)
3. **Elegibilidade** — quem pode participar e fluxo de aprovação
4. **Pipeline** — passo a passo da candidatura
5. **Critérios** — tabela de requisitos com hover destacado
6. **Compromissos** — o que a Yandeh oferece × o que se espera do colaborador
7. **FAQ** — dúvidas frequentes

## Como visualizar

Abra `index.html` direto no navegador, ou publique a pasta no GitHub Pages para acesso via URL.

## Customização

- **Paleta de cores**: variáveis CSS no topo do `<style>`, dentro de `:root`. Editar ali propaga para toda a página.
- **Logos**: substitua os arquivos em `assets/` mantendo os nomes (`logo.png` e `logo_square.png`).
- **Conteúdo textual**: todo o copy está direto no HTML — basta editar o texto entre as tags.

## Stack

HTML5 + CSS3 puro. Sem JavaScript, sem framework, sem build.
