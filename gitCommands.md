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