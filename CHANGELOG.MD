# Changelog


## [1.4.1] (2025/03/31)


## Novinky
* Implementace managementu souborů
* Implementace profilových obrázků - viditelné v různých sektorech. Každý uživatel si může změnit svůj profilový obrázek.
* Implementace uploadu souboru - Drag and Drop + manualní výběr
* Download alert - Upozornění o stahování souboru
* Nabídky - Zakázky nyní mají své unikátní nabídky, které lze vytvářet, upravovat a rušit
* Nabídky - Přidán přehled všech nabídek
* Objednávky - Zakázky nyní mají své unikátní objednávky, které lze vytvářet, upravovat a rušit
* Objednávky - Přidán přehled všech objednávek
* Implementace základních daňových kalkulací

## Změny
* Rework Log Out tlačítka 
* Rework seznamů - Nyní lze otevřít detaily jednotlivých itemů pouhým dvojklikem - viditelné v Zakázkách, Zákazních, Zaměstnancích a dalších sektorech
* Přehled zakázky - přechod na modulární ukládání. Zakázka se ve většině případů ukládá okamžitě
* Přehled zakázky - přechod na modulární loading. Zakázka načte pouze momentálně otevřené sektory. Tato funkce zmenší nároky na server i klientské zařízení.

## Opraveno
* Opraven Přehled kontaktů - Kontakty lze přidávat, upravovat a mazat (Legacy feature)
* Opraveno přidávání nových zákazníků
* Opraven Přehled Instalace v Přehledu zakázky



## [1.4.0] (2024/12/23)


## Novinky
* Kompletní rework přehledu zakázek - Implementace historie, evidence, zadání zakázky a další...
* Přidán Admin Hub - Správa aplikace, defaultních nastaveních a další...
* Správce novinek - Nyní nabízí možnosti skrytí novinky a taky archivaci.
* Přechod na NAS server
* Aplikace nyní umí pracovat s dokumenty - další možnosti budou přidány v dalším releasu
* Implementace serverového času - Zatím ve fázi testovaní kvůli přechodům na zimní-letní čas - time.windows.com
* Implementace JSON modulu - Newtonsoft JSON
* Implementace API modulu - Rest Sharp
* Implementace iText7 modulu - Možnost generování PDF dokumentů
* Implementace MySQL modulu - V souvislosti s přechodem na NAS
* Bezpečnostní update - Obfuskace kódu, zabezpečení přihlašovacích tokenů skrz webové servery
* Implementace testovacícho rozhraní - pouze pro testery

## Změny
* Zakázka > Výroba - kompletní rework sekcí (Legacy feature)
* "Správa novinek" přejmenována na "Správce novinek" (Legacy feature)
* Admin news v Dashboardu teď čerpají data z GitHub stránky (Legacy feature)
* Přechod na selektivní úrovně přístupu - momentálně ve fázi testování
* Status zakázky "Zrušeno" je momentálně protected - nelze přejmenovat, ani smazat (Legacy feature)
* Přehled zakázky - Kontakt je teď viditelný pro celou zakázku (Legacy feature)

## Opraveno
* Opraveny problémy s prvním přihlášením

## Code
* Oprava async funkcí
* Rozdělení kódu na moduly, konstruktory a konektory - více v pracovní dokumentaci



## [v1.3.1] (2024/01/19)


## Novinky
* Menu obsahuje tlačítko "Support", které slouží k reportování chyby v programu. Tickety jsou pak veřejně viditelné na GitHub stránce.
* Přidáno vícevrstvé menu - menu koresponduje s úrovní přístupu
* Přidáno Refresh tlačítko do zakázek
* Přidána komunikace formou chatu pro jednotlivé zakázky
* Přidáno přižazování zaměstnanců k zakázkám
* Přidány kategorie do zakázek - Evidence, Nabídka, Objednávka, Výroba (Grafika, Tisk, Dílna), Předání a Fakturace
* Do sekcí výroby lze přidávat, editovat a mazat zadání práce
* Přidáno zamykání aplikace při pokusech o BruteForce
* GitHub - vytvořena složka Downloads obsahující .zip balíčky s verzí aplikace pro jednotlivé společnosti.
* Přidán stažitelný balíček pro Traxart s.r.o.

## Změny
* Novinky v Dashboard jsou teď spravovány adminy a uživateli s vyšší třídou přístupu přímo v aplikaci (Legacy feature)
* Redesign přehledu zakázky (Legacy feature)
* Redesign barev - odstraněna většina AliceBlue

## Opraveno
* Opravena tlačítka zpět
* Opraveno ukládání zakázky

## Code
* Zdokumentováno vrstvení aplikace
* Zdokumentováno komentování kódu



## [v1.3.0] (2023/11/17)


## Novinky
* Přidán systém updatů a notifikací o updatech
* Do balíčku byl přidán Updater.exe
* Možnost auto-updatu - Program se updatuje na nejnovější verzi
* Zakázky lze nyní zrušit
* Přidán solution pro Traxart s.r.o.

## Změny
* Zrušen changelog.txt na GitHub - nadbytečný
* Přidáno version.txt na GitHub - kontrola verze programu
* Revize infrastruktury GitHub repositáře - odstraněno runtime, přidány solutions



## [v1.2.3] (2023/10/31)


## Novinky
* Vytvořeny changelogy
* Vytvořeno README.MD
* Napojení na GitHub (Octokit)
* Kontrola verze
* Implementace [Sémantického verzování](https://semver.org/) s přídavkem revizního čísla.

## Změny
* Nová infrastruktura složek
