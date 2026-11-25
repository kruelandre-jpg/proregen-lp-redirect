# proregen-lp-redirect

Redirecionamentos estáticos para as landing pages atuais dos e-books Proregen.

Não é uma vitrine: cada caminho antigo leva a **um** e-book.

| Caminho em `lp.proregen.com.br` | Destino |
|---|---|
| `/` e `/artrose/` | https://kruelandre-jpg.github.io/proregen-lp-ebook-artrose/ |
| `/terapia-choque-laser/` | https://kruelandre-jpg.github.io/proregen-lp-ebook-choque/ |
| `/lesoes-no-joelho/` | https://kruelandre-jpg.github.io/proregen-lp-ebook-joelho/ |
| qualquer outro caminho (`404.html`) | e-book de artrose |

O DNS de `lp.proregen.com.br` é configurado à parte, no MDServer, e não faz parte deste repositório. GitHub Pages está neste repo, branch `main`, pasta raiz, com o CNAME `lp.proregen.com.br`.
