# Buscador de Gifs (Gif Expert App)

Este proyecto es una aplicación web para buscar y visualizar GIFs, desarrollada para mi capacitación en React a través del curso de **Fernando Herrera en DevTalles**.

La aplicación permite a los usuarios buscar GIFs, ver búsquedas previas y cargar más resultados a medida que se desplazan.

## Características Principales

* **Buscador en tiempo real:** Los GIFs se cargan automáticamente mientras el usuario escribe en la barra de búsqueda.
* **Historial de búsqueda:** Guarda y muestra un historial de las últimas búsquedas, permitiendo un acceso rápido a términos anteriores.
* **Optimización de rendimiento:** Utiliza un caché local (`useRef`) para evitar peticiones repetidas a la API cuando se busca un término ya consultado.
* **Componentes reutilizables:** La interfaz está construida con componentes modulares, como la barra de búsqueda (`SearchBar`), la lista de GIFs (`GifList`) y el historial de búsquedas (`PreviousSearches`).
* **Consumo de API:** Se usa **Axios** para gestionar las peticiones a la API de Giphy.

## Tecnologías Utilizadas

* **React:** Biblioteca principal para la construcción de la interfaz de usuario.
* **TypeScript:** Añade tipado estático al proyecto, mejorando la robustez y el mantenimiento del código.
* **Axios:** Cliente HTTP para hacer peticiones a la API de Giphy.
* **Vite:** Herramienta de construcción para un entorno de desarrollo rápido.
* **Giphy API:** API pública utilizada para obtener los GIFs.
* **CSS:** Para el diseño y estilos de la aplicación.

## Instalación y Ejecución

Para clonar y ejecutar este proyecto localmente, sigue estos pasos:

1.  Clona el repositorio:
    ```bash
    git clone [https://github.com/AgustinSantillan/react-gift-expert-app.git]
    ```

2.  Navega al directorio del proyecto e instala las dependencias:
    ```bash
    cd [nombre-del-proyecto]
    npm install
    ```

3.  Crea un archivo `.env` en la raíz del proyecto con tu clave de la API de Giphy:
    ```
    VITE_GIPHY_API_KEY=tu_clave_de_api
    ```

4.  Inicia el servidor de desarrollo:
    ```bash
    npm run dev
    ```
