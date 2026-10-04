# Asistente de IA para tienda online (n8n + Gemini)

Agente de atención al cliente que responde preguntas de compradores usando inteligencia artificial.

## Qué hace
- Recibe mensajes de clientes por chat.
- Responde en español, de forma breve y amable.
- Recuerda la conversación (memoria).
- Usa solo la información de la tienda que se le da. Si no sabe algo, ofrece contactar a un asesor humano.

## Herramientas
- n8n (automatización)
- Google Gemini (modelo de IA)
- Nodos: Chat Trigger, AI Agent, Simple Memory

## Cómo usarlo
1. Instala n8n (npx n8n).
2. Importa el archivo .json de este repositorio (Workflows > Import from file).
3. Crea tu credencial de Google Gemini con tu propia clave de API.
4. Cambia en el AI Agent el System Message con los datos de tu tienda.
5. Abre el chat y haz una pregunta.

## Aprendizajes
Primer proyecto de automatización con IA: aprendí a conectar nodos, pasar datos entre ellos, crear un agente con memoria y escribirle instrucciones.

## English summary
AI customer-support agent built with n8n and Google Gemini. It answers shopper questions in Spanish, remembers the conversation, and hands off to a human when it does not know the answer.
