# Starter kit React
[![My Skills](https://skillicons.dev/icons?i=react)]([(https://github.com/FrankAveig/GuiaReact)])

## Índice

- [Iniciar el proyecto](#iniciar-el-proyecto)
- [Estructura del proyecto](#estructura-del-proyecto)
- [Buenas prácticas de importaciones](#buenas-prácticas-de-importaciones)

---
## Iniciar el proyecto
#### El inicio de proyectos se realizara con Vite. Aquí los pasos a seguir:

<details>
  <summary>Ver información</summary>



###  1. Instalación de Vite

Asegúrate de tener Node.js (>=12.0.0) instalado en tu máquina. Luego, instala Vite globalmente:

```bash
npm install -g create-vite
```
### 2. Crear un nuevo proyecto

Para iniciar un nuevo proyecto de React con Vite:
```bash
create-vite my-project --template react
```
Reemplaza my-project con el nombre que desees para tu proyecto.

### 3. Navegar al directorio del proyecto

```bash
cd my-project
```

### 4. Instalar dependencias

Vite ya ha generado un package.json para tu proyecto. Instala las dependencias iniciales:

```bash
npm install
```
### 5. Correr el proyecto localmente

Usa el siguiente comando para iniciar el servidor de desarrollo:

```bash
npm run dev
```
</details>

## Estructura del proyecto
<details>
  <summary>Ver información</summary>

<details>
<summary>📂assets </summary>
    
```bash
Aquí se almacenan todos los recursos gráficos o archivos estáticos que tu aplicación pueda necesitar,
tales como imágenes, íconos, fuentes tipográficas y videos. Es ideal para mantener todos tus recursos
en un solo lugar y acceder a ellos fácilmente.
```
</details>

<details>
<summary>📂components </summary>

```bash
En esta carpeta encontrarás todos los componentes reutilizables y genéricos. Estos componentes pueden
ser botones, encabezados, pies de página, listas, etc. Son las piezas individuales que juntas construyen
tus vistas o páginas.
```
</details>

<details>
<summary>📂constans </summary>

```bash
Aquí se guardan las constantes del proyecto. Pueden ser cosas como rutas formato de datos, códigos de estado, y
cualquier otro valor que no vaya a cambiar a lo largo de la aplicación y se quiera tener centralizado.
```
</details>

<details>
    
<summary>📂context </summary>

```bash
Contiene los Contextos de React que proporcionan una forma de compartir valores como estos entre componentes
sin tener que pasar explícitamente un prop a través de cada nivel del árbol de componentes.
```
</details>

<details>
    
<summary>📂hooks </summary>

```bash
Aquí se almacenan los hooks personalizados. Los hooks son una adición reciente a React que permite usar estado
y otras características de React sin escribir una clase. Al crear tus propios hooks personalizados, puedes extraer
lógica de componentes para reutilizarla o separar la lógica compleja de tus componentes.
```
</details>
<details>
<summary>📂pages </summary>

```bash
Esta carpeta contiene componentes o vistas asociados a rutas específicas de tu aplicación. Por ejemplo, si tienes
una ruta /about, podrías tener un componente AboutPage aquí que representa esa vista.
```
</details>
<details>
<summary>📂services </summary>

```bash
Dentro de services se almacenan funciones o clases que manejan llamadas a APIs externas o cualquier otro tipo de
operaciones asíncronas. Esta separación permite que la lógica de tu aplicación no se mezcle con la lógica de las
peticiones a la red.
```
</details>
<details>
<summary>📁styles </summary>

```bash
En styles, se guardan los estilos globales, variables, mixins, o cualquier otro recurso relacionado con el diseño
y presentación visual de tu aplicación.
```
</details>
<details>
<summary>📂utils </summary>

```bash
Aquí puedes colocar cualquier función utilitaria que quieras reutilizar a través de tu aplicación. Pueden ser funciones
 para formatear fechas, validar formularios, manipular objetos y arrays, entre otros.
```
</details>

</details>

## Estándares tecnológicos
En el desarrollo de nuestros proyectos, establecemos estándares para asegurar la eficiencia, coherencia y calidad del código. Estas herramientas son obligatorias y deben ser utilizadas en el proyecto:
<details>
    <summary>Ver información</summary>
<details>
<summary>✔ Llamadas a la API: Axios</summary>
    
    
Recomendamos el uso de [Axios](https://github.com/axios/axios) para todas las llamadas a la API. Axios es una biblioteca de JavaScript muy popular que facilita la realización de solicitudes HTTP desde el navegador y Node.js. Algunas de las ventajas de Axios incluyen:

- Manejo automático de transformaciones JSON.
- Control de solicitudes concurrentes.
- Protección contra XSRF.
- Cancelación de solicitudes.

Para instalar Axios:
```bash
npm install axios
```
</details>
</details>
