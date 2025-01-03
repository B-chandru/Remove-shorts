# **YouTube Reels Remover**

A Chrome extension that dynamically removes YouTube Reels (Shorts) from the homepage and allows real-time styling changes using a CSS file. This extension enhances your YouTube experience by decluttering the interface and focusing on the content that matters to you.

## **Installation**
1. Clone or download the repository:
   ```bash
   git clone https://github.com/B-chandru/Remove-shorts.git
   ```
![image](https://github.com/user-attachments/assets/52722f4c-350d-48f7-8e6e-e8d0e175ec30)

2. Open Google Chrome and navigate to `chrome://extensions/`.
![image](https://github.com/user-attachments/assets/76f25d56-18b7-4223-b95e-488a001d35fd)

3. Enable **Developer mode** in the top-right corner.
![image](https://github.com/user-attachments/assets/92bdfc2f-eb2b-4361-ad68-6738426e726a)

4. Click **Load unpacked** and select the project folder.

5. The extension will now be loaded and active.
![image](https://github.com/user-attachments/assets/52a3e60c-9a74-426e-b606-46a9dca24170)


---

## **Usage**
1. Visit [YouTube](https://www.youtube.com/).
2. The extension will automatically hide the "Shorts" section and apply custom styles to the page.
3. To modify the appearance:
   - Edit the `styles.css` file to add or update styles.
   - Reload the extension on `chrome://extensions/` for changes to take effect.

---

## **Project Structure**
```
youtube-reels-remover/
│
├── manifest.json       # Chrome extension configuration
├── main.css          # Custom styles to modify YouTube
├── images/              # Extension icons (16x16, 48x48, 128x128)
│   ├── icon16.png
│   ├── icon48.png
│   ├── icon128.png
└── README.md           # Project documentation
```

---

## **Contributing**
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your feature description"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request and describe your changes.

---

## **Acknowledgments**
- Thanks to [Google Chrome Extensions API](https://developer.chrome.com/docs/extensions/) for providing excellent resources.
- Inspired by the need for a cleaner YouTube experience.

---
