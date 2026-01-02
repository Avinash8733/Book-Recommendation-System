# Book Recommender System

A Machine Learning based Book Recommender System using Collaborative Filtering.

## 🚀 Live Demo
(Add your deployed link here after deployment)

## 🛠️ Tech Stack
- **Frontend**: HTML, CSS (Bootstrap 5), JavaScript
- **Backend**: Flask (Python)
- **ML Models**: Pickle, NumPy, Pandas

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/book-recommender.git
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python app.py
   ```

## 🌍 Deployment (Render)

This project is ready for deployment on **Render** (Free Tier).

1. **Push to GitHub**:
   - Create a new repository on GitHub.
   - Push your code:
     ```bash
     git init
     git add .
     git commit -m "Initial commit"
     git branch -M main
     git remote add origin https://github.com/your-username/your-repo-name.git
     git push -u origin main
     ```

2. **Deploy on Render**:
   - Go to [dashboard.render.com](https://dashboard.render.com/).
   - Click **New +** -> **Web Service**.
   - Connect your GitHub repository.
   - **Build Command**: `pip install -r requirements.txt`
   - **Start Command**: `gunicorn app:app`
   - Click **Deploy Web Service**.

## 📂 Project Structure
- `app.py`: Main Flask application.
- `templates/`: HTML files.
- `*.pkl`: Pre-trained models and data.
- `Procfile`: Deployment configuration.
- `requirements.txt`: Python dependencies.

