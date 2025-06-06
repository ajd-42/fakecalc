# 🧮 FakeCalc

This project creates a **fake Android Calculator app** for use in magic routines. It loads a fullscreen image that mimics the real Android calculator—untouchable, perfectly positioned, and visually identical. It also has a blinking cursor and vibrates whenever you tap anywhere on the screen, so it'll feel like you've really pressed a button.

👉 **[Launch the illusion](https://ajd-42.github.io/fakecalc)**  
*Optimized specifically for Google Pixel 9 Pro*

---

## ⚠️ Device Compatibility

This version is **custom-fit** to a Google Pixel 9 Pro.
Because of how Material You customizes the colors to match your background, you'll want to follow the steps below for replacing the screenshots with versions that match your phone.

---

## 🛠️ Want to Make Your Own?

Follow these steps to create a version tailored to your own device:

### 1. Take a Screenshot
- Open the Calculator app on your phone
- Make sure it shows a clean blinking cursor with no numbers
- Take a screenshot while the cursor is showing

### 2. Crop the Screenshot
- Open the image in **Photos → Edit**
- Crop off the **top status bar** (time, battery, etc.) and the **bottom gesture/navigation bar&&
- Save the image as `calc-zero-cursor.png`
- In your preferred image editor, paint out the cursor (so that everything else aligns exactly the same)
- Save the image as `calc-zero.png`

### 3. Update the background color
- In [`index.html`](https://raw.githubusercontent.com/ajd-42/fakecalc/main/index.html) lines 11 and 21, update the color (currently `#f2dfda`) to what you want the top status bar to have behind it (you can use [this tool](https://photoaid.com/en/tools/eyedropper) to grab color of the status bar from your pre-cropped screenshot)

### 4. Use This Repo as a Template
- Download or fork this repository  
- [Click here to view the current `index.html`](https://raw.githubusercontent.com/ajd-42/fakecalc/main/index.html)
- Replace `calc-zero.jpg` with your own cropped screenshot
- Optionally update the `index.html` file to tweak any styling if needed

### 4. Host It
- Create a free GitHub account (if you don’t have one)
- Upload your image and HTML file into a repository
- In your repo, go to **Settings → Pages**
- Choose:
  - Source: `main`
  - Folder: `/ (root)`
- Save and wait a minute for your GitHub Pages site to go live  
  → You’ll get a link like: `https://yourusername.github.io/yourproject`

---

### 5. Add to Home Screen

To complete the illusion and make the fake app indistinguishable from the real one:

1. Open your GitHub Pages site in **Safari**
2. Tap **Share → Add to Home Screen**
3. Rename the app to: **Calculator**
4. Tap **Add**

> 🧠 The Calculator icon (`calc-icon.png`) is already included in this project. When you add it to your Home Screen, Safari will automatically use it as the app icon—no extra steps required.



Want to switch to the **real Calculator app** mid-performance?

Try:
- Setting up a **Shortcut** that opens Calculator
- Trigger it with a Back Tap, triple-click of the Side Button (via Accessibility Shortcut), or the Action Button (on supported models)
- Result: you flip the phone face-up… and the prediction is already there. 🔥

---

## 🙏 Credits

This project was created by [andyjermann](https://github.com/andyjermann) and updated for android by [ajd-42](https://github.com/ajd-42) 
