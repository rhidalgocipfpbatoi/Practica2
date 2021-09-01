# Practica2

1.Abre el IntelliJIdea, creando un proyecto nuevo llamado U1Actividad1.
2.Debes hacer un programa que pida los siguientes datos por consola y acabe mostrando la información indicada (los números en negrita son datos entrados por teclado). DEBES RESPETAR EL FORMATO QUE SE TE PRESENTA:

```sh
Dime el valor del ‘radio’ de un círculo: 3
Ahora dime el valor de la ‘base’ de un rectángulo: 5.0
No olvides decirme también el valor de la ‘altura’ del rectángulo: 4
De momento tenemos un círculo de perímetro 18.84 y área 28.26 y un rectángulo de área 20.00
Me gusta el teorema de Pitágoras, dime el valor del ‘cateto 1’: 3 
Y también del ‘cateto 2’: 3
Vale, pues el valor de la hipotenusa al cuadrado es 18.00, por lo tanto el valor de la hipotenusa es 4.24
```

3.Escribe el programa y compila el código fuente resultante utilizando IntelliJIdea tal y como hemos hecho en clase con el programa “HolaMundo.java”. Llama a tu archivo “U1Actividad1.java” y recuerda añadir tu/s nombre/s en el comentario inicial del fichero.
4.Corrige los errores de compilación que vayan apareciendo hasta obtener el programa resultante sin errores de compilación. Una vez lo tengas, sube tu fichero java a la entrega correspondiente y comprueba que funciona.

NOTAS DE AYUDA: 
- Si quieres ver valores decimales limitados a N decimales, deberás de hacer uso de la función System.out.printf. Por ejemplo, suponiendo que la variable cantidad vale 3.457323432 y la variable resultado vale 8.432312::
System.out.printf("Cantidad vale %.2f y resultado %.2f\n", cantidad, resultado);
Muestra por pantalla: Cantidad vale 3.46 y resultado 8.43
- Si quieres calcular la raíz cuadrada de un número debes utilizar la función Math.sqrt(valor), siendo valor, la variable con el valor de la cual quieres calcular su raíz cuadrada. Por ejemplo, suponiendo que la variable valor vale 4 :
System.out.println(“La raíz cuadrada de “ + valor + “ es ” + Math.sqrt(valor);
Muestra por pantalla: La raíz cuadrada de 4 vale 2
