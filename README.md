# ReconScript
ReconScript is a comprehensive recon automation tool for domain and subdomain enumeration, vulnerability assessment, and information gathering, providing detailed insights into target domains.

# Disclaimer
This script is still a work in progress. Newer and better versions will be uploaded soon. Please report any issues you encounter to help improve the tool.

# Features
Subdomain Enumeration: Utilizes assetfinder, amass, and sublist3r for comprehensive subdomain discovery.
Alive Domain Probing: Uses httprobe to filter out live domains.
Subdomain Takeover Detection: Implements subjack to check for potential subdomain takeovers.
Web Technology Detection: Employs whatweb to identify web technologies used by the domains.
Historical Data Analysis: Extracts historical URLs and parameters using waybackurls.
Directory Busting: Utilizes dirb and ffuf for discovering hidden directories and files.
Open Port Scanning: Uses nmap to scan for open ports and services.
Visual Documentation: Runs EyeWitness to capture screenshots of the identified websites.

# Getting Started
# Prerequisites
Make sure the following tools are installed and accessible in your environment:

assetfinder
amass
sublist3r
httprobe
waybackurls
whatweb
subjack
dirb
ffuf
EyeWitness
You can install these tools using your package manager or directly from their respective repositories.

# Usage
Run the script with the target domain as an argument:


./ReconScript.sh example.com
The script will create a directory structure under the target domain's folder and save all outputs in respective subdirectories.
