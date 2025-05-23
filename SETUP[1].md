## Installation

### Prerequisites
- Python 3.8 or later
- pip (Python package installer)

### Steps
1. Clone the repository:
  ```bash
  git clone https://github.com/your-username/crypto-price-predictor.git
  cd crypto-price-predictor
  ```
2. Create a virtual environment (optional but recommended):
  ```bash
  python -m venv venv
  source venv/bin/activate   # On Windows: venv\Scripts\activate
  ```
3. Install dependencies:
  ```bash
  pip install -r requirements.txt
  ```
4. Place your pre-trained Keras model file (`model.keras`) in the project root.

5. Run the Flask app:
  ```bash
  python app.py
  ```

6. Open your browser and navigate to:
  ```
  http://127.0.0.1:5000/
  ```
