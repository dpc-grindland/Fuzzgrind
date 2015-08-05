========================================
Fuzzgrind
========================================

A fully automatic fuzzing tool for Valgrind.


Requirements
========================================

* bzip2
* autoconf
* make
* gcc
* python


Installation
========================================

.. code-block:: sh

    $ ./install.sh


Configuration
========================================

Configuration file: fuzz/settings.cfg


Execution
========================================

CLI: $ ./fuzz/fuzz.py
GUI: $ ./fuzz/gui.py


Example
========================================

.. code-block:: sh

    $ ./fuzz/fuzz.py test6

New input are created in testcase/input/
Crash files are be saved in testcase/crash/


Contact
========================================

gabriel [at] security-labs [dot] org
