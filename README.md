# NetworkWalks Cybersecurity Internship — Week 3

**Participant:** Adwaidh R  
**Batch:** B084C  
**Week:** 3

This repository contains practical evidence for the Week 3 password-cracking exercises.

## W3-PM1 — Password Cracking with John the Ripper

- Used `pdf2john` to extract a PDF password hash from the assigned local lab PDF.
- Used John the Ripper from the Kali Linux terminal to test the extracted hash.
- The terminal evidence records successful password recovery for the PDFs shown in the screenshots.
- Additional flag-capture images are preserved separately because the images do not all identify which PDF produced each flag.

### Evidence

- `Screenshots/PM1-JTR-John-CLI/` — John CLI results for the three PDF runs shown in the screenshots.
- `Screenshots/PM1-Additional-Flag-Captures/` — additional flag-capture evidence.

**Johnny GUI:** The PM1 guide also describes Johnny on Windows. No Johnny GUI screenshot is included in this upload package; the evidence here documents the John CLI work performed in Kali.

## W3-PM2 — Password Cracking with NetworkWalks Tools

- Used the NetworkWalks Hash Calculator and Password Cracker in the browser.
- The browser evidence shows a PDF hash entered into the Password Cracker and the protected PDF opened with the recovered result/flag.

### Evidence

- `Screenshots/PM2-NetworkWalks-Tools/` — Password Cracker and opened-PDF/flag evidence.
- `Screenshots/PM2-Supporting-Hash-Calculator/` — supporting screenshot of the general hash-calculator output (MD5, SHA-1, SHA-256, SHA-384 and SHA-512). This is included as supplementary evidence, not as the `$pdf$` hash itself.

## Repository contents

```text
README.md
Screenshots/
├── PM1-JTR-John-CLI/
│   ├── john-cli-pdf1-good-luck.png
│   ├── john-cli-pdf2-password1.png
│   └── john-cli-pdf3-password-recovered.png
├── PM1-Additional-Flag-Captures/
│   ├── additional-flag-capture-01.png
│   ├── additional-flag-capture-02.png
│   └── additional-flag-capture-03.png
├── PM2-NetworkWalks-Tools/
│   ├── password-cracker-with-pdf-hash.png
│   ├── locked-pdf-opened-flag.png
│   └── first-flag-captured-summary.png
└── PM2-Supporting-Hash-Calculator/
    └── general-file-hash-output.png
```

Only screenshots and documentation are included. Original locked PDFs, extracted hash files, and recovered passwords are not included.
