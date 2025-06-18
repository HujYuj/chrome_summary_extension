# 🔍 AI-powered Web Page Summarizer – Chrome Extension

This is a Chrome extension that uses Gemini's REST API to extract and summarize web page content directly in your browser. Built with Manifest V3, HTML, CSS, and vanilla JavaScript, it supports multiple summary modes and provides a seamless UX without the need for a custom backend.

## 🚀 Features

- 🧠 Summarizes any web page using Gemini's API
- 🔧 Three summary modes: short, medium, detailed
- 🔑 API key configurable via Options page (stored locally)
- ⚙️ Built with Manifest V3 and uses DOM parsing + async requests

## 🛠️ Tech Stack

- Manifest V3
- HTML, CSS, JavaScript
- Gemini REST API
- DOMParser, Fetch API

## 📦 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/HuYuj/chrome_summary_extension.git
2. Open Chrome and go to chrome://extensions/

3. Enable Developer mode (top right corner)

4. Click Load unpacked and select the chrome_summary_extension folder

## 🔐 Set up your key
1. After installing the extension, click the extension icon → Options

2. Enter your Gemini API key (you can get one from Google AI Studio)

## 🧪 Usage
1. Open any article or web page

2. Click the extension icon

3. Choose your desired summary mode

4. Wait for a few seconds while the summary is fetched and displayed
