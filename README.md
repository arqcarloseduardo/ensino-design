# Ensino Design — Centro de Conhecimento

> Materiais de formação para times de design que querem resultados reais.

Site disponível em: **https://carloseduardo-arq.github.io/ensino-design/**

## Módulos

| Página | Arquivo | Conteúdo |
|--------|---------|----------|
| Hub central | `index.html` | Navegação para todos os módulos |
| Fundamentos do Design Gráfico | `fundamentosdodesign.html` | Elementos, composição, cor, tipografia, Gestalt, Design Systems (13 seções) |
| Diagnóstico de Time de Design | `diagnostico-time-design.html` | Diagnóstico, qualidade, rotina semanal, plano de 4 semanas (10 seções) |
| Intenção Comunicativa | `intencao-comunicativa.html` | Os 4 tipos de intenção: informar, engajar, converter, salvar (7 seções) |

## Estrutura

```
/
├── index.html                  # hub central
├── fundamentosdodesign.html
├── diagnostico-time-design.html
├── intencao-comunicativa.html
├── assets/
│   └── imagens/                # imagens organizadas por tema
└── bases/
    └── baseTextual/            # arquivos markdown (fontes dos conteúdos)
```

## Stack

- HTML5 + CSS3 + Vanilla JS — sem frameworks, sem build tools
- Fontes: [Syne](https://fonts.google.com/specimen/Syne) (títulos) + [DM Sans](https://fonts.google.com/specimen/DM+Sans) (corpo)
- Hospedagem: GitHub Pages

## Como contribuir

1. Edite os arquivos HTML diretamente
2. Para novas imagens: adicione em `assets/imagens/[tema]/`
3. Faça commit e push — o GitHub Pages publica automaticamente
