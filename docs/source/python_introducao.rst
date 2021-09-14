PYTHON: INTRODUÇÃO.
********************

01.”Olá, mundo!”
=================

Talvez a primeira coisa que aprendemos a fazer quando começamos a estudar uma linguagem de programação é imprimir a frase “Hello, world!” (“Olá, mundo!”).

Para isso usamos o comando ``print("Texto a ser impresso aqui")``.

.. code-block:: python

   print("Olá, mundo!")
   >>> Olá, mundo!

   
01.a.Comentários no código.
----------------

Em Python alguns caracteres são especiais e tem uma funcionalidade específica. 

O primeiro que veremos é o ``#``. Quando começamos uma linha com o caracter “#” o texto não é interpretado pelo computador e fica na cor verde.

Isto é um comentário, ou seja, um pedaço do texto que deixamos dentro do código para que outras pessoas (ou nós mesmos no futuro) possam entender melhor o que estamos fazendo ao longo do código.


.. code-block:: python
   
   #Isto é um comentário
   
   
   
02.Variáveis
===================

**Variável é como se fosse uma gaveta na memória do computador.**

Quando armazenamos camisetas, vamos na frente da gaveta e colocamos uma etiqueta com o nome do conteúdo armazenado (no caso “roupa”).

Mas o conteúdo, ou seja, o valor armazenado pode variar, por isso o nome “variável”.

Ex: tiramos as camisetas e colocamos calças.

**Em programação uma variável armazena um valor**, que pode ser inúmeras coisas, desde texto, números, resultados de contas e etc.
Uma variável é criada na primeira vez que um valor é armazenado nela.

 
02.a.Nomenclatura de variáveis.
----------------

+------------------+--------+------------------------------------------------------------------------+
| Nome da Variável | Válido |                               Comentários                              |
+------------------+--------+------------------------------------------------------------------------+
|        a3        |   SIM  | Python permite que uma variável contenha números, porém não no começo. |
+------------------+--------+------------------------------------------------------------------------+
|       idade      |   SIM  |                        Nome formado por letras.                        |
+------------------+--------+------------------------------------------------------------------------+
|      idade90     |   SIM  |                   Nome formado por letras e números.                   |
+------------------+--------+------------------------------------------------------------------------+
|   salario_medio  |   SIM  |              O símbolo _ é permitido e facilita a leitura.             |
+------------------+--------+------------------------------------------------------------------------+
|   salario medio  |   NÃO  |                   Variáveis não podem conter espaços.                  |
+------------------+--------+------------------------------------------------------------------------+
|        _b        |   SIM  |                  O símbolo _ é permitido em variáveis.                 |
+------------------+--------+------------------------------------------------------------------------+
|        2a        |   NÃO  |                Variáveis não podem começar com números.                |
+------------------+--------+------------------------------------------------------------------------+



02.b.Criando uma variável.
----------------

Para criarmos uma variável usamos o símbolo de igualdade ``=`` entre o nome do compartimento e o valor que queremos armazenar. Chamaremos essa operação de atribuição, na qual um valor é atribuido a uma variável. 

Portanto em programação o símbolo de igualdade ``=`` é chamado de **operador de atribuição**.

Por exemplo:

.. code-block:: python
   
   idade = 33  
   
No código acima:

- ``idade`` é o **nome da variável**
- ``=`` é o **operador de atribuição**
- ``33`` é o **valor armazenado na variável**



02.c.Observações.
----------------

Repare que na programação, o **operador de atribuição possui uma função diferente do sinal de igual da matemática**.

O sinal de **igual da matemática é chamado de operador de comparação** é escrito desta forma ``==``.

Exemplo:

.. code-block:: python
   
   idade == 33
   >>> True
   
Mas por enquanto não se preocupe com ele, falaremos sobre ele mais adiante.


03.Comando print( ) com variáveis.
===================

Para exemplificar o porque utilizar o comando ``print( )`` com variáveis pense no seguinte código:

.. code-block:: python
   
   #Somando variáveis
   
   a = 4
   b = 3
   print(a + b)
   >>> 7 

Você pode se perguntar:
*Por que criar duas variáveis ``a`` e ``b`` para somar dois números?*

Poderíamos obter o resultado da mesma forma com o código: 

.. code-block:: python
   
   print(4 + 3)
   >>> 7 
   
   print(7)
   
Escolhemos usar variáveis para mostrar uma grande diferença entre resolver um problema no papel e no computador:

- **Programar é descrever passos para a solução do problema**, portanto é aconselhável descrever os passos de forma que consiga alterá-los com facilidade e mais importante, que possa **entendê-los depois**.

- Quando se escreve ``print(4 + 3)`` o problema foi a soma de 4 e 3, se precisar mudar alguma parte desse problema, irá precisar escrever outro programa. 

- Quando se escreve ``print(7)`` não se descreve nenhum problema em si. 

**A diferença está na clareza da representação do nosso problema**.

Portanto sempre escreva seus programas de forma a que seus códigos sejam limpos, organizados e minuciosos. Caso ainda não tenha ficado claro, pense no seguinte programa para calcular o aumento de salário:

.. code-block:: python

   #Programa para cálcular de aumento de salário
   
   salario = 1500
   aumento = 5
   print(salario + (salario * aumento / 100))
   >>> 1575
   
No problema anterior, é possível alterar o valor das variáveis ``salário`` ou ``aumente`` sem que precise reescrever o programa inteiro, dessa forma pode-se utilizar o código para outro salário e outro aumento. 

03.a.Como usar uma variável com o comando print().
----------------

