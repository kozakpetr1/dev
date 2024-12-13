### Zadání: One-page web s kurzy měn

#### Popis úkolu
Vytvořte **jednostránkovou webovou aplikaci** (one-page web), která bude na klientské straně pravidelně aktualizovat kurzy měn. Data o kurzech budou načítána z JSON souboru dostupného pomocí návodu na stránce [Kurzy.cz](https://www.kurzy.cz/html-kody/json/kurzy-bank.htm). Úlohu implementujte s použitím JavaScriptu nebo jiného vhodného jazyka na straně klienta.

#### Požadavky
1. **Načítání dat z JSON souboru**:
   - Data načtěte pomocí vhodné metody (např. Fetch API).
   - Kurzy měn musí být aktualizovány pravidelně, minimálně jednou za 60 sekund.

2. **Zobrazení dat**:
   - Na stránce zobrazte přehled aktuálních kurzů měn v tabulce nebo jiném vhodném formátu.
   - U každé měny zobrazte název měny, kurz a případně další relevantní informace obsažené v JSON souboru.

3. **Uživatelské rozhraní**:
   - Webová aplikace by měla být přehledná a vizuálně příjemná.
   - Doporučuje se použít jednoduché styly (CSS), ale jejich propracovanost ponechávám na vás.

4. **Pravidelná aktualizace**:
   - Zajistěte automatickou aktualizaci dat bez potřeby obnovení stránky.

5. **Rozšiřující funkce (nepovinné)**:
   - Možnost filtrování měn podle zadaného kritéria (např. zobrazení pouze vybraných měn).
   - Grafické znázornění kurzů (např. pomocí knihovny Chart.js).

#### Způsob odevzdání
1. Vytvořte projekt obsahující následující soubory:
   - **HTML soubor** pro strukturu stránky,
   - **JavaScript (nebo jiný) soubor** pro načítání dat a jejich aktualizaci,
   - **CSS soubor** (nebo vložené styly) pro formátování stránky.

2. Odevzdejte odkaz na svůj projekt v repu na GitHubu.

#### Hodnocení
- **Správnost načítání dat z JSON souboru**.
- **Pravidelnost aktualizace kurzů**.
- **Přehlednost a funkčnost uživatelského rozhraní**.
- **Kreativita a rozšiřující funkce (nepovinné)**.
