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


    * translateY(-60px) eleva el objeto hacia arriba, sin el translateY(-60px) el objeto se agranda desde el centro ej:  transform: scale(1.1)translateY(-60px);*/
/* poner transision de 0.3s para que no sea tan tedioso para el usuario */
/* animation-delay:3s;   para ue haga la animacion antes que el otro, agregar los segundos para que se junte con otras animaciones ej: en el texto del navbar */

/* ANIMACION */
/* translateY(-60px) eleva el objeto hacia arriba, sin el translateY(-60px) el objeto se agranda desde el centro ej:  transform: scale(1.1)translateY(-60px);*/
/* poner transision de 0.3s para que no sea tan tedioso para el usuario */
/* animation-delay:3s;   para ue haga la animacion antes que el otro, agregar los segundos para que se junte con otras animaciones ej: en el texto del navbar */
codigo:
transform: scale(1.1);  
    transition: 0.3s;




    