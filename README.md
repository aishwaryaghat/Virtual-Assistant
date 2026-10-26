# Virtual Assistant

Windows voice assistant with speech recognition, spoken responses, website shortcuts, time queries, WolframAlpha answers, and Wikipedia lookup.

Source: https://github.com/Aish0104/Virtual-Assistant

## Setup

Use Python on Windows with a working microphone.

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
$env:WOLFRAMALPHA_APP_ID = 'your-app-id'
python main.py
```

Speech recognition sends microphone audio to Google's recognition service. Knowledge queries use WolframAlpha and Wikipedia. Configure your own WolframAlpha application ID in the environment.

Say `open YouTube`, `open Google`, or ask for `the time`. Press Ctrl+C to stop.
