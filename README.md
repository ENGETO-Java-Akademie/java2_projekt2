## Java 2 - 2. projekt

Podobně jako v javě 1 budeme pracovat s daňovými sazbami, ale tentokrát nebudeme data získávat přímo ze souboru, ale zde: https://euvatrates.com/rates.json a nepůjde o parsování obyčejného textového souboru, ale data budou ve formátu JSON.

Úkolem bude data načíst, rozparsovat, uložit, vyhledat 3 země s nejvyššími sazbami a 3 země s nejnižšími sazbami a vypsat je.

Postupně:
1. Zavolat API pomocí HTTP
2. Načíst JSON soubor
3. Naparsovat JSON soubor do objektu
4. Implementovat vyhledávací logiku
5. Vypsat hodnoty pomocí interaktivní příkazové řádky
6. Umožnit zapsat výsledek do souboru

BONUS: Následně pak také implementovat vyhledávání daňových sazeb podle zkratek zemí, které bude uživatel zadávat do konzole.
