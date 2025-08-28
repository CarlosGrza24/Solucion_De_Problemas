# Solución de problemas

Este proyecto tiene como objetivo aplicar un modelo de regresión lineal múltiple para predecir la calificación final de estudiantes en un curso, utilizando información demográfica, académica y de hábitos de estudio.

Se trabajó con la base de datos [Calificaciones](Calificaciones.csv) de 395 estudiantes con 10 varibales en total, proveniente del Student Performance Data Set del [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/320/student+performance).

## Datos utilizados
En el archivo se encuentran las siguientes variables:

- **Escuela**: (GP = Gabriel Pereira, MS = Mousinho da Silveira)  
- **Sexo**: F = mujer, H = hombre  
- **Edad**: Edad en años  
- **HorasDeEstudio**: Rango de horas semanales (1–4)  
- **Reprobadas**: Materias reprobadas previamente  
- **Internet**: Acceso a internet (yes/no)  
- **Faltas**: Número de faltas  
- **G1**: Calificación primer periodo (0–20)  
- **G2**: Calificación segundo periodo (0–20)  
- **G3**: **Variable objetivo**, calificación final (0–20)

## Pasos del anáisis

1. **Carga y exploración**
   - Importar datos, revisar tipos de variables y primeras filas.  
2. **Transformación**
   - Variables categóricas convertidas en dummies (0/1).  
3. **Outliers**
   - Identificación y eliminación de valores extremos en *Faltas*.  
4. **Correlación**
   - Matriz de correlación.
   - Busqueda de colinealidad.  
5. **Interacciones**
   - Creación de nuevas variables.
6. **Modelo**
    - Entrenamiento (80/20).
    - Cálculo de métricas.
    - Gráfica real vs predicción.

## Archivos del proyecto

- [Reporte en ipynb](A1.5_648241.ipynb)
- [Reporte en html](A1.5_648241.html)
- [Calificaciones](Calificaciones.csv)
