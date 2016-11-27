# Zvolené řešení
Zvážením výše zmíněných možností jsem dospěl k závěru, že při implementaci aplikace využiji programovací jazyk Swift. Přehlednost a bezpečnost tohoto jazyka stavím z hlediska důležitosti před částečnou znovuvyužitelnost na jiné platdormě (React Native) ale i před vysokou dynamičnost a sílu jazyka Objective-C. Jsem přesvědčen, že popularita tohoto jazyka dále poroste díky aktivnímu vývoji. V tomto názoru mě utvrzují komerční společnosti, které postupem času své aplikace přepisují právě do Swiftu.

# Aktuální stav řešení
Aktuálně mám pro aplikaci připravené testovací rozhraní. Pomocí virtualizačního nástroje Docker a aplikace OctoPrint simuluji chování tiskárny. Ve své práci jsem naimplementoval většinu dostupného API OctoPrintu. Komunikaci s API propojuji do větších logických celků. Pomocí aplikace je nyní možné přihlásit se k tiskárně a získat informace o jejím stavu.
