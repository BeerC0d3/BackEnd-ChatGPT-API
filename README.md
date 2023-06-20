# BackEnd-ChatGPT-API
La API de Acceso a ChatGPT es una interfaz que te permite interactuar con el modelo de lenguaje ChatGPT, desarrollado por OpenAI. Esta API te permite enviar solicitudes de texto al modelo y recibir respuestas generadas por el mismo.


## Configuración

Antes de utilizar la API, necesitarás realizar los siguientes pasos:

* Obtén una clave de API de OpenAI para acceder al modelo ChatGPT.

* Configura tu clave de API de OpenAI: ChatGPT.ApiKey = 'TU_CLAVE_DE_API' que esta en appsettings.json

## Usage

Consumir API

```json
# Setup: https://localhost:7110/api/chat/setup
{
  "conversationId": "8fa85f64-5717-4562-b3fc-2c963f66afa5",
  "message": "",
  "contextFile": "https://localhost:7110/api/context/KSK"
}

# chat: http://www.chatgptintegras3.somee.com/api/chat
{
  "conversationId": "1fa84f64-5717-4562-b3fc-2c963f66afa5",
  "message": "Conoces de integraS3, como entro a kiosko"
}

```

## Consideraciones
Ten en cuenta que el uso de la API de OpenAI puede tener costos asociados. Asegúrate de revisar la documentación de OpenAI para obtener más detalles sobre la facturación y los precios.

El modelo ChatGPT es muy poderoso y puede generar respuestas coherentes y convincentes, pero también puede generar respuestas incorrectas o no deseadas en algunos casos. Siempre es recomendable revisar y filtrar las respuestas generadas según tus necesidades.

Experimenta con diferentes configuraciones y ajusta los parámetros según tus requisitos para obtener los mejores resultados posibles.

Recursos adicionales
[Documentación de OpenAI](https://platform.openai.com/docs/api-reference)
[Página de OpenAI en GitHub](https://github.com/openai)

## License

[MIT](https://choosealicense.com/licenses/mit/)
