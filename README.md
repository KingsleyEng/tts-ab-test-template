# Real vs TTS Listening Test Platform

A web-based perceptual evaluation tool built for my Master's dissertation.  
The system presents randomized **Top/Bottom** pairs of speech samples (real human recordings vs text-to-speech) and collects participant judgments.

---

## ✨ Features

- **Randomised presentation order** (Top/Bottom) to remove bias.  
- **Forced-choice response**: participant selects “Top”, “Bottom”, or “Not sure”.  
- **Correctness auto-computed** based on hidden ground truth.  
- **Google Sheets integration** via Apps Script — results stream directly to a central sheet.  
- **Participant CSV backup** downloads automatically.  
- **Works in-browser**: no installs, just open the link.  
- **Deployed via GitHub Pages** for easy access.

---

## 📂 Project Structure

index.html # main experiment
audio/real/ # real human speech files
audio/fake/ # synthesised TTS files
