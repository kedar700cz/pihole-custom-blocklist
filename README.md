# 🛡️ Kedar700cz Ultimate DNS Blocklist

An automatically updated, aggregated DNS blocklist designed to block ads, tracking, and telemetry. Built primarily for **Pi-hole**, but fully compatible with AdGuard Home and other DNS sinkholes.

## 🌟 Overview

This blocklist combines highly reliable community lists with my own automated telemetry and ad-scraping tool.

Whenever my custom analyzer discovers a sufficient amount of new tracking or ad domains, the repository automatically triggers an update. It merges the new findings with the upstream sources, removes all duplicates, and publishes a fresh, clean list.

## 🚀 How to use (Pi-hole)

To add this list to your Pi-hole setup:

1. Log in to your Pi-hole Web Interface.
2. Navigate to **Adlists** in the left sidebar.
3. Paste the following RAW URL into the **Address** field:
   `https://raw.githubusercontent.com/kedar700cz/pihole-custom-blocklist/main/blocklist.txt`
4. Click **Add**.
5. Go to **Tools > Update Gravity** and click the **Update** button.

## 🧬 Sources & Credits

This project is built upon excellent community foundations. Huge thanks to the following authors for their base lists:

* **Hagezi:** Pro DNS Blocklist
* **r0xd4n3t:** Base Adblock List
* **Kedar700cz Custom Scraper:** My personal, automated telemetry and ad-domain hunting engine.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

# 🇨🇿 Kedar700cz Ultimátní DNS Blocklist

Automaticky aktualizovaný, agregovaný DNS blocklist navržený k blokování reklam, sledování a telemetrie. Vytvořeno primárně pro **Pi-hole**, ale plně kompatibilní i s AdGuard Home a dalšími DNS blokátory.

## 🌟 O projektu

Tento blocklist spojuje vysoce spolehlivé komunitní seznamy s mým vlastním automatickým analyzátorem a sběračem telemetrie a reklam.

Jakmile můj vlastní nástroj objeví dostatečné množství nových domén, tento repozitář automaticky spustí aktualizaci. Sloučí nové objevy s externími zdroji, pečlivě odstraní duplicity a vypublikuje čerstvý, čistý seznam.

## 🚀 Jak list přidat (Pi-hole)

Pro přidání tohoto seznamu do vašeho Pi-hole:

1. Přihlaste se do webového rozhraní Pi-hole.
2. V levém menu přejděte na záložku **Adlists**.
3. Do pole **Address** vložte následující RAW odkaz:
   `https://raw.githubusercontent.com/kedar700cz/pihole-custom-blocklist/main/blocklist.txt`
4. Klikněte na tlačítko **Add**.
5. Přejděte do **Tools > Update Gravity** a klikněte na tlačítko **Update**.

## 🧬 Zdroje a poděkování

Tento projekt staví na skvělých základech komunity. Obrovské díky patří těmto autorům za jejich listiny:

* **Hagezi:** Pro DNS Blocklist
* **r0xd4n3t:** Základní Adblock List
* **Kedar700cz Custom Scraper:** Můj vlastní automatizovaný nástroj pro lov telemetrických a reklamních domén.

## 📜 Licence

Tento projekt je licencován pod MIT licencí – více detailů najdete v souboru [LICENSE](LICENSE).
