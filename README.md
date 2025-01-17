# mia204-rl
Repositorio para el curso de Aprendizaje por reforzamiento MIA204 de la maestria en inteligencia artificial de la UNI - Perú

# Proyecto Grupo 3: Resolviendo el problema del Taxi

Este repositorio contiene tres notebooks que implementan diferentes algoritmos de aprendizaje por refuerzo para resolver el problema del Taxi en el entorno de OpenAI Gym. Los algoritmos utilizados son:

1. **QLearning**: Implementado en `Grupo3_Taxi_1_QLearning.ipynb`
2. **Deep Q-Learning (DQN)**: Implementado en `Grupo3_Taxi_2_DQN.ipynb`
3. **MAXQ-0**: Implementado en `Grupo3_Taxi_3_MAXQ-0.ipynb`

## Requisitos

Tener instalado Python (>=3.7) y los siguientes paquetes:

- `numpy`
- `matplotlib`
- `gym`
- `gymnasium`
- `torch`
- `tqdm` 
- `IPython`

## Instrucciones para Instalar y Usar

1. **Clonar el Repositorio:**
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   cd <NOMBRE_DEL_REPOSITORIO>
   ```

2. **Instalar las Dependencias:**
   Instalar las dependencias indicadas en las sección [[Requisitos]]

3. **Abrir los Notebooks:**
   - Grupo3_Taxi_1_QLearning.ipynb se sugiere correrlo en google Colab ya que hay librerias que solo aplicacion para el SO Linux

   - Para los otros 2 notebooks se puede habrir en google colab o en local  (Windows)
     - `Grupo3_Taxi_2_DQN.ipynb`
     - `Grupo3_Taxi_3_MAXQ-0.ipynb`

4. **Ejecutar los Notebooks:**
   Ejecuta las celdas en el orden en que aparecen para observar cómo funcionan los algoritmos y los resultados obtenidos.

## Notebooks

### 1. QLearning
Este notebook implementa el algoritmo Q-Learning, un método de aprendizaje por refuerzo basado en tablas que aprende una política óptima mediante iteraciones.

### 2. Deep Q-Learning (DQN)
Este notebook utiliza redes neuronales para aproximar la función Q, lo que permite abordar problemas con espacios de estados más grandes que no son factibles de manejar con tablas.

### 3. MAXQ-0
Este notebook implementa el algoritmo MAXQ-0, una técnica jerárquica de descomposición de tareas que divide el problema del Taxi en subtareas manejables.

## Licencia

Este proyecto está bajo la licencia MIT.

