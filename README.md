# 📥 Torrent to Google Drive Downloader (Colab)

**Updated: 2025/08/18**

This project allows you to **download torrent files or magnet links directly into your Google Drive** using Google Colab.  

- Add **one or more torrents**, view their details, reorder them, and change download settings.  
- Files are saved straight into your **Google Drive**, so you don’t need to worry about local storage.  
- Make sure you select the **T4 GPU runtime** in Google Colab before starting. This allows a cumulative download size of approx. **384GiB per session**.  

👉 Even if you don’t understand code or output logs, just follow the instructions step by step and run each cell as guided in the notebook.  

---

## 🚀 Getting Started on Google Colab

To use this notebook in **Google Colab**:

1. Click the badge below to open the notebook in Colab:  

   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ratzlord3125/torrent-to-google-drive-downloader/blob/main/Torr2DriveV2.ipynb)

2. Follow the **instructions inside the notebook**. Each step is explained in markdown cells.  

3. Make sure to:
   - Set the runtime to **GPU → T4**  
   - Connect your **Google Drive** when prompted  
   - Upload your torrent file(s) or paste magnet links  

4. Run each cell in order. The files will be saved directly into your Google Drive.

---

## ⚡ Features

- Download torrents or magnet links directly to Google Drive  
- Parallel download support
- View torrent details, manage downloads, and reorder tasks  
- Easy to use – no coding knowledge required  

---

## 🛠️ Requirements

- Google Account with available **Google Drive storage**  
- Google Colab runtime (**T4 GPU recommended**)  

---

## 📌 Notes

- Session download size may vary depending on Colab runtime allocation.  
- Large torrents should be uploaded **one at a time** for best performance and less risk of runtime getting disconnected.  
- This tool is meant for **personal educational purposes only**. Please respect copyright laws.  

---

## 📃 Credits & License

**Credits:** This project builds upon multiple existing Torrent to Google Drive Downloader scripts available on the internet, which are no longer functional. The main dependency of this script is the [libtorrent](https://www.libtorrent.org/) library, and this script may need updates when changes occur in the library APIs.

**License:** This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
