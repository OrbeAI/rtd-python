PYTHON: ESTRUTURA DE REPETIÇÃO.
********************

01.Estrutura de repetição ``while``
============

A estrutura de repetição ``while`` é composta basicamente por duas partes:

.. code-block:: python
   :linenos:
   
   while condição:
   
    execute esse bloco de código.

Podemos entender a estrutura de condição ``while`` como:

- ``while`` é o “enquanto” em português. Portanto “enquanto a condição for verdadeira, execute esse bloco de código.”

Veja o exemplo de uma estrutura de condição ``while``:

.. code-block:: python
   :linenos:
  
  #Criando uma variável chamada número e atribuíndo o valor de um
  numero = 1
  
  #Estabelecendo que enquanto número for menor que 6
  while numero < 6:
  
    #imprima o valor do número
    print(numero)
    
    #salve o valor atual da variável numero + 1 dentro da variável numero
    numero = numero + 1

**Este é o resultado:**

.. code-block:: python

   >>> 1
   >>> 2
   >>> 3
   >>> 4
   >>> 5

01.a.Incremento de variável
------

Na maioria das vezes usamos um incremento da variável dentro da estrutura de repetição ``while`` para que ela altere de valor e assim altere o estado da condição (verdadeiro ou falso).

Para incrementarmos o valor de uma variável numérica em uma unidade, podemos fazer de duas formas:

01.a.i.Adicionando uma unidade
++++++

.. code-block:: python
   :linenos:
   
   variavel = variavel + 1

______________________________________________________________________________________________________________________________________________

01.a.io.Usando um operador de atribuição especial
++++++

.. code-block:: python
   :linenos:
   
   variavel += 1
   
 
01.a.iii.Looping infinito
+++++

.. warning::

  Caso uma condição do while sempre fique verdadeira, o while entrará em looping infinito (repetição infinita)
  
Veja o exemplo de um looping infinito:

.. code-block:: python
   :linenos:
  
  #Criando uma variável chamada número e atribuíndo o valor de um
  numero = 1
  
  #Criando um looping infinito
  while numero:
  
    #imprima o valor do número
    print(numero)
    
    #salve o valor atual da variável numero + 1 dentro da variável numero
    numero = numero + 1
  
  
**Este é o resultado:**

.. code-block:: python

   >>> 1
   >>> 2
   >>> ...
   >>> 4051
   >>> 4052
   >>> ...
   
01.b.Comando ``break``
------

Com o comando ``break`` (pausa) podemos pausar a repetição mesmo se a condição ainda for verdadeira.

Veja o exemplo do comando ``break``:

.. code-block:: python
   :linenos:
  
  #Criando uma variável chamada número e atribuíndo o valor de um
  numero = 1
  
  #Estabelecendo que enquanto número for menor que 6
  while numero < 6:
  
    #imprima o valor do número
    print(numero)
    
    #criando uma condição
    if numero == 3:
    
      #utilizando o comando break para encerrar a repetição
      break
    
    #salve o valor atual da variável numero + 1 dentro da variável numero
    numero = numero + 1

**Este é o resultado:**

.. code-block:: python

   >>> 1
   >>> 2
   >>> 3
   

01.c.Comando ``continue``
------

Com o comando continue podemos parar a repetição e continuar com o próximo bloco de código.

Veja o exemplo do comando ``continue``:

.. code-block:: python
   :linenos:
  
  #Criando uma variável chamada número e atribuíndo o valor de um
  numero = 0
  
  #Estabelecendo que enquanto número for menor que 6
  while numero < 6:
  
    #imprima o valor do número
    print(numero)
    
    #criando uma condição
    if numero == 3:
    
      #utilizando o comando continue para encerrar a repetição e continuar com o próximo bloco de código
      continue
    
    #salve o valor atual da variável numero + 1 dentro da variável numero
    numero = numero + 1

**Este é o resultado:**

.. code-block:: python

   >>> 1
   >>> 2
   >>> 4
   >>> 5
   >>> 6
