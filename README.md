cd GIT0420  -  (D meghajtón egykülön mappában tartom a Webleres anyagaim, nem az asztalon tárolom)

cd Murguly-Imre

git init

git clone https://github.com/szabopeter92/git-vizsga.git

rm -rf .git  (README.md, GitVizsga Repo.txt és GIT VIZSGA.docx fájlokat áthelyeztem a git-vizsga mappába)

cd git-vizsga

git init

git branch console

git checkout console

git add .  (oldal betöltődés)

git add .  (átmenetes háttérszín)

git commit -m"Oldal betöltődés és CSS-ben a háttérszín megváltoztatva"  (1 commit-om van mert a végén jöttem rá hogy a rögzítés alatt commit-ra gondolt a feladat, nem csak add-ra)

git remote rm origin (nem tudtam feltölteni a saját repository-ba amíg máshoz volt csatolva)

git add .

git commit -m"Végleges verzió rögzítve"

$ git push -u origin main