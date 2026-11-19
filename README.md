# 3ADS EDU AI Playbook

Playbook de Inteligência Artificial da 3ADS EDU, publicado como página estática.

**Visualização:** https://atendimento3ads.github.io/3ads-edu-ai-playbook/

## Estrutura

```
.
├── index.html   # Playbook completo (arquivo único, autocontido)
├── audio/
│   └── orbe-inicio.m4a  # Narração + música da apresentação do Orbe (38 s)
├── favicon.ico, favicon-32.png, favicon-512.png, apple-touch-icon.png  # Ícone do site ("3" da 3ADS)
├── .nojekyll    # Publica no GitHub Pages sem processamento Jekyll
└── README.md
```

## Como visualizar localmente

Abra `index.html` direto no navegador. A página precisa de JavaScript habilitado.

Para a narração do Orbe tocar, a pasta `audio/` precisa estar ao lado do `index.html`. Para trocar o áudio, substitua `audio/orbe-inicio.m4a` mantendo o mesmo nome. As legendas seguem os tempos da narração atual (começa em 1,2 s).

## Publicação

O GitHub Pages serve a branch `main`, pasta raiz (`/`). Qualquer push em `main` atualiza o site em 1 a 2 minutos.
