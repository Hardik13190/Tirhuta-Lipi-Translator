𑒞𑒱𑒩𑒯𑒳𑒞𑒰 — Tirhuta Lipi Translator

A free, browser-based tool to convert text between Devanagari and Tirhuta (Mithilakshar) script — instantly, with Unicode accuracy.


✨ Features

Bidirectional conversion — Devanagari ↔ Tirhuta in one click
Unicode-compliant — uses the official Tirhuta Unicode block (U+11480–U+114DF)
Built-in reference chart — vowels, consonants, mātrās, digits, and signs
Bilingual UI — toggle the interface between English and Maithili (Devanagari)
Copy to clipboard — one-click copy of the converted output
Keyboard shortcut — Ctrl + Enter / Cmd + Enter to translate
Responsive design — works on desktop and mobile
Zero dependencies — pure HTML, CSS, and JavaScript; no frameworks or build tools


🖥️ Demo
Simply open index.html in any modern browser — no server or installation required.

🗂️ Project Structure
tirhuta-translator/
└── index.html      # Complete application — markup, styles, and logic in one file

🔤 Supported Script Elements
CategoryExamplesIndependent Vowelsअ आ इ ई उ ऊ … ↔ 𑒁 𑒂 𑒃 𑒄 𑒅 𑒆 …Consonantsक ख ग … ↔ 𑒏 𑒐 𑒑 …Dependent Vowel Signs (Mātrās)का ↔ 𑒏𑒰Digits० १ २ … ↔ 𑓐 𑓑 𑓒 …Special Signsanusvara, visarga, virama, chandrabinduPunctuationdanda, double danda

🌐 Font Support
For Tirhuta characters to render correctly, users need a compatible font. The following system fonts include Tirhuta support:

Noto Sans Tirhuta (recommended — install from Google Noto Fonts)
Segoe UI Historic (Windows 10+)

If Tirhuta characters appear as boxes (□), please install Noto Sans Tirhuta.

🛠️ Technology

HTML5 — semantic structure
CSS3 — custom properties, responsive layout, animated background
Vanilla JavaScript — Unicode character mapping and script conversion logic
Google Fonts — Cormorant Garamond, Crimson Pro, Laila


🤝 Contributing
Contributions are welcome! If you notice a missing character mapping or incorrect conversion:

Fork the repository
Create a feature branch: git checkout -b fix/character-mapping
Commit your changes: git commit -m 'Fix: correct virama handling'
Push and open a Pull Request

Please reference the Unicode Tirhuta block specification when proposing mapping changes.

📄 License
This project is licensed under the MIT License — see the LICENSE file for details.

🙏 Acknowledgements

Unicode Consortium — for standardising the Tirhuta script block
Noto Project — for the open-source Tirhuta font
The Maithili-speaking community, for keeping Mithilakshar alive
