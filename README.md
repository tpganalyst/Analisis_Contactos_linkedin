# 🚀 Análisis de Contactos de LinkedIn con Gemini API  

Este proyecto utiliza la **API de Gemini** de Google para analizar contactos de LinkedIn a partir de un archivo CSV, clasificando los perfiles según su área de conocimiento.  

## 📌 Características  

- ✅ Procesa automáticamente un archivo `Connections.csv` con los contactos de LinkedIn.  
- ✅ Clasifica cada perfil en categorías como **Desarrollo de Software, Marketing, Finanzas, Ventas**, entre otras.  
- ✅ Utiliza la API de **Gemini** para generar análisis mediante inteligencia artificial.  
- ✅ Guarda los resultados en un archivo CSV con la clasificación de cada contacto.  

## 🔧 Configuración  

1. **Clonar el repositorio o descargar el código.**  
2. **Instalar las dependencias necesarias (si es requerido).**  
3. **Configurar la API Key de Gemini:**  

   En Google Colab, antes de ejecutar el código, agrega la clave de la API de esta manera:  

   ```python
   import os
   import google.generativeai as genai

   # Establecer la clave manualmente
   os.environ['GEMINI_API_KEY'] = 'TU_CLAVE_AQUI'  # Reemplaza con tu clave real

   # Configurar la API de Gemini
   gemini_api_key = os.getenv('GEMINI_API_KEY')
   genai.configure(api_key=gemini_api_key)
   
Subir el archivo Connections.csv a Google Colab.
Ejecutar el script y esperar a que se genere el archivo de salida con los resultados.

📂 Archivos
Connections.csv → Archivo de entrada con los contactos de LinkedIn.

linkedin_contacts_analyzed_YYYYMMDD_HHMMSS.csv → Archivo de salida con los contactos clasificados.

📢 ¡Contribuciones y sugerencias son bienvenidas!
