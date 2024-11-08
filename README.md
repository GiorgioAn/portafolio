# Portafolio Web y Digital de Jorge Antonio García Ortiz

[💼 Portafolio en Línea](https://jgartiz.netlify.app/)

Este es mi portafolio web y digital, donde muestro mis habilidades en tecnologías gráficas y de desarrollo web. El proyecto está construido con **HTML**, **CSS**, y **JavaScript**, y utiliza herramientas como **npm** y **Webpack** para la gestión y empaquetado de archivos. **El portafolio está en constante desarrollo**, por lo que algunos contenidos y funcionalidades están en etapas de diseño y codificación.

## Descripción del Proyecto

Mi portafolio sirve como una muestra de mis habilidades y proyectos en el ámbito del diseño gráfico y la programación web. La interfaz presenta una combinación de creatividad y tecnología, enfocada en brindar una experiencia visual atractiva y profesional. Puedes explorar mis proyectos, habilidades y la variedad de herramientas tecnológicas que manejo en el sitio.

Este portafolio es una **versión inicial** que se seguirá actualizando a medida que agrego más contenido y mejoras.

## Tecnologías Utilizadas

- **HTML**
- **CSS**
- **JavaScript**
- **Webpack**
- **npm**
- Librerías:
  - `eins-modal`: Para manejo de ventanas modales.
  - `normalize.css`: Para estandarizar estilos entre navegadores.

## Cómo Clonar e Instalar el Proyecto

Sigue estos pasos para clonar e instalar el proyecto en tu entorno local.

### 1. Clonar el Repositorio

```bash
git clone https://github.com/GiorgioAn/portafolio.git
cd portafolio
```

### 2. Instalar Dependencias

Dado que el archivo `node_modules` no está incluido en el repositorio, es necesario instalar las dependencias. Ejecuta el siguiente comando para instalar las dependencias necesarias para el desarrollo:

```bash
npm ci
```

Este comando instalará las dependencias exactas listadas en el archivo `package-lock.json` para garantizar consistencia en los entornos de desarrollo.

### 3. Scripts Disponibles

El proyecto cuenta con varios scripts en el archivo `package.json` para facilitar el desarrollo y la producción:

- **`start`**: Ejecuta el servidor de desarrollo de Webpack.

   ```bash
   npm run start
   ```

   Esto iniciará el servidor en modo de desarrollo, permitiéndote visualizar los cambios en tiempo real a medida que editas los archivos.

- **`build`**: Construye el proyecto para producción.

   ```bash
   npm run build
   ```

   Este comando empaqueta los archivos y los optimiza para producción, generando el contenido en la carpeta `dist`.

- **`test`**: Actualmente, el script de prueba solo arroja un mensaje, ya que las pruebas no están especificadas.

### 4. Correr el Proyecto en Desarrollo

Para ejecutar el proyecto en tu entorno local, asegúrate de tener las dependencias instaladas y luego ejecuta:

```bash
npm run start
```

El servidor de desarrollo se ejecutará y podrás ver el proyecto en tu navegador en `http://localhost:8080` (o en el puerto asignado por Webpack Dev Server).

## Contribuciones

Este portafolio es un proyecto personal en desarrollo, y agradezco sugerencias o contribuciones que puedan mejorar la presentación y la funcionalidad del sitio. Si tienes alguna idea o encuentras algún problema, no dudes en abrir un **issue** o enviar un **pull request**.

**Autor**: Jorge Antonio García Ortiz

**Licencia**: ISC

Repositorio en GitHub: [https://github.com/GiorgioAn/portafolio](https://github.com/GiorgioAn/portafolio)
```
