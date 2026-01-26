# PVA4 - Programování a vývoj aplikací

## MaturitniApp - Závěrečná maturitní práce

Tento repozitář slouží jako **pracovní prostor pro praktickou část závěrečné maturitní práce** z předmětu Programování a vývoj aplikací.

## Pravidla práce
- Pracuj **průběžně**, ne jednorázově.
- Commity musí mít **smysluplné zprávy**.
- Praktická část musí odpovídat zadání práce.

## Hodnocení
Hodnocena je **pouze praktická část**:
- funkčnost aplikace
- práce s databází
- struktura kódu
- bezpečnost a ošetření vstupů

# Zadání
Vyplň soubor `zadani.md`

## Funkční požadavky
❌ Aplikace bude pracovat s databází.

✅ Aplikace umožní uživateli vytvořit, upravit a odstranit záznam v databázové tabulce products.

Ukázky ve formě checklistu:
- [ ] Aplikace umožní registraci uživatele pomocí e-mailu a hesla.
- [ ] Nepřihlášený uživatel nemá přístup k chráněným částem aplikace.
- [ ] Aplikace umožní vytvoření nového záznamu v databázové tabulce items.

Vzor
```
# Zadání

## Název práce
**Evidence zakázek pro malou firmu**

---

## Cíl práce
Cílem práce je vytvořit webovou aplikaci, která umožní malé firmě evidovat zakázky, zákazníky a stav jejich zpracování.  
Aplikace je určena pro zaměstnance firmy, kteří potřebují přehledně spravovat zakázky a mít k dispozici aktuální informace o jejich stavu.

---

## Použité technologie
- PHP: PHP 8.x
- Databáze: MySQL / MariaDB
- Další technologie:
  - HTML
  - CSS
  - SQL
  - Apache (XAMPP)

---

## Očekávaný výstup
Výsledkem práce bude **funkční webová aplikace**, která umožní:
- přihlášení uživatele,
- správu zakázek uložených v databázi,
- ukládání a zobrazování dat pomocí PHP a SQL.

---

# Návrh řešení

## Popis aplikace
Aplikace bude fungovat jako jednoduchý interní informační systém.  
Uživatel se po přihlášení dostane do administrace, kde může spravovat zakázky.  
Data budou ukládána do relační databáze a zpracovávána pomocí PHP skriptů.

---

## Funkční požadavky

### Uživatelské účty
- [ ] Aplikace umožní přihlášení uživatele pomocí e-mailu a hesla.
- [ ] Hesla budou v databázi ukládána pomocí hashování.
- [ ] Nepřihlášený uživatel nebude mít přístup k administraci.

### Správa zakázek (CRUD)
- [ ] Uživatel může vytvořit novou zakázku.
- [ ] Uživatel může zobrazit seznam zakázek.
- [ ] Uživatel může upravit existující zakázku.
- [ ] Uživatel může zakázku odstranit.

### Práce s databází
- [ ] Aplikace používá minimálně tři databázové tabulky.
- [ ] Databázové dotazy jsou realizovány pomocí SQL.
- [ ] PHP komunikuje s databází pomocí připravených dotazů.

### Bezpečnost a validace
- [ ] Vstupy od uživatele jsou kontrolovány a validovány.
- [ ] Aplikace je chráněna proti SQL Injection.
- [ ] Aplikace ošetřuje výstupy proti XSS.


```
