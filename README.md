# Weather App

Esta aplicación meteorológica te permite obtener información detallada sobre las condiciones climáticas de cualquier ciudad. Utiliza la API de OpenWeatherMap para proporcionar datos precisos y actualizados. Antes de comenzar, asegúrate de tener una clave de API de OpenWeatherMap y sigue los pasos de configuración mencionados en la sección correspondiente.

## Configuración de la API Key

1. Obtén una clave de API gratuita de OpenWeatherMap registrándote en [OpenWeatherMap](https://openweathermap.org/appid).
2. Copia tu clave de API generada.

## Configuración en la Aplicación

1. Clona este repositorio en tu máquina local:

Abre el proyecto en tu editor de código favorito.

Navega al archivo src/App.js.

En la parte superior del archivo, encontrarás la variable api_key:

javascript
Copy code
let api_key = ""; // Agrega tu clave de API de OpenWeatherMap aquí
Pega tu clave de API entre las comillas.

Instalación y Ejecución
Abre una terminal en la carpeta del proyecto.

Instala las dependencias utilizando el siguiente comando:

npm install
Inicia la aplicación:

npm run dev
Esto abrirá la aplicación en tu navegador predeterminado.

Uso de la Aplicación
Ingresa la ciudad para la cual deseas obtener el pronóstico del tiempo en el formulario de búsqueda.

Haz clic en el botón "Buscar" o presiona "Enter".

La aplicación mostrará la siguiente información:

Temperatura actual<br>
Descripción del clima<br>
Humedad<br>
Velocidad del viento<br>
Características<br>
Interfaz sencilla y fácil de usar.<br>
Datos meteorológicos detallados proporcionados por la API de OpenWeatherMap.<br>
Personalización de la información según la ciudad ingresada.<br>
Tecnologías Utilizadas<br>
React.js para la interfaz de usuario.<br>

