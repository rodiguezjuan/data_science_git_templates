# Plantillas para Git:
## Introducción:
Las plantillas para Git son una herramienta poderosa para automatizar tareas comunes y mantener la consistencia en tu proyecto. Te permiten crear un proyecto con una estructura predefinida, archivos y configuraciones básicas.

## Beneficios de usar plantillas:

* Ahorra tiempo: Evita la configuración manual repetitiva al crear un nuevo proyecto.
* Comienza más rápido: Obtén una estructura de proyecto predefinida con los archivos y configuraciones necesarios.
* Mantén la consistencia: Asegura que todos los proyectos tengan la misma estructura y configuración.
* Mejora la colaboración: Facilita el trabajo en equipo al proporcionar un punto de partida común.

## Cómo usar plantillas:

### Plantilla git commit
1. **Copia la plantilla al proyecto**: Descarga la plantilla `git_commit_template.txt` desde GitHub o crea la tuya propia. Y colóquelo en la raíz del proyecto.

2. Ejecuta un comando:

En la carpeta del proyecto, ejecuta el comando `git config commit.template ./git_commit_template.txt` para instalar la plantilla. El comando puede variar según la plantilla, consulta la documentación de la plantilla para obtener instrucciones específicas.


**Nota**:
Otra opción, si nos interesase distribuir una configuración más compleja para Git, con muchos otros valores, sería incluir un archivo *.gitconfig* en la raíz del repo.
```
[commit]
  template = /git_commit_template.txt
```

`git config --local include.path ../.gitconfig`