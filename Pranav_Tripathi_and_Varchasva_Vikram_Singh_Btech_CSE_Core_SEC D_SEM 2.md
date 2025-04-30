# miniProject_fakejob-analyzer

Client-side web app that scans pasted job-offer emails for suspicious keywords and flags potential scams like “quick money” or “no ID required.” No servers or data storage—100% privacy-preserving, instant scam detection in your browser.

## Fake Job Offer Analyzer

A simple front-end tool that scans pasted job-offer emails for red-flag keywords and warns you if it looks like a scam.

## 🚀 Features

- Keyword-based detection of suspicious phrases
- Instant feedback: “Safe” vs. “Suspicious”
- Fully client-side (no server required)

## 📂 File

`fakejobanalyzer.html`

## 🔗 Repository

https://github.com/ssstrangerx/miniProject_fakejob-analyze.git

## 💪 Team Members

- Pranav Tripathi (Roll no. - 2401010129)
- Varchasva Vikram Singh (Roll no. - 2401010290)

Both in Section D (Btech CSE Core) Semester - 2 (1st Year)

---

## Table of Contents

- Overview
- Getting Started
- Usage
- Configuration
- Roadmap
- Contributing
- License

---

## Overview

This project provides a quick, in-browser way to vet job offer emails for common scam indicators. By scanning for a curated list of suspicious keywords, it gives immediate visual feedback without requiring any back-end services.

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, Safari)

### Installation

```bash
git clone https://github.com/ssstrangerx/miniProject_fakejob-analyze.git
```

Open `fakejobanalyzer.html` in your browser.

## Usage

1. Paste the text of any job offer email into the textarea.
2. Click **Analyze Offer**.
3. View the result panel:
   - **Green**: No suspicious keywords detected (Safe).
   - **Red**: Lists all matched red-flag terms (Suspicious).

## Configuration

- To customize flagged phrases, edit the `suspiciousKeywords` array in `fakejobanalyzer.html`.
- Modify styles directly in the `<style>` block or extract them to a separate CSS file.

## Roadmap

- Enhance detection accuracy with regex-based matching to avoid false positives.
- Add inline highlighting of flagged terms in the pasted text.
- Provide an optional API integration for ML-based phishing detection.

## Contributing

Contributions are welcome! Feel free to open an issue, submit a pull request, or suggest new keywords for better coverage.

## License

This project is released under the MIT License. See [LICENSE](LICENSE) for details.

