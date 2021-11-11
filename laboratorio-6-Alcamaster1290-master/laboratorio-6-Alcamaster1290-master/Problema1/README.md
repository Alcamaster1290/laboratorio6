# Problema 1 (15 puntos):

Usted tiene un arreglo de números en punto flotante de tamaño fijo y con números asignados aleatoriamente.

Para este laboratorio se le pide calcular:
- Mediana (mean)
- Covarianza (covariance)
- Regresión Lineal (linreg)

Estos cálculos solicitados deben ser resueltos en los siguientes lenguajes de programación:
- Python
- ASM
- ASM usando SIMD
- C
Todas estas ecuaciones son brindadas dentro del cuaderno de Jupyter adjunto.

Todos estos resultados deben ser resueltos en un cuaderno de Jupyter Notebook mostrando los siguientes datos:
- Tiempo de ejecución de cada función en cada lenguaje.
- Gráfico del tiempo de ejecución en Python, C, ASM y SIMD.
- Gráfico del tiempo de ejecución de C, ASM y SIMD.
- SpeedUp de C, ASM y SIMD respecto de Python.
- SpeedUp de SIMD respecto de C y ASM.
- Error relativo de las funciones.
- Gráfica de las rectas estimadas y la referencia en el mayor tamaño.

Tengan en cuenta que para cada una de las gráficas es necesario brindar una pequeña explicación sobre sus resultados obtenidos, si no presenta una explicación su respuesta no será evaluada.

## Consideraciones:
- Todas las funciones deben basarse en estructuras iterativas.
- No es válido usar el módulo statistics, numpy o algún otro módulo, salvo que sea para validar sus resultados, presentar gráficos o generar entradas.
- Todos los datos son números en punto flotante.
- En todas sus funciones deberá incluir un comentario indicando cuales serán los parámetros de la función y su tipo de dato.
- Todas las funciones en C deberán estar dentro de un archivo con nombre stats.c, el cual también deberá incluir los prototipos de las funciones en ASM y SIMD.
- Cada función en ASM y SIMD deberá tener su propio archivo.
- Todas las gráficas deberán tener etiquetas en los ejes y títulos.

## Distribución del puntaje de la pregunta

| Sección | Puntos | Requisitos para puntaje completo |
| ------------ | :---------------: | -------------- |
| Python: mean, covariance, linreg | 0.5 | Implementación completa de la función |
| C: meanC, covarianceC, linregC | 1 | Implementación completa de la función |
| ASM: meanASM, covarianceASM, linregASM | 2 | Implementación completa de la función |
| SIMD: meanSIMD, covarianceSIMD, linregSIMD | 2.5 | Implementación completa de la función |
| ctypes | 1 | Llamadas a las funciones desde python |
| Cálculos del tiempo de ejecución | 0.5 | Código comentado |
| Gráfico Python, C, ASM y SIMD | 1.5 | Explicar las diferencias o similitudes en los 3 tiempos de ejecución |
| Gráfico C, ASM y SIMD | 1 | Explicar las diferencias o similitudes de los tiempos de C y SIMD |
| Gráfico SpeedUp C, ASM y SIMD vs Python | 1.5 | Explicar la diferencia o similitud del SpeedUp de C y SIMD respecto del de Python |
| Cálculos Error relativo | 1 | Código comentado |
| Gráfico Error relativo | 1 | Python, C, ASM y SIMD - Explicar qué significan las gráficas obtenidas |
| Gráfico Rectas Estimadas | 1.5 | Referencia, Python, C, ASM y SIMD - ¿ Qué significa cada una de las rectas obtenidas ? |
