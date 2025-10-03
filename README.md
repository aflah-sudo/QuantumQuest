# QuantumQuest (Discontinued) – Advanced Browser Automation Framework

> ⚠️ **Disclaimer:** This project is discontinued and preserved solely for educational and technical demonstration purposes. It is not intended for use with any live services or platforms.

QuantumQuest is a modular Python-based automation framework built for simulating human interaction with web services across multiple accounts and devices. It showcases advanced browser automation, fingerprint evasion, and multi-threaded task orchestration using **Selenium**, **JSON-based configuration**.

---

## 🔧 Technical Highlights

### ✅ Cross-Platform Automation

* Works on **Windows**, **macOS**, and **Linux** (including **Termux** on Android).
* Compatible with **desktop and mobile environments**.

### ✅ Search & Interaction Engine

* **Multi-platform search execution** with randomized timing and input.
* **Simulated human-like typos** and arrow-key suggestion navigation.
* **Scroll through results** and **click entries** dynamically.
* **Randomized queries** with optional integration of trending topics.
* **Session-based tracking** to monitor and adapt to previous behavior.

### ✅ Multi-Account Management

* Manage multiple sessions in parallel with isolated cookies and sessions.
* Automatically detects and handles:

  * **Suspended / locked accounts**
  * **Unusual activity prompts**
* **Account health monitoring** with error-based auto-restarts.
* **Spreadsheet exports** with account/task summaries.

### ✅ Task Automation Modules

* Modular system for automating:

  * **Daily task simulations**
  * **Goal tracking and completion**
  * **Dynamic task list execution**
  * **Form submission and link navigation**
  * **Cache clearance and cleanup**

### ✅ Configuration-Driven Architecture

* Fully customizable via a single `settings.json` file.
* Add, remove, or modify:

  * Extensions
  * Task modules
  * Timings
  * User agents
  * Proxies
* **Real-time updates** reflected instantly via JSON reload.

### ✅ Fingerprint & Stealth Techniques

* **QuantumFingerprint**: Injects randomized browser fingerprinting data.
* Rotate or spoof:

  * **User-Agents**
  * **Browser screen sizes**
  * **Languages and headers**
* Supports **HTTP proxy** integration.
* Optional **headless mode** (not recommended due to detection).

### ✅ Error Handling & Logging

* Automatically:

  * Restarts on errors
  * Captures logs
  * Applies retry logic with exponential backoff
* **Strategic timeouts** to avoid infinite loops and suspicious behavior.

### ✅ Task Scheduling & Performance

* **Scheduled runs** with custom time intervals.
* Tracks task performance over time.
* Logs search and task results to structured formats.

### ✅ Extension & Module Management

* Load/unload browser extensions dynamically from JSON.
* Modular architecture supports plug-and-play for:

  * Search engines
  * Task types
  * Account sources

---

## 📁 Example Output

* 📊 **Spreadsheets** showing task status, account state, error logs.
* 📝 **Structured logs** for each task execution.
* 🔁 Session snapshots for multi-session tracking and debugging.

---

## 📜 Setup & Configuration

Follow the [Setup Guide](setup.md) to run the framework locally or in a controlled environment. Requires Python 3.8+ and ChromeDriver (or equivalent).

---

## ⚠️ Legal and Ethical Use

This framework was built purely for research, experimentation, and skill demonstration in browser automation. **Do not** use this with any web service in violation of its Terms of Service.

---

## 🌀 Future Vision (Archived)

Originally planned for continuous updates including:

* OCR/captcha solving
* Remote dashboard integration
* Smart task prioritization using AI

