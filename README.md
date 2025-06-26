# 1. 🧾 AI Invoice Parser with Gemini

This project extracts structured data from invoices (PDFs and images) using **Google Gemini 2.0**, **Pydantic** for schema enforcement, and a simple **Gradio web interface** for interaction and visualization.  
It was developed in **Google Colab** for rapid prototyping and is easily transferable to production environments.

---

## 🚀 Features

- ✅ Upload invoices in PDF or image format
- ✅ Automatically extract fields like invoice number, items, customer & business info, tax, and total
- ✅ Structured output using `Pydantic` JSON schemas
- ✅ Interactive UI built with `Gradio`
- ✅ Easily extendable to other document types

---

## 📦 Tech Stack

| Tool       | Purpose                         |
|------------|----------------------------------|
| `google-genai` | Connects to Gemini 2.0 API     |
| `pydantic`     | Defines and enforces output schema |
| `gradio`       | Builds the web interface       |
| `Google Colab` | Rapid prototyping environment  |

---

## 🧠 How It Works

1. **Upload the invoice** using the Gradio interface or via file path
2. **Gemini 2.0** receives the file and prompt, and returns a structured response
3. **Pydantic** parses the output and validates the structure
4. **Gradio** displays the JSON result interactively

## 📊 Dataset

Testing was done using real invoice formats from Roboflow Universe

## 🔐 API Access
1. Go to https://aistudio.google.com
2. Click “Get API Key” (top left)
3. Add the key to your environment (e.g., Colab secrets or .env)

# 2. 📄 AI Proposal for VERSO

The proposal includes:
- ✅ Strategic use cases (invoice parsing, regulatory compliance, etc.)
- ✅ LLM system architecture
- ✅ Tech stack recommendations


