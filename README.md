# 🏫 School Chatbot - Llama-3 (8B) Fine-Tuning

A fine-tuned **Llama-3 8B** model built using **Unsloth** to serve as an intelligent, context-aware AI assistant for school inquiries. The model is trained on a custom Q&A dataset covering admissions, fee structure, timings, facilities, and general school policies.

---

## 📌 Project Overview

* **Base Model:** Meta Llama-3 (8B)
* **Framework / Libraries:** Unsloth, Hugging Face Transformers, TRL (SFTTrainer), PyTorch
* **Fine-Tuning Technique:** QLoRA (4-bit quantization for efficient GPU memory usage)
* **Hardware Environment:** Google Colab (Tesla T4 GPU)
* **Dataset Size:** 40+ curated, school-specific Q&A pairs

---

## 🛠️ Key Features

* **Custom Domain Knowledge:** Accurately answers school-related queries regarding admissions, curriculum, extra-curriculars, and administrative policies.
* **Efficient Fine-Tuning:** Optimized using Unsloth for faster training speed and low VRAM usage.
* **Interactive UI:** Supports inference and chat interface testing via Gradio.

---

## 🚀 How to Run in Google Colab

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/hchouhan900/llama3-custom-finetuning.git](https://github.com/hchouhan900/llama3-custom-finetuning.git)
   cd llama3-custom-finetuning