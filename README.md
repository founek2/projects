# Projects

## Web3 buy token page

Garbage token website on Polygon network.

Technologies:

- React
- Web3
- Material UI

[Demo](https://garbage.projects.iotdomu.cz/)

## Product page Alfasilver

Product page for medical product.

Technologies:

- Sass
- Gulp
- pug-i18n

[Demo](https://alfasilver.projects.iotdomu.cz/)

[Repository](https://github.com/founek2/Alfasilver/tree/main)

## Webserver written in C++

Single threaded Webserver with support for virtual hosts.

Technologies:

- Pure C++

[Repository](https://github.com/founek2/cpp-web-server)

## Three.js exercise

This was created in order to try out Three.js library. It is jumping game with generated path.

[Demo](http://threejs.projects.iotdomu.cz)

[Repository](https://github.com/founek2/threejs-jumping-game)

## Skyline filtering

Cílem projektu je vytvoření aplikace umožňující doporučovat uživateli produkty nad zvolenou databází produktů. Uživatel bude s aplikací interagovat pomocí webového rozhraní, ve kterém si zvolí dvojici atributů, na základě kterých aplikace nalezne zajímavé produkty. U každého atributu půjde zvolit, jestli je pro uživatele důležitější nižší nebo vyšší hodnota. Následně aplikace pomocí operátoru skyline nalezne produkty, které dominují ostatní v dané dvojici atributů.

Výstup bude realizován jako 2D graf, kde budou jednotlivé produkty reprezentovány jako body a výsledná skyline jako křivka spojující jednotlivé produkty, které dominují ostatní ve zvolených atributech. Ostatní body budou pod nebo nad skyline křivkou, podle toho, kde na osách leží optimum.

Technologies:

- React SPA application
  - Material UI
- Python desktop application
  - Qt

[Demo](https://skyline.projects.iotdomu.cz/)

[Paper](./_media/skyline.pdf)

[Repository](https://github.com/founek2/school-projects/tree/master/bi-wvm)

## Metadata ordering

Cílem projektu je vytvoření aplikace umožňující vylepšené vyhledávání ve fotografiích uložených na serveru Flickr. Flickr poskytuje aplikační rozhraní umožňující získat prakticky libovolná data o fotografiích, která jsou přístupna i z oficiálního webového rozhraní. Cílem projektu je tedy aplikace, která umožní vyhledávání na serveru Flickr založené na klíčových slovech, stejně jako je tomu na serveru Flickr nyní, ale navíc bude možné zadat výsledky přeřadit podle různých metadat.

Implemented as React SPA application.

[Demo](https://metadata.projects.iotdomu.cz/)

[Paper](./_media/metadata.pdf)

[Repository](https://github.com/founek2/school-projects/tree/master/ni-vmm)

## MongoDB vs InflusDB performance

Ve své bakalářské práci s tématem IoT Platforma s webovým rozhraním jsem využil MongoDB jako hlavní databázi pro ukládání všech dat a to včetně dat získávaných z IoT zařízení. Jedná se o poměrně velké množství, které roste lineárně s přidáváním dalších zařízení - každé zařízení pošle přibližně 600 zpráv každý den a platforma by měla zvládnout obsloužit stovky až tisíce zařízení. Od prvopočátku jsem počítal s jistými výkonostními limity při využití MongoDB na tento typ dat a již při návrhu jsem řešil jisté optimalizace, abych tento dopad minimalizoval.

V nedávné době jsem ukládání dat z IoT zařízení přesunul na databázi InfluxDB, který by měla být pro tento typ dat mnohem vhodnější a v rámci této práce provedu analýzu nad reálným výkonostním dopadem této změny.

[Paper](./_media/mongo_vs_influx.pdf)

[Repository](https://github.com/founek2/school-projects/tree/master/NI-PDB)

## ⭐ IoT Platform ⭐

Projekt vznikl ve volném času za účelem vytvořit alternativní IOT platformu pro co největší množství zařízení. Platforma má moderní webové rozhraní s uživatelskými účty, automatickou detekci nových zařízení a jejich správu včetně implementovaných oprávnění.

Technologies:

- Frontend:
  - React
  - Redux
  - mui
  - Plotify.js
- Backend
  - NodeJS
  - AgendaJS
  - MongoDB
  - InfluxDB
  - RabbitMQ
  - NodeRed

[Running instance](https://ng.iotdomu.cz)

[Repository](https://github.com/founek2/IOT-Platform)

### Arduino library

[Repository](https://github.com/founek2/IOT-Platform-arduino)

### Integrations and bots

[Repository](https://github.com/founek2/IOT-Platform-integration)

## Python curriculum

Curriculum for basic Python programming, which I have been teaching in Education section of biggesst student club in Czech Republic called Sillicon Hill.

[Curriculum](https://python.iotdomu.cz/)

## Services portal

Simple web portal for use, when you have multiple running services (websites) and you are unable to remember them all.

[Demo](https://sluzby.iotdomu.cz/)

[Repository](https://github.com/founek2/services-portal)

## Elm & React interop

I wanted to play with React & Elm interoperability to find out how well it can integrate in order to get experience about possibility to slowly migrate existing React project into Elm.

Technologies:

- React
- Elm
- Webpack

[Demo](https://elm.projects.iotdomu.cz/)

[Repository](https://github.com/founek2/school-projects/tree/master/NI-AFP/ni-afp-project)

## Intranet frontend

On high school we had very ugly intranet, so we decided to create ower own frontend for it. I do not have working credentials for it, but there is fancy panda on logic page create in pure css (try to fill login form and observe Panda)

Technologies:

- React
- Sass
- Webpack

[Demo](https://panda.projects.iotdomu.cz/)

[Repository](https://github.com/founek2/-antiMcBlack-)
