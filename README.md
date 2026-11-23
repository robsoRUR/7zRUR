# 7zRUR

Grafický archivátor pre Windows nad **7-Zipom** s **obnovovacími zväzkami 7zrev**: ak sa niektorá časť rozdeleného archívu stratí alebo poškodí, 7zRUR ju vie dopočítať a archív opraviť (podobne ako `.rev` vo WinRARe).

## Stiahnutie

Najnovšiu verziu nájdeš v časti **[Releases](../../releases/latest)**. Stiahni:

- `7zRUR.exe` – program
- `7zrev.exe` – obnovovacie zväzky (musí byť v tom istom priečinku)

Obidva súbory daj do jedného priečinka (napr. `Dokumenty\7zRUR`) a spusti `7zRUR.exe`. Nič sa neinštaluje.

## Požiadavky

- 64-bitové Windows 10 alebo 11
- nainštalovaný [7-Zip](https://www.7-zip.org) – alebo nakopíruj `7z.exe` a `7z.dll` z 7-Zipu do priečinka so 7zRUR (prenosná verzia)

## Aktualizácie

7zRUR raz denne skontroluje, či je k dispozícii nová verzia, a ponúkne jej inštaláciu (dá sa vypnúť v menu **Pomocník**). Každá aktualizácia je **digitálne podpísaná** (ECDSA P-256) a každý súbor overený cez SHA-256 – program nenainštaluje nič, čo nepodpísal autor.

Súbory `update.json` a `update.json.sig` vo vydaniach slúžia práve na tieto automatické aktualizácie.

## Upozornenie Windows SmartScreen

Program nie je podpísaný certifikátom na podpis kódu, preto Windows pri prvom spustení môže zobraziť „Systém Windows ochránil váš počítač“. Klikni na **Ďalšie informácie → Spustiť aj tak**.

Formát 7z a program 7-Zip © Igor Pavlov (www.7-zip.org).
