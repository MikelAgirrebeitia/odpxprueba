.. prueba documentation master file, created by
   sphinx-quickstart on Tue Sep 27 14:55:03 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Outdpik: The fundamental toolkit for outliers search and visualization
==================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:



==================

First, outdpik class is instanciated = ``outdpik = outdpik()``. It requieres no arguments.


Searching for outiers ``outdpik.outliers(df = *, columns = "all", method = "all")``:
         .. py:function:: def outliers(df, columns, method):

            It returns a dictionary with the columns selected and the outliers

            :param df: The set to explore
            :type df: pd.DataFrame, np.array and list
            :param columns: Selected columns, by default = "all". "all" parameter will return the outliers for all the numeric columns.
            :type columns: list and string
            :param method: Method to use for outliers search. "iqr", "zscore" and 'all' are available. "all" parameter will return the outliers for all the methods.
            :type method: string
            :return: Dictionary of outliers
            :rtype: dict

Plot outiers ``outdpik.outliers(df = *, columns = *, method = "all", size = [5, 7], palette = ((133/255, 202/255, 194/255), (38/255, 70/255, 83/255)))``:
         .. py:function:: def outliers_plot(df, columns, method, size, palette):

            It returns a strip plot with the outliers marked in other color

            :param df: The set to explore
            :type df: pd.DataFrame, np.array and list
            :param columns: Selected column. Only one and numeric column can be selected.
            :type columns: list and string
            :param method: Method to use for outliers search. "iqr", "zscore" and 'all' are available. "all" parameter will return the outliers for all the methods. Default value, method = "all"
            :type method: string
            :param size: Size of the plot. Default value, size = [5, 7]
            :type size: list
            :param palette: Color palette to use. Default value, palette = [5, 7]
            :type palette: tuple of 3 elements each
            :return: Strip plot of the selected column
            :rtype: plt.figure


.. * :ref:`genindex`
.. * :ref:`modindex`
.. * :ref:`search`
