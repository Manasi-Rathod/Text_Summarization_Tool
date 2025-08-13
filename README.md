📝 **Text Summarization Tool (NLP)**

Text Summarization Tool (NLP) is a **Python-based** Text Summarization tool that supports both **Extractive** and **Abstractive** summarization techniques using **NLTK** and **BERT Transformers**.
      
## 🚀 Features
- Extractive Summarization using NLTK (selects the most important sentences from the text)
- Abstractive Summarization using BERT (generates new sentences capturing the meaning)
- Easy-to-use command-line interface
- Works with any text input
      
📂 Project Structure

    text\_summarization\_tool/
    │── main.py              # Main execution script
    │── extractive.py        # Extractive summarization logic
    │── abstractive.py       # Abstractive summarization logic
    │── requirements.txt     # Required Python packages
    │── sample.txt           # Example text file for testing
    │── README.md            # Project documentation

 

## ⚙ Installation
1. Clone the repository:

        git clone https://github.com/Manasi-Rathod/Text_Summarization_Tool.git
        cd Text_Summarization_Tool

2. Install dependencies:

        pip install -r requirements.txt

## 🖥 Usage

Run the tool:

    python main.py

Select:

* 1 → Extractive Summarization
* 2 → Abstractive Summarization

## 📌 Example Output

**Input :**

> Natural Language Processing (NLP) is a field of Artificial Intelligence that enables machines to understand and process human language. It powers applications like chatbots, translators, and sentiment analysis.

**Extractive Summary :**

> NLP is a field of AI that enables machines to understand human language.

**Abstractive Summary :**

> NLP allows computers to comprehend and interpret human language for various applications.

## 📜 Requirements

* Python 3.8+
* NLTK
* Transformers (HuggingFace)
* PyTorch / TensorFlow (for BERT)
