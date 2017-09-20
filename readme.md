# PracticaGit - Respuestas

--

**1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?**

`git reset --hard HEAD~1` 

Porque con ese comando se deshace el último commit realizado y se pierden también los cambios realizados en el working copy.

--

**2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

`git reflog` `git checkout` 

Primero `git reflog` para ver el código que necesitaba para rehacer el último commit. Después `git checkout y el código` para volver al último commit que acababa de deshacer.  

--

**3. El merge del paso 13 ,¿Causó algún conflicto? ¿Por qué?**

No causó ningún conflicto.

--

**4. El merge del paso 19 ,¿Causó algún conflicto? ¿Por qué?**

No causó ningún conflicto.

--

**5. El merge del paso 21 ,¿Causó algún conflicto? ¿Por qué?**

No causó ningún conflicto.

--

**6. ¿Qué comando o comandos utilizaste en el paso 25?**

Se puede dibujar con `git log`, pero yo utilicé `git graph`

--

**7. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

Sí podria ser fast-forward.

--

**8. ¿Qué comando o comandos utilizaste en el paso 27?**

`git reset HEAD~1`

--

**9. ¿Qué comando o comandos utilizaste en el paso 28?**

Primero `git reflog` para ver el código que necesito para regresar y después `git reset y el código` para descartar los cambios.

--

**10. ¿Qué comando o comandos utilizaste en el paso 29?**

`git tag -D title`

--

**11. ¿Qué comando o comandos utilizaste en el paso 30?**

Primero `git reflog` para ver el código que necesito para regresar y después `git reset y el código` para rehacer el merge que había deshecho.

--

**12. ¿Qué comando o comandos utilizaste en el paso 32?**

Primero `git reflog` para ver el código que necesito para regresar y después `git checkout y el código` para volver al commit inicial donde se creó el poema.

--

**13. ¿Qué comando o comandos utilizaste en el paso 33?**

Primero `git reflog` para ver el código que necesito para regresar y después `git checkout y el código` para volver al estado final cuando puse título al poema.
