# 🥦 NutriBot: Tu Asistente de Nutrición 🥦

Este proyecto es un chatbot de nutrición llamado NutriBot, construido con la biblioteca `genai` de Google. NutriBot puede responder a preguntas sobre dietas balanceadas, recetas saludables, información nutricional y mucho más.

## 📦 Instalación

Para instalar las dependencias necesarias, ejecuta el siguiente comando:

```bash
pip install genai
```

## Configuración
Para configurar el proyecto, necesitarás una clave API de Google. Puedes obtenerla siguiendo las instrucciones en la documentación oficial de Google.

Una vez que tengas la clave API, configura genai con la siguiente línea de código

```python
genai.configure(api_key=GOOGLE_API_KEY)
```

## 🚀 Uso

Para usar NutriBot, simplemente ejecuta el código en tu entorno de Python. NutriBot comenzará a interactuar contigo a través de la interfaz de chat.

Puedes hacer preguntas como "¿Qué alimentos me recomiendas?" y NutriBot te responderá con consejos útiles.

## 💬 Interfaz de Chat

NutriBot utiliza `ipywidgets` para crear una interfaz de chat interactiva. Puedes escribir tus preguntas en el cuadro de texto y NutriBot responderá en la misma interfaz.

