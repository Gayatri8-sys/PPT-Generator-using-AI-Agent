# 🎨 AI-Powered PPT Generator

Generate professional and visually appealing PowerPoint presentations automatically using AI! This project leverages **Gemini API** for content generation and **Pexels API** for relevant images. Perfect for students, professionals, and content creators.

---

## 🚀 Features
- Generate **slides automatically** based on any topic.
- Add **relevant images** to content slides.
- Customizable **themes and colors**.
- Automatic creation of **title, content, image, and conclusion slides**.
- Save your presentation as a ready-to-use `.pptx` file.

---

## 📝 Example
I’ve generated a PPT about **"Benefits of Work From Home"** using this project.  
It includes title slides, content slides with bullet points, relevant images, and conclusion slides.

---

## 💡 How It Works
1. Provide your **Gemini API Key** (for AI content generation) and **Pexels API Key** (for images).  
2. Run the `PPTGenerator` class.  
3. Input your topic and number of slides.  
4. The PPT is generated and saved as `presentation.pptx`.

---

## ⚙️ Usage
```python
from ppt_generator import PPTGenerator

gemini_key = "YOUR_GEMINI_API_KEY"
pexels_key = "YOUR_PEXELS_API_KEY"

ppt = PPTGenerator(gemini_api_key=gemini_key, pexels_api_key=pexels_key)
ppt.generate_presentation("Benefits of Work From Home", num_slides=10, output_file="WorkFromHome.pptx")
