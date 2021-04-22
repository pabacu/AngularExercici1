# AngularExercici1
Git test
#- Exercici 1
Gran part de les activitats de la ITAcademy s'hauran de pujar en un repositori GIT, per tant, és molt important que coneguis el seu funcionament. Segueix els següents passos amb el programa SourceTree o semblant.

El teu primer repositori Git (linea comandes):

#Crear un nou repositori al teu GitHub
Crear una nova carpeta al teu PC. (copia_proyecto_git)
Clonar el repositori a aquesta carpeta del teu ordinador (git clone “url/to/repository”).
Crear un fitxer de text (.txt) en aquesta carpeta.
Fer un commit i push per a pujar els canvis al repositori remot de GitHub.
Treballar amb branques:

#Crear una branca anomenada “branch1”.
Modifica el text del fitxer des d’aquesta branca.
Fes Commit i Push dels canvis. (Si mires al GitHub, hauries de veure que tens dues branques)
Torna a la branca “master”.
Fes un altre canvi al document i fer commit i push.
Des d’aquesta fer merge dels canvis de la “branch1” a la teva branca “master”.

#Conflictes!

Com era d’esperar, els Git t’avisa que hi ha canvis a les dues branques. En aquest cas tenim 3 opcions:

Mine: seleccionar que els canvis de la branca actual “master” es la versió bona.
Their: seleccionar que els canvis de l’altra branca “branch1” són els bons.
Resoldre el conflicte: Si accedeixes al fitxer veuras que git ha afegit 3 linies de codi, esborrar-les i deixar les dues línies (una per cada branca). [Per a l’exercici has d’utilitzar aquesta opció]
Un cop resolt el conflicte, s’ha de fer commit i push a la branca master. Si tot ha anat correctament, hauries de visualitzar un fluxe com aquest, més o menys: