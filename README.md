 # Shweeskey

  > Tohle je **distribuční repozitář** — najdeš tu jen hotové buildy ke stažení.
  > Zdrojový kód je vývojářský a veřejně dostupný není.

  ## 📥 Stažení

  Nejnovější verzi vždy najdeš v sekci **[Releases](../../releases/latest)**, nebo přes
  download stránku hry.

  | Systém | Soubor |
  |--------|--------|
  | **Windows** | `Shweeskey Setup <verze>.exe` |
  | **macOS (Apple Silicon)** | `Shweeskey-<verze>-arm64.dmg` |
  | **macOS (Intel)** | `Shweeskey-<verze>.dmg` |

  ## 💾 Instalace

  ### Windows
  1. Stáhni `.exe` instalátor.
  2. Spusť ho. Windows SmartScreen může varovat („Windows ochránil váš počítač") — klikni
  na **Další informace → Přesto spustit**.
  3. Projdi instalací a hru spusť.

  ### macOS
  Build **není podepsaný Apple certifikátem**, takže ho Gatekeeper napoprvé zablokuje.
  Tohle je normální — postup:

  1. Stáhni správný `.dmg` (Apple Silicon = `arm64`, starší Intel Macy = ten bez `arm64`).
  2. Otevři `.dmg` a přetáhni **Shweeskey** do složky **Aplikace**.
  3. Při prvním spuštění:
     - **klikni pravým tlačítkem** (nebo Ctrl+klik) na ikonu hry → **Otevřít** → v dialogu
  potvrď **Otevřít**,
     - případně jdi do **Nastavení systému → Soukromí a zabezpečení** a dole potvrď
  **Přesto otevřít**.

  Od té chvíle už jde hra spouštět normálně.

  ## 🔄 Automatické aktualizace

  Windows verze se **aktualizuje sama** — při vydání nové verze si ji hra stáhne a nabídne
  instalaci na pozadí. Nemusíš nic dělat.