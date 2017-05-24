 # TP1_Eva3
Este es un proyecto para la clase de entorno de desarrollo en el cual nos han proporcionado varias clases con sus test, para que, a partir de ellos generemos una clase JUnitSuite, lo compilemos y lo ejecutemos correctamente.

## Para compilar el proyecto:
`javac -cp <directorio_de_jarjunit>/*:. *.java`

*Ejemplo*

`javac -cp /home/alumnado/jarjunit/*:. JUnitTestSuite.java`


 ## Para ejecutar el TestSuit:
`java -cp <directorio_de_jarjunit>/*:. org.junit.runner.JUnitCore <nombre_del_test>`

*Ejemplo*

`java -cp /home/alumnado/jarjunit/*:. org.junit.runner.JUnitCore JunitTestSuite`

 ## Debe retornar esto
       alumnado@A121PC08:~/Escritorio/git$ java -cp ~/misjars/junit/*:. org.junit.runner.JUnitCore JunitTestSuite
       JUnit version 4.8.1
       .....
       Time: 0,007

       OK (5 tests)

