PYTHON: FUNÇÃO.
********************

**Função é um bloco de código que só é executado quando é chamado.**

 - Funções nos ajudam a diminuir repetições tornando o código mais organizado.


01.Criando uma função
============

Para criar uma função usamos o comando ``def``, uma função é é composta basicamente por duas partes:

.. code-block:: python
   :linenos:
   
   def nome_da_função( ):
    
    bloco de código da função
    
Veja o exemplo de uma função:

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

