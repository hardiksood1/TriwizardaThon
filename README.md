<h1 align="center"> Product Image Intelligence (Multi-language)</h1>
<blockquote align="center"><em>"AI that sees, understands, and speaks your product—instantly."</em></blockquote>


<p align="center">

<img src="https://img.shields.io/badge/python-pink?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/gradio-red?style=for-the-badge&logo=gradio&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenAI-white?style=for-the-badge&logo=openai&logoColor=black"/>
<img src="https://img.shields.io/badge/NVIDIA-blue?style=for-the-badge&logo=nvidia&logoColor=white"/>
<img src="https://img.shields.io/badge/Google%20Cloud-black?style=for-the-badge&logo=googlecloud&logoColor=white"/>
<img src="https://img.shields.io/badge/SerpAPI-orange?style=for-the-badge&logo=google&logoColor=white"/>
<img src="https://img.shields.io/badge/Google%20Translate-pink?style=for-the-badge&logo=googletranslate&logoColor=white"/>
<img src="https://img.shields.io/badge/Pillow-red?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Requests-white?style=for-the-badge&logo=python&logoColor=black"/>
<img src="https://img.shields.io/badge/JSON-blue?style=for-the-badge&logo=json&logoColor=white"/>
<img src="https://img.shields.io/badge/VSCode-orange?style=for-the-badge&logo=visualstudiocode&logoColor=white"/>

</p>

<p align="center">
  <img src="https://github.com/alo7lika/TriwizardaThon/blob/main/demo%20(1).jpeg?raw=true" alt="Demo Image" width="600"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=FF69B4&size=40&width=900&height=80&lines=Welcome-to-Product-Image-Intelligence" alt="Welcome to Product Image Intelligence"/>
</p>

Welcome to a powerful AI tool that analyzes product images and automatically generates:

-  Brand  
-  Title & Description  
-  Key Features  
-  Price Comparisons  
-  Similar Product Suggestions  
-  Translations in multiple languages

---
##  Demo Preview

See how our AI extracts product info, translates it, and compares prices — all from a single image!

<p align="center">
  <img src="https://github.com/alo7lika/TriwizardaThon/blob/main/Demo.gif" alt="Product Image Intelligence Demo"/>
</p>

---


##  What’s Inside

This application converts any product image into a detailed, multilingual product card—perfect for e-commerce, cataloging, and digital retail platforms.

---

## 🌟 Features Overview

| Feature                     | Description                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| 🖼️ Image Upload            | Upload a product image to extract all product details                       |
| 🧠 AI-Powered Metadata      | Uses NVIDIA's model via cloud to understand product visuals          |
| 🌍 Multi-Language Support   | Translate output into English, Hindi, French, and more                      |
| 🛒 Price & Product Compare  | Uses SerpApi to fetch prices and similar products from Google Shopping      |
| 🖥️ Gradio UI                | Simple, no-code web interface for fast interaction                          |

---

## ⚙️ Tech Stack

- Python 3.7+
- Gradio (Frontend)
- Hugging Face Transformers
- NVIDIA model
- SerpApi (Google Shopping API)
- PIL (Image Processing)
- CUDA acceleration (for local GPU inference)

---

## 🚀 Quick Start

```bash
# 1. Clone the repo
git clone https://github.com/your-username/product-image-intelligence

# 2. Navigate to the folder
cd product-image-intelligence

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the app
python app.py
```
## ✅ How to Use

1. Open the **Gradio link** in your browser  
2. 📤 Upload a **product image**  
3. 🌐 Select your desired **language**  
4. 👀 View the AI-generated output:  
   - Brand  
   - Title  
   - Description  
   - Features  
   - Price comparisons & similar products  

---
## 📁 Project Structure

```
Product-Image-Intelligence/
│
├── Dataset/
│   ├── demo(1).jpg           (Example data of product image inputs and outputs)
│   └── README.md                   (Brief about input/output dataset structure)
│
├── Images/
│   ├── demo (1).jpeg and  demo (2).jpeg            (Product image example used in demo)
│   └── Demo.gif                                   (Recorded GIF preview of the app functionality)
│
├── Model_files/
│   ├── core_logic.py              (Handles AI: image-to-text, translation, product comparison)
│   ├── config.py                  (Stores API keys and endpoints: NVIDIA, SerpAPI)
│
├── WebAppfiles with demo/
│   ├── app.py                     (Gradio app interface to run the project)
│   ├── demo.mp4                   (Full working video demo of the app)
│
├── requirements.txt              (Python dependencies for the whole project)
└── README.md                     (Main project overview with badges, contributors, and demo)

```
---

## 🧪 Example Flow

- **Upload**: Headphones image  
- **Select**: French  
- **Output**:

Marque: Sony
Titre: Casque sans fil
Description: Son immersif avec réduction de bruit
Prix: ₹2999 (plus similar products listed)


➡️ Then try again with a **beauty product** → Output appears in **Hindi**!

---

## 📝 Notes

Make sure your `config.py` contains:

- `NVIDIA_API_KEY`  
- `SERPAPI_KEY`  
- `NVIDIA Cloud URL`  

⚠️ Images are **auto-compressed** to meet API size limits  
🌍 English is the **default output language** unless changed

---

## 🚧 Coming Soon

- 🔊 **Voice input/output**  
- 📄 **Export to Excel/PDF**  
- 🛒 **Integration with Shopify / Amazon APIs**  
- 🌐 **More language support** (Spanish, German, Bengali, etc.)

---

## 👨‍💻 Created by **Team Innova1**

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/hardiksood1">
        <img src="https://github.com/hardiksood1.png" width="100px;" alt="Hardik Sood"/><br />
        <sub><b>Hardik Sood</b></sub>
      </a><br />⚙️
    </td>
    <td align="center">
      <a href="https://github.com/alo7lika">
        <img src="https://github.com/alo7lika.png" width="100px;" alt="Alolika Bhowmik"/><br />
        <sub><b>Alolika Bhowmik</b></sub>
      </a><br />🎨
    </td>
  </tr>
</table>


Made with ❤️ for smarter, faster, and multilingual e-commerce automation.

📧 **Contact**: hardiksood8@gmail.com, alolikabhowmik72@gmail.com

🌐 **Live Demo**: *Uploaded above*
