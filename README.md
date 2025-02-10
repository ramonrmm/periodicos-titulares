# Consulta de titulares de los periódicos

Este proyecto realiza web scraping para obtener los titulares principales de los periódicos más destacados en España. Utiliza las librerías `requests` y `BeautifulSoup` para extraer los datos y los muestra en pantalla, además de guardarlos en un archivo.

## Nota importante

Algunos diarios tienen restricciones en su aviso legal o en su `robots.txt` que prohíben el web scraping. Este proyecto tiene fines diácticos y muestra cómo se pueden utilizar las herramientas de Python para este tipo de tareas.

## Requisitos previos

Antes de ejecutar el script, asegúrate de tener instalado Python y las siguientes dependencias:

```bash
pip install requests beautifulsoup4 babel
```

## Uso

Ejecuta el script en un entorno de Jupyter Notebook o directamente como un archivo `.py`:

```bash
python periodicos.py
```

Los titulares serán extraídos y mostrados en pantalla, además de guardarse en un archivo de texto.

## Consideraciones

- Las estructuras HTML de los periódicos pueden cambiar con el tiempo, por lo que es recomendable revisar el código periódicamente.
- Si un periódico bloquea las peticiones, podría ser necesario modificar los `headers` de la solicitud.

## Licencia

Este proyecto está realizado por Ramón Morales y es de uso educativo, no debe emplearse con fines comerciales ni de manera que infrinja los términos de uso de los sitios web consultados.

