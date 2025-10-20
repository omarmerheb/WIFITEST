# Wi-Fi Test & Monitor Script (`wifitest.sh`)

A lightweight Bash script for Termux that checks your Wi-Fi connectivity, notifies you with toasts and vibrations, and keeps a log of your network status.

This script was designed to be simple, yet flexible, letting you choose between a single connectivity check, continuous monitoring, or just viewing a log of your Wi-Fi history.

---

## Features

- **Single Check Mode**: Quickly verify if your Wi-Fi is online.
- **Loop/Background Mode**: Monitor Wi-Fi continuously until stable.
- **Logging**: Keeps a timestamped log of connectivity events.
- **Notifications**: Sends Termux toast messages when Wi-Fi goes up or down.
- **Vibrations**: Optional tactile notifications for connectivity changes.
- **Mode Options**:
  - `-s` → Single check  
  - `-b` → Loop in background  
  - `-l` → Show logs  
  - `-v N` → Number of vibration alerts

---

## Requirements

- [Termux](https://termux.com/) on Android
- Bash (comes with Termux)
- Termux API installed (`termux-api` package)
  ```bash
  pkg install termux-api

---

  ## WHY?
  where i live every couple of weeks internet connection from my ISP gets unstable you have internet access now you wont in 10 seconds its gone for 30 minutes and back for 5 minutes and so on
  so i wanted to have a way of knowing when internet access came back while i touch some grass since its only back for a short while

  other use cases could include network troubleshooting or setting up or idfk anything you want really instead of manually typing out ping google.com 12 times 
  have fun 




  DONATE : 15o7Md2HJrQU2rSNyf5Azt8SPu9aBCCLi9 BTC
