# 🎥 n8n AI Short-Form Video Generator

An automated workflow built with **n8n** that transforms a simple idea into a fully produced short-form video, ready for **TikTok**, **YouTube Shorts**, and **Instagram Reels**.

---

## ✨ Features

- 🚀 **Idea to Video Automation** – Generate a complete short-form video from just a topic.
- 🎨 **Multiple Video Styles** – Minecraft, Pixar, animation, and more.
- 🗣 **Custom Voices** – Choose gender, language, nationality, and tone.
- 🧠 **AI-Powered Script Generation** – Titles, captions, hooks, and tags automatically structured.
- 🖼 **Automated Image & Video Creation** – AI-generated visuals with animation.
- 🎙 **Text-to-Speech & Captions** – Automatic voiceover and synced subtitles.
- 🎵 **Music Integration** – Add background music automatically.
- 🗄 **Database Integration** – Every step is saved and managed in a database.
- 🔮 **Planned Features** – Auto-publishing, quality ratings, trend analysis, and more.

---

![image](https://i.imgur.com/GOJDLVf.png)

## 🛠 Workflow Overview

### **1. User Input**
- Ask user for:
  - **Video topic**
  - **Video style** (e.g., Minecraft, Pixar, animation)
  - **Voice settings** (male/female, language, nationality, tone)

---

### **2. Structured JSON Creation**
- Convert user input into **pre-defined JSON format** (prevents hallucination).
- JSON contains:
  - Topic
  - Style
  - Voice settings
  - AI constraints
- AI generates:
  - **Title**
  - **Caption/Narration text**
  - **Tags**
- AI output is **split into sections**:
  - 🎯 **Hook** (attention-grabber)
  - 📖 **Body**
  - 🏁 **Outro**
- Each section gets **suggested images**.
- **Paid AI models** → faster & more accurate (no hallucinations).

---

### **3. Database Storage**
- Cleaned and structured data saved to the database.

---

### **4. Text-to-Speech & Captions**
- Generate **voiceover audio**.
- Create **captions/subtitles**.
- Save both into database.

---

### **5. Image Generation**
- AI generates images from **suggested visuals** per section.
- 6–12 images typical (depends on video length).
- **Paid AI** → higher quality & faster.
- Store images in database.

---

### **6. Animation**
- Animate generated images into short video segments.
- Save animations to database.

---

### **7. Video Assembly**
- Combine all animated segments into one video.

---

### **8. Audio & Captions Integration**
- Overlay voiceover and captions onto video.

---

### **9. Background Music**
- Add trending background music automatically.

---

### **10. Final Output**
- Save completed video as **final outcome**.
- Mark project status as **complete ✅**.

---

## 🔜 Planned Features

- **Automatic Uploading**
  - Auto-publish to TikTok, YouTube Shorts, Instagram with:
    - Optimized titles  
    - Trending background music  
    - Hashtags and tags

- **Quality Rating & Trend Analysis**
  - Analyze trending videos for inspiration
  - Rate content quality & engagement
  - Optimize posting times for max reach

---

## 🧰 Tech Stack

- **n8n** – Workflow automation  
- **AI Models** – Script, images, and TTS generation  
- **Database** – Stores scripts, images, audio, final videos  
- **Text-to-Speech** – Voice generation  
- **Animation Engine** – Image-to-video conversion  
- **Music API** – Background music integration  

---

## 📌 Status

- Core workflow: **Completed**  
- Auto-upload feature: **In development**  
- Trend analysis & rating: **Planned**

---

## 🤝 Contributing

Contributions are welcome!  
- Open issues for bugs or feature requests  
- Submit pull requests with improvements  

---

## 📜 License

MIT License
