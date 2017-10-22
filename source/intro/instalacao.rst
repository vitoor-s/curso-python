Instalando Python
=================

Linux - Ubuntu
--------------

Provavelmente você já tem o Python instalado e configurado. Para ter certeza
que ele está instalado e descobrir qual versão, abra um terminal e execute o
comando:

.. code::

   $ python --version
   Python 3.6.1

Caso apareça a mensagem ``bash: python: command not found``, você pode
instalá-lo da seguinte maneira:

.. code::

   $ sudo apt-get install python3.6


OSX
---

Obtenha o instalador no site do Python: . Clique duas vezes no Python.mpkg para abrir o instalador.

Para ter certeza que ele está instalado e descobrir qual versão, abra um
terminal e execute o comando:

.. code::

   $ python --version
   Python 3.6.1


Windows
-------

Primeiramente, deve-se obter o arquivo de instalaçao compatível com a arquitetura, x86 deve funcionar em todos, os links estão a seguir:

    | x86_64: https://www.python.org/ftp/python/3.6.1/python-3.6.1-amd64.exe
    | x86:    https://www.python.org/ftp/python/3.6.1/python-3.6.1.exe

A seguir, o aquivo deve ser executado e a seguinte imagem aparecera:

.. figure:: images/install1.png
   :align: center
   :scale: 80%

Deve ser selectionado a opção 'Add Python 3.X to PATH', e deve ser clicado na opção 'Customize installation'


.. figure:: images/install2.png
   :align: center
   :scale: 80%

Clicar en 'Next'

.. figure:: images/install3.png
   :align: center
   :scale: 80%

Selectionar a opção: 'Install for all users' e clicar em 'Install', uma janela pedindo permissão de administrador deve aparecer, é necessário aceitar

.. figure:: images/install4.png
   :align: center
   :scale: 80%

Clicar em 'Disable path lenght limit', novamente, uma janela de permissão de administrador vai aparecer, é necessário aceitar

.. figure:: images/install5.png
   :align: center
   :scale: 80%

Clicar em 'Close'

Parabéns, agora o Python está intalado em sua máquina!