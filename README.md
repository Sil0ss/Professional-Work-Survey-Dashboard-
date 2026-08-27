# 📊 Professional Work Survey Dashboard (Power BI)

## 📌 Project Overview
Proyek ini berisi *dashboard* analitis interaktif yang dibangun menggunakan **Power BI** untuk mengolah dan memvisualisasikan data hasil survei lingkungan kerja profesional. *Dashboard* ini dirancang untuk membantu divisi HR maupun manajemen dalam memahami dinamika tenaga kerja, kepuasan karyawan, dan faktor-faktor pendukung performa kerja.

**🛠️ Tools & Technologies:**
* **Visualisasi & Reporting:** Power BI Desktop
* **Data Transformation:** Power Query (ETL)
* **Calculations & Metrics:** DAX (Data Analysis Expressions)
* **Data Source:** Excel / CSV Dataset

---

## 🖼️ Dashboard Preview
![Dashboard Preview](Dashboard_Preview.jpg)


---

## 💡 Key Business Insights

1. **Faktor Pendorong Kompensasi (Gaji, Peran, & Pendidikan):**
   * **Tingkat Pendidikan:** Pemegang gelar **PhD** mencatatkan rata-rata gaji tertinggi secara signifikan (**$124.7k**), lebih dari 2x lipat dibanding pemegang gelar **Masters ($61.2k)** dan **Bachelors ($49.5k)**.
   * **Spesialisasi Peran:** Peran **Data Scientist** memimpin rata-rata pendapatan tertinggi di antara profesi data, disusul oleh **Data Engineer** dan **Data Architect**.
   * **Disparitas Geografis:** **Amerika Serikat ($78.8k)** dan **Kanada ($67.8k)** menawarkan kompensasi rata-rata tertinggi, sementara **India ($29.9k)** berada di posisi terendah.

2. **Dominasi Bahasa Pemrograman:**
   * **Python** mendominasi secara mutlak sebagai bahasa pemrograman paling favorit (dipilih oleh lebih dari 400 dari 630 responden), jauh melampaui **R** di posisi kedua dan bahasa lainnya seperti C/C++, JavaScript, maupun Java.

3. **Metrik Kepuasan Kerja & Risiko Retensi Karyawan:**
   * **Aspek Positif:** Profesional data merasa paling puas dengan hubungan antar **Rekan Kerja (5.86/10)** dan tingkat **Work-Life Balance (5.74/10)**.
   * **Area Evaluasi Kritis:** Metrik **Gaji (4.27/10)** dan **Peluang Promosi / Upward Mobility (4.76/10)** mendapat skor kepuasan terendah. Hal ini mengindikasikan bahwa persepsi kelayakan kompensasi dan kejelasan jalur karier menjadi isu utama yang berpotensi memicu *turnover* karyawan.

---

## 📁 Repository Structure
```text
├── Dashboard Survey Profesional Work.pbix   # File proyek utama Power BI
├── dashboard_preview.jpg                    # Gambar tangkapan layar dashboard
├── dataset/Survey Professional Work.xlsx    # Folder data mentah (CSV/Excel)
└── README.md                                # Dokumentasi proyek
