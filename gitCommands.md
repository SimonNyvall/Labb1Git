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
15. git reset: Tar bort ändringar från staging area eller drar tillbaka en commit. Kan användas för att dra tillbaka ändringar till staging area.
16. git revert: Skapar en ny commit som ångrar ändringarna gjorda i en föregående commit. Används för att ångra en commit i ett repository.
17. git cherry-pick: Tillsätter ändringar av en specifik commit till den aktiva grenen. Används för att tillsätta förändringar i en specifik commit till den aktiva grenen.
18. git blame: Visar vem som gjorde varje ändring till en fil och när den gjordes. Används för att sparka folk, skapa ovänner och se vem som gjort vad.
19. git remote: Visar vilket remote repository som är assisterat med den locala repot. Används också för att lägga till kopplingar, ändra och ta bort med add, -set-URL och remove
20. git tag: Lägger till en tagg på en commit etikera. Används för att ge mer information om en commit, utöver commit kommentaren.
21. git fetch --prune: Tar bort några remote spårnings grenar som inte längre existerar. Kan användas för att hålla det locala repot synkroniserat med det remote repositoryt, genom att ta bort inaktuella referenser.
22. git checkout -b: Skapar en ny gren och sätter den som aktiv. Används när man vill man är lat och inte orkar skriva `git branch <gren namn>` och `git switch <gren namn>`.
23. git checkout --: Förkastar förändringar gjorda mot en fil och ångar den backs till den senaste commiten. Används för att återställa förändringar i en fil.