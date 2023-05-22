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
Se debe **un servo** e imaginar la funcionalidad.

Decidí utilizar un servo y hacer que el mismo vaya rotando en función del piso en
el que se encuentre el montacargas. Cuanto mayor más alto está el montacargas,
más cerca estará el servo de los 180°.

![image](https://github.com/TomasSassone/PrimerParcialSPD/assets/72427373/118e0bba-ebba-4480-8f56-ddaf2cf310cf)



## Diagrama esquemático del circuito

![image](https://github.com/TomasSassone/PrimerParcialSPD/assets/72427373/c3f1068f-7b8f-40b3-a8eb-edb57726ce5b)

[Link](https://github.com/TomasSassone/PrimerParcialSPD/files/11525742/Parcial.Practico.Domiciliario.-.Sassone.-.1D.pdf)



## Link al proyecto 🤖
[Tinkercad](https://www.tinkercad.com/things/l5eIEKKi1Ie-parcial-practico-domiciliario-sassone-1d/editel?sharecode=_uouFBoCo6iM1ceLNo71j3dTxgfvuHUST7mYmXrhIZw)

[GDB](https://onlinegdb.com/Ob8e-7EMYQ)

## Fuentes 🔍
[Botón - Cambio de estado](https://www.tinkercad.com/things/kAFApLyezbt)

[Función millis()](https://robots-argentina.com.ar/didactica/arduino-usando-la-funcion-millis-en-lugar-de-delay/)
