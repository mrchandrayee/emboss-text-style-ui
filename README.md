# Emboss Text Style UI

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://mrchandrayee.github.io/emboss-text-style-ui/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org) [![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

A complete responsive HTML/CSS recreation of the 12.5-second screen recording.

## Four text styles shown

1. **Soft Emboss** — subtle raised text with a light highlight and soft dark shadow.
2. **Deep Emboss** — stronger raised appearance with layered highlights and shadows.
3. **Debossed (Pressed Inward)** — recessed / pressed-in text.
4. **Metallic Emboss** — grey metallic lettering with crisp highlights and deep shadow.

## CSS visible in the recording

### Soft Emboss

```css
.emboss-soft {
  text-shadow:
    -1px -1px 2px rgba(255,255,255,.8),
     1px  1px 2px rgba(0,0,0,.2);
}
```

### Deep Emboss

```css
.emboss-deep {
  color: #c5cedd;
  text-shadow:
    -2px -2px 4px rgba(255,255,255,.9),
     2px  2px 4px rgba(0,0,0,.3),
    -1px -1px 0 rgba(255,255,255,.5),
     1px  1px 0 rgba(0,0,0,.2);
}
```

### Debossed

```css
.debossed {
  text-shadow:
     1px  1px 2px rgba(255,255,255,.8),
    -1px -1px 2px rgba(0,0,0,.3);
}
```

### Metallic Emboss

```css
.emboss-metal {
  color: #b0b5c0;
  text-shadow:
    -1px -1px 0 rgba(255,255,255,.7),
     1px  1px 0 rgba(0,0,0,.6),
    -2px -2px 5px rgba(255,255,255,.5),
     2px  2px 5px rgba(0,0,0,.5);
}
```

## Run locally

No dependencies or build step required.

```bash
python -m http.server 8000
```

Open http://localhost:8000

## Project structure

```text
emboss-text-style-ui/
├── index.html
├── style.css
└── README.md
```

## Accuracy note

The four style names, sample text, code snippets, grey-blue surface and dark code panels are based on the screen recording. The full page markup and surrounding neumorphic card styling are reconstructed to make a complete runnable project; this is not the original creator's verbatim source.

## 👨‍💻 Author

**mrchandrayee** · [GitHub](https://github.com/mrchandrayee)

## 📄 License

[MIT License](./LICENSE)
