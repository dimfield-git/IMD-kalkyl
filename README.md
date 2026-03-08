# IMD-kalkyl

🔗 **Öppna verktyget:**
https://dimfield-git.github.io/IMD-kalkyl/

---

## Om verktyget

**IMD-kalkyl** är ett webbaserat analysverktyg för att snabbt uppskatta den ekonomiska effekten av att införa **Individuell Mätning och Debitering (IMD) av el** i flerbostadshus.

Verktyget riktar sig främst till:

* bostadsrättsföreningar
* energikonsulter
* fastighetsförvaltare
* tekniska rådgivare

Kalkylen visar hur fastighetens elkostnader förändras när **individuella lägenhetsabonnemang ersätts av central elinköp via IMD**.

---

## Funktioner

Verktyget beräknar:

* totala utgifter **före IMD**
* totala utgifter **efter IMD**
* **årlig besparing**
* **återbetalningstid**
* **besparing över 10 år**
* **internränta över 10 år**

Resultaten visualiseras även med grafer:

* stapeldiagram över utgifter före/efter IMD
* graf över ackumulerad besparing

---

## Exportfunktioner

Följande delar kan exporteras direkt som **PNG**:

* resultatbar
* ekonomisk kalkyl (indata + utfall)
* stapeldiagram
* graf över ackumulerad besparing

Det gör det enkelt att använda resultaten i:

* styrelseunderlag
* energirapporter
* investeringskalkyler
* presentationer

---

## Prisprofiler

Kalkylen innehåller tariffprofiler för:

* Göteborg Energi
* Mölndal Energi
* Kungälv Energi
* Sverigemedel

Användaren kan även välja **Egna priser**.

Prisuppgifterna är baserade på offentliga tariffuppgifter från respektive nätbolag.

**Senaste uppdatering av prisdata:**
2026

Alla priser anges **inklusive moms**.

---

## Kalkylmodell

### Före IMD

Antaganden:

* varje lägenhet har eget elnätsabonnemang
* varje lägenhet har eget elhandelsabonnemang
* fastigheten har abonnemang för fastighetsel

### Efter IMD

Antaganden:

* lägenhetsabonnemang tas bort
* föreningen köper el centralt
* boende debiteras endast för **inköpskostnaden för elenergi**

Tillkommande kostnader:

* effektkostnader
* mättjänstavtal
* avisering

---

## Standardvärden

Standardantaganden i kalkylen:

| Parameter   | Värde                    |
| ----------- | ------------------------ |
| Lägenhetsel | 2500 kWh / lägenhet / år |
| Kalkylränta | 5 %                      |

Alla värden kan ändras av användaren.

---

## Teknisk information

Verktyget är byggt som:

* **en enda statisk HTML-fil**
* all beräkning sker **lokalt i webbläsaren**
* ingen data skickas till server

Fördelar:

* fungerar offline
* enkelt att distribuera
* inga beroenden

---

## Användning

1. Ange fastighetens grunddata
2. Välj tariffprofil eller egna priser
3. Ange investeringskostnad
4. Klicka **Beräkna kalkyl**

Resultaten visas direkt.

---

## Mål

Projektets mål är att skapa ett **enkelt och transparent beslutsstöd** för IMD-investeringar i flerbostadshus.

---

## Licens

Detta projekt distribueras under:

**GPL-3.0**

Se `LICENSE.md` för fullständig licenstext.
