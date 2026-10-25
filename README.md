# 🛡️ The Ultimate SecOps & Threat Hunting Library

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Author](https://img.shields.io/badge/Author-Rizki%20Angga%20Pratama-10b981.svg)]()
[![Maintained](https://img.shields.io/badge/Maintained-Yes-success.svg)]()
[![SOC Level](https://img.shields.io/badge/Tier-L2%20%2F%20L3%20SOC-ec4899.svg)]()

Selamat datang di repositori **Koleksi Lengkap E-Book Cybersecurity & Security Operations Center (SOC)**. 

Repositori ini adalah perpustakaan teknis dan cetak biru arsitektural yang didedikasikan untuk mentransformasi operasional keamanan siber—bergeser dari pemantauan log reaktif (L1) menuju rekayasa deteksi proaktif, otomatisasi respons cerdas, pembedahan *malware*, hingga implementasi agen kecerdasan buatan (L2/L3).

---

## 👨‍💻 About the Author

**Rizki Angga Pratama**  
*L2 SOC Analyst & Security Engineer*  

Saya adalah praktisi keamanan siber yang berfokus pada *Detection Engineering*, *Incident Response Automation* (SOAR), dan *Malware Triage*. Repositori ini merupakan bentuk dedikasi saya untuk membagikan taktik operasional, metodologi *Threat Hunting*, dan inovasi AI di ruang SOC kepada komunitas *Cybersecurity* Indonesia dan global.

---

## 📚 Daftar Koleksi E-Book

Koleksi ini terdiri dari **2 Master E-Book (Enterprise Edition - 50 Halaman)** yang membahas ekosistem pertahanan secara *end-to-end*, serta **10 E-Book Taktis** yang berfokus pada spesialisasi kasus tertentu.

### 🌟 The Master E-Books (50-Pages Enterprise Edition)

Dua buku raksasa ini adalah fondasi utama repositori ini, memberikan panduan komprehensif dari hulu ke hilir:

1. 📘 **SOC Architecture & Engineering: Dari Analisis Log Hingga Respons Otomatis Terintegrasi**  
   > *Master playbook* yang merangkai visibilitas SIEM, arsitektur *Cloud IR*, rekayasa deteksi (KQL/EQL), hingga eksekusi *containment* seketika menggunakan orkestrasi SOAR. Dilengkapi studi kasus forensik ancaman internal (*Insider Threat*).
2. 📕 **Practical Malware Analysis & Reverse Engineering for SOC**  
   > Panduan definitif untuk membongkar "kotak hitam" <em>malware</em>. Mengupas cara membangun laboratorium isolasi (*Air-Gapped Sandbox*), analisis statis/dinamis, *Network Beaconing*, hingga dekompilasi *Assembly x86* menggunakan Ghidra untuk diekstrak menjadi YARA *Rules*.

### 🎯 The Tactical Playbooks (E-Book Spesifik)

Sepuluh panduan taktis ini dirancang untuk menyelesaikan tantangan spesifik di ruang operasi keamanan:

3. 📗 **The Elastic Security Masterclass:** *Advanced KQL, EQL & Log Hunting.*
4. 📙 **The Detection Engineering Blueprint:** *Logic Design, Suppression Windows, & FP Reduction.*
5. 📓 **The Essential SOAR Playbook:** *Practical Use Cases & API Automation for Modern Security Teams.*
6. 🔬 **Advanced Threat Detection & Machine Learning in SIEM:** *Building Anomaly Baselines.*
7. 🤖 **AI-Driven SOC:** *Prompt Engineering, RAG & LoRA for Automated Incident Triage.*
8. ☁️ **Incident Response Playbook for Cloud Environments:** *AWS CloudTrail & Azure AD Triage.*
9. 🧱 **Enterprise Perimeter Defense Playbook:** *Ingress/Egress Monitoring & External Dynamic Lists.*
10. ⚔️ **Purple Teaming & Advanced Detection Engineering:** *Validasi Alert dengan Atomic Red Team.*
11. 🛠️ **SecOps Tooling:** *Building Custom Triage Interfaces (JavaScript/RegEx).*
12. 📊 **Building Interactive SecOps Dashboards:** *Visualisasi Metrik & Ergonomi Kognitif (HTML/Tailwind).*

---

## 🛠️ Tech Stack & Konsep yang Dibahas

Karya dalam repositori ini bukan sekadar teori, melainkan diimplementasikan menggunakan tumpukan teknologi standar industri (*Enterprise Tech Stack*):

* **SIEM & Data Analytics:** Elastic Security (ELK Stack), Splunk, Kibana, KQL, EQL, Machine Learning (Anomaly Detection).
* **EDR & Security Tooling:** CrowdStrike Falcon, SentinelOne, Palo Alto NGFW, Zeek/Suricata.
* **Malware Analysis & RE:** FlareVM, REMnux, INetSim, Ghidra, x64dbg, PeStudio, Sysinternals (Procmon), Wireshark.
* **Automation & Scripting:** Python 3, REST API Integration, JSON Parsing.
* **Frontend & Dashboards:** HTML5, Vanilla JavaScript (RegEx), Tailwind CSS.
* **AI / Next-Gen SOC:** Large Language Models (LLMs), RAG (*Retrieval-Augmented Generation*), LoRA (*Low-Rank Adaptation*).
* **Detection as Code:** YARA Rules, Sigma Rules.

---

## 🚀 Cara Menggunakan (How to Use)

Anda dapat mengakses seluruh *file* PDF/HTML E-Book ini dengan mengkloning repositori ke mesin lokal Anda:

```bash
# Clone repository
git clone https://github.com/username-anda/soc-master-library.git

# Masuk ke direktori
cd soc-master-library

# Buka folder /ebooks untuk mulai membaca
```

Bagi *Detection Engineers*, Anda juga dapat menelusuri folder `/src` atau `/rules` (jika tersedia) untuk menemukan cuplikan *script* Python SOAR, YARA *Rules*, atau *template UI Dashboard* yang dibahas dalam buku.

---

## 🤝 Kontribusi

Pemeliharaan pertahanan siber adalah usaha kolektif. Jika Anda menemukan teknik analisis baru, memiliki *use case* KQL yang lebih tajam, atau ingin memperbaiki *typo*, silakan buat **Pull Request** atau buka **Issue**. Masukan dari sesama praktisi sangat dinantikan!

---

## 💬 Connect with Me

Mari terhubung dan berdiskusi tentang rekayasa deteksi, *malware*, dan operasi keamanan siber:

* 💼 **LinkedIn:** [Rizki Angga Pratama](https://www.linkedin.com/in/username-anda)
* 🐦 **Twitter / X:** [@username_anda](https://twitter.com/username-anda)

---

## 📄 License

Seluruh dokumen dan kode di dalam repositori ini didistribusikan di bawah **MIT License**. Lihat berkas `LICENSE` untuk detail lebih lanjut. Bebas digunakan untuk keperluan pembelajaran, pelatihan internal SOC, maupun referensi akademik (dengan menyertakan atribusi kredit).
