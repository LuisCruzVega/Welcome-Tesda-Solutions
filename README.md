
# Página de Prueba

Este proyecto contiene una página web de prueba que simula una aplicación o sitio web. El objetivo principal es utilizarla como ejemplo para montar la página dentro de un contenedor Docker.

## Descripción

Este repositorio solo contiene un archivo HTML simple que sirve como ejemplo básico para probar el proceso de implementación de páginas web en Docker.

## Tecnologías Utilizadas

- **HTML**

## Instrucciones

1. **Clona este repositorio:**
    ```bash
    git clone https://github.com/LuisCruzVega/Welcome-Tesda-Solutions.git
    ```

2. **Navega a la carpeta del proyecto:**
    ```bash
    cd Welcome-Tesda-Solutions/Desafio-Docker/html
    ```

3. **Construye y corre el contenedor Docker:**
    ```bash
    docker build -t prueba-web .
    docker run -p 80:80 prueba-web
    ```

4. **Accede a la página en tu navegador:**
    Abre tu navegador y ve a `http://localhost`.

## Notas

Esta página es solo una demostración de cómo se puede implementar una página web básica en un contenedor Docker.
