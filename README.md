# Qiskit-Algorithm-Lab

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter" />
  <img src="https://img.shields.io/badge/Qiskit-6929C4?style=for-the-badge&logo=qiskit&logoColor=white" alt="Qiskit" />
</p>

## 🇬🇧 Overview

Quantum computing notebooks with Qiskit: simple circuits, connecting to IBM Quantum, phase and the Bloch sphere, teleportation, and the Bernstein–Vazirani, Deutsch, Grover and Shor algorithms.

**Quick start:** `jupyter notebook`

## 🇹🇷 Proje hakkında

Qiskit ile kuantum hesaplama defterleri; basit devrelerden Grover ve Shor algoritmalarına kadar.

## 📚 İçerik

- `Q01`: basit kuantum devreleri
- `Q02`: IBM Quantum hesabına bağlanma
- `Q03`: faz ve Bloch küresi
- `Q04`: kuantum ışınlama
- `Q05`–`Q06`: Bernstein–Vazirani
- `Q07`: Deutsch algoritması
- `Q08`–`Q09`: Grover araması
- `Q10`–`Q11`: Shor algoritması

## ⚙️ Kurulum ve çalıştırma

```bash
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

IBM Quantum için API anahtarınızı `ibmtoken.txt` dosyasına yazın. Bu dosya `.gitignore` içindedir ve depoya eklenmez.

```bash
jupyter notebook
```

## 📁 Dosya yapısı

```text
Qiskit-Algorithm-Lab/
├── Q01-qiskit_simple_circuits.ipynb
├── Q02-ibm_account.ipynb
├── Q03-phase_bloch_sphere.ipynb
├── Q04-teleportation.ipynb
├── Q05-Bernstein_Vazirani_algorithm.ipynb
├── Q06-Bernstein_Vazirani_algorithm.ipynb
├── Q07-Deutsch_algorithm.ipynb
├── Q08-Grovers_algorithm.ipynb
├── Q09-Grovers_algorithm_ex.ipynb
├── Q10_Shors_algorithm.ipynb
└── Q11-Shors_algorithm.ipynb
```
