# 🛡️ SOC Architecture & Engineering: Enterprise Edition

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Role](https://img.shields.io/badge/role-SOC%20Analyst-orange.svg)
![Tech](https://img.shields.io/badge/tech-Elastic%20|%20SOAR%20|%20AI-06b6d4.svg)

Repositori ini berisi publikasi resmi E-Book **"SOC Architecture & Engineering: Dari Analisis Log Hingga Respons Otomatis Terintegrasi"** (Edisi Enterprise - 50 Halaman). 

Buku panduan ini merupakan kompilasi cetak biru teknis, metodologi deteksi sistem, dan arsitektur respons insiden yang dirancang khusus untuk membawa operasional *Security Operations Center* (SOC) Anda dari pendekatan reaktif menjadi proaktif dan digerakkan oleh kecerdasan buatan (AI).

---

## 🎯 Target Audiens
Buku dan repositori ini dirancang untuk:
- **L1/L2 SOC Analysts** yang ingin naik level menjadi *Threat Hunters*.
- **Detection Engineers** yang bertugas memangkas *Alert Fatigue* dan *False Positives*.
- **Security Engineers & Architects** yang mengelola SIEM (Elastic/Splunk) dan SOAR.

---

## 📖 Sorotan Materi (Highlights)

Buku ini dibagi menjadi 5 pilar utama operasional SecOps modern:

### Bagian I: Visibilitas, Analitik Log, & Rekayasa Deteksi
- Arsitektur ELK Stack & Standarisasi *Elastic Common Schema* (ECS).
- Taktik *Threat Hunting* menggunakan **KQL** (Kibana Query Language) & **EQL** (Event Query Language).
- *The Detection Blueprint*: Manajemen *noise*, *Thresholding*, *Shadow Mode*, dan *Suppression Windows*.

### Bagian II: Orkestrasi Taktis, Perimeter, & Respons Cloud
- Membangun *Playbook* Karantina Malware otomatis di SOAR.
- Automasi API menggunakan Python untuk interaksi dengan EDR (CrowdStrike/SentinelOne).
- Cloud Incident Response: Membedah log AWS CloudTrail & Otomatisasi Karantina IAM.

### Bagian III: Proaktif, Emulasi Ancaman, & SecOps Tooling
- Metodologi *Purple Teaming* menggunakan **Atomic Red Team**.
- Membangun antarmuka triase mandiri (*Custom Triage UI*) menggunakan HTML, JavaScript (RegEx), dan Tailwind CSS.
- Pemetaan dan Visualisasi *MITRE ATT&CK Heatmap*.

### Bagian IV: Kecerdasan Buatan (AI), LLMs, & Otomatisasi Lanjutan
- Membangun asisten AI SOC lokal tanpa membocorkan data (Privasi).
- Arsitektur **RAG (Retrieval-Augmented Generation)** untuk menyuntikkan *Playbook* ke dalam AI.
- *System Prompt Engineering* & *LoRA Fine-Tuning* khusus untuk ekstraksi JSON log.

### Bagian V: Studi Kasus Forensik
- **Kasus 1:** Deteksi 0-detik dan isolasi *Conti Ransomware* menggunakan EQL & SOAR.
- **Kasus 2:** Pelacakan *Insider Threat* (Eksfiltrasi Data) menggunakan korelasi Anomali ML dan Network Flow.

---

## 💻 Tech Stack & Konsep yang Dibahas
- **SIEM / Data Analytics:** Elasticsearch, Logstash, Kibana, KQL, EQL, Machine Learning (Anomaly Detection).
- **SOAR & Scripting:** Python 3, REST API Integration, JSON.
- **Frontend Tooling:** HTML5, Vanilla JavaScript (RegEx Data Parsing), Tailwind CSS.
- **AI / LLM:** System Prompts, RAG, LoRA Fine-tuning.

---

## 🚀 Cara Menggunakan
1. Clone repositori ini ke mesin lokal Anda:
   ```bash
   git clone https://github.com/username-anda/soc-architecture-playbook.git
   ```
2. Buka folder `docs` atau `ebook` untuk mengakses file PDF/HTML dari master e-book.
3. Folder `src` (jika ada) berisi cuplikan skrip Python dan kerangka antarmuka HTML/Tailwind yang dibahas di dalam buku.

---

## 🤝 Kontribusi
Pemeliharaan dan perbaikan deteksi ancaman adalah usaha kolektif. Jika Anda memiliki *use case* EQL baru, <em>script</em> automasi SOAR, atau ide untuk mengurangi *False Positive*, silakan buat *Pull Request* atau buka *Issue*.

---

## ✍️ Penulis
**Rizki Angga Pratama**  
L2 SOC Analyst & Security Engineer  
[LinkedIn Profile](https://www.linkedin.com/in/username-anda) | [Twitter/X](https://twitter.com/username-anda)

---

## 📄 Lisensi
Dokumen dan kode di dalam repositori ini dilisensikan di bawah **MIT License**. Lihat file `LICENSE` untuk detail lebih lanjut. (Kecuali disebutkan lain pada data intelijen spesifik).