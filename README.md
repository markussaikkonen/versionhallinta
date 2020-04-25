# versionhallinta
Palvelinten hallinta 2020 / h3

Tämä raportti on kirjoitettu MarkDownilla

MarkDownin käytön edellytyksenä on raportille luotu Git repository eli varasto. 
Käytin Linux-palvelimet 2020-kurssilla luomaani Git-tunnusta, jonne loin repositoryn "Versionhallinta".

![image](1.png)

Asensin gitin paikallisesti, konfiguroin omat käyttäjätiedot sekä salasana-asetukset 

![image](2.png)

"Kloonasin" Git-repositoryni terminaaliin $ git clone https://github.com/markussaikkonen/versionhallinta.git 
Muokkasin README.md-tiedostoa ja lisäsin muutokset Gittiin $ git add . && git commit; git pull && git push. Päivitin selaimen testatakseni tulokset


![image](3.png)

MarkDown ja Git toimivat onnistuneesti. 

# ‘git log’, ‘git diff’ ja ‘git blame’

Tarkastellaan ja testataan git-komentoja. git log antaa raportin commit-historiasta. Raportissa näkyy commitin käyttäjätiedot, jotka
konfiguroitiin aiemmin. Eli käyttäjän nimi sekä sähköposti. Lisäksi komento tulostaa kirjoitetun komennon sekä tarkan ajan.

![image](7.png)

