# Vivero Gema

**Vivero Gema** es una aplicación web diseñada para monitorear y presentar los reportes de las plantas sembradas en el **Páramo de Guerrero**. La aplicación recoge datos a través de **TAGs de Arduino**, que obtienen información detallada sobre cada planta en tiempo real, facilitando la supervisión y el análisis de su desarrollo.

## Características principales

- **Monitoreo de plantas en el Páramo de Guerrero**: Los datos recolectados incluyen información sobre el estado de crecimiento, humedad, temperatura, y otros parámetros de las plantas.
- **Reportes interactivos**: La aplicación genera reportes gráficos y tablas, presentando la información de cada planta en un formato visualmente accesible.
- **Integración con TAGs de Arduino**: Los TAGs conectados a cada planta envían datos en tiempo real a la plataforma para su procesamiento y visualización.

## Tecnologías utilizadas

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js
- **Base de datos**: MySQL
- **Hardware**: Arduino con sensores RFID
- **Despliegue**: Servidor web (por definir)

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tuusuario/vivero-gema.git
   ```
##Instala las dependencias:

  ```bash
  Copiar código
  cd vivero-gema
  npm install
 ```
##Configura la base de datos MySQL:

##Crea una base de datos llamada vivero_gema.
Importa el archivo schema.sql en tu base de datos.
Inicia el servidor:

 ```bash
Copiar código
npm start
```
##Uso
Accede a la aplicación desde tu navegador web en http://localhost:3000.
Navega por los reportes interactivos y consulta la información de cada planta monitoreada en el Páramo de Guerrero.
Los datos se actualizan automáticamente gracias a los TAGs conectados a cada planta, que envían información periódica al sistema.
##Contribución
Si deseas contribuir al proyecto, realiza un fork del repositorio, realiza tus cambios en una rama separada y envía un pull request para su revisión.

##Licencia
Este proyecto está bajo la licencia MIT. Puedes ver más detalles en el archivo LICENSE.
