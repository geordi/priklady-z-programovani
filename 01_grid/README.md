# Sestavování obrazců v dvourozměrném poli

V této skupině cvičení budete, ve dvourozměrném poli, sestavovat zadaný
geometrický obrazec a po sestavení obrazce toto pole vypíšete na
standardní výstup. Dvourozměrné pole `A`, ve kterém budete sestavovat
zadaný obrazec, bude vždy čtvercové. Jeho velikost bude dána konstantou
`N` a předpokládejte `5 <= N <= 20`. Prvky pole `A`budou typu `bool`.
Geometrický obrazec vznikne nastavením některých prvků tohoto pole na
hodnotu `true`, ostatní prvky pole, které netvoří obrazec, budou nastaveny na
hodnotu `false`. Velikost sestavovaného obrazce bude záviset na velikosti pole
`A`, daného konstantou `N`.

## Poznámky

- Implementovaný program by měl pracovat ve třech krocích:
  1. Nastavení všech prvků pole `A` na hodnotu `false`.
  2.  Sestavení zadaného obrazce v poli `A`.
  3.  Vypsání pole `A` na standardní výstup. Pokud prvek pole `A`má hodnotu `true` na standardní výstup se vypíše znak `*`, v opačném případě se  vypíše jedna mezera ` `.

- Sestavení obrazce musí být plně závislé na hodnotě `N`. Všechny ostatní rozměry obrazce nebo polohy jednotlivých bodů, hvězdiček, v obrazci je nutné odvodit od této hodnoty.

- Hodnota `N` implementujte jako celočíselnou konstantu ve zdrojovém kódu programu. Vypsání obrazce změněné velikosti bude probíhat přepsáním této konstanty ve zdrojovém kódu, kompilací zdrojového kódu a novým spuštěním programu.

- Hodnotu konstanty `N` předpokládejte vždy ve správném rozsahu hodnot.

- Pokud bude potřeba použít operaci dělení, například pro výpočet indexu prostředního sloupce v poli `A`, bude použito vždy celočíselné dělení.

- Každé cvičení si můžete vyzkoušet v několika variantách implementace:

  1.  celá implementace ve funkci `main`,
  2.  jednotlivé kroky implementované jako samostatné funkce - nastavení všech prvků pole `A` na hodnotu `false` ve funkci `Clear`, sestavení obrazce ve funkci `Fill` a vypsání pole ve funkci `Print`; pole `A` je bráno jako globální proměnná, nebo
  3. jednotlivé kroky implementované jako samostatné funkce, ale pole `A` je do funkcí předáváno jako parametr.
