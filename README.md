# System Info Viewer

A Python desktop app for inspecting hardware and resource usage. It uses Tkinter, ttkbootstrap, and psutil to display CPU, memory, disk, network, and battery information.

The app runs on Windows, Linux, and macOS. Hardware details vary by operating system and the data its system tools expose.

## Run locally

Install Python 3 with Tk support, then run:

```bash
git clone https://github.com/mahdi-hajizadh/system_info.git
cd system_info
python -m venv .venv
```

Activate the virtual environment. In PowerShell, run `.\.venv\Scripts\Activate.ps1`. On Linux or macOS, run `source .venv/bin/activate`. You can check Tk support with `python -m tkinter`.

```bash
python -m pip install -r requirements.txt
python system_info.py
```

Open the tabs in the app to inspect the available hardware details and live usage.
