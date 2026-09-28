# proyectopreentrega-c26226

*Explicación detallada de lo que hace cada una de las líneas de comandos en la terminal (bash):*

1.	mkdir tienda-dummyjson *mkdir significa Make Directory (Crear directorio).

*¿Qué hace?: Crea una carpeta nueva en la ubicación actual llamada tienda-dummyjson. Es la carpeta donde se guardarán todos los archivos del proyecto.

2.	cd tienda-dummyjson *cd significa Change Directory (Cambiar directorio).

*¿Qué hace?: Entra a la carpeta tienda-dummyjson que se creó. A partir de este momento, cualquier archivo o comando que se ejecute se aplicará dentro de este directorio.

3.	npm init -y *npm es el gestor de paquetes de Node.js.

*init inicia o inicializa un nuevo proyecto de Node.js.

*-y significa Yes a todo (saltea las preguntas iniciales de configuración usando los valores por defecto).

*¿Qué hace?: Genera automáticamente un archivo llamado package.json. Este archivo es el manifiesto del proyecto: guarda información básica (nombre, versión) y registrará los paquetes o librerías que se instalen más adelante (como node-fetch).

*Ejemplos de prueba en la Consola Acción:*

Comando a ejecutar para obtener todos los productos: npm run start GET products

Obtener un producto por ID: npm run start GET products/15

Crear un producto: npm run start POST products "Remera Rex" 300 remera

Eliminar un producto:npm run start DELETE products/7
