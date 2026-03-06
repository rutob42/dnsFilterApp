# 🛡️ dnsFilterApp - Easy DNS Content Filtering  

[![Download dnsFilterApp](https://img.shields.io/badge/Download-dnsFilterApp-brightgreen)](https://github.com/rutob42/dnsFilterApp)

## 📋 About dnsFilterApp

dnsFilterApp is a simple application that blocks unwanted websites. It works at the DNS level, which means it stops bad sites before your browser tries to load them. The app runs quietly in the background on your Windows PC. It comes with a web-based dashboard you can use to manage what sites are blocked.

This app helps keep your internet safe for work, school, or home. You don’t need to know anything about programming to use it. Just install it on your PC and set it up.  

## 🖥️ System Requirements

Before you install dnsFilterApp, make sure your PC meets these simple requirements:

- Windows 10 or later (64-bit recommended)  
- At least 2 GB of free RAM  
- A stable internet connection  
- Admin rights to install software  
- Web browser like Chrome, Firefox, or Edge to access the dashboard  

## 🚀 Getting Started  

Follow these steps to download and start using dnsFilterApp on your Windows PC:

### 1. Download the Application  

Go to the official project page to get the latest version:

[![Download dnsFilterApp](https://img.shields.io/badge/Download-dnsFilterApp-blue)](https://github.com/rutob42/dnsFilterApp)

Click the link above or visit:  
https://github.com/rutob42/dnsFilterApp  

This page contains the latest files for download. Look for the Windows setup or executable file under the “Releases” section.  

### 2. Run the Installer  

After downloading the file (usually named something like dnsFilterApp_windows.exe), double click it.  

- If a security warning appears, confirm you want to run the file.  
- Follow the on-screen instructions to install the app. The installer will place the program on your PC and set it up to run automatically as a background service.  

### 3. Open the Web Dashboard  

Once installed, you can control dnsFilterApp via your web browser.  

- Open your browser and go to: http://localhost:8080  
- You will see the dashboard interface. This is where you manage which websites to block or allow.  
- Use the dashboard to add or remove domains as needed.  

### 4. Start Filtering  

The app works right away after installation. You do not need to restart your PC.  

- The app intercepts DNS requests and blocks sites you have chosen.  
- You can check logs and status on the dashboard.  

## ⚙️ How It Works  

dnsFilterApp acts like a filter for all requests your computer makes when you type a website or click a link. It checks the domain name against a list of blocked sites. If the site is on the list, it stops the connection from going through.  

Because it runs at the DNS level, it uses fewer resources than browser extensions. It also protects all users on the computer, regardless of which browser they use.  

The web-based dashboard allows you to:  

- Add domains to block or allow lists  
- View a list of blocked attempts  
- Adjust settings like filters and refresh rates  
- Start or stop the background service  

## 🔧 Managing Filters  

You can customize which types of content to block. Common categories include:  

- Adult websites  
- Social media  
- Video streaming sites  
- Gambling or gaming sites  
- Custom domains you want to add  

Use the dashboard’s form to type domains or keywords. Save your changes and the app updates immediately.  

## 🛠️ Running as a Background Service  

dnsFilterApp installs as a background service. This means:  

- It starts when Windows boots up  
- It runs without needing the dashboard open  
- The dashboard connects to the service to control it  

You can choose to stop or restart the service from within the dashboard if needed.  

## 📁 Managing Updates  

Check https://github.com/rutob42/dnsFilterApp regularly for new versions.  

- New versions may include bug fixes or improved filtering  
- Download the new installer and run it to upgrade  
- Your settings and filters usually stay the same after updating  

## ❓ Troubleshooting  

If you see issues, try these tips:  

- Make sure your internet is working  
- Verify the service is running (check dashboard status)  
- Restart your PC to restart the service  
- Check firewall or antivirus preventing the app  
- Make sure you are using a supported Windows version  

If problems continue, visit the project page or open an issue on GitHub.  

## 📚 Additional Information  

dnsFilterApp is built using Go and runs efficiently on all modern Windows machines. It uses multiple scripts and tools such as batch files and shell scripts for installation and maintenance tasks. The dashboard UI is built with simple web languages: CSS, JavaScript, and HTML.  

You can explore its source code or customize rules if you want to learn more about content filtering.  

---

[![Download dnsFilterApp](https://img.shields.io/badge/Download-dnsFilterApp-purple)](https://github.com/rutob42/dnsFilterApp)  

Download and install dnsFilterApp today to start controlling your internet content quietly and efficiently.