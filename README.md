# Kritik reklam

Balík pravidel, který z ChatGPT nebo Claude udělá přísného kritika reklam a kampaní. Od PLACEMENT.cz.

V reelu stačí jedno nastavení. Tady je celek: krátký text do nastavení a skill, který reklamu projde celý.

AI vám řekne, co na reklamě nefunguje. Když nemá data, napíše, že neví. Čísla si nevymýšlí. V účtu se nic nezmění, dokud to neschválíte.

## Co v balíku je

- `chatgpt-claude-pokyny.txt`, text do nastavení ChatGPT i Claude. Má 704 znaků. Vejde se do limitu ChatGPT: 1 500 znaků u tarifů Free a Go, 5 000 znaků u tarifů Plus, Pro, Business, Enterprise a Education. U Claude oficiální limit znaků u osobních instrukcí zveřejněný není, tento text je krátký a lze ho vložit stejně.
- `kritik-reklam/SKILL.md`, skill pro hodnocení reklamy. Projde háček, nabídku, důkaz, námitky, výzvu k akci, soulad se stránkou, rizika pravidel Google, Skliku a Mety, délku, češtinu a text v obrázku. Vrátí verdikt, tři největší problémy a jednu opravenou verzi.
- `kritik-reklam.zip`, stejný skill zabalený k nahrání do Claude.
- `LICENSE`, licence MIT.

## Stažení

Celá složka jako ZIP (až bude repo veřejné):

https://github.com/placementppc/kritik-reklam/archive/refs/heads/main.zip

Na stránce repozitáře to samé uděláte přes Code a pak Download ZIP:

https://github.com/placementppc/kritik-reklam

## 1. Text do nastavení

Vložte obsah souboru `chatgpt-claude-pokyny.txt`.

ChatGPT, počítač: Nastavení, Personalizace, zapněte přizpůsobení a vložte text do pole Vlastní pokyny (v anglické verzi Settings, Personalization, Custom Instructions). Uložte.

ChatGPT, telefon: Nastavení, Přizpůsobit ChatGPT, stejné pole.

Claude: klikněte na iniciály vlevo dole, Nastavení, Váš Claude (v starší verzi Účet) a vložte text do pole Instrukce (dříve také Instrukce pro Claude). V anglické verzi je to Settings, Your Claude, Instructions. Názvy v češtině se můžou podle verze lišit, rozhoduje pole s instrukcemi, které platí pro všechny rozhovory.

Text vložte jednou. Platí pro další rozhovory. Když už v tom poli máte jiné pokyny, přidejte tyhle za ně a zkontrolujte, že se do limitu stále vejdete.

## 2. Jak nahrát skill do Claude

Skill je navíc k nastavení. Použijte ho, když chcete reklamu projít celým kontrolním seznamem.

Nejdřív v Claude zapněte tvorbu souborů. U tarifů Free, Pro, Max a Ultra: Nastavení, Funkce (Capabilities) a zapněte položku Spouštění kódu a tvorba souborů, v novějším rozložení může být jako Vytvářet a upravovat soubory. Bez toho skill nepůjde použít.

Pak:

1. Stáhněte z tohoto repozitáře soubor `kritik-reklam.zip`. Když skládáte ZIP sami, zabalte celou složku `kritik-reklam`, ne jen soubor uvnitř. V archivu musí být cesta `kritik-reklam/SKILL.md`.
2. V Claude otevřete Přizpůsobit a Skills (Customize, Skills).
3. Klepněte na plus, Vytvořit skill, Nahrát skill (Upload a skill).
4. Vyberte `kritik-reklam.zip`.
5. Skill v seznamu zapněte.

Ověření: v novém rozhovoru napište „Zhodnoť tuhle reklamu jako přísný kritik“ a vložte text reklamy. V přemýšlení Claude by mělo být vidět, že skill načetl. Když ho nenačte, skill v seznamu znovu zapněte a zadání zopakujte.

Skill funguje na tarifech Free, Pro, Max, Ultra, Team i Enterprise, pokud je zapnutá tvorba souborů. Na firemním tarifu může nahrávání skillů vypnout správce.

Když nemůžete skill nahrát, otevřete v Claude projekt, přiložte soubor `kritik-reklam/SKILL.md` a napište: Řiď se souborem SKILL.md a zhodnoť tuhle reklamu.

## 3. ChatGPT bez skillu

ChatGPT nemá stejné nahrávání skillů jako Claude. Vložte proto text z `chatgpt-claude-pokyny.txt` do vlastních pokynů. Když chcete celý kontrolní seznam, přiložte do projektu nebo do chatu soubor `kritik-reklam/SKILL.md` a napište: Řiď se souborem SKILL.md a zhodnoť tuhle reklamu.

## Než začnete

- Čísla a výsledky si skill ani pokyny nevymýšlejí. Když chcete hodnotit výkon, musíte dodat skutečná data.
- Posudek k pravidlům Google, Skliku a Mety je upozornění na rizika, ne právní rada a ne rozhodnutí schvalování.
- Pravidla inzerce se mění. Ověřujte je v oficiální nápovědě.

## Poradna zdarma

Když budete chtít probrat svoje reklamy s člověkem, jste zvaní do Poradny zdarma:

https://vzdelavani.placement.cz/poradna

## Autor

Jakub Herrmann, PLACEMENT.cz

https://www.linkedin.com/in/jakubherrmann/

Licence MIT. Verze 1, 25. 11. 2026.
