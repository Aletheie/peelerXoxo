# peelerXoxo

_Skriptík slouží pro vymazávání znaků z názvů souborů v příkazovým řádku._

## Instalace

- Stáhněte si zdrojový kód skriptu z repozitáře.
- Ujistěte se, že máte nainstalovaný Bash.
- Otevřete terminál a přejděte do adresáře, kde se nachází stažený soubor.
- Skript nastavte jako spustitelný příkaz. Použijte následující příkaz:

```
chmod +x peelerXoxo
```

## Použití

```
./peelerXoxo [přepínače]
```

## Přepínače

- -p \<integer>: Vymaže \<integer> znaků z názvu souboru.
- -e \<koncovka>: Zkrátí názvy souborů jen s danou \<koncovka> (výchozí hodnota: \*).
- -w \<string>: Vymaže \<string> z názvu souboru.
- -h: Vypíše nápovědu k použití skriptu.

## Příklady použití

```
./peelerXoxo -p 3
```

Vymaže první tři znaky ze všech názvů souborů ve složce, kde se nachází (kromě sebe).

```
./peelerXoxo -e .txt -p 1 -w xoxo
```

Odebere první znak a string xoxo ze všech .txt názvů souborů ve složce, kde se nachází.

## Poznámky

- Pokud není zadán žádný přepínač, skript vypíše chybovou zprávu a zobrazí nápovědu.
- Skript se ptá uživatele, zda má přepsat každý soubor. Odpověď "y" potvrzuje přepsání souboru.

## TODO

- [ ] přidat --suffix přepínač
- [ ] Udělat README.md víc xoxo
- [ ] Vymyslet víc TODO
