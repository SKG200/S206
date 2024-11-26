A documentação para a API utilizada nos teste se encontra em https://dummyjson.com/docs


Para gerar o relatório de teste, no terminal, navegue até o diretório em que a coleção se encontra, e utilize o comando:

newman run ProvaS206.postman_collection.json

Ou, para gerar um relatório html:

newman run ProvaS206.postman_collection.json -r htmlextra --reporter-htmlextra-export RelatorioProvaS206.html
