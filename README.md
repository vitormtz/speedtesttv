# SpeedTest TV — site

Página institucional e política de privacidade do aplicativo **SpeedTest TV**
para Samsung Smart TV.

Publicado em GitHub Pages. Serve a dois propósitos exigidos pelo
[TV Seller Office](https://seller.samsungapps.com/tv/) da Samsung:

| Campo exigido | Página |
|---|---|
| Home page URL | `index.html` |
| Privacy policy URL | `privacy.html` |

## Estrutura

```
index.html      página principal
privacy.html    política de privacidade
style.css       identidade visual do app
assets/         logo, marca e capturas de tela
```

Bilíngue (pt-BR / en-US). O idioma inicial vem de `navigator.language` e a
escolha do visitante fica em `localStorage`. Sem framework, sem build, sem
dependência externa.

## O aplicativo

Mede ping, download e upload direto da televisão. Não tem conta, não tem
anúncios e não grava nada no aparelho. As medições usam serviços públicos
(Cloudflare e Netflix Open Connect), que entregam um servidor próximo do
usuário em qualquer país.
