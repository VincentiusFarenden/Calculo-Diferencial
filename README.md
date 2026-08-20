# Cálculo Diferencial

Conjunto de guías en Jupyter Notebook sobre cálculo diferencial con Python.

## Contenido

- Funciones y sus gráficas
- Composición de funciones, límites y continuidad
- Derivadas de funciones
- Aplicaciones de la derivada
- Máximos y mínimos
- Problemas de optimización
- Formulario de funciones en Python (definición, evaluación, resolución de ecuaciones)
- Formulario Python EA1 (funciones numéricas y simbólicas)

## Instalación

Clona el repositorio:
```bash
git clone https://github.com/VincentiusFarenden/Calculo-Diferencial.git
cd Calculo-Diferencial
```

Instala las dependencias en un entorno virtual (Para no romper otros paquetes nativos del sistema):

*Nota: Si utilizas Google Colab no es necesario instalar las dependencias ya que vienen pre-instaladas en la instancia por defecto.*

Linux/MacOS
```bash
python3 -m venv ~/venvs/data && ~/venvs/data/bin/pip install --upgrade pip && ~/venvs/data/bin/pip install numpy sympy pandas matplotlib seaborn scipy jupyter scikit-learn
```
Windows (PowerShell)
```bash
python -m venv $HOME\venvs\data ; & "$HOME\venvs\data\Scripts\pip" install --upgrade pip ; & "$HOME\venvs\data\Scripts\pip" install numpy sympy pandas matplotlib seaborn scipy jupyter scikit-learn
```

## Uso

Abre los notebooks (.ipynb) en VS Code o Google Colab y ejecuta las celdas para ver las guías, problemas y resoluciones.

Cada guía distingue los problemas a resolver:
- 📝 Problemas que se resuelven a mano, con lápiz y papel.
- 💻/🐍 Problemas que se resuelven de forma computacional, con Python.

## Librerías utilizadas

- NumPy
- SymPy
- SciPy
- Matplotlib
- ipywidgets
