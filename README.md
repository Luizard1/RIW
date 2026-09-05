# Recuperación de Información de la Web

La **Recuperación de Información de la Web** estudia técnicas para localizar información relevante.

## Rastreadores Web

Un rastreador Web visita automáticamente diferentes páginas de Internet.

### Características

- Descarga páginas Web
- Analiza documentos
- Extrae enlaces
- Almacena información

## Herramientas

Algunas herramientas utilizadas son:

- Scrapy
- Requests
- BeautifulSoup

Más información disponible en [Python](https://www.python.org).

### Ejemplo en Python

```python
import requests
respuesta = requests.get("https://example.com")
print(respuesta.text)
```

## Conclusiones

Los rastreadores son fundamentales para los motores de búsqueda.
