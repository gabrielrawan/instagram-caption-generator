# instagram-caption-generator
Gerador de Legendas para Instagram feito com HTML, CSS e JavaScript
📸 Instagram Caption Generator (AI)

An AI-powered application that generates engaging Instagram captions from images using deep learning techniques.

🚀 Overview

This project combines Computer Vision and Natural Language Processing to automatically generate captions for images. It uses a CNN-based encoder to extract visual features and an LSTM-based decoder to generate human-like text descriptions.

🧠 Features
Generate captions from images
Deep learning pipeline (CNN + LSTM)
Pretrained model support
Custom dataset training capability
Modular and scalable architecture
🛠️ Tech Stack
Python
TensorFlow / Keras
NumPy
Flask (optional for deployment)
📂 Project Structure
├── data/                # Dataset (not included due to size)
├── models/              # Trained models
├── notebooks/           # Experiments and training
├── app.py               # Web app (if applicable)
├── utils.py             # Helper functions
└── README.md
⚙️ Installation
git clone https://github.com/gabrielrawan/instagram-caption-generator.git
cd instagram-caption-generator
pip install -r requirements.txt
▶️ Usage
python app.py

Upload an image and receive generated captions.

📊 Model Details
Encoder: Convolutional Neural Network (e.g., InceptionV3 / ResNet)
Decoder: LSTM-based sequence generator
Tokenization: Word-level tokenizer
Loss Function: Categorical Crossentropy
📌 Notes
Dataset is not included due to size limitations.
You can train the model using publicly available datasets such as Flickr8k or MSCOCO.
🔮 Future Improvements
Web UI improvements
Multiple caption styles (formal, casual, marketing)
Hashtag generation
API deployment
🤝 Contributing

Contributions are welcome. Feel free to fork and improve the project.

📄 License

This project is open-source and available under the MIT License.
