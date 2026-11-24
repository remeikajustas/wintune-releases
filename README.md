# WinTune

Portable Windows 10/11 maintenance tool: system info, processes, cleanup, disk analysis,
duplicates, startup apps, programs, tweaks, driver and app updates, Windows repair tools,
and a "Changes" page to revert settings it changed.

This repository only hosts the release builds. The source code is private.

**Download:** [latest release](https://github.com/remeikajustas/wintune-releases/releases/latest) → `WinTune.exe`

---

## LT: kaip pasileisti

1. Parsisiųskite `WinTune.exe` iš [naujausio leidimo](https://github.com/remeikajustas/wintune-releases/releases/latest).
   Diegti nereikia: tai vienas failas su viskuo, ko reikia (.NET įdėtas).
2. Paleiskite. Windows paklaus administratoriaus teisių: jų reikia valymui, paslaugoms ir atnaujinimams.
3. Jei pasirodo mėlynas langas „Windows apsaugojo jūsų kompiuterį“, spauskite
   **Daugiau informacijos → Vis tiek paleisti**. Programa nepasirašyta sertifikatu, todėl SmartScreen jos dar „nepažįsta“.

### Bandomasis režimas

Pirmą kartą programa paleidžiama **bandomuoju režimu**: viršuje matosi geltona juosta, o mygtukai tik
parodo, ką būtų padarę, ir kompiuteryje nieko nekeičia. Taip galima ramiai viską apžiūrėti.

Kai norite, kad veiksmai vyktų iš tikrųjų, spauskite **„Išjungti bandomąjį režimą“** geltonoje juostoje
(arba ženklelį viršuje, arba skiltyje „Nustatymai“). Vėl įjungti galima bet kada skiltyje „Nustatymai“.

### Ką verta žinoti

- Prieš pirmą optimizavimą automatiškai sukuriamas sistemos atkūrimo taškas.
- Pakeistus nustatymus, paleisties programas, paslaugas ir DNS galima grąžinti skiltyje **„Pakeitimai“**.
- Ištrintų failų ir pašalintų programų grąžinti negalima. Skiltys „Disko analizė“ ir „Dublikatai“ failus perkelia į šiukšlinę.
- Šalia `WinTune.exe` atsiranda aplankas `WinTune_data` (nustatymai, žurnalas, pradinės reikšmės grąžinimui).
  Jo netrinkite, jei norite turėti galimybę grąžinti pakeitimus.
- Kalba (LT/EN) ir tema (šviesi/tamsi) keičiamos skiltyje „Nustatymai“. **F1** arba **?** viršuje parodo puslapio pagalbą.

## EN: getting started

1. Download `WinTune.exe` from the [latest release](https://github.com/remeikajustas/wintune-releases/releases/latest). No install needed.
2. Run it and accept the administrator prompt.
3. If Windows SmartScreen says "Windows protected your PC", click **More info → Run anyway** (the exe is not code-signed).

The app starts in **dry run**: a yellow bar is shown at the top and buttons only show what they would do.
Click **Turn off dry run** in that bar when you want actions to really run. You can turn it back on in Settings.

Settings it changes can be reverted on the **Changes** page; a restore point is created before the first optimization.
Deleted files and removed programs cannot be brought back.

## Requirements

Windows 10 or 11, 64-bit (x64).

## Disclaimer

Provided as is, without warranty. You use it at your own risk.
