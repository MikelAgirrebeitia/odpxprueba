.. prueba documentation master file, created by
   sphinx-quickstart on Tue Sep 27 14:55:03 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Daniel Puente Calculator's documentation!
==================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:



==================

Para sumar 2 números se puede emplear la función ``calculadora.suma(a, b)``:
         .. py:function:: def suma(a, b):

            Suma 2 numeros

            :param a: Primer numero
            :type a: int or float
            :param b: Segundo numero
            :type b: int or float
            :return: Suma de los 2 numeros
            :rtype: int or float

Para restar 2 números se puede emplear la función ``calculadora.resta(a, b)``:
         .. py:function:: def resta(a, b):

            Resta 2 numeros

            :param a: Primer numero
            :type a: int or float
            :param b: Segundo numero
            :type b: int or float
            :return: Resta de los 2 numeros
            :rtype: int or float

Para multiplicar 2 números se puede emplear la función ``calculadora.multi(a, b)``:
         .. py:function:: def multi(a, b):

            Multiplica 2 numeros

            :param a: Primer numero
            :type a: int or float
            :param b: Segundo numero
            :type b: int or float
            :return: Multiplicacion de los 2 numeros
            :rtype: int or float

Para dividir 2 números se puede emplear la función ``calculadora.divir(a, b)``:
         .. py:function:: def division(a, b):

            Divide 2 numeros

            :param a: Primer numero
            :type a: int or float
            :param b: Segundo numero
            :type b: int or float
            :raise calculadora.DivisionEntreCero: If b = 0
            :return: Division de los 2 numeros
            :rtype: int or float 


.. * :ref:`genindex`
.. * :ref:`modindex`
.. * :ref:`search`
