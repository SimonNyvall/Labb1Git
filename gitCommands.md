<<<<<<< HEAD
24. git log --graph: Visar commits i history som en graf, för att kunna simplifiera hur historiken har varit.
25. git log --oneline: Visar commit historia i komprimerat format, möjligt att göra det lättare att läsa historiken på en rad.
26. git merge  --abort: Avbryer pågående operation, om ett misstag har begåtts och man vill avbryta.
27. git rm: Tar bort en fil från repot, t.ex. om man missat gitignore.
28. git mv: Byter namn på en fil i repot. när man vill byta namn.
29. git show: Visar förändringar på en specifik commit. För att kunna följa en bugg som har uppståt.
30. git grep: Söker efter en specifik string i repot. Söka igenom alla repo branches för att hitta något man letar efter.
31. git shortlog: Visar commit historiken i summerat format. Söka igenom och få author och title på en commit.
32. git reflog: Visar en log av alla git kommandon som har genomförts i repot. Används för att kunna kolla vilka kommandon som körts
33. git config: Konfigurerar settings för Git. Möjligheten att kunna skapa egna querys i git.
34. git clone --depth: Skapar en ytlig klon av ett repo med limiterad historik. Andvänds för att kunna skapa en klon men endast få det man vill ha utav historiken.
35. git rebase: Integrerar ändringar från en branch till en annan genom att skriva om commit historiken. Kunna få möjligheten att merga ihop.
36. git bisect: Hjälper till att hitta den specifika commit som introducerade en bugg genom att utföra en binär sökning. Används för att kunna hitta buggar.
37. git push --force: Tvingar en push till ett remote repo, överskriver alla ändringar som kan vara där. När man inte orkar och bara vill forcea sin commit.
38. git remote add: Lägger till en nytt remote repo. Används för att skapa remota repos.
39. git remote remove: Tar bort ett remote repo. Används för att ta bort remota repos.
40. git remote set-url: Ändrar Urlen för ett remote repo. Används för att ändra Urlen för ett remote repo.
41. git log --author: Visar commit historiken för en specifik användare. Hitta historiken för en använders commits.
42. git log --since: Visar commit historiken från ett specifikt datum, Används för att söka commits från ett specifikt datum
43. git log --untill: Visar commit historiken fram till ett specifikt datum, Används för att söka commits till ett specifikt datum
44. git log --grep: Visar commit historiken för en specifik commit message eller string. Används för att hitta historiken för ett specifik commit medelande eller string.
45. git log --pretty: Formaterar commit historiken på ett specifikt sätt. Används för att formatera commit historiken på ett sätt.
=======
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
>>>>>>> Simons-dev
