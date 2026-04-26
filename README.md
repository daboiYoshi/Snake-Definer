# 🐍 Snake Definer

A sleek, minimalist, and "free forever" English Dictionary and Thesaurus web application. Built for speed and simplicity, **Snake Definer** provides instant definitions, pronunciations, and synonyms without the need for API keys or accounts.

## ✨ Features

- **📖 Dual Mode:** Seamlessly switch between **Dictionary** and **Thesaurus** views.
- **🌗 Smart Dark Mode:** A premium visual interface that adapts to your preference, featuring a smooth emerald-accented palette.
- **🔊 Instant Pronunciation:** Integrated text-to-speech (TTS) and native audio playback for learning how to speak words correctly.
- **🧠 Typo Correction:** Built-in fuzzy search logic that suggests the correct spelling if you make a mistake.
- **⚡ Zero Configuration:** Powered by the [Free Dictionary API](https://dictionaryapi.dev/), requiring no setup or API keys.
- **📱 Responsive Design:** Fully optimized for desktop and mobile browsing.

## 🚀 Quick Start

Since **Snake Definer** is a single-file web application, you don't need to install anything.

1.  Download the `snake_definer.html` file.
2.  Open it in any modern web browser (Chrome, Firefox, Safari, Edge).
3.  Type a word and hit **Define**.

## 🛠️ Built With

- **HTML5 & CSS3:** Custom CSS variables for the dynamic theme engine and CSS animations for the signature "slither" loading state.
- **Vanilla JavaScript:** ES6+ logic for API fetching and UI state management.
- **Free Dictionary API:** Reliable backend for word definitions, phonetics, and synonyms.

## 🎨 Customization

The application uses a robust CSS variable system. You can easily modify the primary colors by editing the `:root` and `body.dark` blocks in the `<style>` section:

```css
:root {
    --accent: #10b981; /* Emerald Green */
    --bg: #f8fafc;     /* Light Slate */
}
