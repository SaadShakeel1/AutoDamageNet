# AutoDamageNet – Vehicle Damage Detection  

## 🎥 Live Demo  

Check out the live demo of **AutoDamageNet** deployed on Streamlit:  

👉 [AutoDamageNet Live App](https://auto-damage-net.streamlit.app/)


## 🚗 Overview  
AutoDamageNet is a deep learning project designed to automatically detect **vehicle damage**. The model classifies images of vehicles into **6 categories**:  

- Front Breakage  
- Front Crush  
- Front Normal  
- Rear Breakage  
- Rear Crush  
- Rear Normal  

This system can help in **insurance claims, accident assessment, and vehicle inspection automation**.  

---

## ⚙️ Features  
- End-to-end vehicle damage detection.  
- Multiple deep learning approaches explored:  
  - Baseline CNN  
  - CNN with Regularization  
  - Transfer Learning with **EfficientNet** and **ResNet**  
- Finalized with **ResNet**, achieving **~80% accuracy**.  
- Built with **PyTorch, scikit-learn, and Streamlit** (for deployment).  

---

## 🛠️ Tech Stack  
- **Deep Learning Framework**: PyTorch  
- **Evaluation & Preprocessing**: scikit-learn, NumPy, Pandas  
- **Visualization**: Matplotlib, Seaborn  
- **Deployment**: Streamlit  

---

## Install Dependencies
- **pip install -r requirements.txt**

## Run Streamlit App
- **streamlit run app.py**