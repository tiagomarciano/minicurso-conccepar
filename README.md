CONCCEPAR VIII  
==========================
Congresso Científico da Região Centro-Ocidental do Paraná

Minicurso: Desenvolvimento de layouts com bootstrap
* Tiago Marciano | Analista de Sistemas Pleno (Faculdade Intgrado de Campo Mourão/PR)
* Colaboradores: [Alan Ferreira dos Santos](https://github.com/woodyalan), [Luis Henrique Jurasseck](https://github.com/jurasseck)

Instruções
==========================

* Primeiro faça o download ou clone este repositório.
* No terminal execute `npm install` para instalar as dependências de desenvolvedor.

Você precisa ter o Gulp instalado, caso já o tenha ignore a seguinte linha:
* `npm install -g gulp`

Você também irá precisar ter o Bower instalado, no terminal execute as seguintes linhas:
* `npm install -g bower`
* No terminal execute `bower install` para instalar as dependências de desenvolvedor.
* Para instalar novos pacotes acesse https://bower.io/search, exemplo: 
* `bower install jquery --save`

Durante o desenvolvimento, execute a tarefa padrão para que você tenha observadores e sincronização com o navegador. Basta fazer o seguinte:
* Execute `gulp` para iniciá-lo
* Tente modificar arquivos html, scss e javascript e veja como a página é atualizada com o BrowserSync.

Quando estiver pronto para implementar, basta fazer o seguinte:
* Execute `gulp deploy`.
* Todos os arquivos que você precisa estarão em `/dist` com suas imagens otimizadas, css compactado e js compactado.

Mais informações
==========================
Confira no site http://www.ryanbensonmedia.com/harvest para mais informações.
