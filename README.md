# nunhes.github.io
persoal

Source code to personal Github page
https://nunhes.github.io


## Github pages
Estou aseguir unha practica voluntaria de autoformación. Vou a apuntar a qui as cousas que vou facendo con ligazóns á documentación oportuna.
Estou a traballar con Git, WSL e VSCode. Entorno WSL-Windows.

Sempre é bo ler a documentación ::smiley::


- Encetando coas Paxinas de GitHub
  https://docs.github.com/en/github/working-with-github-pages/getting-started-with-github-pages

- Probar Paxinas de GitHub con Jekyll nun entorno local
  https://docs.github.com/en/github/working-with-github-pages/testing-your-github-pages-site-locally-with-jekyll

- Instalar Jekyll e dependencias
  https://jekyllrb.com/docs/installation/windows/    ver apartado adicado a WSL
  

  - Engadir o repositorio Ruby aquí [brightbox](https://www.brightbox.com/docs/ruby/ubuntu/#adding-the-repository)
  
  - ``sudo apt-get install ruby2.5 ruby2.5-dev build-essential dh-autoreconf`` me deu error asi que empreguei a referencia de https://www.ruby-lang.org/en/documentation/installation/#apt &rarr; ``sudo apt-get install ruby-full``
  
  - e para instalar jekyll: ``sudo apt install jekyll``
  
- https://jekyllrb.com/tutorials/using-jekyll-with-bundler/     foime moi útil para rematar unha instalación con exito.

  ver https://jekyllrb.com/docs/installation/ubuntu/


## Estilo
Minimizar o emprego de recursos de estilo.
.ref: https://css-tricks.com/snippets/css/complete-guide-grid/

###  Jekyll uses the kramdown Markdown processor
``sudo gem install kramdown``
https://jekyllrb.com/docs/configuration/markdown/
https://www.markdownguide.org/tools/jekyll/

## Previsualizar
bundle exec jekyll serve --watch