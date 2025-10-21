# ChatBot-Gemini

## 🤖 Chatbot con Gemini AI
Un chatbot moderno y funcional construido con HTML, CSS y JavaScript vanilla, que utiliza la API de Google Gemini para generar respuestas inteligentes en tiempo real.

## 🎯 Descripción
Este proyecto es un chatbot web inspirado en ChatGPT que utiliza la API de Google Gemini para proporcionar respuestas inteligentes a las preguntas de los usuarios. Está desarrollado completamente con tecnologías web frontend (HTML, CSS, JavaScript) sin necesidad de un servidor backend.
El proyecto fue desarrollado como parte de la materia Programación para Internet y demuestra el uso de:

*Consumo de APIs REST
*Manipulación del DOM
*Diseño responsive
*Programación asíncrona con async/await
*Manejo de errores

## 🛠 Tecnologías Utilizadas
### Frontend

*HTML5 - Estructura del documento
*CSS3 - Estilos y animaciones
  *Flexbox para layouts
  *Gradientes CSS
  *Animaciones y transiciones
  *Media queries (responsive)


*JavaScript (ES6+) - Lógica de la aplicación
  *Fetch API para peticiones HTTP
  *Async/Await para código asíncrono
  *DOM Manipulation
  *Event Listeners



### API
*Google Gemini API - Inteligencia artificial conversacional
  *Modelo: gemini-2.0-flash-exp
  *Versión: v1beta
  *Endpoint: generateContent




## 📦 Requisitos Previos
Antes de comenzar, necesitas:

1.Un navegador web moderno (Chrome, Firefox, Safari, Edge)
2.Una API Key de Google Gemini (gratuita)
3.Conexión a internet (para llamadas a la API)

### Obtener API Key de Google Gemini

1.Ve a Google AI Studio
2.Inicia sesión con tu cuenta de Google
3.Haz clic en "Create API Key"
4.Copia la API Key generada (guárdala en un lugar seguro)

Nota: La API Key es gratuita y tiene límites de uso generosos para proyectos personales y educativos.

## 🚀 Instalación
### Opción 1: Descarga Directa

1.Descarga el archivo index.html
2.Guárdalo en una carpeta de tu computadora
3.Abre el archivo con tu navegador favorito

```bash
 No se requiere instalación de paquetes
# Solo abre el archivo HTML en tu navegador
```
### Opción 2: Clonar Repositorio
```bash
 Clona el repositorio (si está en GitHub)
git clone https://github.com/tu-usuario/chatbot-gemini.git

# Navega a la carpeta
cd chatbot-gemini

# Abre index.html en tu navegador
```

## 💻 Uso
### Paso 1: Configurar API Key

1.Abre la aplicación en tu navegador
2.En el campo superior, pega tu API Key de Google Gemini
3.Haz clic en "Guardar API Key"
4.Verás un mensaje de confirmación ✅

### Paso 2: Comenzar a Chatear

1.Escribe tu mensaje en el campo de texto inferior
2.Presiona Enter o haz clic en "Enviar"
3.Espera la respuesta del bot (verás "Pensando...")
4.La respuesta aparecerá en formato de burbuja
5.¡Continúa la conversación!

## 📸 Capturas de Pantalla
### Pantalla Principal
<img width="983" height="597" alt="image" src="https://github.com/user-attachments/assets/7d2d2c40-468d-4a7b-9921-402367e59dc6" />

### Chat en Acción
<img width="786" height="89" alt="image" src="https://github.com/user-attachments/assets/55e1e87c-e622-4b62-a85d-8790c67983c6" />
<img width="483" height="136" alt="image" src="https://github.com/user-attachments/assets/5a76ffe2-1ab6-484a-9829-dd7561ba262d" />
<img width="924" height="237" alt="image" src="https://github.com/user-attachments/assets/0e8e0405-0daa-421f-a6ef-5c07d229df73" />
<img width="955" height="577" alt="image" src="https://github.com/user-attachments/assets/84b95449-a199-4af3-bce5-40a6ef572010" />


## 🐛 Problemas Comunes
### Error: "API Key no válida"
Solución:

  *Verifica que copiaste correctamente la API Key
  *Asegúrate de que la API Key esté activa en Google AI Studio
  *Revisa que no haya espacios al inicio o final

### Error: "models/gemini-xxx is not found"
Solución:

  *Asegúrate de usar el modelo correcto: gemini-2.0-flash-exp
  *Verifica que la URL use v1beta y no v1

### Error: "Failed to fetch"
Solución:

  *Verifica tu conexión a internet
  *Comprueba que no haya un bloqueador de anuncios o firewall
  *Revisa la consola del navegador para más detalles

### El bot no responde
Solución:

  *Abre la consola del navegador (F12)
  *Busca mensajes de error
  *Verifica que hayas guardado la API Key
  *Comprueba que el botón "Enviar" esté habilitado

### Límite de peticiones excedido
Solución:

  *Espera unos minutos antes de continuar
  *La API gratuita tiene límites de 60 peticiones/minuto
  *Considera espaciar tus peticiones

