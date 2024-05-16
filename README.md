# Clean-code
CLEAN CODE

1. ¿Qué es optimización de código?
R: La optimización de código es el conjunto de fases de un compilador que transforman un fragmento de código en otro fragmento con un comportamiento equivalente y que se ejecuta de forma más eficiente, es decir, usando menos recursos de cálculo como memoria o tiempo de ejecución. 

2. ¿Qué es la refactorización de código?
R:  El término refactorización se usa a menudo para describir la modificación del código fuente sin cambiar su comportamiento, lo que se conoce informalmente por limpiar el código. La refactorización se realiza a menudo como parte del proceso de desarrollo del software: los desarrolladores alternan la inserción de nuevas funcionalidades y casos de prueba con la refactorización del código para mejorar su consistencia interna y su claridad. Los tests aseguran que la refactorización no cambia el comportamiento del código.
La refactorización es la parte del mantenimiento del código que no arregla errores ni añade funcionalidad. El objetivo, por el contrario, es mejorar la facilidad de comprensión del código o cambiar su estructura y diseño y eliminar código muerto, para facilitar el mantenimiento en el futuro.

3. ¿Que es Continuous Integration/Continuous Deployment (CI/CD) o integracion continua?
R: La CI/CD, o integración continua/entrega o implementación continuas, es una práctica de desarrollo de software que es posible gracias a la automatización. Las actualizaciones frecuentes y confiables aceleran los ciclos de las versiones debido a la entrega continua de código.

4. ¿Que es DRY (Don't Repeat Yourself)?
R: El acrónimo DRY significa “Don’t repeat yourself”, es uno de los principios del buen desarrollo de software que nos recomienda no repetir código fuente que ya hemos escrito.
Repetir código puede generar que, si el día de mañana debemos modificarlo en un lugar, también debamos modificarlo en los otros y si nos olvidamos de esto causará problemas en nuestra aplicación, además del esfuerzo que conlleva tener que realizar todas las modificaciones.
Si tenemos un mismo código fuente en un único punto de nuestra app, será mucho más fácil cambiarlo y también mejoraremos el rendimiento y el peso de los archivos.
