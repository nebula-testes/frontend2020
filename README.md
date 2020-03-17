# Teste Frontend Dev (estágio)

## Descrição
Bem-vindo ao processo seletivo da Nébula Sistemas. Primeiramente, desejamos boa sorte e esperamos que você se divirta programando o que for proposto. Estamos ansiosos para te conhecer!

A Nébula Sistemas é uma software house localizada em Betim – MG, que atende o ramo de food service há 9 anos, entregando software como serviço (SaaS), promovendo a transformação tecnológica em bares, restaurantes, cantinas escolares e até mesmo eventos.

O teste a seguir servirá para avaliar sua capacidade básica de codificar uma solução simples e objetiva, utilizando as tecnologias que são usadas diariamente pela equipe de desenvolvimento. Sem mais delongas... bora codar!

## Aplicação
O objetivo é reproduir um cenário muito parecido com o que é vivido no cotidiano da Nébula. Nesse repo, existem alguns wireframes que devem servir de modelo para construção das telas.

Seu papel será elaborar o frontend **utilizando ReactJS** e consumir uma API já pronta para dar vida à aplicação.

### Contexto
Você foi contratado pela Offline Disco, uma empresa de discos de vinil raros, para poder criar o frontend de uma aplicação web que consumirá os recursos necessários do backend que já foi desenvolvido. O protótipo já foi criado pelo designer e agora cabe à você dar vida à aplicação convertendo-o para código.

Dentro do link http://wasd.com.br/swagger, haverá uma lista de endpoints os quais você pode consumir para buscar informações de um banco de dados real - tais como: lista de discos, lista de categoria, etc - e fazer com que sua aplicação torne-se funcional. Segue abaixo uma breve lista com os endpoints:

| Verbo HTTP    | Descrição     | Resultado esperado  |
| :------------ |:-------------| :-----|
| [GET]         | Obter uma lista de todos os discos |  Status 200|
| [GET]         | Obter uma lista de categorias|   Status 200    |
| [POST]        | Criar um novo disco              | Status 201      |
| [PUT]         | Alterar informações de um artista já cadastrado               | Status 200 |
| [DELETE]       | Excluir uma faixa de um disco               | Status 200 |

### Telas
Existem dois tipos de tela: as de usuários comuns e as de administradores. Basicamente, a única diferença entre elas é a adição de controles para adição/remoção/alteração nas telas de administradores.

Sinta-se livre para dar seu toque ao layout proposto, mas matenha-se dentro do contexto. 

## Deploy

Para entregar seu código, basta fazer um fork desse repo, criar uma branch com seu nome completo e realizar um pull request. 

Será feita uma análise da aplicação e o resultado será enviado para o e-mail que iniciou o contato, ou seja, o email que enviou o currículo.
