##EncontrosPET

O projeto criado no *GitHub* tem objetivo de incentivar a organização de projetos por meio de modificações enviada com log de alterações para melhor entendimento entre programadores que trabalham em um mesmo projeto. Aqui não é diferente, o objetivo principal do projeto *EncontrosPET* no *GitHub* é manter organizado e comentado todas as alterações feitas em códigos que se referem a projetos sob **AUTORIA** do *EncontrosPET* seja quais forem eles.

##Estrutura das pastas

A estrutura das pasta é feita de maneira que possa ser realizado um trabalho da maneira mais facil possível para os desenvolvedores, então para entender como o projeto **EncontrosPET** está organizado, veja o esquema e explicação logo abaixo.

```
.
├── node_modules
├── dist
    ├── pasta1
    ├── pasta2
    ├── ...
    └── pastaN
├── src
    ├── pasta1
    ├── pasta2
    ├── ...
    └── pastaN
```

- Pasta `dist`: Onde ficará pasta dos arquivos de produção, raramente deve-se mexer no conteúdo desta pasta, pois os arquivo colocados aqui serão gerados automáticamente.
- Pasta `src`: Onde ficará os arquivos que serão modificados, os arquivos de deenvolvimento e em fase de testes, estes sim pode-se mexer até ser desenvolvido ou solucionado algum tipo de problema.
- Pasta `node_modules`: Pasta onde ficar modulos e dependenciar que serão gerenciadas pelo gerenciador `npm` e `gulp`, apenas em casos de extrema necessidade pode-se mexer nesta pasta, mas é recomendado que nunca se mexa.

As sub-pastas que ficarão nas pastas `dist` e `src` são os denominados projetos, por exemplo: *forum*, *blog* e outros.

##Minificação e Compressão

No projeto iremos utilizar o [GulpJS](http://gulpjs.com/) para fazer a minificação e compressão de arquivos *javascripts*, *css* e *html (quando possível)* para deixar o nosso código mais seguro e ilegível para programadores fora da nossa equipe, dificultando a sua leitura e levando também um conteúdo mais leve para quem visita a nossa página.

> Sugiro que quem não tem conhecimento sobre essa belíssima ferramenta, deem uma olhada e breve estudada.

##Bugs

Em caso de alguém dentro do projeto algum problema que deva ser resolvido ou sugestão de novas funções que acha interessante implementar em algum projeto, deverá obrigatoriamente ser informado na aba [Issues](https://github.com/EncontrosPet/encontrospet/issues) do projeto, visando manter organizado as solicitações de correção e melhorias.

Issues é onde as pessoas colocam dúvidas, problemas a serem solucionados, sugestões e outras informações, mantendo organizado todo esquema de alterações em projetos.

####Informando sobre bug ou sugestão

O usuário que quiser informar algum bug ou problema em determinado projeto, deverá abrir uma [nova issue](https://github.com/EncontrosPet/encontrospet/issues/new) referenciando ao qual projeto o problema ou bug se refere adicionando link se possível.

Se caso o usuário ache necessário colocar algum tipo de código como sugestão, o mesmo deverá criar um [Gist](https://gist.github.com/) preferencialmente ou caso seja código pequeno poderá criar usando a linguagem Markdown do *GitHub* para referencia-las. [Veja aqui como deve-se criar citações de códigos](https://help.github.com/articles/creating-and-highlighting-code-blocks/).

####O Gist

O [Gist](https://gist.github.com/) é um local onde poderá ser colocado trechos de códigos ou até mesmo códigos completos para ser referenciados em algum lugar deste projeto, caso o usuário ache necessário. Dê preferencia a criar gist de modo secreto, onde os código não será listado em buscar por outros usuários do mundo. Entenda que gist secreto não é o mesmo que gist privado, mas o gist secreto poderá ser compartilhado entre os desenvolvedores do projeto *EncontrosPET*.
