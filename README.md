# 🏫 School AI Assistant - Custom Llama-3 Fine-Tuning Pipeline

An end-to-end parameter-efficient fine-tuning (PEFT) pipeline using **Unsloth**, **LoRA**, and **Meta Llama-3 (8B)** to train a custom domain-specific chatbot for educational and school inquiry management.

---

## 🌟 Highlights & Features
- **4-bit Quantization:** Memory-efficient training optimized for consumer/free-tier GPUs (Google Colab T4).
- **Parameter-Efficient Fine-Tuning (PEFT):** Utilized **LoRA (Low-Rank Adaptation)** adapters to adapt Meta's Llama-3 (8B) model to specialized school domain QA.
- **Fast Training with Unsloth:** Achieved faster convergence and lower memory consumption during training.
- **Interactive Chat Interface:** Deployed a web interface using **Gradio** for real-time model interaction.

---

## 🛠️ Tech Stack & Libraries
- **Base Model:** Meta Llama-3 (8B / 8B-Instruct)
- **Frameworks:** PyTorch, Hugging Face Transformers
- **Fine-Tuning Toolkit:** Unsloth, PEFT, `bitsandbytes`, `trl`
- **UI & Deployment:** Gradio

---

## 📂 Project Structure
```text
.
├── school_chatbot.ipynb   # Main Google Colab Jupyter Notebook containing the full training pipeline
└── README.md              # Project documentation