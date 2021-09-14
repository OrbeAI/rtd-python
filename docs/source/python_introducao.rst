PYTHON: INTRODUÇÃO.
=====

.. 01.PRIMEIROS PASSOS:

01.”Olá, mundo!”
------------

Talvez a primeira coisa que aprendemos a fazer quando começamos a estudar uma linguagem de programação é imprimir a frase “Hello, world!” (“Olá, mundo!”).

Para isso usamos o comando ``print("Texto a ser impresso aqui")``.

.. code-block:: python

   print("Olá, mundo!")
   >>> Olá, mundo!

   
01.b.Comentários no código.
----------------

Em Python alguns caracteres são especiais e tem uma funcionalidade específica. 

O primeiro que veremos é o ``#``. Quando começamos uma linha com o caracter “#” o texto não é interpretado pelo computador e fica na cor verde.

Isto é um comentário, ou seja, um pedaço do texto que deixamos dentro do código para que outras pessoas (ou nós mesmos no futuro) possam entender melhor o que estamos fazendo ao longo do código.


.. code-block:: python
   
   #Isto é um comentário
   
   
  02.Variáveis
----------------

**Variável é como se fosse uma gaveta na memória do computador.**

Quando armazenamos camisetas, vamos na frente da gaveta e colocamos uma etiqueta com o nome do conteúdo armazenado (no caso “roupa”).

Mas o conteúdo, ou seja, o valor armazenado pode variar, por isso o nome “variável”.

Ex: tiramos as camisetas e colocamos calças.

**Em programação uma variável armazena um valor**, que pode ser inúmeras coisas, desde texto, números, resultados de contas e etc.
Uma variável é criada na primeira vez que um valor é armazenado nela.

  02.a.Nomenclatura de variáveis.
----------------

| Nome da Variável | Válido | Comentários |
|------------------|--------|-------------------------------------------------|
| a3               |  SIM   | Python permite que uma variável contenha números|
| idade            |  SIM   | Nome formado por letras                         |
| idade90          |  SIM   | Nome formado por letras e números               |
| salario_medio    |  SIM   | O símbolo _ é permitido                         |
| salario medio    |  NÃO   | Nome de variáveis podem conter espaços          |
| _b               |  SIM   | O símbolo _ é permitido em variáveis            |
| 2a               |  NÃO   | Variáveis não podem começar com números         |
