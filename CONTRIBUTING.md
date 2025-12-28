# Contribuyendo al Proyecto

Sigue estas pautas al contribuir para asegurar que el código se mantenga limpio y organizado.

## Pasos para contribuir

### 1. Haz un Fork del repositorio
Primero, haz un fork de este repositorio. Esto crea una copia de este proyecto en tu cuenta de GitHub para que puedas trabajar en él sin afectar al repositorio original.

- Haz clic en el botón de **"Fork"** en la parte superior derecha de esta página.
- Esto creará una copia del repositorio en tu cuenta de GitHub.

### 2. Clona tu fork en tu computadora
Una vez que hayas hecho el fork, clona el repositorio en tu máquina local para trabajar en él. Agrega el repositorio original como un remote.

```bash
git clone git@github.com:tu-usuario/GitHub-Flow.git
cd GitHub-Flow
git remote add upstream git@github.com:JMProf/GitHub-Flow.git
```

### 3. Crea una nueva rama para tus cambios

Es importante trabajar en una nueva rama para no afectar la rama principal (main). Usa un nombre descriptivo para tu rama.

```bash
git switch -c nombre-de-tu-rama
```

### 4. Haz los cambios en el código

Realiza los cambios que consideres necesarios. Puedes editar los archivos index.html y styles.css para mejorar el diseño y la estructura de la página web o añadir nuevas funcionalidades. También puedes crear nuevos archivos HTML y CSS para añadir nuevas páginas o estilos.

### 5. Realiza un commit de tus cambios

Cuando hayas hecho los cambios, guarda los archivos y realiza un commit para registrarlos.

```bash
git add .
git commit -m "Descripción breve de los cambios realizados"
```

### 6. Sube los cambios a tu repositorio remoto

Una vez que hayas realizado el commit, sube los cambios a tu repositorio en GitHub.

```bash
git push origin nombre-de-tu-rama
```

### 7. Abre un Pull Request

Ve a tu repositorio en GitHub y verás un botón que muestra "Compare & Pull Request". Haz clic en él y crea un Pull Request (PR) hacia la rama main del repositorio original.

En la descripción del PR explica los cambios que has realizado adjuntando capturas de pantalla de la página web antes y después de los cambios.

### 8. Espera la revisión

Una vez que hayas enviado el PR debes esperar a que revise tus cambios. Si todo está bien, tu PR será fusionado con el repositorio principal.

Si hay errores de validación de HTML o CSS (por ejemplo, debido a problemas de sintaxis), GitHub Actions te mostrará los errores y te indicará en qué parte del código se encuentran. Puedes corregirlos y volver a enviar tu PR.

## Estilo y buenas prácticas

* HTML: asegúrate de seguir las buenas prácticas de HTML, como usar etiquetas semánticas, cerrar las etiquetas correctamente y mantener el código limpio y bien organizado.

* CSS: usa una estructura limpia y organizada. Asegúrate de que el código CSS sea consistente y fácil de leer, utilizando convenciones como la indentación adecuada.

* Evita cambios innecesarios: solo realiza cambios relacionados con la tarea o la mejora que estás proponiendo. No cambies demasiado el formato o la estructura si no es necesario.

* Nombres descriptivos: al nombrar tus ramas y commits, usa descripciones claras que expliquen el propósito de los cambios.

## Validaciones Automáticas con GitHub Actions

Este proyecto usa GitHub Actions para validar automáticamente tu código cada vez que envíes un Pull Request. Cuando envíes un PR, GitHub verificará:

* HTML: se validará que el código HTML sea válido según los estándares de la W3C.

* CSS: se validará que tu código CSS siga las buenas prácticas y esté libre de errores.

Si el flujo de trabajo de GitHub Actions detecta algún error, el Pull Request no podrá ser fusionado hasta que los errores sean corregidos.

## Código de conducta

Por favor, sigue un comportamiento respetuoso y profesional en todas tus interacciones. Este es un espacio para aprender y mejorar, y todos debemos ayudarnos mutuamente para que sea una experiencia positiva.

Si tienes alguna pregunta o necesitas ayuda, no dudes en abrir un issue o enviarme un mensaje.