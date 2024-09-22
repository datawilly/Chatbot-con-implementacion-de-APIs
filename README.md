# Simple Chatbot with NLTK and External APIs

## Overview
This project implements a simple chatbot using Python's **NLTK** library for natural language processing. The chatbot can interact with users to provide weather information, latest news, and perform web searches using external APIs.

The chatbot includes:
- **Weather Information**: Fetches current weather details for Colombian cities using the OpenWeather API.
- **News Search**: Provides the latest news on a specified topic using the NewsAPI.
- **Google Search**: Performs web searches via the Google Custom Search API.
- **Conversation Logging**: All user interactions are saved in a JSON file for future reference.

## Table of Contents
- [Overview](#overview)
- [Installation](#installation)
- [APIs and Setup](#apis-and-setup)
- [Functionality](#functionality)
- [Logging](#logging)
- [Contributing](#contributing)

## Installation
To run this project on your local machine, you need the following Python libraries:

```bash
pip install nltk scikit-learn requests
```

There is no `requirements.txt` file provided, so you will need to install the required libraries manually.

## APIs and Setup
This project requires the following APIs:
- **OpenWeather API**: For weather information.
- **NewsAPI**: To fetch the latest news.
- **Google Custom Search API**: For performing web searches.

Before running the notebook, make sure you set up your API keys as environment variables:

```python
import os
os.environ['OPENWEATHER_API_KEY'] = 'your_openweather_api_key'
os.environ['NEWS_API_KEY'] = 'your_newsapi_key'
os.environ['GOOGLE_API_KEY'] = 'your_google_api_key'
os.environ['CSE_ID'] = 'your_custom_search_engine_id'
```

## Functionality
The chatbot responds to a variety of user inputs. Here are some examples:

- **Weather**: Type "What's the weather in Bogotá?" to get the current weather details.
- **News**: Ask for the latest news by typing "Give me the latest news about technology."
- **Google Search**: Perform a search by typing "Search for Python tutorials."
- **Other commands**: The chatbot can also respond to general phrases like "What is your name?" or "Thank you."

## Logging
All interactions between the user and the chatbot are logged into the `interacciones.json` file. This includes user input and chatbot responses for tracking purposes.

## Contributing
If you would like to contribute to this project, feel free to fork the repository and submit a pull request. Contributions are always welcome!

---

# Chatbot Simple con NLTK y APIs Externas

## Descripción General
Este proyecto implementa un chatbot simple utilizando la biblioteca **NLTK** de Python para el procesamiento de lenguaje natural. El chatbot puede interactuar con los usuarios para proporcionar información sobre el clima, noticias recientes y realizar búsquedas en la web utilizando APIs externas.

El chatbot incluye:
- **Información del Clima**: Obtiene los detalles del clima actual de las ciudades colombianas utilizando la API de OpenWeather.
- **Búsqueda de Noticias**: Proporciona las últimas noticias sobre un tema especificado utilizando la API de NewsAPI.
- **Búsqueda en Google**: Realiza búsquedas web mediante la API de Google Custom Search.
- **Registro de Conversaciones**: Todas las interacciones con el chatbot se guardan en un archivo JSON para futuras referencias.

## Tabla de Contenidos
- [Descripción General](#descripción-general)
- [Instalación](#instalación)
- [APIs y Configuración](#apis-y-configuración)
- [Funcionalidades](#funcionalidades)
- [Registro de Conversaciones](#registro-de-conversaciones)
- [Contribuciones](#contribuciones)

## Instalación
Para ejecutar este proyecto en tu máquina local, necesitarás las siguientes librerías de Python:

```bash
pip install nltk scikit-learn requests
```

No se incluye un archivo `requirements.txt`, por lo que deberás instalar las librerías necesarias manualmente.

## APIs y Configuración
Este proyecto requiere las siguientes APIs:
- **API de OpenWeather**: Para información meteorológica.
- **API de NewsAPI**: Para obtener las últimas noticias.
- **API de Google Custom Search**: Para realizar búsquedas en la web.

Antes de ejecutar el notebook, asegúrate de configurar las claves de API como variables de entorno:

```python
import os
os.environ['OPENWEATHER_API_KEY'] = 'tu_clave_openweather'
os.environ['NEWS_API_KEY'] = 'tu_clave_newsapi'
os.environ['GOOGLE_API_KEY'] = 'tu_clave_google'
os.environ['CSE_ID'] = 'tu_id_motor_busqueda'
```

## Funcionalidades
El chatbot responde a una variedad de entradas del usuario. Algunos ejemplos:

- **Clima**: Escribe "¿Cómo está el clima en Bogotá?" para obtener los detalles actuales del clima.
- **Noticias**: Solicita las últimas noticias escribiendo algo como "Dame las últimas noticias sobre tecnología."
- **Búsqueda en Google**: Realiza una búsqueda escribiendo "Buscar tutoriales de Python."
- **Otros comandos**: El chatbot también puede responder a frases generales como "¿Cómo te llamas?" o "Gracias."

## Registro de Conversaciones
Todas las interacciones entre el usuario y el chatbot se registran en el archivo `interacciones.json`. Esto incluye las entradas del usuario y las respuestas del chatbot para fines de seguimiento.

## Contribuciones
Si deseas contribuir a este proyecto, siéntete libre de bifurcar el repositorio y enviar una solicitud de extracción. ¡Las contribuciones son siempre bienvenidas!
