# CLOUD COMPUTING: Actividad Semana 2

## Instrucciones de uso

**Paso 1:** Haz fork o clona este repositorio.  
**Paso 2:** Crea un entorno virtual con `uv venv`.  
**Paso 3:** Activa el entorno virtual:  
- En Windows: `.\venv\Scripts\activate`  
- En macOS/Linux: `source venv/bin/activate`  

**Paso 4:** Instala las dependencias con `uv sync`.  
**Paso 5:** Crea un archivo `id_confidential.json` donde pongas tu id de Azure.  
**Paso 6:** Corre `01_preprocesamiento.ipynb` para limpiar y preparar los datos.  
**Paso 7:** Corre `02_entrenamiento_modelo.ipynb` para entrenar el modelo de predicción.  
**Paso 8:** Corre `03_deploy_api_azure.ipynb` para desplegar el modelo como servicio en Azure.  
**Paso 9:** Para hacer inferencia con nuevos datos, corre `04_inferencia_api.ipynb` sustituyendo el archivo `test_data.csv` por el que desees consultar.

### Especificaciones mínimas:
- OS: Windows 10, macOS 10.15, o una distribución moderna de Linux
- RAM: 8 GB
- Ancho de banda: Conexión a internet de al menos 10 Mbps
- Almacenamiento: 20 GB de espacio libre
- Python: Versión 8.8 o superior

## Autores y departamentos:
- Nombre del equipo: **RAR Solutions**
- Departamento de datos: Blas, Analista de datos
- Departamento de modelos: David, Ingeniero de modelos
- Departamento de cómputo en la nube: Rodrigo, Desplegador de Azure