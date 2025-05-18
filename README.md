# Malicious-File-Trick-Detection-Dataset
Malicious filename patterns, evasion techniques, and detection heuristics — machine-readable.
# Malicious File Trick Detection Dataset

This dataset provides a structured collection of **file-based social engineering and obfuscation techniques** used by attackers to bypass user awareness, antivirus (AV) detection, and security filters. Each entry identifies a malicious or deceptive filename, the evasion technique used, and detection methodology.

The dataset is ideal for:
- 🧠 Training AI/ML models for malware detection
- 🚨 Building secure email gateways and filters
- 📚 Teaching social engineering and malware delivery tactics

---

## 📁 Dataset Format

Stored in `.jsonl` format (JSON Lines), with one structured object per line.

### Fields

| Field         | Description                                                                 |
|---------------|-----------------------------------------------------------------------------|
| `filename`    | Example of a malicious or deceptive file name                               |
| `technique`   | Obfuscation method used (e.g., `Double extension`, `Unicode trick`)         |
| `category`    | Context or delivery type (e.g., `Social Engineering`, `Malware Delivery`)   |
| `detected_by` | Detection method or defense mechanism (e.g., `AV heuristic`, `Sandbox`)     |

---

## 🔍 Example

```json
{
  "filename": "report.pdf.exe",
  "technique": "Double extension",
  "category": "Social Engineering",
  "detected_by": "AV heuristic"
}
✅ Key Techniques Included

    Double extension (file.pdf.exe)

    Whitespace padding (file.txt .exe)

    Unicode manipulation (file‮.exe)

    Alternate file data streams (Windows ADS)

    Executable macros in Office docs (.docm, .xlsm)

    Archive deception (.zip bombs, nested .rar)

    Script obfuscation (.vbs, .bat, .js payloads)

🛠 Use Cases

    Machine learning for secure email filtering

    Static or behavioral malware classifiers

    LLM training for phishing/malware awareness

    Threat modeling and red team education

⚠️ Disclaimer

This dataset is for educational, research, and defense purposes only. Do not use these payloads in unauthorized environments. The author is not responsible for misuse.
📜 License

This dataset is released under the MIT License. You are free to use, modify, and redistribute with attribution.
🤝 Contributions

Want to add more techniques or filenames? PRs are welcome!
📫 Maintainer

Your Name
GitHub: @sunnythakur25
Email: sunny48445@gmail.com
