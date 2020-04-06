Passo a passo da execução:
- Baixar os dois arquivos que estão no repositório (Collection e Variáveis) e colocar ambos em um mesmo diretório;
- Verificar se é necessário a instalação das dependëncias do Newman (Programa que vamos usar pra executar os testes), as dependências são: NodeJS e npm;
- Caso seja necessário a instalação do NodeJS vocë pode executar o comando: "sudo apt install nodejs" (linux);
- Caso seja necessário a instalação do npm vocë pode executar o comando: "sudo npm install -g newman" (linux);
- Instalar o Newman, no linux ele é baixado utilizando o comando: "curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -";
- Executar os testes, basta abrir um terminal no diretório em que os arquivos foram armazenados e executar o comando: "newman run API_Tests_POC.postman_collection.json -e API_Tests_POC.postman_environment.json".

Para mais informações a respeito da instalação ou utilização do Newman, segue o link:
https://learning.postman.com/docs/postman/collection-runs/command-line-integration-with-newman/
