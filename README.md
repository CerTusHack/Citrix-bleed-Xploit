# Citrix-bleed-Xploit
An Exploitation script developed to exploit the CVE-2023-4966 bleed citrix information disclosure vulnerability

Hackers have wildly exploiting this vulnerability Citrix gateway and this is exploitation script with enabled concurrency and capable to exploit files of target and single target

Installation:
git clone https://github.com/CerTusHack/Citrix-bleed-Xploit.git

cd Citrix-bleed-Xploit

pip install -r Requirements.txt

python3 CVE-2023-4966.py -h

# USAGE

Single exploitation:

python3 CVE-2023-4966.py -d target.com -o output.txt

Mass exploitation:

python3 CVE-2023-4966.py -dL domains.txt -o output.txt

# INFO:
This exploitation script is an upgraded version of the original work by ASSETNOTE and Dr. Sanjay. Some changes have been made to enhance its capabilities. The developer is not responsible for any illegal or unethical use of this script.

# Disclaimer
Use this script responsibly and only on systems you have explicit permission to test. Unauthorized use is strictly prohibited.
