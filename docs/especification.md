# Especificações do Projeto

Diversos leitores enfrentam desafios na organização de suas leituras e na descoberta de novos livros de acordo com seus gostos individuais. 
Nesse contexto, desenvolveremos um Sistema Web para ajudar os amantes da leitura a organizar seus livros de forma prática. 
O usuário poderá cadastrar um livro e informar seu status de leitura, categorizar livros, marcar páginas, realizar anotações e recomendação de novos livros de acordo com os gostos individuais.

## Personas

1º Persona

Carla Mendes é uma bibliotecária de 35 anos apaixonada por livros e pela promoção da leitura. Ela trabalha em uma biblioteca comunitária em um bairro de baixa renda, onde enfrenta o desafio de atrair mais leitores, especialmente crianças e jovens, para a biblioteca. Carla está sempre em busca de novas formas de incentivar a leitura e expandir o acesso aos livros na comunidade.

2º Persona

Sofia Oliveira é uma estudante universitária de 20 anos cursando Letras. Ela é uma leitora ávida e está sempre em busca de novos livros para expandir seus horizontes literários. Sofia enfrenta o desafio de conciliar os estudos com sua paixão pela leitura, buscando maneiras eficientes de gerenciar seu tempo e suas leituras.


3º Persona

Marcos Silva é um advogado de 45 anos com uma rotina agitada e estressante. Apesar de seu trabalho exigente, ele sempre encontra tempo para relaxar e descontrair por meio da leitura. Marcos busca uma forma conveniente de acessar e gerenciar seus livros favoritos, mesmo em meio à correria do dia a dia e compartilhar suas opiniões literárias com outros leitores. 

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Leitor ávido  | Organizar minhas leituras          | Conciliar estudos e leitura
|Bibliotecária | Recomendar novos livros | Incentivar a leitura
|Leitor  | Gerenciar meus lviros | Organizar minhas leituras
|Estudante | Encontrar novos livros | Expandir meus horizontes literários
|Leitor | Compartilhar minhas opiniões literária | Conhecer novos leitores e participar de um grupo


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade | 
|------|-----------------------------------------|----|  
|RF-001|	Permitir que os usuários adicionem livros à sua biblioteca pessoal, inserindo informações como título, autor, gênero, data de leitura, classificação, entre outros.|	ALTA
|RF-002|	Permitir que os usuários organizem seus livros em diferentes categorias, como lidos, em andamento, desejados, favoritos, etc.	|ALTA
|RF-003|	Oferecer uma função de busca que permita aos usuários encontrar livros por título, autor, gênero, ou outras categorias relevantes.|	MÉDIA
|RF-004|	Basear recomendações de livros em preferências de leitura do usuário, histórico de leitura e avaliações de outros usuários.	|ALTA
|RF-005|	Permitir que os usuários avaliem e escrevam resenhas sobre os livros que leram, compartilhando suas opiniões com a comunidade.|	MÉDIA
|RF-006|	Permitir que os usuários exportem seus dados de leitura, incluindo listas de livros, resenhas e estatísticas, para outros formatos ou plataformas.|	MÉDIA


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001|	Garantir que a plataforma seja responsiva.|	ALTA
|RNF-002|	Desenvolver uma interface intuitiva e fácil de usar, que permita aos usuários navegar e interagir com a plataforma sem dificuldades.|	ALTA
|RNF-003|	Assegurar que a plataforma seja compatível com uma variedade de dispositivos e navegadores web, incluindo computadores, tablets e smartphones.|	ALTA
|RNF-004|	Desenvolver o código-fonte de forma modular e bem documentada, facilitando futuras atualizações e manutenção do sistema.|	MÉDIA
|RNF-005|	Garantir a privacidade dos usuários, implementando políticas claras de privacidade e obtendo consentimento para o uso de dados pessoais.|	ALTA

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |
|03| Ter FrontEnd com ( Javascripit, HMTL, Css) desenvolvidos|


