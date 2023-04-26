EJERCICIO COMPILADOR

i- El compilador utilizado es el GCC

ii y iii- En Visual Code, hago el siguiente codigo:

        #include <stdio.h>

        int main (void)
        {
          printf("Hola, Mundo!");

          return 0;

        }
       
La cual envía a stdout la linea Hola, Mundo!

iv- Para redireccionar el stdout al output.txt realizo lo siguiente:
1) Dentro de la carpeta donde tengo el archivo, abro con mi consola del sistema el archivo utilizando el compilador previamente mencionado: gcc hello.c
2) Tras esto, ejecuto el programa dándole un nombre al .exe. En este caso, el nombre es "a".
3) Una vez hecho el exe, redirecciono el .exe al archivo de texto previamente creado (output.txt) con la siguiente linea de comando: a > output.txt 
Esta linea lo que hace es enviar lo que hace el .exe al .txt


