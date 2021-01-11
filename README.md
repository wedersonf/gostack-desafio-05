<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios-new.png" />
<h2 align="center">Desafio 05 Banco de dados e upload de arquivos no Node.js</h2>


Criação de uma API que possibilita registar transações de entrada e saída com suas categorias, se a categoria não existe no banco de dados, a mesma é criada automaticamente. Além disso, é feita uma validação onde só é possível realizar a transação de saída se houver valor suficiente em caixa.
<br><br>
Também é possível listar todas transações com um balanço do total de entradas, saídas e valor total em caixa.
<br><br>
A aplicação permite ainda, que seja importado um arquivo .csv com as transações, e as mesmas são incluídas com as demais, após o registro o arquivo que foi realizado o upload é deletado, ficando apenas registrada as transações na aplicação.
<br>
<br>
Diferente do desafio 04, essa aplicação armazena os dados em uma base de dados PostgreSQL, utilizando os conceitos de migrations com TypeORM.
