# Lucas Pio — Linktree

🇺🇸 [Read in English](./README-en.md)

Uma página pessoal e responsiva que reúne minha empresa, canais de contato e trabalhos em um só lugar.

## Propósito

Este repositório contém uma landing page independente que funciona como meu cartão de visitas digital. O layout limpo e responsivo em cartões destaca a O Ponto Web e facilita o contato de potenciais clientes.

Ela leva para:

- **O Ponto Web** — minha empresa de desenvolvimento web
- **WhatsApp** — conversa rápida
- **E-mail** — contato direto
- **GitHub** — meu código e projetos

A página também inclui navegação semântica, foco visível para teclado, suporte à preferência por movimento reduzido e layout para dispositivos móveis.

## Stack

Apenas um arquivo HTML. Sem build, framework, gerenciador de pacotes ou JavaScript — é só abrir no navegador e usar.

- HTML5
- CSS3
- `DM Sans` — textos corridos e de interface
- `Manrope` — títulos e elementos da marca

As duas fontes são carregadas via Google Fonts (CDN).

## Estrutura do projeto

```
.
├── index.html          # a landing page e seus estilos
├── README.md           # seletor de idioma
├── README-en.md        # documentação em inglês
├── README-pt-br.md     # documentação em português brasileiro
└── LICENSE             # licença MIT
```

## Executando localmente

Abra o arquivo `index.html` diretamente no navegador. Se preferir servi-lo por HTTP, inicie um servidor estático na pasta do projeto, por exemplo:

```bash
python3 -m http.server 8000
```

Depois, acesse `http://localhost:8000`.

## Personalizando

Tudo está em `index.html`:

| O que mudar | Onde procurar |
|---|---|
| Cores | `:root { ... }` dentro do `<style>` |
| Título da página e descrição de busca | `<title>` e `<meta name="description">` |
| Nome e apresentação | `<header class="profile">` |
| Empresa em destaque | `<a class="company-card">` |
| Links de contato e projetos | `<nav class="links">` |
| Texto do rodapé | `<footer>` |

## Publicando

Qualquer hospedagem estática funciona, por exemplo:

- **GitHub Pages** — envie o repositório e ative o Pages nas configurações.
- **Vercel** ou **Netlify** — arraste a pasta e pronto.

## Contato

- GitHub: [github.com/LukasPio](https://github.com/LukasPio)
- E-mail: contato.lukaspio@gmail.com
- WhatsApp: [wa.me/5511945462692](https://wa.me/5511945462692)

## Fique à vontade pra usar

Fique à vontade pra dar fork ou copiar esse código e trocar pelas suas próprias informações — nome, bio, links e cores. Não precisa pedir permissão nem me dar crédito, é só fazer sua versão.

Este projeto está disponível sob a [Licença MIT](./LICENSE).
