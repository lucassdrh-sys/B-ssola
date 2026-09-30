# A Bússola — Landing page

Landing page da plataforma A Bússola, de Lucas Rocha (psicólogo, CRP 04/64296): educação sobre ansiedade com ferramentas da TCC, DBT e ACT.

## Stack

Site estático: um único `index.html` com CSS e JS embutidos. Sem build, sem dependências, sem framework.

- Fonte: Archivo (Google Fonts)
- Imagens e símbolo: `assets/`
- Design de origem: projeto Claude Design "Site Inspirado em Reservatório de Dopamina", arquivo `Bussola Landing v3` (design system Modernist, acento azul)

## Estrutura

```
.
├── index.html      # a página inteira (markup + estilos + scripts)
├── assets/         # imagens das trilhas, mockup, foto e símbolo
├── vercel.json     # cleanUrls, cache de imagens e headers de segurança
└── README.md
```

## Rodar localmente

Abrir `index.html` direto no navegador já funciona.

## Deploy

Na Vercel, importar o repositório como projeto sem etapa de build — a Vercel publica os arquivos como estão.

## Editar conteúdo

Textos, preços e imagens ficam em `index.html`. O link de checkout da Hotmart (`https://pay.hotmart.com/Y107740330C`) aparece em todos os botões "Quero me inscrever" / "Inscrever-se" — ao trocar, substitua todas as ocorrências.
