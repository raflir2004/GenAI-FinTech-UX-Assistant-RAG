# GenAI-Driven FinTech UX Assistant: RAG Pipeline & Literature GAP Matrix

Repositori ini dibuat untuk memenuhi tugas **Awal RTM 2** pada mata kuliah **Generative AI (Program Pascasarjana S2 Magister Kecerdasan Buatan)** di Universitas Dian Nuswantoro. Proyek ini berfokus pada otomatisasi evaluasi dan rekomendasi antarmuka transaksi finansial pada aplikasi mobile banking menggunakan pendekatan Generative AI dan pipeline Retrieval-Augmented Generation (RAG).

## 🏛️ Profil Use-Case Sektor Finance
* **Judul Ide:** GenAI-Driven FinTech UX Assistant: Asisten AI Generatif untuk Otomatisasi Evaluasi dan Rekomendasi Antarmuka Transaksi Finansial pada Aplikasi Mobile Banking.
* **Masalah (The Problem):** Data clickstream log akses server perbankan sangat rumit dan sulit dipahami secara instan oleh tim UI/UX non-teknis, sehingga memperlambat pengambilan keputusan perbaikan alur transaksi (UX redesign) yang krusial bagi conversion rate bank.
* **Solusi GenAI:** Menggunakan kemampuan reasoning LLM untuk membaca data log, mencocokkannya dengan standar Heuristic Evaluation, menghasilkan narasi laporan tertulis (Bahasa Bisnis), serta men-generate draf kode komponen visual perbaikan secara otomatis.

## 🛠️ Spesifikasi Arsitektur RAG Pipeline
Sistem dibangun secara mandiri menggunakan ekosistem **LangChain** dengan implementasi modern **LCEL (LangChain Expression Language)** guna menjamin stabilitas integrasi jangka panjang.
* **Framework:** LangChain (v0.3+)
* **Vector Database:** FAISS (Facebook AI Similarity Search) - *In-Memory Database*
* **Embeddings Model:** HuggingFace `all-MiniLM-L6-v2` (Gratis & Efisien)
* **LLM Engine:** Groq API Cloud Inference Engine (Menggunakan model produksi `openai/gpt-oss-20b`)
* **Knowledge Base:** Dokumen ilmiah internasional (Rentang Publikasi 2024-2026) hasil kurasi platform Elicit mengenai evaluasi heuristik otomatis dan pengujian kegunaan berbasis LLM Agents.

## 📊 Hasil Eksekusi: Literature GAP Matrix
Hasil inferensi RAG Pipeline yang termuat di dalam berkas pemrograman berhasil mengekstrak matriks celah penelitian (*GAP Matrix*) akademis, memetakan keterbatasan riset terdahulu (seperti batasan evaluasi GUI generik, ketiadaan aspek kepatuhan/security perbankan pada model dasar), serta memvalidasi posisi orisinalitas proyek *FinTech UX Assistant* ini sebagai solusi mutakhir penutup gap literatur.

---
*Catatan Keamanan: Seluruh kredensial dan API Key personal telah dibersihkan dari berkas notebook `Untitled0.ipynb` demi mematuhi prinsip kebersihan kode dan credential safety sebelum diunggah ke repositori publik.*
