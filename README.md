# clonetest
Dette er en README.md fil og bruges normalt til at forklare indeholdet af repo'en og diverse guide, eg. guides til at kompilere/køre din kode.

Brug chatGPT til at finde ud af hvordan man udfører de unævnte trin :) (det gør jeg normalt, og det er meget hurtigere end at læse stackoverflow posts nogle gange)

Der er nemlig nogle ting du skal gøre lokalt, eksempelvis at logge ind på din konto online.

Ellers bare spørg mig på messenger.

Følg guiden:

Clone repo

**git clone intast_selv**

For at loade nye filer fra github ned til dit locale repo eller "mappe", kør **git pull**

Tilføj en filer til mappen kaldet **fil_jeg_vil_have_på_github.txt** og **fil_jeg_ikke_vil_have_på_github.txt**


Tilføj **fil_jeg_ikke_vil_have_på_github.txt** til din **.gitignore**

Note: dette kunne være irrelevante filer såsom kompilerede binaries du kører lokalt. Husk fra c++ at du compilede dine source scripts, eg. **ex2.cpp**, til **ex2.o**. Derfor kunne du også tilføje ***.o** filer til din **.gitignore** da andre selv kan kompilere kon

Du har nu nye filer i dit lokale repo


Få filerne op på github ved at tilføje filer til et commit, lave et commit med dine ændringer, og til sidst pushe alle dine lokale commits til github repo'et (remote/origin):

Tilføj alle ændringer i dit lokale repo som ikke er nævnt i:

**git add .**

Denne kommando tilføjer **alle** ændringer

Du kan tilføjer enkelte filer til commit ved:

**git add fil1 fil2 fil3**

Dernæst vil du gerne committe dine ændringer du har tilføjet

**git commit**

Tilføj en lille beskrivelse til commit, måske kunne det være hvad dine ændringer er. Brug det på en måde så du senere nemmere kan forstå hvad du tidligere har tilføjet til dit projekt/repo, og også hvornår du lavede de ændringer.

Nu er du glad for dit arbejde! Så lad os tilføje det online til github ved at pushe alle dine lokale commits:

**git push**

Tjek github repo'et og verificer at dine lokale ændringer er tilføjet i git repo'et online. Skriv til jesper
