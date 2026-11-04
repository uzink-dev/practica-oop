# practica-oop

El objetivo del ejercicio es crear una clase User que simule operaciones bancarias básicas entre usuarios.

Para ello, hemos definido las siguientes funciones:

- __init__(): constructor que inicializa cada usuario con su nombre, saldo y permiso para recibir transferencias (checking_account).
- withdraw(): permite retirar dinero, comprobando el saldo disponible y actualizándolo.
- deposit(): permite ingresar dinero y aumentar el saldo del usuario.
- transfer(): pretende transferir dinero entre usuarios, verificando el destinatario y el saldo disponible.