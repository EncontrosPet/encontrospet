## Pasta `dist`

Esta pasta é destinada a arquivos de produção raramente deve-se mexer nesta pasta, pois os arquivos do mesmo serão gerados e movidos automáticamente da pasta `src`.

## Informações

É importante citar que dentro da pasta de cada projeto, que ficará localizada na pasta `dist` deverá conter somente os arquivos necessário para que o sistema rode como desejado. Um exemplo de como seria é, se você estiver desenvolvendo um plugin para *Wordpress* dentro da pasta do projeto `Plugin_Wordpress` deverá conter somente os arquivo do plugin, evitando ser criado um repositório grande.

## Estrutura

A estrutura também é importante, como no caso acima a estrutura deveria ser como esta que está logo abaixo:

```
├── dist
    └── Plugin_Wordpress
    	└── wp-content
    		└── plugins
    			└── Plugin_Wordpress
    				├── Arquivo1.php
    				├── Arquivo2.php
    				└── ArquivoN.php  
```

> Note que os arquivos da pasta `dist` serão gerados automáticamente, mas para titulo de informação esta é a estrutura que irá permanecer na pasta `dist`.