1)a) En el codigo 
  conhilos.py: 
              Primero empiezan las tareas (1, 2 y 3) y luego las termina (1, 2 y 3).
                El tiempo de ejecucion no es predecible ya que las tres tareas se ejecutan en simultaneamente.  
  
  sinhilos.py: 
              Primero empieza la tarea 1 y la termina. Luego empieza la tarea 2 y la termina. Y lo mismo hace con la tarea 3.
                El tiempo de ejecucion es predecible ya que las tareas se ejecutan secuencialmente.

Los tiempos de ejecucion
  conhilos.py: Aproximadamente 4,05 segundos.
  sinnhilos.py: Aproximadamente 5,5 segundos.
  
  b) Los tiempos de ejecucion no son iguales, van variando.

  c) Al descomentar las líneas 11, 12, 19 y 20, se ejecuta esta istruccion: for i in range(1000): pass ,dentro de las funciones sumador() y restador(). 
      Esa istruccion es una operacion de espera, esto ralentiza la ejecucion de estas funciones y da lugar a que las operaciones de incremento 
      y decremento en acumulador() se realicen con menos frecuencia.
