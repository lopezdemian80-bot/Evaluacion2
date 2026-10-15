# Evaluacion2 – CUY6142

Proyecto de la Evaluación 2 de Telepresencia y Entornos Innovadores de Colaboración Humana (Duoc UC).

## Archivos
- **Ramdom50libros.py**: agrega 50 libros aleatorios (título, autor e ISBN generados con Faker) a la API de la biblioteca de la VM DEVASC y lista todos los libros.
- **geolocalizacion.py**: calcula rutas con la API de GraphHopper. Textos en español, valores con 2 decimales, narrativa del viaje en español y opción de salir con "s" o "salir".

## Requisitos
- VM DEVASC
- Python 3
- Librerías: `pip3 install requests faker`
- API key de GraphHopper (incluida en el script): `dfbf7038-0f9b-4ab5-8d44-b4f051585379`

## Ejecución
### Ramdom50libros.py
    python3 Ramdom50libros.py

### geolocalizacion.py
    python3 geolocalizacion.py

1. Ingresar el perfil de vehículo (car, bike o foot).
2. Ingresar la ubicación de origen y el destino.
3. Escribir `s` o `salir` para terminar.
