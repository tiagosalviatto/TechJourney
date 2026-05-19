# Tech Journey

Página institucional do programa de desenvolvimento **Tech Journey** da Yandeh.

## Sobre

Landing page única que apresenta o programa interno de capacitação técnica e comportamental para colaboradores: modalidades aceitas, critérios de elegibilidade, processo de candidatura e compromissos entre empresa e participante.

## Estrutura

Arquivo único, autocontido — sem dependências de build:

```
TechJourney/
├── TechJourney_Expanded.html   # Página completa (HTML + CSS inline)
└── README.md
```

A única dependência externa é a fonte **Roboto** via Google Fonts.

## Seções da página

1. **Hero** — apresentação do programa e CTAs
2. **Modalidades** — cinco formatos elegíveis (plataformas, cursos curtos, eventos, certificações, outros)
3. **Elegibilidade** — quem pode participar e fluxo de aprovação
4. **Pipeline** — passo a passo da candidatura
5. **Critérios** — tabela de requisitos
6. **Compromissos** — o que a Yandeh oferece × o que se espera do colaborador
7. **FAQ** — dúvidas frequentes

## Como visualizar

Abra `TechJourney_Expanded.html` direto no navegador.

## Customização

Toda a paleta está em variáveis CSS no topo do `<style>`, dentro de `:root`. Para ajustar cores da identidade, edite ali — as variáveis se propagam para toda a página.

## Stack

HTML5 + CSS3 puro. Sem JavaScript, sem framework, sem build.
