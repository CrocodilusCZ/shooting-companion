# Zásady ochrany soukromí pro Shooting Companion Lite

**Datum účinnosti:** [Sem vložte aktuální datum, např. 21. května 2025]

Vítejte v aplikaci Shooting Companion Lite (dále jen "Aplikace"). Tyto zásady ochrany soukromí vysvětlují, jaké informace shromažďujeme, jak je používáme a chráníme. Vývojářem aplikace je [Sem vložte Vaše Jméno / Název Firmy] (dále jen "my", "nás" nebo "naše").

## 1. Informace, které shromažďujeme a jak je používáme

Aplikace vyžaduje určitá oprávnění k poskytování svých funkcí. Níže je uveden přehled:

*   **Přístup k fotoaparátu (`android.permission.CAMERA`):**
    *   **Účel:** Umožňuje vám pořizovat fotografie vašich terčů přímo v aplikaci za účelem jejich následné analýzy.
    *   **Zpracování:** Pořízené obrázky jsou zpracovávány lokálně na vašem zařízení.

*   **Přístup k úložišti/médiím (`android.permission.READ_EXTERNAL_STORAGE` / `android.permission.READ_MEDIA_IMAGES`):**
    *   **Účel:** Umožňuje vám vybírat existující obrázky terčů z galerie vašeho zařízení pro analýzu v aplikaci.
    *   **Zpracování:** Vybrané obrázky jsou zpracovávány lokálně na vašem zařízení.

*   **Přístup k internetu (`android.permission.INTERNET`):**
    *   **Účel:** [**SPECIFIKUJTE PROSÍM PŘESNÝ ÚČEL, POKUD JE INTERNET AKTIVNĚ VYUŽÍVÁN.** Například: "Internetové připojení může být využito pro budoucí funkce, jako je kontrola aktualizací aplikace nebo anonymní hlášení chyb pro zlepšení stability. V současné verzi aplikace není aktivně využíváno pro přenos uživatelských dat." Pokud internet vůbec nepoužíváte pro žádné funkce, zvažte jeho odstranění z manifestu, pokud to pluginy nevyžadují.]
    *   **Zpracování:** [Podle specifikovaného účelu]

*   **Přístup k poloze (`android.permission.ACCESS_FINE_LOCATION`, `android.permission.ACCESS_COARSE_LOCATION`):**
    *   **Účel:** [**SPECIFIKUJTE PROSÍM PŘESNÝ ÚČEL, POKUD JE POLOHA AKTIVNĚ VYUŽÍVÁNA.** Například: "Údaje o poloze mohou být využity pro označení místa střelby u uložených analýz, pokud tuto funkci povolíte. V současné verzi aplikace není tato funkce implementována / není poloha aktivně využívána." Pokud polohu vůbec nepoužíváte, zvažte její odstranění z manifestu.]
    *   **Zpracování:** [Podle specifikovaného účelu]

*   **Data analýzy a historie:**
    *   **Účel:** Aplikace ukládá výsledky analýzy terčů (např. pozice zásahů, statistiky, názvy relací, data) a případně i samotné obrázky terčů (pokud je tak nakonfigurováno) pro vaši osobní evidenci a historii.
    *   **Zpracování:** Všechna tato data jsou ukládána výhradně lokálně v privátním úložišti aplikace na vašem zařízení.

## 2. Sdílení informací

Vaše osobní údaje a data z analýzy (včetně obrázků) **nejsou automaticky sdíleny s žádnými třetími stranami**. Veškeré zpracování probíhá lokálně na vašem zařízení.

Pokud se rozhodnete využít funkci sdílení výsledků (pokud je v aplikaci implementována), budete k tomu využívat standardní systémové funkce sdílení vašeho operačního systému a data budou sdílena pouze s aplikacemi a službami, které si sami vyberete.

## 3. Bezpečnost dat

Přijímáme přiměřená opatření k ochraně informací uložených v aplikaci na vašem zařízení. Uvědomte si však, že žádná metoda přenosu nebo ukládání dat není 100% bezpečná. Data jsou uložena v privátním úložišti aplikace, ke kterému by jiné aplikace neměly mít přístup bez root oprávnění zařízení.

## 4. Uchovávání dat

Data (obrázky terčů, výsledky analýz) jsou uchovávána na vašem zařízení, dokud je sami nesmažete prostřednictvím funkcí aplikace (pokud jsou k dispozici) nebo dokud neodinstalujete aplikaci, což by mělo vést ke smazání jejího privátního úložiště.

## 5. Vaše práva

Máte právo na přístup k vašim datům uloženým v aplikaci a na jejich smazání. To lze obvykle provést prostřednictvím funkcí aplikace nebo smazáním dat aplikace v nastavení vašeho zařízení.

## 6. Změny těchto zásad ochrany soukromí

Tyto zásady ochrany soukromí můžeme čas od času aktualizovat. O jakýchkoli změnách vás budeme informovat zveřejněním nových zásad ochrany soukromí v rámci aplikace nebo na našich webových stránkách. Doporučujeme vám pravidelně kontrolovat tyto zásady.

## 7. Kontaktujte nás

Máte-li jakékoli dotazy týkající se těchto zásad ochrany soukromí, kontaktujte nás na adrese:
[Sem vložte Vaši kontaktní e-mailovou adresu]

---

**Další kroky:**
1.  **Doplňte chybějící informace:** Zejména účely použití internetu a polohy (nebo je z manifestu odstraňte, pokud je nepotřebujete a žádný plugin je nevyžaduje).
2.  **Zveřejněte:** Nahrajte tento text (ideálně jako HTML stránku nebo PDF) na veřejně dostupnou URL (např. GitHub Pages, Google Sites, váš web).
3.  **Vložte URL do Play Console:** V Google Play Console přejděte do sekce "Obsah aplikace" (nebo podobně nazvané) a tam do části "Zásady ochrany soukromí" vložte odkaz na vaše zveřejněné zásady.

Pamatujte, že oprávnění pro polohu (`ACCESS_FINE_LOCATION`, `ACCESS_COARSE_LOCATION`) a internet (`INTERNET`) jsou v manifestu deklarována. Pokud je vaše aplikace aktivně nevyužívá, je dobré zvážit jejich odstranění, aby se snížil počet oprávnění, která musíte zdůvodňovat uživatelům a v zásadách. Pokud je však vyžaduje některý z použitých Flutter pluginů, budete je muset ponechat a vysvětlit jejich potenciální použití.# Zásady ochrany soukromí pro Shooting Companion Lite

**Datum účinnosti:** [Sem vložte aktuální datum, např. 21. května 2025]

Vítejte v aplikaci Shooting Companion Lite (dále jen "Aplikace"). Tyto zásady ochrany soukromí vysvětlují, jaké informace shromažďujeme, jak je používáme a chráníme. Vývojářem aplikace je Aleš Kozubík (dále jen "my", "nás" nebo "naše").

## 1. Informace, které shromažďujeme a jak je používáme

Aplikace vyžaduje určitá oprávnění k poskytování svých funkcí. Níže je uveden přehled:

*   **Přístup k fotoaparátu (`android.permission.CAMERA`):**
    *   **Účel:** Umožňuje vám pořizovat fotografie vašich terčů přímo v aplikaci za účelem jejich následné analýzy.
    *   **Zpracování:** Pořízené obrázky jsou zpracovávány lokálně na vašem zařízení.

*   **Přístup k úložišti/médiím (`android.permission.READ_EXTERNAL_STORAGE` / `android.permission.READ_MEDIA_IMAGES`):**
    *   **Účel:** Umožňuje vám vybírat existující obrázky terčů z galerie vašeho zařízení pro analýzu v aplikaci.
    *   **Zpracování:** Vybrané obrázky jsou zpracovávány lokálně na vašem zařízení.

*   **Přístup k internetu (`android.permission.INTERNET`):**
    *   **Účel:** Aplikace využívá internetové připojení k načtení aktuálních údajů o počasí (např. teplota, vlhkost, rychlost a směr větru) z externí služby (OpenWeatherMap API) pro vaši aktuální polohu. Tyto údaje mohou být použity k automatickému předvyplnění informací při zakládání nové střelecké relace, což vám usnadní záznam relevantních podmínek.
    *   **Zpracování:** Při vyžádání údajů o počasí jsou na server služby OpenWeatherMap odeslány pouze nezbytné geolokační údaje (zeměpisná šířka a délka) pro získání relevantní předpovědi. Žádné jiné osobní údaje nejsou s touto službou sdíleny. Načtené údaje o počasí jsou následně použity pouze v rámci aplikace pro zobrazení a případné uložení k vaší střelecké relaci.

*   **Přístup k poloze (`android.permission.ACCESS_FINE_LOCATION`, `android.permission.ACCESS_COARSE_LOCATION`):**
    *   **Účel:** Aplikace vyžaduje přístup k údajům o poloze vašeho zařízení, aby mohla automaticky zjistit vaši aktuální polohu. Tato poloha je následně použita k získání relevantních údajů o počasí z externí služby (OpenWeatherMap API) a k jejich případnému předvyplnění při zakládání nové střelecké relace. Údaje o poloze mohou být také uloženy spolu s vaší střeleckou relací pro vaši osobní evidenci místa střelby, pokud se tak rozhodnete.
    *   **Zpracování:** Údaje o poloze jsou získávány pouze s vaším souhlasem. Jsou použity k odeslání dotazu na službu OpenWeatherMap pro získání dat o počasí a mohou být uloženy lokálně na vašem zařízení jako součást záznamu o střelecké relaci. Údaje o poloze nejsou sdíleny s žádnými jinými třetími stranami kromě služby OpenWeatherMap za účelem získání počasí.

*   **Data analýzy a historie:**
    *   **Účel:** Aplikace ukládá výsledky analýzy terčů (např. pozice zásahů, statistiky, názvy relací, data) a případně i samotné obrázky terčů (pokud je tak nakonfigurováno) pro vaši osobní evidenci a historii.
    *   **Zpracování:** Všechna tato data jsou ukládána výhradně lokálně v privátním úložišti aplikace na vašem zařízení.

## 2. Sdílení informací

Vaše osobní údaje a data z analýzy (včetně obrázků) **nejsou automaticky sdíleny s žádnými třetími stranami**. Veškeré zpracování probíhá lokálně na vašem zařízení.

Pokud se rozhodnete využít funkci sdílení výsledků (pokud je v aplikaci implementována), budete k tomu využívat standardní systémové funkce sdílení vašeho operačního systému a data budou sdílena pouze s aplikacemi a službami, které si sami vyberete.

## 3. Bezpečnost dat

Přijímáme přiměřená opatření k ochraně informací uložených v aplikaci na vašem zařízení. Uvědomte si však, že žádná metoda přenosu nebo ukládání dat není 100% bezpečná. Data jsou uložena v privátním úložišti aplikace, ke kterému by jiné aplikace neměly mít přístup bez root oprávnění zařízení.

## 4. Uchovávání dat

Data (obrázky terčů, výsledky analýz) jsou uchovávána na vašem zařízení, dokud je sami nesmažete prostřednictvím funkcí aplikace (pokud jsou k dispozici) nebo dokud neodinstalujete aplikaci, což by mělo vést ke smazání jejího privátního úložiště.

## 5. Vaše práva

Máte právo na přístup k vašim datům uloženým v aplikaci a na jejich smazání. To lze obvykle provést prostřednictvím funkcí aplikace nebo smazáním dat aplikace v nastavení vašeho zařízení.

## 6. Změny těchto zásad ochrany soukromí

Tyto zásady ochrany soukromí můžeme čas od času aktualizovat. O jakýchkoli změnách vás budeme informovat zveřejněním nových zásad ochrany soukromí v rámci aplikace nebo na našich webových stránkách. Doporučujeme vám pravidelně kontrolovat tyto zásady.

## 7. Kontaktujte nás

Máte-li jakékoli dotazy týkající se těchto zásad ochrany soukromí, kontaktujte nás na adrese:
shooting.app.dev@gmail.com

---
