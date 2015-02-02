# developers.redu.com.br

Este é o código fonte da documentação da [API REST do Redu](http://developers.redu.com.br).

## Pré-requisitos

Esta documentação foi feita utilizando o [Jekyll](https://github.com/mojombo/jekyll). Para utiliza-lo você precisa ter o [interpretador Ruby](http://rvm.io/) instalado bem como o [Bundler](http://gembundler.com/#getting-started).

## Instalação

Clone o repositório:

    $ git clone git@github.com:redu/redu.github.com.git

Dentro do diretório, instale as dependências:

    $ bundle install

Inicialize o servidor:

    $ bundle exec jekyll --server
    
Pronto, basta visitar [http://0.0.0.0:4000](http://0.0.0.0:4000) através do navegador para ter acesso a documentação.

## Uso

A documentação é escrita utilizando a linguagem de marcação [Textile](http://textile.thresholdstate.com/). 

Para cada link da navegação global há um arquivo correspondente dentro do diretório ``resources``. Arquivos estáticos devem ficar na pasta ``assets``.

## Contribuindo

1. Faça fork do projeto
2. Crie um novo branch (`git checkout -b my-new-feature`)
3. Realize seus commits (`git commit -am 'Add some feature'`)
4. Dê push nas modificações (`git push origin my-new-feature`)
5. Envie um pull request

## Publicando

Após qualquer mudança em arquivos .textile do site, é necessário executar o seguinte comando para gerar as páginas estáticas localmente e publicar o novo site em produção:

    $ rake publish

O usuário deve ter privilégios de commiter, além de possuir uma [SSH key no computador associada à respectiva conta](https://help.github.com/articles/generating-ssh-keys/).

<img src="https://github.com/downloads/redu/redupy/redutech-marca.png" alt="Redu Educational Technologies" width="300">

Este projeto é financiado e mantido pelo [Redu Educational Techologies](http://tech.redu.com.br).

## Copyright

Copyright (c) 2012 Redu Educational Technologies

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
