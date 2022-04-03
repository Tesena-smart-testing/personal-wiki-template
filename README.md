# personal-wiki

Tohle je **nový domov** pro všechny tvoje *osobní* i *sdílené* poznámky.

1. [Použij GitHub šablonu](https://github.com/jan-beranek/personal-wiki/generate) a vytvoř si z ní svůj vlastní centrální repozitář pro poznámky.

Všechny sdílené poznámky z jiných repozitářů si sem pak přidávej jako git submoduly.
- Tesena-wiki už je tu pro tebe připravena :-)

## Synchronizace
2. Pokud si svůj nový repozitář **naklonuješ** do počítače s přepínači `--recurse-submodules --remote-submodules` a vlezeš dovnitř pomocí `cd`
	- například takto:
	```
	git clone --recursive git@github.com:jan-beranek/personal-wiki.git
	cd personal-wiki
	```
	- popřípadě v běžně naklonovaném repozitáři dodatečně stáhneš submoduly:
		`git submodule update --init --recursive --remote`
3. přepneš u submodulů, aby trackovaly branch:
	```
	git submodule foreach "git checkout main"
	```
4. a **otevřeš** ho v aplikaci Obsidian, 
    - pak se předkonfigurovaný Obsidian Git plug-in postará o automatickou synchronizaci v obou směrech a to včetně vnořených submodulů.
    - (Takže naučit se pracovat s Gitem můžeš opět odložit na jindy... a nebo tu může být hned teď první užitečná věc, kterou v Tesena-wiki také najdeš.)
5. **Hotovo**? Fakt? Jo!
   - Tak bež něco dělat a piš si u toho poznámky :-)