# Studio Aura

Landing page premium para um escritório de arquitetura e design de interiores em São Paulo, com visual sofisticado, tom escuro e detalhes em dourado.

## Visão geral

Este projeto é uma landing page estática desenvolvida em HTML, CSS e JavaScript puro, com foco em uma experiência visual luxuosa e editorial. A interface foi pensada para transmitir elegância discreta, materiais refinados e uma sensação de exclusividade.

A página inclui:

- hero com vídeo em full screen
- manifesto e posicionamento da marca
- processo de trabalho em etapas
- seleção de projetos em portfólio
- seção sobre o studio e a fundadora
- depoimentos de clientes
- formulário de contato com validação
- CTA para WhatsApp e redes sociais
- layout responsivo para desktop, tablet e mobile

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript vanilla
- Google Fonts
- Vídeos e imagens locais em `assets/`

## Estrutura do projeto

```text
lp-aura-desing/
├── assets/
│   ├── interior-dark-video.mp4
│   ├── video-camadas.mp4
│   ├── projeto-banheiro.png
│   ├── projeto-biblioteca.png
│   ├── projeto-cozinha.png
│   ├── projeto-quarto.png
│   ├── projeto-sala.png
│   ├── projeto-sala-2.png
│   └── projeto-terracota.png
├── email-marina.txt
├── index.html
├── README.md
└── skills-lock.json
```

## Como executar

Como o projeto é uma página estática, basta abrir o arquivo `index.html` em um navegador.

Para uma experiência mais fiel ao ambiente de desenvolvimento, você pode rodar um servidor local:

```bash
cd "c:\Users\user\Desktop\Curso DD\projetos\lp-aura-desing"
python -m http.server 8000
```

Em seguida, acesse:

```text
http://localhost:8000
```

## Personalização

Os principais pontos de edição ficam no arquivo `index.html`:

- textos e mensagens da marca
- títulos de seções
- dados de contato e WhatsApp
- projetos do portfólio
- blocos de depoimentos
- mensagens e labels do formulário

Para alterar a identidade visual, ajuste as variáveis CSS do `:root` no início do documento, incluindo:

- paleta de cores
- fontes
- espaçamento
- bordas e efeitos

## Design e estilo

O visual foi inspirado por referências de hotéis boutique, galerias de arte e interiores de alto padrão, com:

- fundo em tons de preto e grafite
- detalhamento em dourado suave
- tipografia elegante com contraste editorial
- composição minimalista e espaços bem respirados
- movimento sutil para reforçar a sensação de refinamento

## Observações

- O projeto foi construído em um único arquivo HTML para facilitar a entrega e a manutenção.
- Não há dependências de build ou bundler.
- A página foi pensada para funcionar como uma apresentação comercial da marca, não como um app web complexo.

## Licença

Este projeto foi criado para fins de apresentação e estudo. Consulte o proprietário do conteúdo antes de reutilizar imagens, textos ou marca para uso comercial.
