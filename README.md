# 📰 News Topic Classifier

A machine learning application that classifies news headlines into four topic categories: **World**, **Sports**, **Business**, and **Sci/Tech**.



---

## 🎯 Objective
To build a lightweight and interactive news topic classifier by fine-tuning a transformer model (BERT) on the AG News dataset.  
The goal is to demonstrate transfer learning, text classification, and model deployment using Gradio.

---

## ⚙️ Methodology / Approach
- Collected and tokenized the **AG News dataset** using Hugging Face Datasets.
- Fine-tuned the `bert-base-uncased` model with Hugging Face Transformers on the dataset.
- Evaluated model performance with accuracy and F1-score metrics.
- Deployed the trained model as an interactive web app using **Gradio**.
- Designed a custom UI with a newspaper-themed background for a clean, user-friendly interface.

---

## 📊 Key results or observations
- Achieved high accuracy (**~95%**) and F1-score (**~95%**) on the test set.
- The model predicts the topic of short news headlines quickly and accurately.
- Transfer learning with BERT proved effective, even with a limited number of epochs.

---

## 🚀 Installation & Usage

```bash
# Clone the repository
git clone https://github.com/yourusername/news-topic-classifier.git
cd news-topic-classifier

# Install dependencies
pip install -r requirements.txt

<img width="1358" height="631" alt="Screenshot" src="https://github.com/user-attachments/assets/93647f2c-0fe3-418c-9bbd-9ae34a92bb46" />


# Run the Gradio app
python app.py
