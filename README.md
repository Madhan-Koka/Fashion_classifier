# Fashion_classifier
an Image Classification Model
Step 1:
👗 FashionVision AI

FashionVision AI is an image classification project that uses deep learning to identify clothing items from images. It is built with FastAPI for the backend and Streamlit for the frontend.

 🚀 Features
- Upload an image of clothing (e.g., shirt, dress, shoe).
- The AI predicts the clothing category.
- Clean and user-friendly interface.
- Lightweight and easy to deploy.

 🛠️ Technologies Used
- Backend: FastAPI
- Frontend: Streamlit
- Deep Learning: TensorFlow/Keras
- Dataset: Fashion MNIST

  Project Structure 

fashion_classifier/
├── app.py # FastAPI backend
├── streamlit_app.py # Streamlit frontend
├── styles.css # Custom CSS for the frontend
├── fashion_mnist_model/ # Trained model files
├── requirements.txt # Python dependencies
├── README.md # This file

 How to Run the Project
Step 1:
Prerequisites
1. Python 3.8+: Install Python from [python.org](https://www.python.org/).
2. Git: Install Git from [git-scm.com](https://git-scm.com/).
  Clone the Repository
1. Open a terminal and run:  
   git clone https://github.com/your-username/fashion-classifier.git
2. Navigate to the project folder:
cd fashion-classifier

Step 2: Set Up a Virtual Environment

1. Create a virtual environment:
python -m venv venv
2. Activate the virtual environment:
-On Windows:
venv\Scripts\activate
-On macOS/Linux:
source venv/bin/activate

Step 3: Install Dependencies

-Install the required Python packages:
pip install -r requirements.txt

Step 4: Run the Backend (FastAPI)

1. Start the FastAPI server:
uvicorn app:app --reload
2. Open your browser and go to:
http://localhost:8000/docs

Step 5: Run the Frontend (Streamlit)

1. Open a new terminal and activate the virtual environment (if not already activated).
2. Start the Streamlit app:
streamlit run streamlit_app.py
3. Open your browser and go to:
http://localhost:8501

Step 6: Use the App

1. Upload an image of clothing (e.g., shirt, dress, shoe).
2. Wait for the AI to analyze the image.
3. View the predicted clothing category.
