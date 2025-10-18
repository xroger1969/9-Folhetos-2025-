# JW Folhetos – Página de Ministério

Este repositório contém uma página web simples que reúne os nove folhetos digitais lançados em outubro de 2025 no jw.org (versão português de Portugal).
Cada folheto é apresentado numa carta com o respectivo título, um código QR gerado em tempo real e um link para abrir directamente o folheto em jw.org.

## Estrutura

```
jw-folhetos/
├── index.html        # Página principal com a lista de folhetos
├── assets/
│   ├── style.css     # Folha de estilos inspirada nas cores do jw.org
│   └── favicon.png   # Ícone "JW" em azul para a aba do navegador
└── README.md         # Este ficheiro
```

## Como usar

1. **Publicação**: Para disponibilizar esta página através do GitHub Pages, basta criar um repositório com estes ficheiros e activá-lo em *Settings → Pages* na branch principal.
2. **Modo offline**: Também pode abrir o arquivo `index.html` directamente no navegador sem ligação à internet; os códigos QR são gerados localmente via `QRCode.js`.
3. **Adaptação**: Caso necessite de actualizar os links dos folhetos, edite a lista no script JavaScript em `index.html`.

## Nota

Esta página é meramente informativa e não oficial. Os textos, imagens e links pertencem a jw.org e são usados apenas para ajudar na partilha durante o ministério.