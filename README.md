
# Proyecto Modelado de base datos

## Descripción
Este proyecto de ciencia de datos, modelan entidades clave como clientes, datasets, analistas y proyectos utilizando Programación Orientada a Objetos (POO) en Python.

## Estructura del Proyecto
- `requirements/requirements.txt`: Listado de dependencias del proyecto.
- `main.ipynb` (o similar): Notebook principal con la lógica del sistema.
- Otras carpetas para datos, modelos, etc.

## Instalación
1.  **Clonar el repositorio** (si aplica):
    ```bash
    git clone <URL_DEL_REPOSITORIO>
    cd <NOMBRE_DEL_REPOSITORIO>
    ```

2.  **Crear y activar un entorno virtual**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # Linux/macOS
    # venv\Scriptsctivate.bat  # Windows (cmd)
    # venv\Scripts\Activate.ps1  # Windows (PowerShell)
    ```

3.  **Instalar dependencias**:
    ```bash
    pip install -r requirements/requirements.txt
    ```

## Uso
Una vez instalado, puedes ejecutar los notebooks o scripts de Python para interactuar con el sistema.

## Clases Principales
- `Cliente`: Gestiona la información de los clientes.
- `Dataset`: Representa los conjuntos de datos, incluyendo su estado y calidad.
- `Analista`: Gestiona los analistas, su especialidad y disponibilidad.
- `Proyecto`: Agrupa clientes, datasets y analistas, gestionando el estado del proyecto.
- `DataCoSystem`: Sistema central para registrar y gestionar proyectos.

## Contribución
Si deseas contribuir a este proyecto, por favor sigue las siguientes guías...

## Licencia
Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.
