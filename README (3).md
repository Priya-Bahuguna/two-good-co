
# Two Good Co. – Website Clone

This is a visually-rich, interactive clone of the [Two Good Co.](https://twogood.com.au) website, built as a frontend project using modern web technologies like HTML5, CSS3, JavaScript, GSAP, and Locomotive Scroll.

## 🔥 Features

- Smooth scroll animations with [Locomotive Scroll](https://github.com/locomotivemtl/locomotive-scroll)
- Custom cursor interaction
- Animated text and image sections using [GSAP](https://greensock.com/gsap/)
- Responsive layout for both desktop and mobile
- Click-to-expand overlays on products
- Integrated video with custom hover `PLAY` button
- Section-based scrolling for easy storytelling

## 🚀 Live Preview

> _(Add GitHub Pages link here once deployed)_  
> Example: [Live Demo](https://priya-bahuguna.github.io/two-good-co)

## 📁 Project Structure

```
├── index.html
├── style.css
├── script.js
├── video.mp4         ← Optional local video
├── .gitattributes     ← Enables Git LFS for large files
└── README.md
```

## 📸 Screenshots

| Desktop Version | Mobile Version |
|-----------------|----------------|
| ![Image](https://github.com/user-attachments/assets/148c7cbd-f141-4637-bb11-030d04e582ed) | ![Image](https://github.com/user-attachments/assets/665d64fb-7eaa-456c-9ad2-4c65ce494b42) |

## 🛠️ Tech Stack

- HTML5
- CSS3 (custom fonts: Futura, Gilroy)
- JavaScript (Vanilla)
- GSAP for animations
- Locomotive Scroll for smooth scrolling
- Google Fonts and RemixIcon for styling

## 📦 Requirements

- Modern browser (Chrome, Firefox, Safari)
- Internet connection (for CDN assets like GSAP, fonts)

## 🧠 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/Priya-Bahuguna/two-good-co.git
   cd two-good-co
   ```

2. (Optional) If using Git LFS for large video:
   ```bash
   git lfs install
   git lfs pull
   ```

3. Open `index.html` in your browser.

## 🎥 Video Integration Notes

If you want to use your own `.mp4` video, place it in the root folder and update this tag in `index.html`:

```html
<video autoplay muted loop playsinline>
  <source src="video.mp4" type="video/mp4">
</video>
```

## 📄 License

This is a personal educational project and is **not** affiliated with or endorsed by [Two Good Co.](https://twogood.com.au). For inspiration and learning purposes only.

---

