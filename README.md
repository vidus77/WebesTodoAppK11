 # WebesTodoAppK11
A NetAcademia "Az első Webes C# projektem> TO-DO alkalmazás készítése" tanfolyam ismétlésének 2019-01 kódtára 

Általános DotNet csoport a facebook-on: DotNet Cápák
A tanfolyam célja

                               +------------------------+
                               |   Desktop számítógép   |
                               |                        |
                               |    +-------------+     |
+---------------+              |    |  Alkalmazás |     |
|               |              |    |             |     |
|  Felhasználó  |              |    +-------------+     |
|               |              |                        |
|               |              |                        |
+---------------+              |                        |
                               +------------------------+


    Hagyományos Desktop/Mobil alkalmazásfejlesztés

                                                                          +--------------------------+
                                                                          |  Szerver számítógép      |
                               +------------------------+                 |                          |
                               |   Desktop számítógép   |                 |                          |
                               |    Mobil eszköz        |    Hálózati     |                          |
                               |                        |    kapcsolat    | +----------------------+ |
+---------------+              |                        |                 | |                      | |
|               |              |    +-------------+     +---------------> | |  Szerver alkalmazás  | |
|  Felhasználó  |              |    | Alkalmazás  |     |                 | |  (WebSzerveren futó  | |
|               |              |    | (Böngésző)  |     | <---------------+ |  app)                | |
|               |              |    +-------------+     |                 | |                      | |
+---------------+              |                        |        ^        | +----------------------+ |
                               +------------------------+        |        |                          |
                                                                 |        |              ^           |
                                            ^                    |        |              |           |
                                            |                    |        |              |           |
                                            |                    |        |              |           |
                                            |                    |        +--------------------------+
                                            |                    |                       |
                                            +                    +                       +
                                          HTML                 HTTP                     MVC



                                               Webes Alkalmazásfejlesztés

Ajánlott tanfolyamok

    HTML Lenyűgöző weblapok készítése
    HTTP Hálózati alapismeretek
    GIT Fedezzük fel a gitet!

Az első webes alkalmazásunk létrehozása

Mivel a környezet és a fejlesztési munkafolyamat az ilyen típusú fejlesztéseknél összetett, így nem kézzel hozzuk létre, hanem a Visula Studio template-jének a segítségével.

A varázslóval létrehozzuk az ASP.NET MVC Webalkalmazást (.NET framework), az alábbi módon:

Új projekt létrehozása: 