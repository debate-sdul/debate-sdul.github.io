## README
![SDUL LOGO](https://gitlab.com/alexaagithub/sitesdul/-/raw/master/sdul/static/images/redname.png)

Website da Sociedade de Debate da Universidade de Lisboa. Criado com [Hugo](https://gohugo.io/) a partir do tema [Bigspring](https://github.com/themefisher/bigspring-light).

## Instalação
```bash
$ git clone https://github.com/debate-sdul/debate-sdul.github.io.git

$ hugo server -D
```
(abrir http://localhost:1313/ no browser)

## Modificar o conteúdo das páginas
```bash
$ cd content/'pagina_a_modificar'

$ open _index.md
```
## Publicar as alterações
```bash
$ hugo -t bigspring-light

$ mv /site/public/* /site/

$ rm -r public/

$ git add .

$ git commit -am "alteracao"

$ git push