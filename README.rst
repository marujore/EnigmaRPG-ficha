===============
EnigmaRPG-ficha
===============

Este repositório traz o criador de ficha para o RPG Enigma.


1. Instalação
=============

Por enquanto ele não tem um instalador nem interface gráfica, então para utiliza-lo é necessário executar por linha de comando.

2. Requisitos
-------------
- Python (preferencialmente > 3.8)

2.1 Download ou clone o repositório
-----------------------------------

.. code-block:: shell

    $ git clone https://github.com/marujore/EnigmaRPG-ficha.git

Entre no diretório:

.. code-block:: shell

    $ cd EnigmaRPG-ficha

2.2 Crie um ambiente Python separado no qual serão instaladas as dependências (opcional)
----------------------------------------------------------------------------------------

Você pode usar Conda ou Venv para criar ambientes isolados

2.3 (Opção 1: requer Conda instalado) Ambiente com Conda
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Crie um novo ambiente

.. code-block:: shell

    $ conda create --name enigma python=3.8

Ative o ambiente

.. code-block:: shell

    $ conda activate enigma

2.3 (Opção 2: requer Venv instalado) Ambiente com Venv
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Crie um novo ambiente

.. code-block:: shell

    $ python3 -m venv venv

Ative o ambiente

.. code-block:: shell

    $ source venv/bin/activate
3. Instale os pacotes necessários
---------------------------------

.. code-block:: shell

    $ pip3 install .[all]

4. Uso
======

4.1 Criação de Nova Ficha
-------------------------

Veja `example.py <./enigmarpg/examples/example.py>`_.

.. image:: https://raw.githubusercontent.com/marujore/EnigmaRPG-ficha/master/docs/img/ficha-example.png
    :target: https://raw.githubusercontent.com/marujore/EnigmaRPG-ficha/master/docs/img/ficha-example.png
    :width: 240
    :alt: Ficha de Exemplo
