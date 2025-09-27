# 📄💬 Chat PDF – Questions-Réponses sur Documents

Une application **Streamlit** qui permet de charger un ou plusieurs fichiers PDF et de poser des questions directement sur leur contenu.
Le système utilise **LangChain**, **FAISS** et le modèle **Gemini-Pro** de Google pour fournir des réponses précises et contextuelles.

---

## 🚀 Fonctionnalités

* 📂 Import de plusieurs fichiers PDF.
* 🔎 Extraction automatique du texte.
* ✂️ Découpage du texte en morceaux optimisés pour le traitement.
* 🧠 Indexation vectorielle avec **FAISS**.
* 🤖 Réponses contextuelles grâce à **LangChain** et **Gemini-Pro**.
* 📝 Historique des questions/réponses pour suivre la conversation.

---

## ⚙️ Installation

1. **Cloner le dépôt :**

```bash
git clone https://github.com/votre-utilisateur/qr_document.git
cd qr_document
```

2. **Créer un environnement virtuel et installer les dépendances :**

```bash
pip install -r requirements.txt
```

3. **Configurer la clé API Google Generative AI :**
   Créer un fichier `.env` à la racine du projet :

```
GOOGLE_API_KEY=your_api_key_here
```

---

## ▶️ Utilisation

Lancer l’application avec :

```bash
streamlit run QR_Document.py
```

Puis ouvrir l’URL fournie (par défaut : [http://localhost:8501](http://localhost:8501)).

---

## 🛠️ Technologies

* [Python](https://www.python.org/)
* [Streamlit](https://streamlit.io/)
* [LangChain](https://www.langchain.com/)
* [Google Generative AI (Gemini-Pro)](https://ai.google.dev/)
* [FAISS](https://github.com/facebookresearch/faiss)
* [PyPDF2](https://pypi.org/project/pypdf2/)

---

## 📌 Auteur

Projet développé par **Ibrahima Diallo & David lutala Lushuli **.
