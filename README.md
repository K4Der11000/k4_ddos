# k4_ddos


# kader11000 Request Tool

This tool sends a large number of HTTP requests to a list of URLs using proxies, and displays system usage stats (CPU, RAM) along with request counters in a dynamic web interface.

## Features
- Multi-threaded request sending
- Cloudflare bypass using cloudscraper
- Real-time CPU and RAM usage monitoring
- Proxy support with auto-refresh
- Start/Stop/Resume requests via UI
- Save, Read, Download, Delete results
- HTML output with colored response codes
- Dynamic animated banner with your name

## Requirements

Make sure you have Python 3.8+ installed.

Install the required packages:
```bash
pip install flask psutil cloudscraper
```

## How to Run

1. Unzip the project
2. Open a terminal in the project folder
3. Run the app:
```bash
python app.py
```

4. Open your browser and go to:
```
http://127.0.0.1:5000
```

## Notes
- To update proxies: proxies are fetched from the internet automatically on start.
- You can enter multiple target URLs separated by new lines.
- Results are saved in `results.txt` and `results.html`.

## Coded by: kader11000
