# Creamos una APP RAG para suministrarle datos de manera privada y constante a traves de documentos PDF.
#### Se suministro el libro en formato PDF "Ciencia-de-datos-desde-cero.de Joel-Grus", sin embargo el RAG puede ser alimentado con cualquier documento. Se deben ubicar en la carpeta "data"
## Herramienta:
En este ejemplo a través del prompt y de preguntas de lenguaje natural, se le puede pedir al modelo que respondan a interrogantes planteados, usando Llama-Index para catalogar la información y ChatGpt como modelo de respuesta.
* Se ha usado la API de OpenAI junto a LlamaIndex y el modelo "gpt-
* Se ha tomado como ejemplo el libro Ciencia-de-datos-desde-cero. de Joel-Grus
## Uso:
* Se debe contar con Jupyther notebok o Google Colab, para poder ejecutar de forma dinamica el archivo "RAG_Llama-Index.ipynb".
* Se debe contar con una cuenta de OpenAI y crear en ella un proyecto y crear una contraseña de API, usar la variable "OPENAI_API_KEY".
### Creditos:
Este ejercicio esta basado en el video https://www.youtube.com/watch?v=FRsd8tYX6n4 del canal @CodingMindsetIO. Gracias a su autor.