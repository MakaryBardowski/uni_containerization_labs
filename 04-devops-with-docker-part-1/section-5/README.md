<h4>Zadanie 1.9</h4>
Zeby zmountowac folder na hoscie do folderu w kontenerze mozemy zrobic to za pomoca ( w przypadku tego zadania ):
docker run -v /mojFolderZLogami:/usr/src/app/text.log devopsdockeruh/simple-web-service
<h4>Zadanie 1.10</h4>
uruchomienie kontenera z zamapowanymi portami:
docker run -p 8080:8080 devopsdockeruh/simple-web-service server
