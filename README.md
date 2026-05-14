# 🎌 Basic Anime Recommendation System

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](#)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)](#)
[![Machine Learning](https://img.shields.io/badge/Machine_Learning-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](#)

## 📝 Project Overview
This project is an interactive **Anime Recommendation System** designed to help users find their next favorite anime. By analyzing user ratings and anime metadata, the system suggests similar anime titles that align with the user's taste. The application features a clean, user-friendly web interface powered by **Streamlit**.

## 📂 Repository Structure
* `app.py` 🖥️: The main application script that contains the Streamlit web app layout and recommendation logic.
* `anime1.csv` 📊: The dataset containing anime information (e.g., titles, genres, episodes).
* `rating1.csv` ⭐️: The dataset containing user ratings for different anime, used to generate recommendations.
* `.streamlit/` ⚙️: Directory containing configuration files for the Streamlit app's appearance and deployment settings.
* `requirements.txt` 📦: A list of necessary Python dependencies and packages required to run the project.
* `README.md` 📖: Project documentation.

## 🛠️ Tech Stack
* **Language:** Python
* **Web Framework:** Streamlit
* **Data Handling:** Pandas, NumPy
* **Machine Learning / Recommendation Logic:** Collaborative Filtering / Content-Based Filtering (via Scikit-Learn or built-in similarity matrices)

## 🚀 How to Run the Project Locally

Follow these steps to set up and run the Anime Recommender App on your own machine:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/ManOfSteel161/anime-recommender-system.git](https://github.com/ManOfSteel161/anime-recommender-system.git)
    cd anime-recommender-system
    ```

2.  **Create a virtual environment (Optional but recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Launch the Streamlit App:**
    ```bash
    streamlit run app.py
    ```

5.  **Enjoy!** Open the provided local URL (usually `http://localhost:8501`) in your web browser and start exploring anime recommendations.

## 💡 Features
* **Interactive UI:** Simply search or select an anime title to get instant recommendations.
* **Data-Driven:** Uses real user-rating datasets to compute similarity scores between anime titles.
* **Fast & Responsive:** Built entirely in Python using Streamlit for rapid prototyping and deployment.

---
**Developed by:** [ManOfSteel161](https://github.com/ManOfSteel161)
