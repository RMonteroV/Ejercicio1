# Ejercicio1

**Que comando utilizaste en el paso 11?**
  git reset --hard HEAD~1
**Por que?**
  He utilizado "hard" porque queremos perder los cambios realizados en el working copy.

**Que comando o comandos utilizaste en el paso 12?**
  git reflog
  git reset --hard identificadorCommitPrimerModificacion
**Por que?**
  He utilizado "reflog" para coger el "identificadorCommitPrimerModificacion" y "reset --hard"
  con el identificadorCommitPrimerModificacion para forzar a deshacer los cambios.
  
**El merge del paso 13, Causo algun conflicto?**
  Sin conflictos, se queda como esta.
**por que?**
  Ya esta esta actualizado, es un merge Fast Forward, no cambia nada.

**El merge del paso 19, Causo algun conflicto?**
  Conflicto. CONFLICT (content): Merge conflict in git-nuestro.md
  Automatic merge failed; fix conflicts and then commit the result.
**por que?**
  Es un merge Non Fast Forward, por lo cual los ficheros tienen informacion diferente en algunas
  de las mismas lineas.
  
**El merge del paso 21, Causo algun conflicto?**
  Sin conflictos, se queda como esta.
**por que?**
  Ya esta esta actualizado, es un merge Fast Forward, no cambia nada.

**Que comando o comandos utilizaste en el paso 25?**
  git log --graph --decorate --oneline

**El merge del paso 26, Podria ser fast forward?**
  Si.
**por que?**
  Por que el commit donde esta master es el padre del commit donde apunta title.
  
**Que comando o comandos utilizaste en el paso 27?**
  git reset HEAD~1
  
**Que comando o comandos utilizaste en el paso 28?**
  git reset --hard identificadorCommitMergePaso26

**Que comando o comandos utilizaste en el paso 29?**
  git branch -d title

**Que comando o comandos utilizaste en el paso 30?**
  Ninguno, ya que el merge se encuentra porque en el paso 28 hemos descartado los cambios.

**Que comando o comandos utilizaste en el paso 32?**
  git reset identificadorCracionFichero

**Que comando o comandos utilizaste en el paso 33?**
  git reflog
  git reset identificadorUltimoMerge









  
  
  
  
  
  


  
  
  
  
  
  
  
  
  
  
  
  
  
  
 
