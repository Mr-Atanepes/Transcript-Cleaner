# Transcript-Cleaner 🧹✨

[![License: MIT](https://shields.io)](https://opensource.org)
[![GitHub Pages](https://shields.io)](https://mr-atanepes.github.io/Transcript-Cleaner/)

**Transcript-Cleaner** is a lightweight, privacy-focused client-side web application designed to instantly strip timestamps, metadata, and systemic clutter from video and audio caption files. 

The primary goal is to deliver clean, highly readable text optimized for direct, friction-free pasting into Large Language Models (LLMs) like ChatGPT, Claude, or Gemini in just one click.

🚀 **Live Demo:** [Launch Transcript-Cleaner](https://mr-atanepes.github.io/Transcript-Cleaner/)

---

## 💡 Why Transcript-Cleaner?

When feeding YouTube transcripts, `.srt`, or `.vtt` caption tracking files into AI assistants, formatting characters like `-->` arrows, sequential line numbers, and microsecond timestamps waste precious context window tokens. 

This tool intelligently formats the text structure on-the-fly, stripping structural text artifacts without altering the underlying narrative or dialogue text.

## 🔥 Key Features

- **Multi-Format Processing:** Full out-of-the-box support for raw copy-pasted text, `.txt`, `.srt`, and `.vtt` file uploads.
- **Granular Cleaning Rules:** Toggle individual constraints depending on your preferred AI parsing format:
  - Remove all timestamps (e.g., `00:00:00.000` or `[00:00]`).
  - Collapse multiple blank lines for structural tightening.
  - Strip SRT/VTT technical metadata, syntax headers (`WEBVTT`), and structural block markers.
- **Paragraph Merger:** Intelligently combines broken subtitle lines into unified, fluid paragraph chunks.
- **One-Click Actions:** Instant clipboard copy and instant file download mechanisms.
- **Live Utility Metrics:** Dynamic counting panels that instantly showcase total lines removed, active word count tracking, and your overall size reduction percentage.
- **100% Client-Side:** Processes everything directly in the browser using raw, native Web API capabilities. Zero sign-ups required, zero data sent to external servers.

---

## 🛠️ Tech Stack & Architecture

To maintain zero deployment dependencies and instantaneous runtime speeds, this utility is built entirely on native web foundations:

- **Frontend Interface:** Semantic HTML5 structurally styled with responsive CSS3 layouts.
- **Core Processing Engine:** Vanilla JavaScript (ES6+) leveraging safe Client-Side File Reader APIs. No heavy external state libraries, layout frameworks, or Node modules required.

---

## 📦 Getting Started & Local Development

Because this application relies strictly on standard web languages, setting up a local development environment takes seconds.

### Prerequisites

You only need an up-to-date modern web browser (Chrome, Firefox, Safari, Edge).

### Running Locally

1. Clone the repository to your workstation:
   ```bash
   git clone https://github.com
   ```

2. Access the target workspace directory:
   ```bash
   cd Transcript-Cleaner
   ```

3. Launch the project layout:
   - Double-click the `index.html` file to open it directly in your browser.
   - *Alternative:* Serve it locally using your preferred development server extension or python module:
     ```bash
     python -m http.server 8000
     ```
     Then navigate to `http://localhost:8000` in your web browser.

---
## 🧪 Quick Test (Try it out!)

Want to see how it works instantly? You don't need to hunt for your own transcript file. We have provided a sample tracking file directly in this repository.

1. **Download the sample file:** Right-click [📥 transcript.txt](transcript.txt) and select **"Save Link As..."** to save it to your computer.
2. **Open the web app:** Head over to the [Live Demo](https://github.io).
3. **Drop it in:** Drag and drop that `transcript.txt` file straight into the upload area to see the timestamps and technical metadata disappear instantly!

## 🤝 Contributing

Contributions to further enhance processing filters or add new utility features are welcome! Feel free to branch out or tweak execution models:

1. Fork the Project Repository.
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes locally (`git commit -m 'Add some AmazingFeature'`).
4. Push your working branch back up (`git push origin feature/AmazingFeature`).
5. Open a formal Pull Request for review.

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
