**AmpliPi 🌐🎶**
A self-hosted, Raspberry Pi-powered dashboard that allows you to control ad-blocking, host personal websites, download YouTube music, manage files, and enjoy an online music player — all accessible remotely via a secure web interface.

**🔧 Features:**
1. 🎛️ Pi Life: Live monitoring of internet connection, CPU, RAM, storage, and more
2. 🎵 YouTube Downloader: Input a YouTube link → download audio to Pi
3. 🎧 Music Player: Stream downloaded songs directly to your mobile or desktop
4. 🗂️ File Manager: Upload, delete, and organize files on your Pi storage
5. 🌐 Website Manager: Host your own websites and toggle them online/offline
6. 🔒 Secure Login: Web UI protected with login credentials
7. 🌍 Accessible Anywhere: Secure remote access via HTTPS, using Nginx + DuckDNS/Cloudflare

**⚙️ Tech Stack**
1. Python 3.11 + FastAPI (Backend)
2. HTML5 + JavaScript + Bootstrap (Frontend)
3. Docker + Docker Compose (Containerization)
4. Nginx (Reverse Proxy)
5. yt-dlp (YouTube Audio Downloader)
6. psutil (System Monitoring)

**🚀 Getting Started**

Prerequisites:
a. Raspberry Pi (any model with Raspbian installed)
b. Docker and Docker Compose installed on your Pi

Setup:
Clone the repository and set up the environment:

# Clone the repository
git clone https://github.com/vedant-rekulwad/AmpliPi.git

# Navigate into the project directory
cd amplipi

# Build and start services using Docker Compose
docker-compose up --build
Accessing AmpliPi
Once the containers are running, you can access AmpliPi from your mobile or desktop browser by visiting the Pi’s IP address or domain name (if configured with DuckDNS or Cloudflare).

Login Page: Upon first access, you'll be prompted to enter the login credentials.
