FUNÇÕES.
********************

Uma função é composta basicamente por duas partes:

.. code-block:: python
   :linenos:
   
   def nome_da_função( ):
    
    bloco de código da função
    
Podemos entender uma função como: 

- Função é um bloco de código que só é executado quando é chamado.

- Funções nos ajudam a diminuir repetições tornando o código mais organizado.

- Função é sempre uma ação de fazer algo.


01.Criando uma função
============

Para criar uma função usamos o comando ``def``.
    
Veja o exemplo de como criar e chamar uma função:

.. code-block:: python
   :linenos:
  
    #Criando uma função chamada parabens
    def parabens( ):
     
      #Estabelecendo o bloco de código que a função parabens irá executar
      print('Parabéns, você criou uma função.')

.. code-block:: python
   :linenos:
   
   #Chamando a função parabéns
   parabens()
 

**Este é o resultado:**

.. code-block:: python

   >>> Parabéns, você criou uma função.



02.Criando uma função com parâmetros
===================

Quando precisamos que a função seja executada de forma específica é necessário usar:

- **Parâmetro:** é a variável que recebe um valor (argumento) para ser usado na função.

- **Argumento:** valor atribuído ao parâmetro.

Uma função com parâmetros e argumentos é composta basicamente da seguinte forma:

.. code-block:: python
   :linenos:
   
   def nome_da_função(parametro_01 = argumento_01, parametro_02 = argumento_02):
    
    bloco de código da função


Veja o exemplo de como criar uma função com parâmetros e argumentos:

.. code-block:: python
   :linenos:
   
   #Criando uma função chamada barra um, com os "parâmetros quantidade" e "caracter" e com os argumentos "40" e "@" 
   def barra_01(quantidade=40, caracter='@'):
   
      #Estabelecendo o bloco de código que a função barra_01 irá executar
      print(quantidade*caracter)
      
.. code-block:: python
   :linenos:
   
   #Chamando a função barra_01
   barra_01()
   

**Este é o resultado:**

.. code-block:: python

   >>> @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
   
.. warning::

   Repare que como não passamos nenhum parâmetro para a função, ela nos devolve os parâmetros padrões ``(default)``, que neste caso é 40 vezes o símbolo '@'.
   
02.a.Alterando os argumentos de uma função

Pense na função ``barra_01``:

.. code-block:: python
   :linenos:
   
   #Criando uma função chamada barra um, com os "parâmetros quantidade" e "caracter" e com os argumentos "40" e "@" 
   def barra_01(quantidade=40, caracter='@'):
   
      #Estabelecendo o bloco de código que a função barra_01 irá executar
      print(quantidade*caracter)
      
      
Caso deseje alterar a quantidade e o símbolo do caracter, sem precisar toda vez ir onde definiu a função, você pode fazê-lo ao chamar a função.

Veja o exemplo de como alterar os argumentos de uma função na hora de chamá-la:

.. code-block:: python
   :linenos:
   
   #Chamando a função barra_01 e alterando os argumentos para "quantidade = 10" e "caracter = !"
   barra_01(quantidade = 10, caracter = !)
   
**Este é o resultado:**

.. code-block:: python

   >>> !!!!!!!!!!
   
