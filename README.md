# 🌐 Google Resonance Audio Spatializer

**Real-Time 3D Audio Spatialization in the Browser**  

This project enables lifelike **spatial audio rendering** directly on the web using **HRTFs**, **reverberation**, and **shoebox-style acoustic modeling**.  
Built on top of **Google’s Resonance Audio SDK** and the **Web Audio API**, it allows you to spatialize mono sound sources dynamically and hear the results in real time — right in your browser 🎶.  

---

## ⚙️ Installation & Setup

1. 📦 **Clone the Repository**  
   ```bash
   git clone https://github.com/<yourusername>/GoogleResonanceAudioSpatializer.git
   ```  
   Ensure the folder is named `GoogleResonanceAudioSpatializer`.

2. 💻 **Install Visual Studio Code**  
   Download from [code.visualstudio.com](https://code.visualstudio.com).

3. 🚀 **Open the Project**  
   - Launch **VS Code**  
   - Go to **File → Open Folder** → select your cloned repo  

4. 🔌 **Install “Live Server” Extension**  
   - In VS Code, open the **Extensions** tab  
   - Search for **Live Server** and install it  

5. 🧠 **Edit Parameters**  
   Modify `spatialise.js` to:  
   - Set the sound source  
   - Load trajectory data from a CSV file  
   - Adjust room properties (dimensions, wall materials, etc.)

6. 🌍 **Run the Demo**  
   - In the **Explorer** pane, right-click `demo.html` → **“Open With Live Server”**  
   - The demo will launch automatically in your default browser *(Chrome recommended)*  

7. 🧾 **Monitor & Debug**  
   - Right-click the webpage → **Inspect → Console**  
   - View real-time JavaScript logs and spatialization progress  

8. 🎧 **Hear It in Action**  
   - Click **“Click to Spatialize!”**  
   - Audio will play in real time with spatial cues applied  

9. 💾 **Download Results**  
   - Once processing finishes, click the generated `.wav` link to download your spatialized file  

---

## 🚀 Features

- 🔊 **HRTF-based binaural rendering** for realistic sound localization  
- 🏠 **Shoebox-room modeling** with controllable reverb and reflections  
- ⚡ **Real-time browser processing** — no external DAW required  
- 🧩 **JavaScript + Web Audio API** for full transparency and easy modification  
- 🎯 Built using **Google Resonance Audio SDK** for the Web  

---

## 💬 Feedback & Contributions

Open to feedback, creative extensions, and research-driven improvements!  
If you’d like to enhance realism (e.g., multi-listener setups, dynamic HRTF switching, or GPU-based processing), feel free to open an issue or PR.  

> ✉️ *Let’s push the boundaries of spatial audio — one waveform at a time!*  
