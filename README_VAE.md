# 🧠 Variational Autoencoder (VAE) with Keras

This project demonstrates the implementation of a Variational Autoencoder (VAE) using TensorFlow/Keras. A VAE is a type of generative model that learns a probability distribution over a dataset and can generate new samples similar to the training data.

---

## 📂 Project Structure

```
├── Lecture_31_Variational_Auto_Encoder.ipynb  # Jupyter notebook with full implementation
├── README.md                                  # Project documentation
├── requirements.txt                           # Python dependencies
```

---

## 🔍 Features

- Implementation of the encoder and decoder networks
- Latent space sampling using the reparameterization trick
- Loss function combining reconstruction loss and KL divergence
- Training on image data (e.g., MNIST)
- Visualization of original vs. reconstructed images
- Generation of new samples from the latent space

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/vae-keras.git
cd vae-keras
```

### 2. Install Dependencies

Ensure you have Python 3.7+ installed, then run:

```bash
pip install -r requirements.txt
```

### 3. Run the Notebook

```bash
jupyter notebook Lecture_31_Variational_Auto_Encoder.ipynb
```

---

## 📊 Results

The notebook includes side-by-side plots of original and reconstructed images, along with samples generated from the latent space.

---

## 🛠 Dependencies

- Python 3.7+
- TensorFlow / Keras
- NumPy
- Matplotlib

All packages are listed in `requirements.txt`.

---

## 🧾 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

This project is inspired by academic and practical resources on generative models, particularly VAEs using TensorFlow and Keras.
