# Lucas Pio — Linktree

Uma página de link-in-bio pessoal com visual de terminal, feita para reunir meus canais de contato e trabalhos em um só lugar — e me ajudar a conseguir novos clientes freelancer.

## Propósito

Este repositório contém uma landing page única e independente que funciona como meu cartão de visitas digital. Em vez de uma lista genérica de botões, ela é estilizada como uma sessão de terminal de editor de código, o que combina com o público a que se destina: pessoas procurando contratar um desenvolvedor.

Ela leva para:

- **GitHub** — meu código e projetos anteriores
- **E-mail** — contato direto
- **WhatsApp** — mensagem rápida
- **Portfólio** *(em breve)* — uma futura página reunindo todos os projetos que já construí ou vendi

## Stack

Apenas um arquivo HTML. Sem build, sem framework, sem lógica em JavaScript — é só abrir e usar.

- `JetBrains Mono` — títulos e textos de interface no estilo terminal
- `Inter` — texto corrido (a bio)

As duas fontes são carregadas via Google Fonts (CDN).

## Estrutura do projeto

```
.
├── lucas-pio-linktree.html   # a página em si
└── README.md
```

## Personalizando

Tudo está em `lucas-pio-linktree.html`:

| O que mudar | Onde procurar |
|---|---|
| Cores | `:root { ... }` dentro do `<style>` |
| Nome / cargo | classes `.name` e `.role` |
| Texto da bio | bloco `<div class="bio">` |
| Links | seção `<div class="links">` |

### Ativando o link do portfólio

Quando a página do portfólio estiver no ar, troque:

```html
<span class="link disabled" aria-disabled="true">
```

por:

```html
<a class="link" href="https://sua-url-aqui.com" target="_blank" rel="noopener noreferrer">
```

e remova a linha `<span class="badge">em breve</span>`.

## Publicando

Qualquer hospedagem estática funciona, por exemplo:

- **GitHub Pages** — renomeie o arquivo para `index.html`, suba num repositório e ative o Pages nas configurações.
- **Vercel** ou **Netlify** — arraste a pasta e pronto.

## Contato

- GitHub: [github.com/LukasPio](https://github.com/LukasPio)
- E-mail: contato.lukaspio@gmail.com
- WhatsApp: [wa.me/5511945462692](https://wa.me/5511945462692)
