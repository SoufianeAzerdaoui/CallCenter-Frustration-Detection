# 🎧 Projet  : Détection de Frustration et Suggestions Contextuelles dans les Centres d’Appels (Call Center AI)

## 📌 Contexte
Dans les centres d’appels, une grande partie de l’insatisfaction client provient de conversations frustrantes avec des chatbots ou des réponses inadaptées.  
Ce projet vise à développer une solution IA capable de **détecter la frustration dans les dialogues**, **résumer les échanges**, et **suggérer des réponses adaptées** aux agents, en tenant compte de l’historique du client.

---

## 🎯 Objectifs
- 🔎 Détection automatique des signes de frustration dans une conversation client-agent ou client-bot.  
- 📝 Génération d’un **résumé automatique** des échanges.  
- 💡 Suggestion de **réponses/actions adaptées** à l’agent (ex. proposer une réduction, transfert à un humain).  

---

## 🗂️ Structure du projet

---

## 🔄 Pipeline du projet
1. **Audio Input** 🎙️  
   - Input : fichiers audio (`.mp3`, `.wav`)  
   - Outils : FFMPEG (nettoyage), Whisper (Speech-to-Text)  

2. **Data Modeling** 📑  
   - Structure des données en JSON  
   - Historique client intégré  

3. **Machine Learning** 🤖  
   - **Sentiment Analysis** : Détection frustration (BERT, CamemBERT)  
   - **Q&A Model** : Résumé + Suggestion (T5, BART)  

4. **Intégration Résultats** 📊  
   - Résumé de la conversation  
   - État émotionnel détecté  
   - Suggestions de réponses/actions  

---

## 🛠️ Technologies utilisées
### 🎵 Audio Processing
- OpenAI Whisper  
- FFMPEG  
- Python Audio Libraries  
- Speech Recognition  

### 📑 Data Processing
- JSON Data Structure  
- Pandas / NumPy  
- Data Preprocessing  

### 🤖 Machine Learning
- **T5** (modèle de Question-Réponse)  
- **BERT / CamemBERT** (analyse de sentiments)  
- Hugging Face Transformers  
- PyTorch / TensorFlow  

### 💻 Interface & Déploiement
- Streamlit  
- Jupyter Notebook  
- FastAPI  



