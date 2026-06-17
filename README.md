# TEM Flight Operations Safety Analysis

Automated Threat and Error Management (TEM) framework processor for flight training observations. This application turns raw flight notes into structured safety data with visual evidence mapping.

## Features

- **AI-Powered Analysis**: Uses Gemini 3.1 Pro to identify Threats, Errors, and Undesired Aircraft States (UAS).
- **Visual Evidence Mapping**: Programmatically highlights source text in Word documents based on TEM categories.
- **Audit-Ready Reports**: Generates annotated `.docx` files for immediate visual audit trails.
- **Professional Dashboard**: Real-time visualization of safety findings across flight phases.

## Tech Stack

- **Frontend**: React, Tailwind CSS, Framer Motion, Lucide Icons.
- **Backend**: Node.js, Express, Multer, Mammoth (Docx parsing), Docx (Docx generation).
- **AI**: Google Gemini API (@google/genai).


