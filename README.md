[README (1).md](https://github.com/user-attachments/files/27929473/README.1.md)
# Weather App ☀️🌧️

Aplicación web desarrollada en React que permite consultar el clima en tiempo real de cualquier ciudad del mundo, consumiendo la API REST de [WeatherAPI](https://www.weatherapi.com/).

## 🚀 Características

- 🔎 **Búsqueda de clima** por nombre de ciudad.
- 🌡️ Información en tiempo real: temperatura, condición climática, viento y humedad.
- 🌗 **Diseño adaptativo** según condiciones día/noche.
- 📱 Interfaz responsiva construida con Bootstrap.
- ⚙️ **Manejo seguro de credenciales** mediante variables de entorno (`.env`).

## 🛠️ Tecnologías utilizadas

- **React 18** — Librería principal para la UI.
- **JavaScript (ES6+)**
- **Custom Hooks** — `useForm` para manejo de formularios.
- **PropTypes** — Validación de props en componentes.
- **Fetch API** — Para consumir la API REST.
- **Bootstrap 5** — Para estilos y diseño responsivo.

## 📦 Instalación y uso

### Requisitos previos
- Node.js 18 o superior
- npm o yarn
- Una API key gratuita de [weatherapi.com](https://www.weatherapi.com/)

### Pasos

```bash
# 1. Clonar el repositorio
git clone https://github.com/Sxito8/Weather-App.git
cd Weather-App

# 2. Instalar dependencias
npm install

# 3. Crear el archivo .env en la raíz del proyecto con tu API key
# (copia el formato de .env.template)
echo "VITE_WEATHER_API_KEY=tu_api_key_aqui" > .env

# 4. Ejecutar el servidor de desarrollo
npm start
```

La aplicación quedará disponible en `http://localhost:3000`.

## 📂 Estructura del proyecto

```
Weather-App/
├── public/
├── src/
│   ├── api/
│   │   └── weatherapi.js       # Conexión con la API
│   ├── assets/
│   │   └── css/                # Estilos
│   ├── components/
│   │   ├── Search.jsx          # Barra de búsqueda
│   │   └── WeatherCard.jsx     # Tarjeta de información del clima
│   ├── Hooks/
│   │   └── useForm.js          # Hook personalizado
│   ├── App.jsx                 # Componente raíz
│   └── main.jsx                # Punto de entrada
├── index.html
├── package.json
└── vite.config.js
```

## 🧠 Lo que aprendí

- Construcción de **custom hooks** en React para reutilización de lógica.
- Manejo seguro de **variables de entorno** con `.env` para proteger credenciales.
- Consumo asíncrono de APIs REST con `async/await` y `useEffect`.
- Validación de props con **PropTypes** para mayor robustez del código.
- Renderizado condicional según el estado de la aplicación.
- Diseño responsivo con Bootstrap.

## 👤 Autor

**Sixto Exiga Martínez**
Ingeniero en Sistemas Computacionales — Instituto Tecnológico de Tuxtepec
[GitHub](https://github.com/Sxito8)

---

*Proyecto desarrollado durante el curso de Frontend Development 2024.*
