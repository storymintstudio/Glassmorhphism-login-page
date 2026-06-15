# 🌌 Glassmorphism Login Page

A stunning dark-themed login page with a galaxy background, frosted glass card, and smooth micro-interactions — built in pure HTML & CSS with minimal JavaScript.

-----

## ✨ Live Preview

> Galaxy background → Frosted glass card → Smooth interactions

-----

## 🎨 Design Highlights

|Element         |Detail                                                         |
|----------------|---------------------------------------------------------------|
|**Background**  |Deep space nebula with CSS-only twinkling stars & floating orbs|
|**Glass Card**  |`backdrop-filter: blur(24px)` with purple-blue top glow        |
|**Inputs**      |Floating label animation on focus                              |
|**Button**      |Purple → Blue gradient with hover lift effect                  |
|**Google Login**|Real Google logo colors                                        |
|**Password**    |Show / Hide toggle                                             |

-----

## 🛠️ Built With

- HTML5
- CSS3 — backdrop-filter, keyframe animations, radial-gradient
- Vanilla JavaScript — password toggle only
- Google Fonts — Syne (headings) + Inter (body)

-----

## 🎨 Design Tokens

```css
--bg:           #05050f;
--nebula-1:     #1a0638;
--nebula-2:     #0a1a4a;
--glass:        rgba(255, 255, 255, 0.04);
--border:       rgba(255, 255, 255, 0.10);
--accent-1:     #7c3aed;   /* violet */
--accent-2:     #2563eb;   /* blue   */
--glow:         rgba(124, 58, 237, 0.35);
```

-----

## 🚀 How to Use

1. Clone or download this repository
1. Open `index.html` in your browser
1. Customize colors, logo, and copy to match your project

-----

## 🔑 Core CSS — Glass Effect

```css
.card {
  background: rgba(255, 255, 255, 0.04);
  backdrop-filter: blur(24px);
  -webkit-backdrop-filter: blur(24px);
  border: 1px solid rgba(255, 255, 255, 0.10);
  border-top-color: rgba(255, 255, 255, 0.18);
  border-radius: 24px;
  box-shadow:
    0 40px 80px rgba(0, 0, 0, 0.5),
    inset 0 1px 0 rgba(255, 255, 255, 0.1);
}
```

-----

## 🔑 Core CSS — Floating Label

```css
.field label {
  position: absolute;
  left: 16px;
  top: 50%;
  transform: translateY(-50%);
  transition: all 0.2s cubic-bezier(0.4, 0, 0.2, 1);
}

.field input:focus + label,
.field input:not(:placeholder-shown) + label {
  top: 10px;
  transform: translateY(0);
  font-size: 10px;
  color: rgba(160, 100, 255, 0.9);
}
```

-----

## 📁 Folder Structure

```
glassmorphism-login/
│
├── index.html      ← main file
└── README.md       ← you are here
```

-----

## 🤝 Credits

- First draft generated with **Claude AI**
- Customized & crafted by **Storymint Studio**

-----

## 📸 Follow for more UI components

**Instagram:** [@storymint.studio](https://instagram.com/storymint.studio)
**GitHub:** [storymint-shivani](https://github.com/storymint-shivani)

-----

*Your login page is boring. Here’s the glow up. 🌌*
