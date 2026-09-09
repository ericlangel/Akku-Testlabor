# 📈 Test-Details: GAONENG GNB 3S 11.1V 3500mAh 70C

Hier werden die Serienstreuung fabrikneuer Akkus sowie die individuellen Langzeit-Alterungsprozesse dokumentiert.

---

## ⚙️ Globales Test-Setup & Settings
> [!IMPORTANT]
> Um die Vergleichbarkeit aller Messungen zu garantieren, werden alle Tests mit exakt denselben Parametern durchgeführt.

![Globale Test-Einstellungen](./assets/global_settings.png)

* **Lade-Abschaltspannung:** 4.20 V pro Zelle (12.6 V Gesamt)
* **Entlade-Abschaltspannung:** 3.30 V pro Zelle (9.9 V Gesamt)
* **Messmethode Ri:** DC-Lastpulsverfahren bei vollgeladenem Akku

---

## 👥 1. Serien-Vergleich (Fabrikneue Akkus)
Diese Tabelle vergleicht unterschiedliche Akkus derselben Serie im Neuzustand, um die Fertigungstoleranzen zu ermitteln.

| Akku-ID | Kauf-/Prüfdatum | DC-Ri (Gesamt) | Gemessene Kapazität | Echte C-Rate | Link zum Einzel-Graph |
| :--- | :---: | :---: | :--- | :--- | :--- |
| `GNB3S-01` | 2026-09-09 | **3 mOhm** | *folgt* | *folgt* | [🔍 Graph anzeigen](./assets/GNB3S-01_neu_graph.png) |
| `GNB3S-02` | 2026-09-09 | **3.2 mOhm** | *folgt* | *folgt* | [🔍 Graph anzeigen](./assets/GNB3S-02_neu_graph.png) |
| `GNB3S-03` | 2026-10-12 | *folgt* | *folgt* | *folgt* | *ausstehend* |

### 🖼️ Serien-Overlay (Direktanzeige)
Die Grafik zeigt alle neuen Akkus im direkten Vergleich:
![Overlay Serienvergleich](./assets/serien_vergleich_overlay.png)

---

## ⏳ 2. Langzeit-Verlauf: Akku `GNB3S-01`
Chronologische Dokumentation der Alterung und des Leistungsverlusts von Akku 01.

| Prüfdatum | Alter / Zyklen | DC-Ri (Gesamt) | Gemessene Kapazität | Echte C-Rate | Link zum Einzel-Graph | Zustand / Notiz |
| :--- | :---: | :---: | :--- | :--- | :--- | :--- |
| 2026-09-09 | Neu | **3 mOhm** | *folgt* | *folgt* | [🔍 Graph anzeigen](./assets/GNB3S-01_neu_graph.png) | Erstmessung |
| 2027-03-15 | 6 Mon. / 50 Zyk. | *folgt* | *folgt* | *folgt* | [🔍 Graph anzeigen](./assets/GNB3S-01_6m_graph.png) | *Beispiel* |

### 🖼️ Langzeit-Overlay `GNB3S-01` (Direktanzeige)
Der Alterungsverlauf von Akku 01 über alle Messungen hinweg:
![Overlay GNB3S-01](./assets/GNB3S-01_alterung_overlay.png)

---

## ⏳ 3. Langzeit-Verlauf: Akku `GNB3S-02`
Chronologische Dokumentation der Alterung und des Leistungsverlusts von Akku 02.

| Prüfdatum | Alter / Zyklen | DC-Ri (Gesamt) | Gemessene Kapazität | Echte C-Rate | Link zum Einzel-Graph | Zustand / Notiz |
| :--- | :---: | :---: | :--- | :--- | :--- | :--- |
| 2026-09-09 | Neu | **3.2 mOhm** | *folgt* | *folgt* | [🔍 Graph anzeigen](./assets/GNB3S-02_neu_graph.png) | Erstmessung |

### 🖼️ Langzeit-Overlay `GNB3S-02` (Direktanzeige)
Der Alterungsverlauf von Akku 02 über alle Messungen hinweg:
![Overlay GNB3S-02](./assets/GNB3S-02_alterung_overlay.png)

