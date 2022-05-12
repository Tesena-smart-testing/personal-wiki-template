 Osobní a teseňácká wikipedie

Ahoj Teseňáku. 

Tohle je **nový domov** pro všechny tvoje *osobní* i *sdílené* poznámky. Pokud se na tohle díváš na GitHubu, nainstaluj si prosím Wiki s Obsidianem dle tohoto návodu: [[Tesena-wiki/README]].


> [!tldr] TL;DR
> Dále v textu najdeš základní informace a návody pro orientaci ve wikipedii.
> Můžeš v ní **hledat**, **doplňovat** informace a **zakládat nová témata** tak, jak se je budeš učit například v rámci Tesena Fridays. Jen když se do ní zapojí co nejvíce Teseňáků, knowledge base nám poroste a bude čím dál tím víc užitečná. 

## Jak je teseňácká wiki vymyšlená?
Už po otevření Obsidianu sis jistě v levé horní části všiml, že je rozdělená na dvě hlavní sekce (složky), a to **Personal** a **Tesena-wiki**. Tyto složky jsou připravené tak, abys mohl pro poznámky využívat jak osobní prostor Personal, do kterého ti nikdo nevidí, tak společnou znalostní databázi Tesena-wiki, která je sdílená se všemi ostatními Teseňáky.

> [!FAQ]- Nevidíš levý panel s průzkumníkem souborů? Klikni na mě. :)
> - V horní části levé lišty je šipka >, kterou panel vysuneš, pro zasunutí se změní na <.  
> - V levém panelu jsou defaultně dvě hlavní funkce: Průzkumník souborů a Vyhledávání, přepínat je lze poklikem.
> ![[navod_wiki02.png]]

### Základní rozdělení poznámek
![[navod_wiki01.png]] 

Složka **Personal** (1), celý její obsah (a i soubory a složky mimo základní složky Personal a Tesena-wiki) totiž bydlí jen na tvém GitHub účtu. Cokoliv do ní uložíš se s nikým nesdílí (pokud to sám neumožníš v repozitáři) a můžeš ji použít na cokoliv - osobní poznámky, denní záznamy, drafty, ...

Složka **Tesena-wiki** (2) se stahuje z GitHub účtu Teseny, odkud si jej může prohlížet každý, kdo tam má přístup. Cílem je sdílet si tam know-how z toho, co jsme se naučili během Tesena Fridays, na projektech, kurzech, ale můžeme si tam sdílet i tipy na zajímavé zdroje, zkušenosti s testovacími nástroji a podobně.

> [!INFO] Tento návod je součástí tvé osobní části wiki a tím pádem si do něj můžeš psát poznámky, zkoušet si na něm Markdown (dál v textu je návod) a podobně. Je to hlavní rozdíl proti souborům v Tesena-wiki, kde se jakákoliv tvoje úprava zobrazí všem Teseňákům.

#### Rozdělení teseňácké wiki
![[navod_wiki03.png]]
Ve wikipedii jsou 4 složky - rozcestníky, poznámky, soubory a šablony. 
- Poznámky (Notes) jsou jasné, jsou to jednotlivé textové (markdownové) soubory, které se věnují vždy konkrétnímu tématu (SQL, Playwright, Git). 
- Rozcestníky jsou také textové soubory, ale jsou v nich odkazy (wikilinky, viz dále) na další relevantní poznámky (v rozcestníku Test automatizace jsou odkazy na Playwright, Cypress a další). 
- Soubory (Files) obsahují všechny přílohy - obrázky, PDF, apod. Obsidian je tam ukládá automaticky, dá se upravit v nastavení. 
- Šablony (Templates) jsou textové soubory připravené jako šablony pro další poznámky. V kapitole o používání Markdownu je vysvětleno, jak se používají. 

Nezakládej prosím v Tesena-wiki další složky a poznámky mimo dané složky. Všechna nová témata patří do Poznámek (Notes), nový rozcestník (větší téma, když vznikne více podtémat) do Rozcestníků. 

## Jak se používá Obsidian?
Obsidian je poznámkový blok na steroidech. Zvládne jednoduše editovat jednoduché textové soubory (markdown, ne texťáky), ale tyto soubory pak umí také propojovat na základě různých funkcí - odkazů, zpětných odkazů, grafu. Ze souborů umí vytvořit i databázi poznámek, ve které se dá vyhledávat podobně jako s SQL, ale o tom až radši příště, protože se jedná o pokročilé funkce. :)

### Základní orientace v programu
Jak už jsme si ukázali dříve, Obsidian má levý panel s průzkumníkem souborů a vyhledáváním. Otevírá se z levé lišty tlačítkem >. To se po otevření změní na tlačítko < pro skrytí panelu. Na levé liště jsou další tlačítka - tři ve spodní části jsou neměnná, poskytují přístup k nastavení, nápovědě a přepínání mezi trezory/vault. 

> [!TIP] V nápovědě si můžeš také otevřít sandboxový trezor (vault), ve kterém si můžeš zkoušet jak Obsidian funguje, aniž by ses musel bát o něčí poznámky. 

V programu je také pravý panel, otevírá a skrývá se obdobně jako ten levý. Používá se obvykle pro různé pluginy. Můžeš v něm mít kalendář s odkazy na denní záznamy, zpětné odkazy (backlinky), seznam používaných tagů a mnoho dalšího. Můžeš si tam ale zobrazovat i karty s poznámkami, které potřebuješ mít častěji po ruce, rozcestník a podobně.

### Proč zrovna Markdown a co to vlastně je?
[[Markdown]] je jednoduchý značkovací jazyk, který nám umožňuje rychle formátovat text. Soubor v markdown formátu vypadá jako obyčejný texťák, jen má příponu `.md`. Protože je tenhle soubor uložený ve složce Personal, tudíž se nesdílí ostatním, můžeš si to hned sám vyzkoušet na tomhle návodu. 

Základní strukturu textu nám umožňují nadpisy, které se značí mřížkou a je až 6 úrovní. Zkus si na následujícím volném řádku (řádek totiž musí začínat tou mřížkou) napsat nadpis 2. úrovně - stačí ti pro mřížka, mezera a text nadpisu: # nadpis. 


Kdybys mezi mřížku a nadpis nedal mezeru, vznikl by tag. Tagem si můžeš označit celé poznámky a nebo segmenty textu a lze jej pak snadno vyhledávat a filtrovat. 

Text lze formátovat **tučně** nebo *kurzívou* pomocí hvězdiček - pro kurzívu text uzavřeš mezi dvě hvězdičky: `*kurzíva*`, pro tučný text jsou hvězdičky zdvojené `**tučně**`. Fungují také obvyklé klávesové zkratky Ctrl+B pro tučný a Ctrl+I pro kurzívu. 

Důležitým prvkem wikipedie jsou propojení - linky. V Obsidianu můžeme propojit poznámky pomocí tzv. wikilinků, kdy je text odkazu zabalen do zdvojených hranatých závorek: `[[link]]`. Jakmile napíšeš dvě otevírací hranaté závorky `[[`, Obsidian začne v modálním okně nabízet již existující poznámky. Zkus si to na následujícím řádku pro stránku s dalšími informacemi o Markdownu, která už je napsaná ve složce "02 - Notes", stejného odkazu sis mohl všimnout hned na začátku této kapitoly. Pokud chceš, můžeš na něj kliknout se stisknutým Ctrl (to jej otevře na nové kartě), pokud jej rozklikneš na této kartě, k tomuhle návodu se vrátíš šipkou <- v levém horním rohu Obsidianu.

Pozn. pokud máš v Obsidianu zapnuté Live Preview/Živý náhled (vlevo dole ozubené kolečko Nastavení->Režim úprav->Obecné->Defaultní režim pro editování), což doporučuji (je to součást nastavení šablony), Markdown formátování se zobrazuje dvojím způsobem - pokud máš zakliknutý kurzor v editovaném textu (v tučném textu, kolem linku, v nadpisu), zobrazují se formátovací značky. Pokud přesuneš kurzor jinam, formátování se rovnou promítne a text s hvězdičkami se rovnou zobrazuje tak, jak je naformátovaný. Zkus si to na následujících řádcích přesouváním kurzoru:

-- *Vzorový text* pro ukázku **živého náhledu**, který Obsidian umožňuje. Díky němu jsou odkazy, třeba na [[Markdown]] klikatelné hned, jak se skryjí závorky. --

## Šablony pro poznámky
Pro naše zápisky jsme se rozhodli používat dvě základní šablony, aby měly všechny poznámky alespoň trochu jednotný vzhled, i když samotný obsah poznámky pak už je na tvém uvážení. Jsou uloženy ve složce Tesena-wiki/04 - Templates. Použít je můžeš dvěma způsoby:
- První je přes paletu příkazů. Tu vyvoláš klávesovou zkratkou Ctrl + P a psaním najdeš příkaz "Templater: Open Insert Template modal". Po jeho výběru se otevře nové modální okno s nabídkou šablon ve složce. 
- V defaultním nastavení je pro šablony také připravená klávesová zkratka Alt + E, která tě dostane rovnou na výběr připravených šablon. 

Připraveny jsou dvě šablony:
- *Základní poznámka_basic note* - používá se pro všechny poznámky, které patří do složky 02 - Notes. Všechna nová témata, o kterých chceš sepsat informace, patří na tuto šablonu. Základní pravidlem pro psaní poznámek do společné wiki, je psát je tak, aby byly srozumitelné a jasné i někomu, kdo poznámku sám nepsal.  
> [!example]- Jak vypadá šablona poznámky:
> ![[navod_wiki_sablona1.png]]
- *Rozcestník* - používá se pro rozcestníky a je na něm navržena základní struktura poznámky. Základním cílem rozcestníku je usnadnit orientaci. Mělo by se tedy ideálně jednat jen o sadu odkazů logicky rozdělených do kategorií pokud je potřeba. 
> [!example]- Jak vypadá šablona rozcestníku:
> ![[navod_wiki_sablona2.png]]

Šablony lze používat díky pluginu Templater, který nejen použije připravený text do nové poznámky, ale také umí zpracovávat jednoduché části kódu pro šablony, to znamená, že umí doplnit např. aktuální čas, název souboru, přesunout kurzor někam do textu (místo aby byl na konci) a mnoho dalších i komplikovanějších věcí. Kód vypadá například takhle <%tp.file.title%>, což je segment pro doplnění názvu souboru, ve kterém šablonu používám. S tímto si, teseňáku, nemusíš dělat starosti, uvádím to jen na vědomí. Občas se totiž stane, že při načítání šablony chviličku trvá, než si plugin šablonu převede tak, jak má a tento text se na obrazovce může objevit. Stačí chvilku počkat.
> [!bug] Pokud se kód nepřevádí, zkontroluj si, že needituješ přímo šablonu. Pokud ne, může být problém v pluginu nebo šabloně a v tom případě kontaktuj správce wiki.

## Kde se dozvíš víc?
Zaujalo tě to a chceš se s Obsidianem naučit lépe? Psát si chytré poznámky tak, aby ti byly dlouhodobě užitečné? Můžeš mrknout na tahle videa:

- Linking Your Thinking má pár geniálně jednoduchých videí, která se zaměřují vyloženě na Obsidian a propojování poznámek - začni [zde](https://www.youtube.com/watch?v=QgbLb6QCK88&list=PL3NaIVgSlAVLHty1-NuvPa9V0b0UwbzBd) (celkem necelá 1h videí)
- The Productive Engineer má půlhodinové vide na úvod do psaní poznámek v Obsidianu, najdeš ho [zde](https://www.youtube.com/watch?v=47hOfPGsrqk)
- Bryan Jenks natočil hodinu a půl dlouhý kurz Markdownu přímo v kontextu Obsidianu, podívat se můžeš [tady](https://www.youtube.com/watch?v=FEa2diI2qgA)

Všechny tři youtube kanály se Obsidianu věnují i nad rámec těchto odkazů. 

V poslední době je populární pojem chytré poznámky, a to díky knize Sonke Ahrense How to take smart notes (vyšlo i česky u Melvila), kde se dozvíte, čím se tahle wiki snaží inspirovat. 

A kdo by si o tom chtěl jen pokecat a třeba si nasdílet zkušenosti, neváhejte napsat na Teamsech Janě Neufusové. Budu se těšit. :)