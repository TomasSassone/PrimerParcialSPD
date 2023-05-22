# Primer Parcial SPD - Proyecto Montacargas
![gif montacargas sassone](https://github.com/TomasSassone/PrimerParcialSPD/assets/72427373/300eada1-371c-4c1f-b309-ca8957d6814b)

## Alumno 👦
Tomás Santiago Sassone - 1°D

## Descripción 📓
Se nos pide armar un modelo de montacarga funcional como maqueta para un hospital.
El objetivo es que implementes un sistema que pueda recibir ordenes de subir, bajar o pausar desde
diferentes pisos y muestre el estado actual del montacargas en el display 7 segmentos.

1. **Interfaz de usuario:**

    • Deberá haber 3 botones, uno para subir pisos, otro para bajar pisos y otro para
    detener el montacarga.

    • Deberá tener 2 LEDs, uno verde que indicará cuando el montacarga este en
    movimiento, otro rojo que indique cuando el montacarga esté pausado.
    
    • En el display 7 segmentos deberán informar en tiempo real en qué piso se
    encuentra el elevador.

    • Se sabe que el tiempo de trayecto entre pisos es de 3 segundos (3000 ms).
    
    • Se deberá informar por monitor serial el piso en el que se encuentra el
    montacarga, este en funcionamiento o en pausa.
    
    
2. **Funcionamiento del montacarga:**

    • Implementa un algoritmo que permita que el elevador suba y baje o frene
    presionando los botones correspondientes.

    • Deberán buscar una forma para pausar el montacargas cuando el usuario lo
    determine.
  
  
3. **Documentación:**

    • Deberán presentar un diagrama esquemático del circuito y explicar el
    funcionamiento aplicado de cada componente.
    
    • Presentar el código fuente del proyecto de Arduino listo para ser
    implementado.
    
    • Deberán explicar el funcionamiento integral utilizando documentación
    MarkDown.
    

## Nueva función - Corrector parcial
Con la parte domiciliaria terminada , se deberá agregar funcionalidades con
los siguientes elementos:
Se debe agregar un **sensor de luz ambiental**, un **sensor de inclinación**, un **servo** e imaginar la funcionalidad.

Decidí utilizar un servo y hacer que el mismo vaya rotando en función del piso en
el que se encuentre el montacargas. Cuanto mayor más alto está el montacargas,
más cerca estará el servo de los 180°. El sensor de luz ambiental indica si el LED del
servo debe encenderse o no (si hay poca luz ambiental se encenderá). Mientras que el sensor
de inclinación determina si el montacargas puede iniciarse (Si el montacargas está inclinado,
no iniciará).

![image](https://github.com/TomasSassone/PrimerParcialSPD/assets/72427373/5865b0bb-e2f4-46cd-a541-6cda6ce67cf8)




## Diagrama esquemático del circuito

![image](https://github.com/TomasSassone/PrimerParcialSPD/assets/72427373/1c690ede-01c7-4058-aac3-9518ad764c2e)

![image](https://github.com/TomasSassone/PrimerParcialSPD/assets/72427373/31147010-832b-4916-a159-34d1d38a8a35)


[Link](https://github.com/TomasSassone/PrimerParcialSPD/files/11531508/Parcial.Practico.Domiciliario.-.Sassone.-.1D.1.pdf)



## Link al proyecto 🤖
[Tinkercad](https://www.tinkercad.com/things/l5eIEKKi1Ie-parcial-practico-domiciliario-sassone-1d/editel?sharecode=_uouFBoCo6iM1ceLNo71j3dTxgfvuHUST7mYmXrhIZw)

[GDB](https://onlinegdb.com/4apqXeOWq)

## Fuentes 🔍
[Botón - Cambio de estado](https://www.tinkercad.com/things/kAFApLyezbt)

[Función millis()](https://robots-argentina.com.ar/didactica/arduino-usando-la-funcion-millis-en-lugar-de-delay/)
