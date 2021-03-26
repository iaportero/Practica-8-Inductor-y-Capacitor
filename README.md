# Practica 8 Inductor y Capacitores
Integrantes: Bryan Santiago Torres Reyes , Roger Steveen Armas Simbaña , Israel Alejandro Portero Cazares

NRC:  4877

1.  Objetivo

* Objetivo General

Analizar y verificar  el  desarrollo de las señales producidas por  inductores y capacitores alimentadas con diferentes fuentes  ( AC, DC)


*  Objetivos especificos 

Analizar las señales producidas de los diferentes circuitos compuesto por bobinas  y capacitores 

Verificar el comportamiento  de las señales producidas en los  diferentes instrumentos de medicion propuestos  para esta practica


2. Marco teorico  / Diagramas

Inductores ( Bobinas)

![](https://github.com/iaportero/Practica-8-Inductor-y-Capacitor/blob/main/Imagenes/ima%201.png)


Capacitores

![](https://github.com/iaportero/Practica-8-Inductor-y-Capacitor/blob/main/Imagenes/ima%202.png)

3.  Lista de componentes

![](https://github.com/iaportero/Practica-8-Inductor-y-Capacitor/blob/main/Imagenes/ima%203.png)

4.  Explicacion

1.- Construya en el protoboard el circuito mostrado en la Figura 1.

![](https://github.com/iaportero/Practica-8-Inductor-y-Capacitor/blob/main/Imagenes/ima%204.png)


*  Utilice el osciloscopio para observar el voltaje 𝑉􀯢 variando la frecuencia entre los
valores de 0, 10, 50, 100, 500, 1000 𝐻𝑧. Anote los valores pico de las ondas observadas.

*  Utilice un multímetro para medir el voltaje  vo  variando la frecuencia entre los valores
de 0, 10, 50, 100, 500, 1000 𝐻𝑧. Anote los resultados.


*  Utilice un multímetro para medir la corriente que atraviesa la resistencia variando la
frecuencia entre los valores 0, 10, 50, 100, 500, 1000 𝐻𝑧. Anote los resultados.


2.- Construya el circuito mostrado en la Figura 2

Realice las mismas mediciones de los ítems del numeral anterior y presente los resultados.

![](https://github.com/iaportero/Practica-8-Inductor-y-Capacitor/blob/main/Imagenes/ima%205.png)


3.-  Analisis de resultados

Para cada uno de los circuitos anteriores, elabore una tabla con los resultados de las
diferentes mediciones de voltaje realizadas con el osciloscopio y multímetro. Compare y
comente los resultados obtenidos tomando en cuenta las distintas frecuencias utilizadas.

Figura 1

![](https://github.com/iaportero/Practica-8-Inductor-y-Capacitor/blob/main/Imagenes/ima%206.png)

Figura 2


![](https://github.com/iaportero/Practica-8-Inductor-y-Capacitor/blob/main/Imagenes/ima%207.png)


4.-   Preguntas 

1.- ¿Cómo se comportan la bobina y el capacitor en corriente continua (cero Hz)?


La bobina en corriente continua con una frecuencia de cero Hz se comporta como un corto circuito dejando pasar la corriente como si fuera un conductor.El capacitor en corriente continua con una frecuencia de cero Hz se carga por completo y se transforma en un circuito abierto esto se da por dos fases conocidas como fase de transición y fase continua. En la fase de estabilización, se producen los fenómenos que se describen en las curvas de carga del capacitor hasta que se estabiliza y pasa a estar en fase continua, en esta fase la intensidad de corriente que atravesaría el capacitor es igual a cero entonces se lo toma como una “ rama abierta” en el circuito.


2.- ¿Cómo se comportan la bobina y el capacitor en corriente alterna?


La bobina en corriente alterna se comporta como la resistencia se opone al flujo de la corriente, pero a diferencia de ésta, el valor de esta oposición se llama reactancia inductiva y se representa por: XL y se puede calcular con:

La Ley de Ohm: XL = V / I y por la fórmula: XL
2π x f x L, donde:

XL: reactancia inductiva en ohmios

V: voltaje en voltios

I: corriente en amperios

π: constante (pi): 3.1416

f : frecuencia en hertz

L: inductancia en henrios


El comportamiento de los capacitores en corriente alterna dependerá de las funciones que describan su comportamiento en un intervalo de tiempo definido.
En corriente alterna el capacitor se carga y descarga según sea la frecuencia de oscilación.

3.- ¿Qué cree usted que ocurriría con el voltaje Vo y la corriente de la resistencia en los circuitos analizados en esta práctica, si se utilizan dos bobinas o dos capacitores de valores distintos?

Para el circuito 1, si se aumenta el valor de los capacitores, la corriente se mantendría constante, pero el voltaje disminuiría. Para el circuito 2, si se aumenta el valor de los inductores, la corriente disminuiría, y el voltaje se mantendría constante.



4.- ¿Qué son los valores eficaces de voltaje y corriente?


Los medidores eléctricos que se usan para tomar lecturas en los circuitos de corriente alterna "CA" miden el valor EFICAZ, o la raíz cuadrática media (RCM) de la corriente y el voltaje. Estos valores son siempre positivos y están relacionados con la amplitud de los valores sinusoidales instantáneos, a través de:


Vrcm = 0.707 x Vo

Ircm = 0.707 x  Io

A la corriente y voltaje efectivos, es también común llamarles "valores medios cuadráticos" o "rms" (del inglés "root-mean-square").


5. Manual de usuario

*  Manual de usuario simulador Multisim

http://electronica.ugr.es/~amroldan/asignaturas/curso04-05/ftc/pdf/manual.pdf

6.  Descripcion de prerrequsitos y configuracion

*  Instalacion de Multisim

Paso 1. Instala Multisim.

Primero que nada es necesario contar con una instalación previa de Multisim, si no cuentas con una licencia puedes descargar una evaluación por 30 dias

Paso 2. Descargar los archivos de soporte.

Visita NI Labs y descarga los archivos necesarios para instalar el idioma Español

Paso 3. Descomprime el archivo y cópialo al directorio de instalación.

Descomprime el archivo multisim_espanol_12.zip, el resultado será una carpeta de nombre Spanish:

Paso 4. Revisa el directorio de instalación.

Copia la carpeta Spanish y localiza el siguiente directorio en tu PC:

Paso 5. Selecciona el idioma Español en Multisim.

Abre Multisim, selecciona el menú Options»Global preferences. Después ve a la pestaña General y localiza el campo de Language. En la lista desplegable selecciona Spanish

7. Conclusiones

*  Para el circuito 1, a medida que aumenta la frecuencia, disminuye el voltaje y aumenta la corriente.

*  Para el circuito 2, a medida que aumenta la frecuencia, aumenta el voltaje y disminuye la corriente.

*  El comportamiento de los capacitores en corriente alterna dependerá de las funciones que describan su comportamiento en un intervalo de tiempo definido.
En corriente alterna el capacitor se carga y descarga según sea la frecuencia de oscilación.

*  Para el circuito 1, si se aumenta el valor de los capacitores, la corriente se mantendría constante, pero el voltaje disminuiría

*  Para el circuito 2, si se aumenta el valor de los inductores, la corriente disminuiría, y el voltaje se mantendría constante.


8. Bibliografia

¿Qué es un capacitor? y sus tipos - Ingeniería Mecafenix. (n.d.). Retrieved March 26, 2021, from https://www.ingmecafenix.com/electronica/el-capacitor/


Las bobinas. (n.d.). Retrieved March 25, 2021, from https://www.electronicafacil.net/tutoriales/Las-bobinas.html

9. Anexos

Link del video

https://youtu.be/xUlryBKBQww

https://youtu.be/1u6jclsgMT8

Link del archivo generado













