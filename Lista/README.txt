A documentação para a API utilizada nos teste se encontra em https://fakestoreapi.com/docs


Para gerar o relatório de teste, navegue até o diretório em que a coleção e o ambiente se encontram, e utilize o comando:

newman run Lista.postman_collection.json -e FakeStore.postman_environment.json

no terminal, ou, para gerar um relatório html:

newman run Lista.postman_collection.json -e FakeStore.postman_environment.json -r htmlextra --reporter-htmlextra-export relatorio.html