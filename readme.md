- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
Utilicé el comando git reset --hard HEAD~1
El indicador --hard indica que sobreescriba todos los cambios en el working copy

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
Utilicé el comando git reflog para ver todo los los registros, copie el hash id del commit a restaurar y luego use el comando git reset 71af7dd 
y por último use el comando git add . y git commit

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué? 
No, no hay cambios en master que mergear, la rama styled se origino desde master

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Sí causó conflictos, ya que ambas partieron de main y fueron modificandose por separado

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No causó conflictos ya que la rama styled se originó desde main

- ¿Qué comando o comandos utilizaste en el paso 25?
git log --all --decorate --oneline --graph

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Pedir ayuda en este, diferencia entre ff y no ff

- ¿Qué comando o comandos utilizaste en el paso 27?
git reset 4f2a899

- ¿Qué comando o comandos utilizaste en el paso 28?
git restore git-nuestro.md

- ¿Qué comando o comandos utilizaste en el paso 29?
git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30?
git reset 0ecf622
git add .
git commit -m "Agrego de nuevo merge"

- ¿Qué comando o comandos usaste en el paso 32?
git checkout a58e5bd


- ¿Qué comando o comandos usaste en el punto 33? 
git checkout 24dff26

