1. git init: Skapar ett nytt git repository, används för att starta ett nytt project.
2. git clone: Skapar en kopia av ett avlägset repository på sin locala maskin, används för att kopia ett repository till sin locala maskin för att jobba vidare med projected.
3. git add: Lägger till ändringar till uppställningsområdet, vilja filer som skall läggas till kan specifieras med en filväg till exempel . för att lägga till allt i den stådende mappen.
4. git commit: Sparar ändringar till det locala repositoryt, används för att spara ändringar för att sedan pusha sitt locala repository.
5. git status: Visar det nuvarande läget av repositoryt, används för att se vilka filer som har ändrats men inte lagts till i repositoryt med git add.
6. git push: Laddar upp de locala förändringarna till ett remote repository. Används för att ladda upp de senaste förändringarna gjorde i sett projekt.
7. git pull: Hämtar och sammanfogar ändringar från ett remote repository. Används för att hämta de senaste ändringarna gjorda till projektet.
8. git fetsh: Hämtar ändringar fråm ett remote repository. Används för att se de förändringar som har hänt i repositorut.
9. git merge: Sammanfogar förändringar från en gren till en annan. Kan användas för att integrera förändringar från development grenen in i main grenen till exempel.
10. git branch: Listar alla granar i repositoryt. Används också för att skapa nya grenar med `git branch <gran namn>`
11. git checkout: Byter till en annan gren. Används för att byta vilken gren man vill kode emot.
12. git log: Visar commit historiken. Används för att se commit historiken, commit ID och se vart HEAD står.
13. git diff: Visar skillnaden mellan två variationer av en fil. Kan användas för att se skillnaden mellan två commits `git diff <commit01_ID> <commit02_ID>`
14. git stash: Temporärt förvarar ändringar som inte är klara för att bli commitade. Används för att lägga undan arbete för att arbeta på det senare.