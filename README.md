# Traductor con OpenAI

Este es un programa Python que utiliza la API de OpenAI para realizar traducciones de texto. Utiliza el modelo "text-davinci-003" de OpenAI para realizar las traducciones.

## Configuración

Antes de ejecutar el programa, asegúrese de configurar correctamente las variables de entorno:

1. Cree un archivo `.env` en la raíz del proyecto.
2. Agregue las siguientes líneas al archivo `.env`:

    OPENAI_API_KEY=`SU_CLAVE_DE_API`

    Sustituya `SU_CLAVE_DE_API` por su clave de API de OpenAI.

3. Ejecute el siguiente comando para instalar las dependencias necesarias:

```shell
pip install openai python-dotenv
```

## Uso

Ejecute el programa escribiendo el siguiente comando en el terminal:

```shell
python traductor.py
```

El programa solicitará el texto a ser traducido y el idioma de destino. Después de la traducción, el resultado se mostrará en la consola.

## Observaciones

Asegúrese de tener una cuenta en OpenAI y de que su clave de API esté activa.

Verifique su cuota de uso en OpenAI para garantizar que no exceda los límites permitidos.

Observe que este es un ejemplo completo en lenguaje de marcado, siguiendo la sintaxis de Markdown, para un archivo README.md.

Asegúrese de copiar todo el contenido correctamente en su archivo README.md.

