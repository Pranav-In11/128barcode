# Modern Code-128 Barcode Generator

A minimal, single-file web application that generates 1D Code-128 barcodes in real-time. Designed with a **Khroma-inspired** aesthetic for a clean and modern user interface.

## 🚀 Features

* **Real-time Generation:** Barcodes update instantly as you type.
* **Format:** Supports Code-128 (standard for logistics and inventory).
* **Download:** Export barcodes as high-quality PNG images.
* **Zero Dependencies:** No build step required. Uses a CDN for the barcode library.
* **Responsive:** Works on desktop and mobile.

## 🛠️ Tech Stack

* **HTML5 & CSS3** (Custom CSS variables for easy theming)
* **JavaScript** (Vanilla ES6)
* **Library:** [JsBarcode](https://github.com/lindell/JsBarcode)

## 📦 How to Use

### Run Locally
1.  Clone the repository or download the ZIP.
2.  Open `index.html` in your web browser.
3.  That's it!

### Deploy to GitHub Pages
1.  Upload `index.html` to your GitHub repository.
2.  Go to **Settings** -> **Pages**.
3.  Under **Branch**, select `main` (or `master`) and click **Save**.
4.  Your site will be live at `https://<your-username>.github.io/<repo-name>`.

## 🎨 Customization (Khroma Colors)

You can easily change the color scheme by editing the CSS variables at the top of the `<style>` block in `index.html`.

```css
:root {
    /* Paste your Khroma hex codes here */
    --khroma-bg: #1a1a1a;        /* Background */
    --khroma-card: #ffffff;      /* Card color */
    --khroma-accent: #6366f1;    /* Button/Focus color */
    --khroma-text: #1f2937;      /* Text color */
}
