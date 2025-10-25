# crest-gold-bird-app
AI-powered app to identify bird species from chirps using audio classification
🐦 Bird Chirp Recognition AI — CREST Gold Project
🎯 Project Overview
This project aims to identify bird species based on their chirps using audio classification and machine learning. It was developed as part of a CREST Gold award submission, combining AI model training, audio preprocessing, and app development.

🧠 Team Roles
Chubz – AI Developer Responsible for data preprocessing, model training, evaluation, and Hugging Face integration.

Toast – App Developer Designed and implemented the user-facing app interface using Gradio.

🛠️ Tools & Technologies
Python (Anaconda environment)

Librosa – Audio preprocessing

PyTorch – Model training

Gradio – Web app interface

Hugging Face – Model experimentation and deployment

VS Code – Development environment

GitHub – Version control and collaboration

📁 Folder Structure
Code
bird-chirp-ai/
├── ai/                  # AI model, training scripts, inference
├── app/                 # Gradio app code
├── data/                # Sample bird chirps and spectrograms
├── results/             # Accuracy scores, confusion matrix
├── report/              # CREST report and reflection log
├── presentation/        # PowerPoint slides and screenshots
├── README.md            # Project overview and instructions
🚀 How to Run the App
Clone the repo:

bash
git clone https://github.com/yourusername/bird-chirp-ai.git
cd bird-chirp-ai
Activate your environment:

bash
conda activate bird-ai
Install dependencies:

bash
pip install -r requirements.txt
Launch the app:

bash
python app/main.py
📈 Model Performance
Accuracy: 92% on test set

Classes: Robin, Blackbird, Blue Tit, Woodpecker

Evaluation: Confusion matrix, precision-recall

📜 License
This project is licensed under the MIT License. See LICENSE for details.
