# Desafio FullCycle Docker, Node e Nginx

Esse repositório foi criado para o desáfio do módulo de docker do curso Full Cycle. 

**Para rodar digite docker-compose up -d no terminal**

**Abaixo segue a descrição do desafio fornecida pelo curso:**

> Nesse desafio você colocará em prática o que aprendemos em relação a utilização do nginx como proxy reverso. A idéia principal é que quando um usuário acesse o nginx, o mesmo fará uma chamada em nossa aplicação node.js. Essa aplicação por sua vez adicionará um registro em nosso banco de dados mysql, cadastrando um nome na tabela people.
>
> O retorno da aplicação node.js para o nginx deverá ser:
>
> </p>
>
> <p>&lt;h1&gt;Full Cycle Rocks!&lt;/h1&gt;</p>
>
> <p> 
>
> </p>
>
> <p>- Lista de nomes cadastrada no banco de dados.</p>
>
> <p> 
>
> Gere o docker-compose de uma forma que basta apenas rodarmos: docker-compose up -d que tudo deverá estar funcionando e disponível na porta: 8080.
>
> Suba tudo em um repositório e faça a entrega.
