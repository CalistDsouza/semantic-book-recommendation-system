# Semantic Book Recommendation System 📚

A book recommendation system leveraging **Natural Language Processing (NLP)** and **semantic search** to provide highly relevant book suggestions. It uses vector embeddings and sentiment analysis to understand book context, going beyond simple collaborative filtering or rating-based methods.

## Features

* **Semantic Search:** Uses **vector embeddings** (`vector-search.ipynb`) of book descriptions to find titles with similar meaning and themes.
* **NLP Analysis:** Includes notebooks for **Text Classification** and **Sentiment/Emotion Analysis** (`text-classification.ipynb`, `sentiment-analysis.ipynb`) to enrich book data.
* **Gradio Dashboard:** An interactive web interface (`gradio-dashboard.py`) for easy testing and demonstration.

---

## Technologies

* **Language:** Python
* **Key Libraries:** Pandas, NumPy, Scikit-learn, NLP embedding libraries (e.g., Hugging Face models), **Gradio**.
* **Development:** Jupyter Notebooks (`.ipynb`) and Python scripts (`.py`).

---

## Setup and Run

### Prerequisites

* Python 3.8+

### Steps

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/CalistDsouza/semantic-book-recommendation-system.git](https://github.com/CalistDsouza/semantic-book-recommendation-system.git)
    cd semantic-book-recommendation-system
    ```

2.  **Install Dependencies:**
    *(You will need a `requirements.txt` file for this step, containing all necessary libraries like `pandas`, `gradio`, and NLP tools.)*
    ```bash
    pip install -r requirements.txt
    ```

3.  **Launch the Dashboard:**
    ```bash
    python gradio-dashboard.py
    ```
    The application will typically start on `http://127.0.0.1:7860`.

---

## Data

The project utilizes several processed datasets:
* `books.csv` (Original Dataset)
* `books_cleaned.csv`
* `books_with_categories.csv`
* `books_with_emotions.csv`
