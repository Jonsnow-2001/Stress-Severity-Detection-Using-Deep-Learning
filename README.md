# Emotional Pulse Signals Based Stress Severity Detection in College Students Using Deep Learning

->I’m thrilled to share my first-ever Machine Learning & Deep Learning project, where I explored how AI can quantify human stress from physiological signals like PPG (Photoplethysmography). This marks the beginning of my journey into AI, deep neural architectures, and multimodal fusion!

->The goal was to simulate and predict stress levels using synthetic PPG signals across five emotions — calm, happiness, sadness, tension, and fear. I built the entire pipeline from scratch: data generation → preprocessing → deep feature extraction → emotional fusion → multimodal fusion → final prediction.

⚙️ Project Workflow
*Phase 1 — Synthetic Dataset: Generated PPG signals for 20 subjects, assigned stress scores, and created metadata.
*Phase 2 — Preprocessing: Wavelet denoising (db8), PRV extraction via peak detection, and dPPG segmentation + interpolation.
*Phase 3 — Data Splitting: Subject-level stratified split ensuring balanced stress levels.
*Phase 4 — Deep Learning Features: Built 1D-CNN + BiLSTM models and extracted 32D embeddings for each emotion.
*Phase 5 — Emotional Fusion: Designed a Transformer-inspired weighted cross-attention module.
*Phase 6 — Multimodal Fusion: Fused PRV + dPPG embeddings using cross-attention and dense layers.
*Phase 7 — XGBoost & Classification: Achieved -
   Accuracy = 0.800, 
   Precision = 0.776, 
   Recall = 0.800, 
   F1-Score = 0.745 
   using quantile-binned stress categories.

🧩 Tech Stack: TensorFlow/Keras, XGBoost, PyWavelets, SciPy, NumPy, Pandas, Matplotlib, Seaborn.

💡 Outcome: Gained hands-on experience in temporal modeling, attention mechanisms, multimodal fusion, and ML evaluation pipelines.

❤️ Personal Note :-
This being my first-ever ML/DL project, it holds a special place in my journey. It’s where I wrote my first neural network, tuned my first model, and saw AI “learn” emotions for the first time. Truly grateful for this milestone in my path toward Human-Centric AI. 🌱✨

GitHub Repo :-
