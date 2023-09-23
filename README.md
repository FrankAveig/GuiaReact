# GuiaReact

Para mantener la consistencia y legibilidad en nuestro código, seguimos una convención específica para el orden de las importaciones. A continuación se detalla el orden recomendado:

1. **Bibliotecas Externas**: Importa primero las bibliotecas o dependencias externas.
    ```javascript
    import React from 'react';
    import axios from 'axios';
    ```

2. **Funciones y Utilidades**: Importaciones de funciones generales o utilidades.
    ```javascript
    import { fetchData } from '../utils/apiHelpers';
    ```

3. **Constantes**: Importa las constantes que usarás en tu componente o módulo.
    ```javascript
    import { API_ENDPOINT, STATUS_CODES } from '../constants/config';
    ```

4. **Componentes**: Importaciones de componentes, ya sean generales o específicos.
    ```javascript
    import MyComponent from '../components/MyComponent';
    ```

5. **Imágenes y Estilos**: Importa archivos de estilos, imágenes, SVGs, etc., al final.
    ```javascript
    import logo from '../assets/logo.svg';
    import './styles.css';
    ```

6. **Lazy Imports y Otras Importaciones Dinámicas** (si las usas):
    ```javascript
    const DynamicComponent = React.lazy(() => import('../components/DynamicComponent'));
    ```

---

Recuerda siempre mantener una línea en blanco entre cada grupo de importaciones para mejorar la legibilidad. Además, es útil agregar comentarios antes de cada grupo si consideras que ayudará a clarificar el propósito de cada bloque.

El orden de las importaciones no solo facilita la legibilidad, sino que también ayuda a identificar rápidamente dependencias, utilidades y componentes específicos cuando revisamos el código.
