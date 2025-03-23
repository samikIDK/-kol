# Storage

Tento program slouží k správě produktů ve skladu, kde lze přidávat produkty, vyhledávat je, upravovat a provádět různé výpočty (celková cena, průměrná cena, nejlevnější a nejdražší produkt).

## Funkce 
Po spuštění programu se zobrazí menu s možnostmi (1–9).
Vyberete číslo odpovídající požadované akci a postupujete podle instrukcí.
```python
Vítej ve skladu
###############

1. Výpis položek
2. Přidání položky
3. Hlédání produktu
4. Celková cena všech produktů
5. Nejlevnější produkt
6. Nejdražší produkt
7. Průměrná cena
8. Úprava produktů
Zadej 9 pokud chceš odejít ze skladu

Volba: 
``` 

### 1. Výpis položek
První funkce `print_products()` prochází seznam produktů a pro každý produkt vypíše jeho název a cenu ve formátu:

### 2. Přidání položky
Druhá funkce `add_product()` umožňuje přidat nový produkt se zadaným názvem a cenou, přičemž cena musí být číslo; jinak se požaduje opětovné zadání.

### 3. Hlédání produktu
Třetí funkce `search_product()` umožňuje uživateli hledat produkty podle názvu nebo ceny. Když uživatel zadá `A` nebo `a` je to jedno, tak se mu vypíšou všechny produkty, které mají v sobě písmeno `A`.V tomto případě to bude `Auto` a `Škoda`.

### 4.-7. Funkce
Funkce `sum_price()` sečte všechny ceny produktů a zobrazí celkovou cenu. 

Funkce `min_product_price()` najde a vypíše nejlevnější produkt,
stejně jako `max_product_price()`, která najde a vypíše nejdražší produkt.

Funkce `average_price()` vypočítá průměrnou cenu produktů a zobrazí ji.

### 8. Úprava produktů
Funkce `edit_product()` umožňuje upravit název a cenu produktu podle zadaného čísla. 
Pokud je číslo neplatné, zobrazí se chybová zpráva.

### 9. Vypnutí programu
Když by jste zadali číslo 9 tak by se program ukončil stejne jako když zadáte jakékoliv větší číslo které je větší jak 9.

## Výpomoc
1. Kamarád
2. Google
3. ChatGPT

### Autor

Tento projekt byl vytvořen by Samuel Samohýl.






