# Funciones
* ☢️Es un bloque de código Reusable (como una caja negra)
    * Se usa el pass para no escribir bloque de codigo y evitar un SyntaxError
    * Un "fn" puede tener varios nombres (funcion como objecto o tipo de dato)
* ☢️ ABSTRACIÓN
* TIPOS DE FUNCIONES
    * PURAS (su valor de salida solo depende de los datos de entrada)
    * IMPURAS (su valor de salida depende de los datos en entrada y el contexto "scope" global)
    * DETERMINISTAS (los mismos valores de entrada producen las mismas salidas)
    * NO-DETERMINISTAS (los mismos valores de entrada producen diferentes salidas)
* (CALL) Se pueden llamar
    * dentro de una función puedes llamar también a otra función
    * se puede definir una función dentro de otra
    * RECURSIVIDAD: Una función se puede llamar a si misma
* (ARGS & PARAMS) Las funciones se le pasan argumentos (respecto a la llamada) y reciben parámetros (respecto la firma de una función)
    * Ojo: Puede haber funciones que no recibir ningún argumento
    * El numero de argumentos y parametros para una misma función puede variar en número. Ejemplo, se puede llamar a una misma función con 2,3 o mas argumentos.
    * El orden IMPORTA
    * Existen los parámetros con un valor POR DEFECTO
* Se definen con `def` (en python)
    * Se pueden definir en cualquier parte del código
* (RETURN) Devuelve un valor
    * No es obligatorio poner return
    * puede devolver una estructura de datos con multiples cosas
    * **UNA FUNCIÓN QUE NO TIENE RETURN DEVUELVE None**
        * Por ejemplo: print, que devuelve none pero realiza la tarea de imprimir por consola (stdout)
* En python, hay funciones ya existentes (built-in functions) (len, range, zip, max, min, print, etc...)
* (STRUCTURE)
    * Variables locales: Las variables definidas dentro de una función solo son accesibles desde dentro de esta
    * Variables globales: Son variables definidas fuera de una función, desde dentro se pueden leer y modificar
* Las funciones también se llaman métodos cuando pertenecen a un objeto
    * Una función no es un método
    * Un método si es una función
* **CALLBACK**: Una función recibie como argumento otra función