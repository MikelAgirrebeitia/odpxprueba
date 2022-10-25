.. prueba documentation master file, created by
   sphinx-quickstart on Tue Sep 27 14:59:11 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to calculadora's documentation!
==================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:


-------------------------------------------------

In order to sum two numbers, you can use ``calculadora.sum(a,b)``:
      
         .. py:function:: def sum(a,b):

            Returns the sum of two numbers

            :param a: First number.
            :type a: Int or Float
            :param b: Second number.
            :type b: Int or Float
            :return: sum
            :rtype: Int or Float


In order to get the difference between two numbers, you can use ``calculadora.difference(a,b)``:

         .. py:function:: def difference(a,b):

            Returns the difference of two numbers

            :param a: First number.
            :type a: Int or Float
            :param b: Second number.
            :type b: Int or Float
            :return: difference
            :rtype: Int or Float


In order to multiply two numbers, you can use ``calculadora.multiply(a,b)``:

         .. py:function:: def multiply(a,b):

            Returns the multiplication of two numbers

            :param a: First number.
            :type a: Int or Float
            :param b: Second number.
            :type b: Int or Float
            :return: multiplication
            :rtype: Int or Float


In order to divide two numbers, you can use ``calculadora.division(a,b)``:

         .. py:function:: def division(a,b):

            Returns the division of two numbers

            :param a: First number.
            :type a: Int or Float
            :param b: Second number.
            :type b: Int or Float
            :raise DividebyzeroError: If b is 0.
            :return: division
            :rtype: Int or Float
