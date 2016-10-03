## Pasta `src`

Esta pasta é destinada a arquivos de desenvolvimento, aqui deverão ser colocado todos os arquivos que estão sendo desenvolvido, e, todos estes arquivos deverão está na estrutura indicada para melhor funcionamento do sistema.

## Estrutura

A estrutura é muito importante para um bom funcionamento do sistema. E deverá seguir todo o modelo abaixo.

```
├── src
    └── Plugin_Wordpress
     	├── app
     	├── src
	    |	└── wp-content
	    |		└── plugins
	    |			└── Plugin_Wordpress
	    |				├── Arquivo1.php
	    |				├── Arquivo2.php
	    |				└── ArquivoN.php
	 	└── gulfile.js	   
``` 

- Arquivos da pasta `src` deverão ser organizado da forma indicada no exemplo acima.
- Dentro da pasta `app` deverá conter o núcleo do *Wordpress*. Mas esta será ignorada na hora do `commit`.
- Dentro da pasta `src` deverá conter apenas os arquivos que estão sendo desenvolvidos, na estrutura informada acima.
- Quando o arquivo `gulpfile.js` for executado, automáticamente ele irá fazer um **build** dos arquivos, minificando e comprimindo e copiando para a pasta `app` assim poderá ser realizado testes antes de realizar o `commit`.

> O **Wordpress** foi usado como exemplo apenas, mas este modelo servirá para qualquer aplicação.