<!-- hide -->
# Decision Tree Project Tutorial
<!-- endhide -->

- El objetivo de este proyecto es clasificar a los pacientes que tienen o no diabetes, en función de su diagnóstico.
- Hacer algunos análisis exploratorios básicos y preparar los datos para el modelado.
- Utiliza árboles de decisión y afina tu modelo. Esta carpeta tiene una guía de solución en caso de que te quedes atascado.
- No olvides que estás creando software, así que construya canalizaciones en app.py.

## 🌱  Cómo iniciar este proyecto

Esta vez no se hará Fork, tómate un tiempo para leer estas instrucciones:

1. Crear un nuevo repositorio basado en el [proyecto de Machine Learing](https://github.com/4GeeksAcademy/machine-learning-python-template/generate) [haciendo clic aquí](https://github.com/4GeeksAcademy/machine-learning-python-template).
2. Abre el repositorio creado recientemente en Gitpod usando la [extensión del botón de Gitpod](https://www.gitpod.io/docs/browser-extension/).
3. Una vez que Gitpod VSCode haya terminado de abrirse, comienza tu proyecto siguiendo las instrucciones a continuación.

## 🚛 Cómo entregar este proyecto

Una vez que hayas terminado de resolver los ejercicios, asegúrate de confirmar tus cambios, hazle "push" a el fork de tu repositorio y ve a 4Geeks.com para subir el enlace del repositorio.

## 📝 Instrucciones

**Predeciendo la diabetes**:

Este conjunto de datos proviene originalmente del Instituto Nacional de Diabetes y Enfermedades Digestivas y Renales. El objetivo es predecir en base a medidas diagnósticas si un paciente tiene diabetes.

Diccionario de datos:

- Embarazos: Número de veces embarazadas.

- Glucosa: Concentración de glucosa en plasma a las 2 horas en un test de tolerancia oral a la glucosa.

- Presión arterial: presión arterial diastólica (mm Hg).

- Grosor de la piel: Grosor del pliegue cutáneo del tríceps (mm).

- Insulina: insulina sérica de 2 horas (mu U/ml).

- IMC: Índice de masa corporal (peso en kg/(altura en m)^2).

- DiabetesPedigreeFunction: función de pedigrí de diabetes.

- Edad: años.

- Resultado: Variable de clase (0 o 1), Distribución de clase: (el valor de clase 1 se interpreta como "diabetes positivo")

Fuente:

(a) Propietarios originales: Instituto Nacional de Diabetes y Enfermedades Digestivas y
Enfermedades Renales.
(b) Donante de la base de datos: Vincent Sigillito (vgs@aplcen.apl.jhu.edu)
Centro de Investigación, Líder de Grupo RMI
Laboratorio de Física Aplicada
la Universidad Johns Hopkins

**Paso 1:**

Ve al siguiente conjunto de datos en línea (`https://raw.githubusercontent.com/4GeeksAcademy/decision-tree-project-tutorial/main/diabetes.csv`) y descarga los datos.

Guárdalo en la carpeta 'data/raw' de tu proyecto. ¡Es hora de trabajar en ello!

**Paso 2:**

Usa notebook explore.ipynb para encontrar patrones e información valiosa que te ayudarán en tu proceso de limpieza. 

No olvides escribir tus observaciones.

Usa app.py para crear tu pipeline de limpieza. Guarda tus datos limpios en la carpeta 'datos/procesados'.

**Paso 3:**

Ahora que tienes un mejor conocimiento de los datos, en tu notebook exploratorio crea un modelo de árbol de primera decisión con sus datos limpios.

**Paso 4:**

Cambia tu árbol de decisión para usar 'entropía' como criterio.

**Paso 5:**

Hiperajuste su modelo usando GridSearch para encontrar los mejores hiperparámetros.

Entrena tu modelo con los hiperparámetros óptimos.

Vuelve a utilizar app.py para crear tu modelo final de Machine Learning.

Guarda tu modelo final en la carpeta 'modelos'.

En tu archivo README escribe un breve resumen de tu proceso de limpieza y modelado.

Guía de soluciones: https://github.com/4GeeksAcademy/decision-tree-project-tutorial/blob/main/solution_guide.ipynb
