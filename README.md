# GNC-LURO

! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/...

Encontré una forma de "corregirlo":

git pull
git branch --set-upstream-to=origin/main main
git pull --allow-unrelated-histories
git push -u origin main

COMENTARIO
antes del git push debes obtener la informacion del estado actual del repositorio remoto siempre, sino hay comflictos, con git pull por ejemplo la obtienes, solo sin git branch ni el resto, luego despliga tus cambios, con git push sin -u origin si la rama la tienes por defecto