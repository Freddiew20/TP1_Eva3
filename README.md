# TP1_Eva3
Este es un proyecto para la clase de entorno de desarrollo en el cual nos han proporcionado varias clases con sus test, para que, a partir de ellos generemos una clase JUnitSuite, lo compilemos y lo ejecutemos correctamente.

## Para compilar el proyecto:
`javac -cp /(directorio de jarjunit)/*:. *.java`

*Ejemplo*

`javac -cp /home/alumnado/jarjunit/*:. *.java`


## Para ejecutar el TestSuit:
`java -cp /(directorio de jarjunit)/*:. org.junit.runner.JUnitCore (nombre del test)`

*Ejemplo*

`java -cp /home/alumnado/jarjunit/*:. org.junit.runner.JUnitCore JunitTestSuite`
