# EjercicioMarchena
Ejercicio Tecnico
--Los metodos para este ejercicio son creados en diferentes clases.


-El parametro(message) tiene el mismo nombre que una existente - Duplicado
-Falta añadir el System.Configuration desde la misma herramienta de referencia.(assemblie)
-El parametro de tipo string tiene el operador !, esto no puede ser aplicado para este tipo string.

-Al momento de escribir en el txt no se puede porque le pasa el DateTime.Now.ToShortDateString() como nombre para el archivo, lo cual esto es 12/03/2016, cuando quiere escribir en este archivo, lo busca pero no lo encuentra ya que windows no permite los caracteres / o \
--Solucion : Podria guardarse con la fecha pero si necesidad de guardar el slash, solamente dando formato a la fecha
Date.Now.ToString(ddMMyyyy); . Entonces ya no guarda el slash pero guardando la fecha.


-Los nombres de los appSetings["Log FileDirectory"] debe estar de forma correcta, ya que si no, no lo encontrará . No deberia haber espacios en blanco en la cadena.

-Antes de que se pueda escribir en el archivo txt, este ya deberia haber sido creado con el nombre correcto con la fecha a la que se le hace referencia.

-La mejor opcion para verificar si el archivo existe o no, es hacer una validación antes.
--Lo que se deberia hacer es que se valide si el archivo existe o no


-En este caso, no se esta estableciendo las exceptiones que deberian ser, ya que esto podria tomar mas tiempo si ponemos una simple exception
