# Utilização do Sass no projeto

Neste projeto foi utilizado o pré-processador Sass
Para utilizar o Sass é necessário instala-lo na maquina, para isso basta seguir o guia abaixo:

[Como instalar Sass](https://sass-lang.com/install)

Para edição do css é necessário alterar o arquivo que sem encontra na pasta "html/styles/src/sample.scss"
Após as edições necessárias no arquivo é preciso compilar o arquivo scss em css, para isso basta executar o comando abaixo na raiz do projeto:
```sh
sass html/styles/src/sample.scss html/styles/sample.css
```

Ou se preferir, é possivel utilizar a compilação continua, em que cada alteração realizada no arquivo scss ele irá gerar um css atualizado, para isso basta executar o comando abaixo e manter o terminal aberto
```sh
sass --watch html/styles/src/sample.scss html/styles/sample.css
```