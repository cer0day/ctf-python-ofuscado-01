# ctf-python-ofuscado-01
Reto de condigo de python ofuscado
tutorial:https://www.youtube.com/watch?v=OogKo4NlsL4

1-ejecutar archivo de python
2.-analizar el codigo del archivo
3.-decodificar con base64 (cuberchef)
4.-descomprimir zlib (cyberchef)
5.-buscar la contraseña
6.-comvertir para obtener cadena

import binascii
v ="cadena de password"
hex_string = binascii.hexlify(v)
print(hex_string)

7.-dentificar que hash es
8.-ataque de diccionario a hash(hashcat o john)
9.-ejecutar e introducir la contraseña
10.-Observar el contenido del archivo que se genera
