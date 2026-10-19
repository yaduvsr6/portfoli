# Yadukrishna V — Cybersecurity & Ethical Hacking Portfolio

A modern, responsive personal portfolio website with a **black and neon red hacking aesthetic**, engineered specifically for **Yadukrishna V** — Final-year B.Tech Computer Science and Engineering student specializing in **Cybersecurity and Ethical Hacking**.

---

## 🎨 Theme & Visual Design Specifications

- **Background**: Pure Black (`#050505`) and Dark Charcoal (`#0d0d0d`).
- **Primary Accent**: Neon Red (`#ff003c`) with subtle glowing shadows (`rgba(255, 0, 60, 0.35)`).
- **Secondary Accent**: Crimson Red (`#b30021`).
- **Text Hierarchy**: White (`#f5f5f5`) for high contrast readability and Muted Gray (`#a0a0a0`) for body descriptions.
- **Typography**: `Inter` for clean body text, `JetBrains Mono` / `Fira Code` for terminal & code text.
- **Visual Features**:
  - Matrix digital stream background (Canvas) with low opacity.
  - Cyber grid background overlay with subtle ambient red lighting.
  - Cyber terminal window framing Yadukrishna's portrait photo with scanline and status diagnostics.
  - Dynamic typing animation cycling through:
    `"Cybersecurity Enthusiast"`, `"Future Security Analyst"`, `"Digital Defender"`.
  - Accessible, keyboard-friendly navigation respecting `prefers-reduced-motion`.
  - Minimalized content without artificial hardware dashboards or inflated claims.

---

## 📁 File Structure

```
anniversary/
│
├── index.html       # Complete, semantic single-page portfolio (HTML5)
├── style.css        # Hacker-themed stylesheet (Black & Neon Red CSS3)
├── script.js        # Matrix canvas, terminal typing, scrollspy, mailto handler (Vanilla JS)
├── resume.html      # Clean printable/downloadable ATS-friendly resume
├── README.md        # Documentation and deployment manual
│
└── assets/
    └── yadukrishna.jpg   # Profile portrait photo
```

---

## 🚀 How to Run the Website Locally on Windows

### Option 1: Direct Double-Click (Zero Setup)
1. Open File Explorer and navigate to:
   ```
   C:\Users\yadus\Downloads\anniversary\
   ```
2. Double-click **`index.html`** to open it directly in Google Chrome, Microsoft Edge, or Mozilla Firefox.

### Option 2: Using Built-in Python Server (Recommended)
1. Open PowerShell or Command Prompt in the project folder:
   ```powershell
   cd C:\Users\yadus\Downloads\anniversary
   ```
2. Run Python's built-in HTTP server:
   ```powershell
   python -m http.server 8000
   ```
3. Open your web browser and navigate to:
   ```
   http://localhost:8000
   ```
4. To view the printable resume:
   ```
   http://localhost:8000/resume.html
   ```

---

## 🌐 Step-by-Step Instructions: Publishing to GitHub Pages (100% Free)

Since your GitHub username is **`Yadukrishnasr4`**, you can host your portfolio for free with your custom subdomain:

### Step 1: Create a Repository on GitHub
1. Sign in to your GitHub account at [github.com](https://github.com).
2. Click the **+** (New Repository) icon in the top-right corner.
3. Name your repository exactly:
   ```
   Yadukrishnasr4.github.io
   ```
4. Set the visibility to **Public**.
5. Leave "Initialize with a README" unchecked, then click **Create repository**.

### Step 2: Push Your Local Files to GitHub
Open PowerShell in `C:\Users\yadus\Downloads\anniversary\` and execute:
```powershell
git init
git add .
git commit -m "Deploy modern cybersecurity portfolio"
git branch -M main
git remote add origin https://github.com/Yadukrishnasr4/Yadukrishnasr4.github.io.git
git push -u origin main
```

### Step 3: Verify Live Deployment
1. Go to your repository settings on GitHub:
   `https://github.com/Yadukrishnasr4/Yadukrishnasr4.github.io/settings/pages`
2. Under **Build and deployment**, ensure the source is set to `Deploy from a branch` and branch is `main` (`/root`).
3. Your website will be live worldwide in 1–2 minutes at:
   **`https://yadukrishnasr4.github.io/`**

---

## 🛠️ Where to Customize Your Information

All three files contain clear comments marking customizable sections:

| Item | File Location | Line / Tag |
|---|---|---|
| **Full Name** | `index.html` | `<h1 class="hero-name">` |
| **Email Address** | `index.html` & `script.js` | `yadukrishnasr4@gmail.com` |
| **GitHub URL** | `index.html` | `href="https://github.com/Yadukrishnasr4"` |
| **LinkedIn URL** | `index.html` | `href="https://www.linkedin.com/in/yadukrishna-v-855942273"` |
| **Photo** | `assets/yadukrishna.jpg` | Replace image file in `assets/` folder |
| **PDF Resume** | `assets/` | Place your PDF as `assets/resume.pdf` |
| **Project Links** | `index.html` | `// SECURITY_PROJECTS` section |
| **Certificates** | `index.html` | `// CREDENTIALS` section |

---

## 🔒 Content & Integrity Policy

- **No Fabrications**: No artificial job histories, fake metrics, or unconfirmed certifications.
- **Accurate Academic Status**: Explicitly frames projects as undergraduate research frameworks and lab exercises.
- **Client-Side Transparency**: Clearly discloses that the contact form generates a pre-filled transmission via the `mailto:` protocol without false claims of remote database storage.
