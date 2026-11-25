# Kritik reklam

Pravidla, která z ChatGPT nebo Claude udělají přísného kritika vašich reklam. Od PLACEMENT.cz.

AI má sklon všechno chválit. S těmito pravidly vám místo chvály řekne, proč by reklama neprodala, dá jednu opravenou verzi a čísla si nevymýšlí. Hodí se na reklamy v Google Ads, Skliku i na Facebooku a Instagramu (Meta), hlavně pro e-shopy a služby.

## Co v balíku je

- `chatgpt-claude-pokyny.txt`: text, který vložíte jednou do nastavení. Funguje v ChatGPT i v Claude, i v bezplatné verzi.
- `kritik-reklam/SKILL.md`: podrobný kontrolní seznam (skill) pro Claude. Reklamu projde bod po bodu.
- `kritik-reklam.zip`: stejný skill zabalený k nahrání do Claude.
- `LICENSE`: licence MIT. Můžete to volně používat i upravovat.

Stažení všeho najednou: na stránce repozitáře klikněte na zelené tlačítko Code a pak Download ZIP. Nebo přímo:

https://github.com/placementppc/kritik-reklam/archive/refs/heads/main.zip

## Jedna věta z videa

Když chcete jen to nejnutnější, vložte do nastavení tuhle větu:

> Když ti dám reklamu, buď přísný kritik: nechval mě, napiš tři největší problémy a jednu opravenou verzi a čísla si nikdy nevymýšlej.

Celý text v souboru `chatgpt-claude-pokyny.txt` dělá totéž důkladněji. Doporučuji vložit celý.

## ChatGPT za 2 minuty

1. Otevřete soubor `chatgpt-claude-pokyny.txt` a zkopírujte celý text.
2. Na počítači: Nastavení, Personalizace. Na telefonu: Nastavení, Přizpůsobit ChatGPT. V anglické verzi Settings, Personalization nebo Customize ChatGPT.
3. Zapněte přizpůsobení (Enable customization).
4. Text vložte do pole Vlastní pokyny (Custom Instructions) a uložte.

Funguje to i v bezplatné verzi ChatGPT. Text se vejde i do nejmenšího limitu, který ChatGPT u vlastních pokynů má. Když už v poli máte jiné pokyny, přidejte tyhle na konec.

Chcete v ChatGPT i podrobný kontrolní seznam? Otevřete soubor `kritik-reklam/SKILL.md`, zkopírujte jeho text do chatu a napište: Řiď se tímto postupem a zhodnoť tuhle reklamu.

## Claude za 2 minuty

1. Zkopírujte celý text ze souboru `chatgpt-claude-pokyny.txt`.
2. V Claude klikněte vlevo dole na svoje iniciály, pak Nastavení a Váš Claude (ve starším rozložení Účet). Anglicky Settings, Your Claude.
3. Text vložte do pole Instrukce (ve starším rozložení Instrukce pro Claude) a uložte.

Instrukce platí pro všechny rozhovory.

## Skill pro Claude, podrobný rozbor

Skill je navíc. Hodí se, když chcete projít reklamu celým kontrolním seznamem.

1. V Claude zapněte v Nastavení, Funkce (Capabilities) položku Spouštění kódu a tvorba souborů. V novějším rozložení se jmenuje Vytvářet a upravovat soubory. Bez ní skill nefunguje.
2. Stáhněte soubor `kritik-reklam.zip`. Nerozbalujte ho.
3. Otevřete Přizpůsobit, Skills (Customize, Skills).
4. Klikněte na plus, Vytvořit skill a Nahrát skill (Upload a skill). Vyberte `kritik-reklam.zip`.
5. Skill v seznamu zapněte.

Vyzkoušení: v novém rozhovoru napište "Zhodnoť tuhle reklamu" a vložte text reklamy, ideálně i odkaz na stránku, kam vede.

Skills fungují na tarifech Free, Pro, Max, Ultra, Team i Enterprise. Ve firmě je může vypnout správce. Když skill nahrát nejde, vytvořte v Claude projekt, vložte text ze `SKILL.md` do instrukcí projektu a reklamy hodnoťte v něm.

## Co dát AI, aby byl rozbor dobrý

- Text reklamy, obrázek nebo video.
- Kde poběží: Google vyhledávání, Sklik, Meta feed, Stories nebo Reels.
- Odkaz nebo text stránky, kam reklama vede.
- Pro koho je: noví lidé, nebo ti, kdo už u vás byli.
- Když máte, skutečná čísla z účtu.

Co nedodáte, AI nedomýšlí. Napíše, že to posoudit nešlo.

## Ukázka před a po

Reklama e-shopu s kávovary na Facebooku:

> Nejlepší kávovary za super ceny! Kvalita, které věříte. Nakupte teď!

Bez pravidel AI často odpoví nějak takto:

> Skvělá, úderná reklama! Text je krátký a výzva k akci jasná. Možná bych přidal emoji, aby víc zaujala.

S pravidly vypadá odpověď takto (zkráceno):

> **Verdikt:** Upravit. Reklama neříká, jaký kávovar prodává, komu a proč koupit právě u vás.
>
> **Tři největší problémy:**
> 1. "Nejlepší" a "super ceny" nic neříkají a nejsou doložené. Člověk je přejede. Napište konkrétní produkt nebo výhodu.
> 2. Chybí důkaz a odpověď na námitky. Neznámému e-shopu lidé nevěří. Doplňte recenze, dopravu nebo vrácení, pokud je opravdu máte.
> 3. "Nakupte teď" bez důvodu. Řekněte, co člověk po kliknutí najde.
>
> **Opravená verze:** Pákové kávovary pro domácí espresso. [doplňte skutečný údaj o dopravě nebo vrácení]. Vyberte si svůj.
>
> **Co ověřit daty:** proklikovost a nákupy proti původní verzi. Jestli lidé po kliknutí neodcházejí hned ze stránky.

Ukázka je ilustrační. Skutečná odpověď se liší podle modelu a podle toho, co AI dáte. Všimněte si, že číslo ani recenzi si nevymyslela. Nechala místo, kam doplníte skutečný údaj.

## Než začnete

- Pokyny ani skill nic nemění ve vašem reklamním účtu. Jen radí.
- Výkon reklamy AI hodnotí jen ze skutečných dat, která jí dáte.
- Upozornění na pravidla Google, Skliku a Mety je jen upozornění na riziko, ne právní rada. Pravidla se mění, ověřujte je v oficiální nápovědě.
- I přísnou AI berte jako druhý názor. Rozhodnutí je vaše.

## Poradna zdarma

Chcete svoje reklamy probrat s člověkem? Jste zvaní do Poradny zdarma:

https://vzdelavani.placement.cz/poradna

Jakub Herrmann, PLACEMENT.cz. Licence MIT. Verze 2, 25. 11. 2026.
