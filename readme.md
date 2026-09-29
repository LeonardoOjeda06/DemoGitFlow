## GITFLOW TEST
 1. primer paso feature: 
- git clone
- git fetch: descarga en local los ultimos cambios realizados en el repo(estructura, ramas, etc)
- git checkout develop: Instruccion que permite cambiar de una rama a otra en este caso la rama de desarrollo
- git pull origin develop: Una vez en rama de desarrollo se bajan los cambios que estan en remoto en el repo para la rama desarrollo
- git checkout -b feature/HU10-crear-solicitud-leonardo (en esta rama es donde nosotros vamos a desarrollar nuestra funcionalidad)
- git add .
- git commit -m "mis ajustes melomaneish"
- git push
### Commit Ammend Papus (Cambiando el mensaje del commit)

- Ya hechos los ajustes entonces lo que hacemos es:
    - git add .
    - git commit --amend -m "mis ajustes oficiales"
    - git push --force-with-lease

### Commit Ammend Papus (Sin cambiar el mensaje del commit)
- Ya hechos los ajustes entonces lo que hacemos es:
    - git add .
    - git commit --amend --no-edit
    - git push --force-with-lease
