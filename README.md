# Red Neuronal con NumPy

Este repositorio contiene una implementación de una red neuronal simple utilizando NumPy. El script principal `main.py` ejecuta la función definida en `src/neural_network_numpy.py`.

## Estructura del Repositorio

```
📦 neural_network_numpy
├── 📂 src
│   ├── neural_network_numpy.py  # Implementación de la red neuronal con NumPy
├── .gitignore                    # Archivos a excluir en el control de versiones
├── main.py                       # Punto de entrada para ejecutar la red neuronal
├── README.md                     # Documentación del proyecto
├── requirements.txt               # Dependencias necesarias
```

## Requisitos

Para ejecutar este proyecto, asegúrate de tener Python instalado y las siguientes bibliotecas:

```
numpy
matplotlib
scikit-learn
```

Puedes instalar las dependencias ejecutando:

```
pip install -r requirements.txt
```

## Uso

1. Clona el repositorio:
   ```
   git clone https://github.com/tuusuario/nombre-del-repositorio.git
   cd nombre-del-repositorio
   ```

2. Activa el entorno virtual (opcional pero recomendado):
   ```
   python -m venv venv
   source venv/bin/activate  # En Mac/Linux
   venv\Scripts\activate  # En Windows
   ```

3. Instala las dependencias:
   ```
   pip install -r requirements.txt
   ```

4. Ejecuta el script principal:
   ```
   python main.py
   ```

Esto entrenará la red neuronal y mostrará una gráfica con los datos de clasificación.

## Explicación del Código

- `neural_network_numpy.py` contiene la implementación de una red neuronal desde cero usando NumPy.
- Se usa una arquitectura con múltiples capas y funciones de activación como `ReLU` y `sigmoide`.
- Se emplea el error cuadrático medio (`MSE`) como función de pérdida y un método de retropropagación para actualizar los pesos.
- Se genera un conjunto de datos sintético usando `make_gaussian_quantiles` de `scikit-learn` para entrenar el modelo.


