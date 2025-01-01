# ShowAttendAndTell: Image Caption Generation with Adaptive Attention

This project implements an adaptive attention mechanism for image captioning, inspired by the **"Show, Attend and Tell"** paper. It dynamically balances focus between visual features and language context, achieving a baseline **BLEU score of ~18.5** on the Flickr8k dataset.

---

## 📂 **Project Overview**
- **Objective**: Generate captions by focusing on relevant image regions while dynamically incorporating language context.
- **Model**: Combines a ResNet50-based encoder, an LSTM decoder, and adaptive attention with a sentinel gate.
- **Dataset**: Flickr8k, with preprocessing for tokenization, padding, and vocabulary creation.
- **Evaluation**: BLEU scores to measure caption quality.

---

## 📊 **Results**
- **BLEU Score**: ~18.5 (baseline).
- Demonstrated ability to generate grammatically correct captions, with room for improvement on complex scenes.

---

## 🔍 **Future Directions**
- Scale to larger datasets (e.g., Flickr30k, MS COCO).
- Explore metrics like METEOR or CIDEr for contextual evaluation.
- Integrate advanced spatial encodings for improved scene understanding.

---

## 🛠 **Technologies**
- Python, PyTorch, Google Colab
- ResNet50, LSTM, Adaptive Attention
- BLEU Scoring, NLTK

---

## 📄 **For More Details**
Refer to the detailed project report: `SAT Report.pdf`.

---

## 📬 **Contact**
Developed by Rahul Vinay  
Reach out: [Your Email]