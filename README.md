# Multi-Task Theological Distillation on Islamic Sermon Texts

This repository contains the official implementation and reproducibility pipeline for our paper. 

---

## 📝 Reproducibility and Audit Guidelines 

To ensure full transparency and compliance with open-science principles, the entire experimental pipeline—including automated weak supervision labeling, theological distillation via Maximum Marginal Relevance (MMR), and baseline benchmarking—has been fully externalized and automated. Reviewers can replicate our exact empirical tables by following the protocols below:

### 🔗 Artifact Repositories
* **Source Code Repository:** [GitHub Repository](https://github.com/irwanaja19/Sermon-MultiTask-NLP)
* **Remote Dataset Hub:** [Hugging Face Dataset](https://huggingface.co/datasets/irwan19/khutbah-balanced-v2)
* **Pre-trained Core Model:** [Hugging Face Model Hub](https://huggingface.co/irwan19/albertir-quran-hadith)

### 🚀 Step-by-Step Replication Protocol

1. **Access the Notebook:** Go to the GitHub source code repository listed above and click on the `reproducibility_pipeline.ipynb` file.
2. **Launch in Google Colab:** Click the **"Open in Colab"** badge displayed at the top of the notebook file to port the environment seamlessly into a cloud instance.
3. **Hardware Configuration (Crucial):** Before execution, change the hardware accelerator to a GPU instance. In the Google Colab top menu, navigate to **Runtime** $\rightarrow$ **Change runtime type**, select **T4 GPU** under Hardware Accelerator, and click **Save**.
4. **Execute the Pipeline:** Run all cells sequentially or click **Runtime** $\rightarrow$ **Run all**.
