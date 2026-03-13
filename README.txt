## RAGBot - Cohere Chat Bot

---

### ⚠️ Note

Make sure to **get your API key from Cohere** before running the bot.

---

### Features

* Read and analyze documents (PDF, DOCX, TXT)
* Search for keywords in your documents
* Summarize content intelligently
* Export results to CSV or PDF for easy sharing

---

### Installation

#### 1. Clone the repository

```bash
git clone https://github.com/yourusername/RAGBot.git
cd RAGBot
```

#### 2. Install required Python packages

```bash
pip install -r requirements.txt
```

#### Optional: Use a virtual environment to avoid conflicts

```bash
# Create and activate virtual environment
python -m venv myenv

# macOS/Linux
source myenv/bin/activate

# Windows
myenv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

---

### 3. Prepare your documents

* Place all files you want the bot to read in the `data/` folder
* Supported formats: **PDF, DOCX, TXT**

---

### 4. Run RAGBot

```bash
python main.py
```