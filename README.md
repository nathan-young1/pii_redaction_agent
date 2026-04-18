# Blog Companion Repository

This repository accompanies the blog post **“PII (Personal Identifiable Information) Redaction with Qwen 3.6 on Jozu Rapid Inference Container”** and contains a medical_pii_sample PDF and Jupyter notebook (`main.ipynb`) that contains the comands and examples demonstrated in the article.

The goal of this repo is **reproducibility**: if you follow both the blog and notebook, you will be able to install the required tooling, pull the 1-bit quantized Qwen 3.6 from huggingface, package it as a ModelKit using KitOps, upload to Jozu Hub and run the model for PII redaction with Jozu Rapid Inference Container (RICs).

---

## 📁 Repository Structure

```text
.
├── .gitignore
├── README.md
├── main.ipynb        # Commands & Examples shown on the blog
├── medical_pii_sample.pdf