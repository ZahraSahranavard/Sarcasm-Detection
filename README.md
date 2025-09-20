# 🤖 Sarcasm Detection Using Deep Learning
![Sarcasm Detection](https://github.com/ZahraSahranavard/Sarcasm-Detection/blob/main/Image/Sarcasm%20Detection.png)

## 📖 Overview
This project implements a **deep learning pipeline for detecting sarcasm in in texts** using **pre-trained word embeddings (GloVe)** and **Bidirectional LSTM networks**. The model classifies headlines as sarcastic or non-sarcastic, showcasing applications of **NLP** and **sequence modeling** in text analysis.

**⚠️ Project Status:**  
This is a **pilot project** in the field of **Natural Language Processing (NLP)** focused on sarcasm detection and is **still in progress**.  
I'm currently working on **improving the accuracy** of the model.  
If you have experience in NLP or related areas, I would greatly appreciate your **input and collaboration**.

## 🛠️ Tech Stack

- **Python**  
- **TensorFlow / Keras** → Model building and training  
- **NLTK** → Text preprocessing (stopwords removal)  
- **GloVe embeddings** → Pre-trained word vectors  
- **Matplotlib** → Visualization of training history

##  📊 Model Architecture

- Embedding Layer: Pre-trained GloVe embeddings (100D, non-trainable)

- Bidirectional LSTM: Two layers (128 & 64 units) with dropout and recurrent dropout

- Dense Layer: 32 units with ReLU activation and L2 regularization

- Output Layer: Single neuron with sigmoid activation for binary classification
  
## 🔮 Future Work

- Focus on **improving model accuracy** by experimenting with different architectures and hyperparameters.  
- Explore **transformer-based models** (e.g., BERT, RoBERTa) to better capture context and long-range dependencies in text.  
- Expand the dataset or apply **data augmentation** to enhance generalization.  
- Potentially deploy the model as a **real-time web application** for sarcasm detection.
  
## 📜 License
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
