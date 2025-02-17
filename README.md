## Dev

1. Clonar el repositorio
2. Crear un .env basado en el .env.template
3. Ejecutar el comando `docker compose up --build`
4. Añadir los cambios al repositorio (git add, git commit, git push) Ej:
```
git add .
git commit -m "Add submodule"
git push
```
5. Inicializar y actualizar Sub-módulos, cuando alguien clona el repositorio por primera vez, debe de ejecutar el siguiente comando para inicializar y actualizar los sub-módulos
`git submodule update --init --recursive`
6. Para actualizar las referencias de los sub-módulos
`git submodule update --remote`