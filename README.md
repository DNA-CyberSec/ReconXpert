# 🚀 ReconXpert – Advanced Network Scanner

![GitHub repo size](https://img.shields.io/github/repo-size/DNA-CyberSec/ReconXpert)
![GitHub contributors](https://img.shields.io/github/contributors/DNA-CyberSec/ReconXpert)
![License](https://img.shields.io/github/license/DNA-CyberSec/ReconXpert)

ReconXpert is a professional-grade Bash script designed for cybersecurity enthusiasts and penetration testers. It automates the entire reconnaissance process, generating detailed, organized HTML reports, and comprehensive activity logs to simplify security assessments.

---

## 📌 Features

- ✅ **Automated Nmap Scans** – Detects open ports, services, and versions.
- 🌐 **Whois Lookup** – Retrieves domain ownership and registration details.
- 📡 **DNS Information Gathering** – Collects DNS records comprehensively.
- 📝 **Detailed HTML Reports** – User-friendly reports generated automatically.
- 📁 **Structured Logging** – Records every activity with timestamp, user, and action status.
- 🛠️ **Dependency Auto-Installation** – Checks and installs missing dependencies automatically.

---

## 🎯 Usage

Clone the repository:

```bash
git clone https://github.com/DNA-CyberSec/ReconXpert.git
cd ReconXpert
chmod +x scanner.sh
```

### Run the script:

```bash
./scanner.sh <target-domain/IP>
```

Or simply:

```bash
./scanner.sh
```
Then enter your target when prompted.

---

## 📦 Dependencies

The script automatically checks and installs:

- [Nmap](https://nmap.org/)
- [Whois](https://linux.die.net/man/1/whois)
- [Dig (DNS utils)](https://linux.die.net/man/1/dig)

---

## 📂 Project Structure

```
ReconXpert/
├── 📂 reports/
│   ├── 📑 report_<target>_<user>_<timestamp>.html
│   ├── 📑 nmap_scan.txt
│   ├── 📑 whois.txt
│   ├── 📑 dns_info.txt
│   └── 📑 activity.log
├── 🖥️ scanner.sh
└── 📖 README.md
```

---

## 🧑‍💻 Author

- **Rami Hacmon** – [GitHub Profile](https://github.com/DNA-CyberSec)

Feel free to contribute, fork, or open issues!

⭐ **Star this repository if you find it helpful!**
