# PracticaDetachedHead

Explicación:
- Escenario 1: tan solo cambiamos el puntero de la rama master a un commit anterior y,
como solo observamos información, al terminar volvemos al HEAD con "git checkout HEAD".

-Escenario 2: Al realizar cambios en commits anteriores, es necesario realizar un
"git switch -c otra_rama" para realizar los cambios en esa rama y, tras ello, realizar
un "git merge" a la rama master para volver a tener los commits realizados y el último
cambio en la rama master.
