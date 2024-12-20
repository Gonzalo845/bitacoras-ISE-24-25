# Bitácoras de Prácticas de Ingeniería de Servidores - Curso 24/25

Bienvenidos a la asignatura de **Ingeniería de Servidores (ISE)** del curso 24/25. Este repositorio tiene como objetivo gestionar las bitácoras individuales de los estudiantes mediante enlaces a sus repositorios privados.

Cada estudiante debe crear un repositorio privado en GitHub llamado `practicas-ISE` y agregar al profesor como colaborador. Transcurrida cada lección, el estudiante deberá realizar un **pull request** (PR) a este repositorio (`bitacoras-ISE-24-25`) para agregar un enlace a su bitácora individual.

## Instrucciones detalladas

Sigue los pasos a continuación para añadir tu bitácora a este repositorio utilizando la interfaz web de GitHub.

### 1. Crea tu repositorio privado en GitHub
1. Inicia sesión en tu cuenta de GitHub y crea un repositorio privado llamado **`practicas-ISE`**.
2. Dentro de tu repositorio, lleva un registro de tu progreso en las prácticas de la asignatura.
3. Invita al profesor como colaborador a tu repositorio privado para que pueda revisarlo. El usuario del profesor en GitHub es: `orestibl`.

### 2. Crea un fichero con los resultados de la lección  
1. En tu repositorio llamado **`practicas-ISE`**, crea un nuevo fichero llamado `<practica-leccion>-resultados.md` (por ejemplo `P1-L0-resultados.md` para la lección 0 de la práctica 1). Para ello:
2. Haz clic en `Add file` y escribe la ruta completa `<practica-leccion>-resultados.md`.
3. Luego, haz clic en el icono del lápiz (✏️) en la esquina superior derecha del archivo para editarlo.
4. Añade los resultados de la práctica.
5. Haz clic en **Commit changes** para guardar tus cambios en tu repositorio.
6. Escribe un mensaje de confirmación en el campo **Commit changes**. Ejemplo: "Agrego resultados de lección 0 de la práctica 1 en mi repositorio".

### 3. Haz un **Fork** del repositorio del profesor
1. Ve a la página del repositorio del profesor: `https://github.com/orestibl/bitacoras-ISE-24-25`.
2. Haz clic en el botón **Fork** en la esquina superior derecha. Esto creará una copia del repositorio en tu propia cuenta de GitHub.

### 4. Edita el archivo `<SUBGRUPO>/<practica-leccion>.md` desde la web
1. Dentro de tu fork (el repositorio que acabas de copiar a tu cuenta), dentro de la carpeta de tu subgrupo (por ejemplo `D1`), edita el fichero llamado `<practica-leccion>.md` (por ejemplo `P1-L0.md` para la lección 0 de la práctica 1).
2. Haz clic en el icono del lápiz (✏️) en la esquina superior derecha del archivo para editarlo.
3. Introduce el enlace al archivo markdown (.md) de tu repositorio que contenga los resultados de la práctica (por ejemplo al archivo `P1-L0-resultados.md` para los resultados de la lección 0 de la práctica 1). Debes ponerlo en la línea de la tabla donde aparezca tu nombre (iniciales de tus apellidos seguidos de tu nombre de pila). Por ejemplo:

| Nombre       | Enlace                                                                   |
| --------------- | ---------------------------------------------------------- |
| X. Y. ZETA | [https://github.com/tu-usuario-github/practicas-ISE/P1-L0-resultados.md](https://github.com/tu-usuario-github/practicas-ISE/P1-L0-resultados.md)|

4. Haz clic en **Commit changes** para guardar tus cambios en tu fork.
5. Escribe un mensaje de confirmación en el campo **Commit changes**. Ejemplo: "Agrego enlace a mi bitácora para la lección 0 de la práctica 1".

### 5. Crea un Pull Request

1. Después de confirmar tus cambios en el archivo `<practica-leccion>.md`, ve a la pestaña **Pull Requests** en el repositorio de tu fork (copia).
2. Haz clic en el botón verde **New Pull Request**.
3. Asegúrate de que GitHub esté comparando tu fork con el repositorio original del profesor. Debería mostrar algo como:
-  **base repository**: `orestibl/bitacoras-ISE-24-25`
-  **head repository**: `tu-usuario-github/bitacoras-ISE-24-25`
4. Revisa los cambios propuestos para asegurarte de que todo esté correcto.
5. Haz clic en **Create Pull Request**.
6. En la página siguiente, escribe un título descriptivo para el pull request, como "Agrego enlace a mi repositorio de bitácoras para la lección 0 de la práctica 1". Finalmente, haz clic en **Create Pull Request**.

### 6. Espera la aprobación

Una vez que hayas creado el Pull Request, el profesor revisará tu solicitud y, si todo está correcto, la aceptará. Cuando el Pull Request sea aprobado y fusionado, tu enlace aparecerá en el archivo `<practica-leccion>.md` (por ejemplo `P1-L0.md` para la lección 0 de la práctica 1) del repositorio `bitacoras-ISE-24-25` del profesor.

### IMPORTANTE (solo para los sucesivos pull requests)

Cada vez que vayas a hacer un pull requests tendrás que sincronizar previamente. Este paso es muy importante de cara a tener la versión más actualizada del repositorio base. Recuerda sincronizar justo antes de hacer el pull request, ya que de otra forma puede que haya cambios en el repositorio (por ejemplo, realizados por otros compañeros y validados por el profesor) que no tengas en tu fork, y por tanto, generar potenciales conflictos. Estos conflictos impedirán que el profesor apruebe tu pull request.

### Contacto

Si tienes alguna duda sobre el proceso, no dudes en ponerte en contacto con el profesor a través del correo electrónico o en las horas de tutoría.

