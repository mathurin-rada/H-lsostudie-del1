# 📊 Hälsostudie – Dataanalysprojekt

Detta projekt analyserar hälsodata med fokus på kön, vikt, ålder och andra faktorer. Målet är att visualisera mönster, jämföra grupper och testa hypoteser.

---

## 🚀 Kom igång – steg för steg

1. **Klona projektet**
   ```bash
   git clone https://github.com/ditt-repo/halsostudie.git
   cd halsostudie

2. **Skapa och aktivera virtuell miljö**
    python -m venv .venv
    .\.venv\Scripts\activate

3. **Intallera bibliotek**
    pip install pandas matplotlib seaborn jupyter

4. **Starta Jupyer Notebook**
    kör på terminal/powershell "jupyter notebook"

5. **Öppna filerna i ordning**
    - 1_data.ipynb – Ladda och utforska data
    - 2_statistik.ipynb – Beskrivande statistik
    - 3_group_annalysis.ipynb – Gruppjämförelser
    - 4_visualization.ipynb – Grafer och diagram
    - 5_simulation.ipynb – Simuleringar
    - 6_test.ipynb – Hypostestester


## 📁 Filstruktur

| Filnamn                  | Syfte                                                                 |
|--------------------------|-----------------------------------------------------------------------|
| `1_data.ipynb`           | Laddar in datasetet och visar grundläggande översikt av datan         |
| `2_statistik.ipynb`      | Beräknar medel, median, min, max för viktiga variabler                |
| `3_group_analysis.ipynb` | Jämför grupper (t.ex. kön, rökare) med hjälp av groupby och statistik |
| `4_visualization.ipynb`  | Skapar grafer som histogram, boxplot och stapeldiagram                |
| `5_simulation.ipynb`     | Simulerar sjukdomsförekomst med numpy och jämför med verklig data     |
| `6_test.ipynb`           | Hypotesprövning (t.ex. t-test mellan rökare och icke-rökare)          |
| `Del1.ipynb`             | Allt-i-ett notebook – innehåller hela Del 1 i ett körbart flöde       |
| `health_study_dataset.csv` | Dataset med hälsodata från studien                                 |
| `.venv/`                 | Virtuell miljö med installerade Python-paket                         |
| `.gitignore`             | Ignorerar `.venv` och andra filer i Git                              |
| `README.md`              | Projektbeskrivning och instruktioner                                 |



✅ Krav
- Python 3.10+
- Jupyter Notebook
- Pandas, Matplotlib, Seaborn

