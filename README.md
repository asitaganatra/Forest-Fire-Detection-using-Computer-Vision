🔥 Forest Fire Detection using Computer Vision

This project is built to detect forest fires in images using a Convolutional Neural Network (CNN) and provides a user-friendly interface via **Streamlit**. It helps in early detection of forest fires, which can play a vital role in preventing widespread damage.

📂 Project Files

- `forest.h5` – Trained CNN model for fire detection
- `forest.ipynb` – Jupyter notebook used for model development and training
- `app.py` – Streamlit web app for real-time fire detection
- `requirements.txt` – Python libraries required to run the project

🧠 Model Summary

The deep learning model was trained using **TensorFlow** and **Keras** on a dataset containing images of forests with and without fire. The final model classifies input images into two categories:
- 🔥 Fire
- 🌲 No Fire

💻 Getting Started

✅ Prerequisites

Ensure Python 3.7+ is installed. Then install required libraries:

```bash
pip install -r requirements.txt
```

The `requirements.txt` includes:
```
streamlit
tensorflow
Pillow
numpy
```

▶️ Running the Streamlit App

```bash
streamlit run app.py
```

Then go to the URL shown in the terminal (typically `http://localhost:8501`) to interact with the app.

📸 How It Works

1. Upload an image of a forest
2. The model processes the image and classifies it as `Fire` or `No Fire`
3. Result is displayed in the browser with probability/confidence

📘 Notebook

You can use `forest.ipynb` to:
- Train or retrain the CNN model
- Visualize training accuracy/loss
- Export the model as `forest.h5`

 📌 Future Scope

- Integrate real-time video feed analysis
- Add alert system or email/SMS notifications
- Expand dataset for higher accuracy

✍️ Author

**Asita Ganatra**  
GitHub: [@asitaganatra](https://github.com/asitaganatra)

#Application Link: https://forest-fire-detection-using-computer-vision-dvats959eynkbeymrw.streamlit.app/
