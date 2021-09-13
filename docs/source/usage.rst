PYTHON: INTRODUÇÃO.
=====

.. 01.PRIMEIROS PASSOS:

01.”Olá, mundo!”
------------

Talvez a primeira coisa que aprendemos a fazer quando começamos a estudar uma linguagem de programação é imprimir a frase “Hello, world!” (“Olá, mundo!”).

Para isso usamos o comando ``print("Texto a ser impresso aqui")``.

```python

print("Olá, mundo!")
>>> Olá, mundo!

```
   
01.b.Comentários no código.
----------------

Em Python alguns caracteres são especiais e tem uma funcionalidade específica. 

O primeiro que veremos é o ``#``. Quando começamos uma linha com o caracter “#” o texto não é interpretado pelo computador e fica na cor verde.

Isto é um comentário, ou seja, um pedaço do texto que deixamos dentro do código para que outras pessoas (ou nós mesmos no futuro) possam entender melhor o que estamos fazendo ao longo do código.

```python

#Isto é um comentário

```

```python
import donkey as dk

#initialize the vehicle
V = dk.Vehicle()

#add a camera part
cam = dk.parts.PiCamera()
V.add(cam, outputs=['image'], threaded=True)

#add tub part to record images
tub = dk.parts.Tub(path='~/mycar/data',
                   inputs=['image'],
                   types=['image_array'])
V.add(tub, inputs=inputs)

#start the vehicle's drive loop
V.start(max_loop_count=100)
```
