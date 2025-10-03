# 🎭 Interactive AI Story Teller

This project is an **AI-powered storytelling application** that generates interactive stories from user prompts or Images/Multi-Images.  
It uses **Streamlit** for the user interface and Python libraries for story flow, audio, and image handling.  

---


## 📂 Project Structure
```
Interactive-AI-Story-Teller/
│── Interactive_AI_Story_Teller.py      → Main Python script
│── requirements.txt                     → Python dependencies
│── README.md                            → Project documentation
│── resources/
│    └── data/                           → Input data files (e.g., images, datasets)
│         └── sample_image.png
│    └── output/                         → Generated outputs
│         ├── audio/                     → Generated story narrations (audio files)
│         └── text/                      → Generated story text files
│    └── website_background/             → Background images for web UI
```


---

## ⚙️ Technologies Used
- Python 3  
- Streamlit  
- NumPy, Pandas  
- OpenCV, Pillow  
- Requests  

---

## 🚀 How to Run the Project

1. **Clone this repository**  
   ```bash
   git clone https://github.com/your-username/Interactive-AI-Story-Teller.git
   cd Interactive-AI-Story-Teller
   ```


2. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit app**  
   ```bash
   streamlit run Interactive_AI_Story_Teller.py
   ```

4. **Open the app**  
   Go to the URL displayed in the terminal (usually `http://localhost:8501/`) and start interacting with the AI storyteller.  

---

## 📊 How It Works
- User enters a **prompt** (e.g., “A dragon in a futuristic city”).  
- The AI dynamically generates story text.  
- Streamlit interface provides a simple and interactive environment for storytelling.  
- Generated **text outputs** and **audio narrations** are saved in the `resources/output` folder.  

---

## ✅ Features
- Create **interactive and personalized stories**.  
- Add **visual elements** using image libraries.  
- Save **audio narration** and **story text** automatically.  
- Lightweight and easy to run locally or on Colab.  

---

## 🔮 Future Work
- Expand story genres and character profiles.  
- Add **text-to-speech narration** for immersive storytelling.  
- Integrate with generative image models (Stable Diffusion, DALL·E).  
- Build a **web deployment** for public use.  

---

## 👨‍💻 Author
- Sudhakar Govindasamy  
- [LinkedIn Profile](www.linkedin.com/in/sudhakargovindasamy) | [GitHub Profile](https://github.com/sudhakargovindasamy)
