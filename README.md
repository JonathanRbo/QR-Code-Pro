# QR Code Generator Pro

Gerador de QR Codes com duas versoes: uma funcional e uma... nem tanto.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## Sobre

Projeto com dois geradores de QR Code side by side:

- **Versao Oficial** — gerador real, funcional, com opcoes de personalizacao
- **Versao Meme** — identico visualmente, mas todo QR gerado leva para o Rick Astley

## Funcionalidades

### Versao Oficial (`index.html`)

- Gera QR Codes a partir de URLs ou texto livre
- Escolha de tamanho (200x200 ate 512x512)
- Color picker para cor do QR Code
- Validacao de URL
- Contador de caracteres no modo texto
- Download em PNG
- Layout responsivo

### Versao Meme (`meme.html`)

- Interface identica a versao oficial
- Todo QR Code gerado aponta para [Never Gonna Give You Up](https://www.youtube.com/watch?v=dQw4w9WgXcQ)
- Fake loader com etapas convincentes
- No segundo download, abre video fullscreen com rickroll
- A vitima nao percebe a diferenca

## Tecnologias

- [Squeleton CSS](https://squeleton.dev) — framework CSS utilitario
- [QRCode.js](https://github.com/davidshimjs/qrcodejs) — geracao de QR Codes client-side
- [WOW.js](https://github.com/graingert/wow) — animacoes on-scroll

## Como Usar

1. Clone ou baixe o projeto
2. Abra `index.html` para o gerador real
3. Abra `meme.html` para a versao troll
4. Nao precisa de servidor — tudo roda no navegador

## Estrutura

```
├── index.html    # Gerador oficial (funcional)
├── meme.html     # Gerador meme (rickroll)
└── README.md
```

## Licenca

MIT — use como quiser, inclusive pra trollar seus amigos.
