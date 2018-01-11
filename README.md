UML usecase modellezés
======================

Mik azok a használati esetek (use case, UC)?
--------------------------------------------
Hogyan épül fel egy használati eset leírása?
--------------------------------------------
Milyen kapcsolatban lehetnek az egyes aktorok, UC-ek?
--------------------------------------------
Hogyan fejthető ki részletesebben egy UC?
--------------------------------------------
Hogyan követhetők nyomon az egyes UC-ek (avagy mi a hatásuk) a tervezés későbbi fázisaiban?
--------------------------------------------

Lekérdezések, validáció: EMF-IncQuery és Eclipse OCL (2013-tól)
===============================================================

Ismertesse az EMF-IncQuery rendszer lekérdezőnyelvét!
--------------------------------------------
Hogyan használható az EMF-IncQuery modellalapú fejlesztőeszközökben?
--------------------------------------------
Milyen funkciókat támogathat? Mondjon pár példát hasonló technológiákra!
--------------------------------------------
Miben hasonlítanak és különböznek? 
--------------------------------------------
Mi az OCL célja?
--------------------------------------------
Jellegzetesen hol (milyen UML diagrammokban) használunk OCL kényszereket?
--------------------------------------------
Hogyan kapcsolható az OCL EMF modellekhez?
--------------------------------------------
OCL kifejezésekben hogyan kell megfogalmazni a navigációt és a halmazelméleti műveletek végrehajtását? 
--------------------------------------------
Hogyan használható az EMF-IncQuery, illetve Eclipse OCL technológia domain-specifikus modellek validációjára?
--------------------------------------------
Melyek az egyes technológiákban nehezen megfogalmazható és drágán kiértékelhető szabályok? 
--------------------------------------------

Architekturális modellezés: AADL, AUTOSAR (2013-tól)
====================================================

Miért van szükség architektúra leíró nyelvekre?
--------------------------------------------
Soroljon fel néhány példát!
--------------------------------------------
Milyen módszerrel tervezhetjük meg a rendszer architektúráját az egyes komponensek megvalósítása nélkül? 
--------------------------------------------
Mi az AADL? 
--------------------------------------------
Milyen szakterületeken használható? Ismertesse az AADL alapvető tulajdonságait! 
--------------------------------------------
Milyen módon csoportosíthatók az AADL nyelvi elemei? 
--------------------------------------------
Soroljon fel néhány nyelvi elemet? 
--------------------------------------------
Hogyan kapcsolódik az AADL az UML-hez? 
--------------------------------------------
Mi az AUTOSAR? 
--------------------------------------------
Milyen szakterületeken használható? 
--------------------------------------------
Ismertesse az AUTOSAR alapvető tulajdonságait!
--------------------------------------------	
Ismertesse röviden az AUTOSAR által javasolt tervezési folyamatot! 
--------------------------------------------
Mit jelent egy komponens az AUTOSAR-ban és hogyan kommunikálnak a komponensek? 
--------------------------------------------
Mi az EAST-ADL? 
--------------------------------------------
Miben különbözik más architektúra leíró nyelvektől (AADL, AUTOSAR, UML, SysML)?
--------------------------------------------
Milyen szinteket definiál az EAST-ADL?
--------------------------------------------

Domain-specifikus modellezési nyelvek
=====================================

Mi szükséges egy modellezési nyelv definiálásához?
--------------------------------------------
Mit értünk absztrakt szintaxis alatt?
--------------------------------------------
Mi a konkrét szintaxis?
--------------------------------------------
Miért van rá szükség?
--------------------------------------------
Mit értünk jólformáltsági kényszer alatt?
--------------------------------------------
Mik a legtipikusabb (sok nyelvben előforduló) kényszerek?
--------------------------------------------
Hogyan lehet egy nem tipikus (nyelvspecifikus) kénszert kifejezni (példával)?
--------------------------------------------
Értelmezhető-e példányosítási ill. finomítási viszony éltípusok (asszociációk, relációk) között?
--------------------------------------------
Mi következik ebből a végpontokra nézve?
--------------------------------------------
Mik az absztrakt szintaxis és konkrét jelölésrendszer közötti viszony multiplicitása?
--------------------------------------------
Miért? 
--------------------------------------------
Mik az absztrakt modell és egy rögzített jelölésrendszer szerinti konkrét megjelenése közötti viszony multiplicitása? 
--------------------------------------------
Miért? 
--------------------------------------------
Milyen kétféle módon adható meg egy viselkedésmodellezési nyelv dinamikus szemantikája? 
--------------------------------------------
Melyik hogy működik?
--------------------------------------------
Mutassa be (szabadon választva) a MOF vagy az EMF modellezés metaszintjeit! 
--------------------------------------------
Illusztrálja egy egyszerű Jedi-adatbázis (név, mester-padawan viszony) példán keresztül!
--------------------------------------------
Mit nevezünk többszintű (multi-level) metamodellezésnek?
--------------------------------------------
Mire való, mi az előnye? 
--------------------------------------------
Milyen formalizmust ismer, ami képes erre?
--------------------------------------------

Parser (elemző), AST, DOM
=========================

Hogyan épül fel az Absztrakt Szintaxis Fa?
--------------------------------------------
Mi a különbség az AST és a DOM között?
--------------------------------------------
Mire használható az AST és a DOM a szoftverfejlesztés során? 
--------------------------------------------
Hogyan változott a fordítók szerepe a modern fejlesztési környezetekben és milyen új funkcionalitást nyújtanak? Miért van szükség a prediktív elemzőkre? Ismertesse röviden a prediktív elemzők működését!
--------------------------------------------

​Eclipse Modeling Framework
==========================

Ismertesse a legalapvetőbb Ecore struktúrákat, azaz az Ecore metamodelljét!
--------------------------------------------
Írjon egy egyszerű metamodellt egy személygépjárműhöz.
--------------------------------------------
Ismertesse az EMF fejlesztési workflowt, kitérve, hogy egyes pontokabn milyen elemek jönnek létre (file-ok, modellek, forrás kód, stb.)
--------------------------------------------
Milyen különböző módokon lehet ecore modellt létrehozni?
--------------------------------------------
Ismertesse a genmodelt, mire használják és milyen jellegű attribútumokat lehet vele beállítani? 
--------------------------------------------
Milyen projektek generálhatóak genmodelból és ezek mire szolgálnak?
--------------------------------------------
Ismertesse a generált EMF.model-t.
--------------------------------------------
Térjen ki a generált Java kódban alkalmazott modelltárolási megoldásokra.
--------------------------------------------
Egy egyszerű példán keresztül ismertesse a generált Java osztályok és Interfészek kapcsolatát.
--------------------------------------------
Mire szolgálnak a különböző generált EFactory-k?
--------------------------------------------
Milyen módon lehet reflektiven modelleket módosítani és lekérdezni?
--------------------------------------------
EMF esetén mi tekinthető absztrakt szintaxisnak és mi konkrétnak?
--------------------------------------------

ORM és JPA
==========

Mi az ORM célja, bemenete, kimenete? 
--------------------------------------------
Ismertesse röviden az ORM folyamatát! 
--------------------------------------------
Milyen változatok vannak az öröklődés leképezésére ORM esetén?
--------------------------------------------
Mely öröklődés leképezési módokat támogatja a JPA? 
--------------------------------------------
Milyen módon lehet leképezni a különböző multiplicitású kapcsolatokat ORM segítségével? 
--------------------------------------------
Mi a JPA? 
--------------------------------------------
Milyen feladatai vannak egy JPA szolgáltatónak (provider)? 
--------------------------------------------
Ismertesse a JPA alkalmazásának módját! 
--------------------------------------------
Mutassa be és hasonlítsa össze a JPA betöltési stratégiákat! 
--------------------------------------------
Hogyan lehet JPA lekérdezéseket definiálni? 
--------------------------------------------
Milyen módon lehet konkurenciát kezelni JPA-ban? 
--------------------------------------------
Milyen felelőssége van az Entity Manager-nek? 
--------------------------------------------
Ismertesse az entitások életciklusát! 
--------------------------------------------

Kódgenerálás
============

Ismertesse a 3 legelterjedtebb kódgenerálási megközelítést. 
--------------------------------------------
Mik az erősségeik és gyengeségeik? 
--------------------------------------------
Mi az AST? 
--------------------------------------------
Miért fontos a kódgenerálás körében és milyen előnyöket/hátrányokat hoz be a használata. 
--------------------------------------------
Mik a generátor modell használatának előnyei és hátrányai?
--------------------------------------------
Ismertessen legalább 3, a kódgenerálás körében ismert problémát és adjon rájuk megoldási ötleteket.
--------------------------------------------
Milyen szabályok alapján származtathatók egy PSM szintű osztálydiagramból egy modern webalkalmazás interfészei és implementációs osztályai? 
--------------------------------------------
Milyen funkcionalitás támogatásáig lehet eljutni kódgenerálásban (pl. EMF)?
--------------------------------------------
Definiálja a refactoring és a reverse engineering fogalmát! 
--------------------------------------------
A házi feladat fejlesztése során milyen refactoring lépésekkel találkozhatott?
--------------------------------------------

Modelltranszformációk, gráftranszformációk
==========================================

Ismertesse azon területeket, ahol a modelltranszformáció jól hasznosítható! 
--------------------------------------------
Adjon példát egy konkrét transzformációs nyelvre! 
--------------------------------------------
Rajzolja fel és ismetesse egy általános modelltranszformációs keretrendszer felépítését! 
--------------------------------------------
Sorolja fel az ismert modelltranszformációs megközelítéseket! 
--------------------------------------------
Miben különböznek és miben hasonlítanak?
--------------------------------------------
Ismertesse a gráftranszformáció alapjait! 
--------------------------------------------
Írjon fel egy egyszerű szabályt és mutassa be, hogyan alkalmazható egy modellen!
--------------------------------------------
Ismertesse a gráftranszformációs formalizmus kiterjesztésének lehetőségeit!
--------------------------------------------
Ezek közül adjon példát legalább egyre. 
--------------------------------------------
Ismertesse a gráftranszformációs rendszereket (GTS)!
--------------------------------------------
Milyen rendszereket lehet ezzel a módszerrel leírni?
--------------------------------------------
Ismertesse a három legelterjedtebb gráfmintaillesztési (graph pattern matching) stratégiát! 
--------------------------------------------
Miben különböznek és miben hasonlítanak? 
--------------------------------------------
Hogyan használhatóak a modell-lekérdezések modellalapú fejlesztőeszközökben? 
--------------------------------------------
Milyen gyakori funkciók támogatására használható? 
--------------------------------------------
Mondjon pár példát modell-lekérdezés-kiértékelő technológiákra! 
--------------------------------------------
Miben hasonlítanak és különböznek?
--------------------------------------------
