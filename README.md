# Nginx Log Analyser

A simple and clean Bash tool to analyse Nginx access logs from the command line.

**Project URL:** https://roadmap.sh/projects/nginx-log-analyser  
**GitHub Repository:** https://github.com/PasinduKaveesha/nginx-log-analyzer

![Bash](https://img.shields.io/badge/Bash-Script-blue)
![Linux](https://img.shields.io/badge/Platform-Linux-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

## Features

- Top 5 IP addresses with the most requests
- Top 5 most requested paths
- Top 5 response status codes
- Top 5 user agents
- Clean and human-readable output

## Requirements

- Linux / Unix-based system
- Bash
- Standard tools:
  - `awk`
  - `sort`
  - `uniq`
  - `head`

## Installation & Usage

```bash
# Clone the repository
git clone https://github.com/PasinduKaveesha/nginx-log-analyzer.git

# Navigate into the project directory
cd nginx-log-analyzer

# Make the script executable
chmod +x nginx-log-analyser.sh

# Run the analyser
./nginx-log-analyser.sh
```

## Project Structure

```text
nginx-log-analyzer/
├── nginx-log-analyser.sh   # Main analysis script
├── nginx-access.log        # Sample Nginx access log
└── README.md               # Documentation
```

## Demo Output

```text
Top 5 IP addresses with the most requests:
178.128.94.113 - 1087 requests
142.93.136.176 - 1087 requests
138.68.248.85 - 1087 requests
159.89.185.30 - 1086 requests
86.134.118.70 - 277 requests

Top 5 most requested paths:
/v1-health - 4560 requests
/ - 270 requests
/v1-me - 232 requests
/v1-list-workspaces - 127 requests
/v1-list-timezone-teams - 75 requests

Top 5 response status codes:
200 - 5740 requests
404 - 937 requests
304 - 621 requests
400 - 192 requests
- - 31 requests

Top 5 user agents:
DigitalOcean Uptime Probe 0.22.0 - 4347 requests
Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/129.0.0.0 Safari/537.36 - 513 requests
Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/129.0.0.0 Safari/537.36 - 332 requests
Custom-AsyncHttpClient - 294 requests
Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/128.0.0.0 Safari/537.36 - 282 requests
```

## License

This project is licensed under the MIT License.

## Author
Pasindu Kaveesha Meepawala
