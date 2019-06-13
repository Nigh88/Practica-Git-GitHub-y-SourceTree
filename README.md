# Practica-Git-GitHub-y-SourceTree

- ¿Qué comando utilizaste en el paso 11? ¿Por qué? 
 git reset --hard HEAD~1, por que si usaba git reset HEAD~1 los cambios del working copy se mantendrian
 y solo se desharía el ultimo commit.

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué? 
 git reflog y git reset --hard xxxxxxxx, para poder volver a la versión donde realicé los cambios, justo 
 antes de hacer el  hard reset.

- El merge del paso 13, ¿Causó algún conﬂicto? ¿Por qué? 
 No, pero si se cancelo el merge porque la versión de la rama 'styled' está en una linea mas avanzada 
 y actualizada a la de 'master'.

- El merge del paso 19, ¿Causó algún conﬂicto? ¿Por qué? 
 Sí, por que se hizo un merge del mismo archivo modificado en diferentes ramas y al mismo nivel.
 
- El merge del paso 21, ¿Causó algún conﬂicto? ¿Por qué? 
 No, por que al hacerlo desde la rama 'master', que es un archivo mas antiguo y por debajo de la rama 'styled', absorve los cambios
 de la otra rama.

- ¿Qué comando o comandos utilizaste en el paso 25? 
  git log --graph --decorate --pretty=oneline

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 
  Sí, por que el archivo de la rama 'title' esta en un nivel más avanzado que el de la rama 'master', al hacer el merge absorve 
 los cambios, sin causar conflictos si quiera.

- ¿Qué comando o comandos utilizaste en el paso 27?
 git reset HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 28?
 git checkout -- <file>

- ¿Qué comando o comandos utilizaste en el paso 29?
 git branch -D <branch>

- ¿Qué comando o comandos utilizaste en el paso 30? 
 git reflog y git checkout xxxxxxx

- ¿Qué comando o comandos usaste en el paso 32? 
 git reflog y git reset --hard xxxxxxx, aunque podría haber usado también git reflog y git checkout xxxxxx

- ¿Qué comando o comandos usaste en el punto 33?
 git reflog y git reset --hard xxxxxxx
