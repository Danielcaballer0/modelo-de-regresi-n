# Predicción de Precios de Casas en Bengaluru

## Descripción
Este proyecto implementa un modelo de regresión lineal para predecir el precio de viviendas en Bengaluru, India. Utiliza datos de propiedades, incluyendo ubicación, tamaño, número de baños y balcones, para realizar predicciones interactivas a través de una interfaz web con Voilà.

## Características
- Preprocesamiento de datos con Pandas.
- Modelo de regresión lineal con Scikit-learn.
- Evaluación del modelo con métricas de error.
- Interfaz interactiva con widgets en Voilà.
- Implementación en GitLab y despliegue con Binder.

## Instalación
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/Danielcaballer0/modelo-de-regresi-n.git
   cd house-price-prediction
   ```
2. Crear un entorno virtual e instalar dependencias:
   ```bash
   python3 -m venv voila_env
   source voila_env/bin/activate  # En Windows: voila_env\Scripts\activate
   pip install -r requirements.txt
   ```

## Uso
1. Ejecutar el modelo en un Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Para usar la interfaz interactiva con Voilà:
   ```bash
   voila app.ipynb
   ```
3. Ingresar los valores en la interfaz y obtener la predicción del precio de la vivienda.

## Despliegue con Binder
Puedes ejecutar este proyecto en Binder sin necesidad de instalar nada:
[![Abrir en Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/danielcaballero3514%2Fhouse-price-prediction/HEAD)

## Contribución
Si deseas mejorar este proyecto:
1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature-nueva`).
3. Realiza cambios y haz commit (`git commit -m 'Agregando nueva funcionalidad'`).
4. Sube los cambios (`git push origin feature-nueva`).
5. Abre un Pull Request en GitLab.

## Licencia
Este proyecto está bajo la licencia MIT. Puedes usarlo y modificarlo libremente.
