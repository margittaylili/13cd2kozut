# crud_react

Előszőr betöltjük a könyvtárakat sorrendbe az express-t ami egy webes szerver keretrendszer, cors ami lehetővé teszi a frontendes adat átvevést, mysql ez kapcsolatot biztosít az adatbázissal, body-parser a json adatok feldolgozására van amit app.use()-al automatizálunk.

A db (database) egy msql kapcsolatot hoz létre megadott adatokkal például port, host, adatbázis.

Az első lekérés egy teszt lekérés hogy megnézzük hogy fut-e a backend.

A második lekérésnél látjuk az sql lekérdezésből hogy ez egy index function lekérdezés vagyis minden adatot lekérünk a regiok táblából.