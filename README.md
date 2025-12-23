# DeepTSMC

> A full-stack application that predicts TSMC's next-day closing stock price using deep learning models and visualizes forecasts via an interactive React UI.

##  Tech Stack
![Python](https://img.shields.io/badge/Python-3.9-blue)
![Frontend](https://img.shields.io/badge/Frontend-React-61DAFB)
![Backend](https://img.shields.io/badge/Backend-Flask-green)
![ML](https://img.shields.io/badge/ML-TensorFlow-orange)
![Docker](https://img.shields.io/badge/Tools-Docker-2496ED)

* **Languages:** Python, JavaScript, CSS
* **Frameworks/Libraries:** Flask, React, Vite, TensorFlow/Keras, Pandas, Plotly
* **Tools/Platforms:** Docker, Docker Compose, Google Cloud Run, Firebase Hosting, GitHub Actions

##  Key Features
* **Multi-Model Forecasting:** Evaluates and compares LSTM, GRU, Conv1D, and FFN architectures for time series prediction.
* **Interactive Visualization:** A modern React frontend using Plotly to visualize validation and test predictions against true stock prices.
* **Full-Stack Deployment:** Containerized backend on Google Cloud Run and static frontend hosting on Firebase, orchestrated via Docker for local development.
* **Automated CI/CD:** GitHub Actions workflows ensure code quality and automated testing upon every push.

##  Results / Demo
**Live Demo:** [https://time-series-backend.web.app/](https://time-series-backend.web.app/)

The **FFN** and **GRU** models demonstrated the most reliable generalization to unseen data.

*   **FFN:** Test MAE: $4.24 (2.19%) - *Best generalization*
*   **GRU:** Test MAE: $4.27 (2.21%) - *Balanced fit*
*   **LSTM:** Test MAE: $6.56 (3.40%) - *Showed overfitting*

##  How to Run
```bash
# Clone the repository
git clone https://github.com/hungkaihsin/tsmc_stock_forecasting.git
cd tsmc_stock_forecasting

# Build and Start with Docker Compose
docker-compose build
docker-compose up

# Access the application
# Open your browser to http://localhost:8080
```

##  Contact
Created by **Daniel** - [k_hung2@u.pacific.edu](mailto:k_hung2@u.pacific.edu)

