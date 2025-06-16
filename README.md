# 📚 Information Retrieval and Document Processing with Python Terrier

This project demonstrates core concepts of **information retrieval**, **document clustering**, and **IR system evaluation**, utilizing state-of-the-art tools like **python-terrier**, **ir\_datasets**, and **NLTK**. It offers practical insight into document ranking, user query negotiation, and clustering methods using inverted files.

---

## 🧠 Project Overview

This notebook explores the theoretical and practical aspects of **Data Mining and Information Retrieval (IR)**, focusing on:

* Query formulation
* Document retrieval
* Result evaluation
* Clustering
* Statistical inference in IR systems

---

## 🚀 Features

### 🔍 Information Retrieval Tasks

* Retrieval of articles based on titles and textual content
* Explanation of core IR concepts such as:

  * Image recognition for digitizing printed text
  * Common challenges in information systems usage
  * Online bibliographic database search programs
  * Clustering and similarity calculation via inverted files
  * IR test evaluation parameters and metrics
  * Negotiation of user queries through system interaction

### 🛠️ Tools and Libraries Used

* **Core Libraries:**

  * `python-terrier`: For building and evaluating IR pipelines
  * `ir_datasets`: Access to popular benchmark datasets
  * `nltk`: For natural language processing
  * `pandas`, `numpy`: Data manipulation and numerical computation
* **Additional Utilities:**

  * `beautifulsoup4`, `inscriptis`, `lxml`: HTML processing
  * `trec-car-tools`, `pytrec_eval_terrier`, `ir_measures`: TREC-style IR evaluation
  * `transformers`, `huggingface-hub`, `tokenizers`: Optional for semantic retrieval models
* **Web Development (Commented out in notebook):**

  * `flask`, `flask_ngrok`: Intended for serving a basic web UI for IR interaction

---

## 📦 Technologies & Dependencies

This project uses the following tools and dependencies (install via `pip`):

```bash
pip install python-terrier ir_datasets nltk pandas numpy beautifulsoup4 inscriptis lxml pytrec_eval_terrier ir_measures flask flask_ngrok tqdm transformers
```

> Note: The project also involves cloning the `terrier-prf` repository and installing `maven` for some extensions.

---

## 🧪 How to Run the Project

1. **Install Python 3.8+**
2. **Install required libraries** using `pip` or `conda`
3. **Clone any necessary repositories:**

   ```bash
   git clone https://github.com/terrierteam/terrier-prf
   ```
4. **Install Java and Maven** if using Terrier extensions
5. **Run Jupyter Notebook:**

   ```bash
   jupyter notebook
   ```
6. **Open and run the notebook** (e.g., `IR_Project_Notebook.ipynb`) step-by-step

---

## 📁 Dataset Information

* **Name:** Dataset varies based on usage (likely `ir_datasets`)
* **Accessed Via:** `ir_datasets` library
* **Type:** Text corpora used in IR benchmarks (e.g., TREC, ClueWeb, CORD-19)

