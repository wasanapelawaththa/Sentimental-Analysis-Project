#  📝 Review Catcher - Review classification model with web application

**Review Catcher** is a modern web application designed to analyze and extract sentiments from customer reviews. It uses natural language processing (NLP) to determine whether feedback is positive, neutral, or negative—empowering businesses to make informed decisions based on real customer experiences.

🔗 [Live Demo](https://review-catcher-fea3fxhsaef5dqa8.canadacentral-01.azurewebsites.net/)

---

## 🚀 Features

- 🔍 **Sentiment Analysis** – Analyze review text and classify sentiment.
- 📊 **Instant Feedback** – Get real-time response on the nature of customer feedback.
- 🌐 **Responsive Design** – Works well across devices (desktop, tablet, mobile).
- ⚡ **Fast & Lightweight** – Optimized for quick load and interaction.
- 📁 **Azure Hosted** – Deployed via Microsoft Azure App Services.

---

## 🛠️ Tech Stack

| Category       | Technology         |
|----------------|--------------------|
| Frontend       | HTML5, CSS3, JavaScript |
| Backend        | Python (Flask)     |
| NLP            | TextBlob / NLTK / spaCy (as applicable) |
| Deployment     | Microsoft Azure    |

---

## 📦 Installation & Setup

To run the project locally:

```bash
# Clone the repository
git clone https://github.com/yourusername/review-catcher.git
cd review-catcher

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the Flask server
python app.py

